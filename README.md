#include <iostream>
using namespace std;

int main() {
  int N = 100;

  for (int a = 1; a <= N; a++) {
    for (int b = a; b <= N; b++) {
      for (int c = b; c <=N; c++){
        if (a * a + b * b == c * c){
          cout << "(" << a << ", " << b << ", " << c << ")" << endl;
        }
      }
    }
  }

  return 0;
]
