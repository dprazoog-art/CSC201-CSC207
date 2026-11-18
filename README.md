# CSC201-CSC207
For the csc201/csc207 assignment from Wed 18th of November, 2026

*Assignment - COS 201/CSC 207 Lecture* 
1. Write a C++ program to check if a number is Odd or Even 
2. Create a repository in GitHub and upload your code then 
3. Submit your code using the link below
https://forms.gle/bXnrSdgeQQRFVSW8A

Deadline: *Friday, 20th November, 2026*

SOLUTION TO ASSIGNMENT BELOW👇:

#include <iostream>
using namespace std;

int main() {
    int number;
    cout << "Enter a number: ";
    cin >> number;

    if (number % 2 == 0) {
        cout << number << " is Even" << endl;
    } else {
        cout << number << " is Odd" << endl;
    }

    return 0;
}
