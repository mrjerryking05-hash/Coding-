#include <iostream>
using namespace std;
int main() {
    int a, b, c;
    cout << "Enter three numbers: ";
    cin >> a >> b >> c;
    if (a >= b && a >= c) {
        cout << "Greatest = " << a << endl;
        if (b >= c) {
            cout << "Middle = " << b << endl;
            cout << "Smallest = " << c << endl;
        } else {
            cout << "Middle = " << c << endl;
            cout << "Smallest = " << b << endl;
        }
    }
    else if (b >= a && b >= c) {
        cout << "Greatest = " << b << endl;
        if (a >= c) {
            cout << "Middle = " << a << endl;
            cout << "Smallest = " << c << endl;
        } else {
            cout << "Middle = " << c << endl;
            cout << "Smallest = " << a << endl;
        }
    }
    else {
        cout << "Greatest = " << c << endl;
        if (a >= b) {
            cout << "Middle = " << a << endl;
            cout << "Smallest = " << b << endl;
        } else {
            cout << "Middle = " << b << endl;
            cout << "Smallest = " << a<< endl;
        }
    }
    return 0;
}
