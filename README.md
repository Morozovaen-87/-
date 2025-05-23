include <iostream>
#include <cmath>
#include <conio.h>
using namespace std;
int sfig(int a, int b, int c) { return 2 * (a * b + b * c + a * c); }
float fig(float a, float b,float c) { return 2 * (a * b + b * c + a * c); }
double ig(float a, float b, float c) { return 2 * (a * b + b * c + a * c); }
long g(float a, float b, float c){ return 2 * (a * b + b * c + a * c); }
int ling(int a, int b, int d) { return 2 * d * (a + b); }
float ing(float a, float b, float d) { return 2 * d * (a + b); }
double ng(double a, double b, double d) { return 2 * d * (a + b); }
long gs(long a, long b, long d) { return 2 * d * (a + b); }
int cls(int R, int p, int h) { return 2 * R * p * h; }
float dls(float R, float p,float h) { return 2 * R * p * h; }
double xls(double R, double p, double h) { return 2 * R * p * h; }
long zls(long R, long p, long h) { return 2 * R * p * h; }
int main() {
    int  a, b, c, d;
    long a, b, c, d;;
    cout << "use a line of []\ ";
    cin >> a >> b >> c;
    cout << "int.S=" << sfig(a, b, c) << endl<<"float.S=" << fig(a, b, c) << endl<<"double.S=" << ig(a, b, c) << endl<<"long.S=" << g(a, b, c) << endl;
    cout << "use a line of [0]";
    cin >> a >> b >> d;
    cout << "int.S=" << ling(a, b, d)<< endl << "float.S=" << ing(a,b,d)<< endl<<"double.S="<<ng(a,b,d)<< endl << "long.S="<< gs(a,b,d) << endl;
    cout << "use a h,R\ ";
    cin >> h >> R;
    cout << "int.S=" << cls(R, p, h) << endl <<"float.S="<< dls(R, p, h) << endl <<"double.S="<< zls(R, p, h) << endl <<"long.S="<< xls(R, p, h) << endl;
}
# -