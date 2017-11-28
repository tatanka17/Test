#include <iostream>
using namespace std;
int main () {
  int y;
    cout << "Wie viele Zahlen wollen Sie addieren? \n";
    cin >> y;
  int array [y]{};
  int x;
  int total = 0;
  for (x=0;x<y;x++){
   cout << "Geben Sie die " << x + 1 << " te Zahl ein! \n";
   cin >> array[y];
   total = total+array[y];
   }
   cout << "Die Summe beträgt: " << total << "\n";
}
