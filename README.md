# Sum

#include <iostream>

int main() {
    int num, sum = 0;
    
    std::cout << "Enter a sequence of positive integers (0 to stop): ";
    
    while (true) {
        std::cin >> num;
        if (num == 0) {
            break;
        }
        sum += num;
    }
    
    std::cout << "Sum: " << sum << std::endl;
    
    return 0;
}
