#include <iostream>
#include <iomanip>
using namespace std;
int main()
{
cout << setw(10) << right << showpos << 4 << noshowpos << endl;
cout << setw(15) << internal << -67.09 << endl;
cout << setw (10) << right << showpos << 235 << noshowpos << endl;
cout << '8' << 'a' << '1' << endl;
cout << fixed << setprecision(2) << -121.00 << endl;
cout << showpos << 1 << noshowpos << showpos << 24 << noshowpos << endl;
}

