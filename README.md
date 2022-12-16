infa 2 yrok

#include <iostream>
#include <stdlib.h>
#include <time.h>
#include <conio.h>
using namespace std;
int main()
{   int n,m,d;
        srand((unsigned)time(NULL));
        std::cout << "n="; std::cin >> n;
        d=rand()%(10);
        for(int i=2;i<=n;i++)
        {
        m=rand()%(10);
        d=d*10+m;
        }
        cout << "d= "<< d << endl;
        getch();
        return 0;
}
