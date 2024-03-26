# test
test
ну да у меня нет фантазии и я написал калькулятор 
//privet
#include <iostream>
using namespace std;

int main() {
    char op;
    double a, b;

    cout << "из математики 2 класса чота выбери (+, -, *, /): ";
    cin >> op;
    cout << "напеше 2 чесла: ";
    cin >> a >> b;

    switch (op) {
    case '+':
        cout << a << " + " << b << " = " << a + b;
        break;
    case '-':
        cout << a << " - " << b << " = " << a - b;
        break;
    case '*':
        cout << a << " * " << b << " = " << a * b;
        break;
    case '/':
        if (b != 0)
            cout << a << " / " << b << " = " << a / b;
        else
            cout << "ээээээээээээээээээээ на ноль делать нельзя ";
        break;
    default:
        cout << "моя твоя не понимать";
        break;
    }

    return 0;
}
