# test
test
ну да у меня нет фантазии и я написал калькулятор 
//privet
#include <iostream>
using namespace std;

int main() {
    char op;
    double c, d;

    cout << "из математики 2 класса чота выбери (+, -, *, /): ";
    cin >> op;
    cout << "напеше 2 чесла: ";
    cin >> c >> d;

    switch (op) {
    case '+':
        cout << c << " + " << d << " = " << c + d;
        break;
    case '-':
        cout << c << " - " << d << " = " << c - d;
        break;
    case '*':
        cout << c << " * " << d << " = " << c * d;
        break;
    case '/':
        if (b != 0)
            cout << c << " / " << d << " = " << c / d;
        else
            cout << "ээээээээээээээээээээ на ноль делать нельзя ";
        break;
    default:
        cout << "моя твоя не понимать";
        break;
    }

    return 0;
}
