#include <iostream>
#include <stack>

using namespace std;

int main() {
  stack<int> myStack; // Deklarasi stack dengan nama myStack

  int pilihan;
  int elemen;

  do {
    cout << "OPERASI STACK" << endl;
    cout << "[1] PUSH" << endl;
    cout << "[2] POP" << endl;
    cout << "[3] Clear Stack" << endl;
    cout << "[4] Quit" << endl;
    cout << "Input Menu Pilihan Anda : ";
    cin >> pilihan;

    switch (pilihan) {
      case 1:
        cout << "Push elemen = ";
        cin >> elemen;
        myStack.push(elemen); // Menambahkan elemen ke stack
        cout << "Isi Stack = " << myStack.top() << endl; // Menampilkan elemen teratas stack
        break;
      case 2:
        if (myStack.empty()) {
          cout << "Stack kosong!" << endl;
        } else {
          cout << "Elemen yang di-pop = " << myStack.top() << endl;
          myStack.pop(); // Menghapus elemen teratas stack
        }
        break;
      case 3:
        while (!myStack.empty()) {
          myStack.pop(); // Mengosongkan stack
        }
        cout << "Stack telah dikosongkan." << endl;
        break;
      case 4:
        cout << "Keluar dari program." << endl;
        break;
      default:
        cout << "Pilihan tidak valid." << endl;
    }
  } while (pilihan != 4);

  return 0;
}
