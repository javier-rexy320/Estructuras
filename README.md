# Estructuras
# Estructuras
Este documento muestra ejemplos básicos sobre cómo se utilizan las estructuras de selección simple `if - else` y múltiple `switch` en C++.

---

## 🔹 Estructura de selección simple: `if - else`

```cpp
#include <iostream>
using namespace std;

int main() {
    int numero;
    cout << "Ingrese un número: ";
    cin >> numero;

    if (numero > 0) {
        cout << "El número es positivo." << endl;
    } else {
        cout << "El número es cero o negativo." << endl;
    }

    return 0;
}
