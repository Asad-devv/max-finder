# max
#include <iostream>
using namespace std;
void getmax(int a, int b, int c);
int k;
int l;
int main()
{
    
    getmax(1,3,2);

    return 0;
}

void getmax(int a, int b, int c)
{
    if (a > b)
    {
        k = a;
        
    }
    else if (b > a)
    {
        l = b;
    }
    if (l > c)
    {
        cout << "the greater number is " << l << endl;
    }
    else if (k > c)
    {

        cout << "the greater number is " << k << endl;
        // cout << c << endl;
    }
    else
    {
        cout << "the greater number is" << c << endl;
    }
}
