# UTS_Algoritma

## Soal 1

**Alur algoritma**
1. Mendeklarasikan variabel `int A,B,X,Y` sebagai variabel input
2. Membaca input dari keyboard `cin >> A >> B >> X >> Y `
3. Membandingkan variabel **X** dengan **Y** jika sama
4. Karena statement **false** tidak akan terjadi karena `{X != Y}`
5. Dan jika statement **True** maka **X < Y** berlaku rumus statement **True** dengan syntax `X = X + A`
6. Dan jika statement **False** `Y = Y + B`


**Kode lengkap program**
**soal A**

```
#include<iostream>

using namespace std;

int main ()
{
    int A,B,X,Y;

    cout << "masukan bilangan X: ";
    cin >> A;
    cout << "masukan bilangan Y: ";
    cin >> B;

    X = A;
    Y = B;
    if(X != Y )
          {if ( X < Y  )
                { X = X + A;}
           else
                { Y = Y + B;}
          }

    cout << X;


}
```

**hasilnya**

![hasilnya](https://github.com/iisamelia/UTS_Algoritma/blob/master/soal1.cpp/hasil1A.PNG)


**Kode lengkap program**
**soal B**

```
#include<iostream>

using namespace std;

int main ()
{
    int A,B,X,Y;

    cout << "masukan bilangan X: ";
    cin >> A;
    cout << "masukan bilangan Y: ";
    cin >> B;

    X = A;
    Y = B;
    if(X != Y )
          {if ( X < Y  )
                { X = X + A;}
           else
                { Y = Y + B;}
          }

    cout << Y;


}
```

**hasilnya**

![hasilnya](https://github.com/iisamelia/UTS_Algoritma/blob/master/soal1.cpp/hasil1B.PNG)


