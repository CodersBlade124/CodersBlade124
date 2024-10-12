- 👋 Hi, I’m @CodersBlade124
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
CodersBlade124/CodersBlade124 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---> КАЛЬКУЛЯТОР ДЛЯ КВАДРАТНЫХ УРАВНЕНИЙ
#include <iostream>
#include <math.h>
using namespace std;

int main()
{
setlocale(0, "");
int a, b, c; 
cout << "Введите коэффицент А: ";
cin >> a; 
cout << "Введите коэффицент В: ";
cin >> b;
cout << "Введите коэффицент С: ";
cin >> c;
int d = b*b-4*a*c; 
cout << "Дискриминант = "<< d << endl ;
if(d>0){cout<< "У этого уравнения имеется 2 корня" <<endl;
int x1 = (-b+sqrt(d))/2*a ;
cout << "Первый корень = "<< x1 <<endl;
int x2 = (-b-sqrt(d))/2*a ;
cout << "Второй корень = "<< x2 <<endl;
}
else if(d<0){cout<< "У этого уравнения корней нет" <<endl;}
else{cout<<"у этого уравнения один корень"<<endl;
int x = -b/2*a ;
cout << "Корень = "<< x <<endl;}
return 0;
