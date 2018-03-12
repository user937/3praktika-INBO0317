# 3praktika-INBO0317
Сделать форк данного репозитория
Написать в файле README.md имя фамилия группа
#include <iostream>
using namespace std;
 
class kniga {
public:
    char janr[20];
    char avtor[30];
    char nazvanie[40];
    int god_izdania;
    int cena;
 
void set()
{
    cout<<"ввдите жанр:";
    cin>>janr;
    cout<<"введите автора:";
    cin>>avtor;
    cout<<"введите название:";
    cin>>nazvanie;
    cout<<"введите год выпуска:";
    cin>>god_izdania;
    cout<<"введите цену:";
    cin>>cena;
}
void show()
{
    cout<<"Janr:"<<janr<<endl;
    cout<<"Avtor:"<<avtor<<endl;
    cout<<"Nazvanie:"<<nazvanie<<endl;
    cout<<"GOd vipyska:"<<god_izdania<<endl;
    cout<<"Cena:"<<cena<<endl;
}
 
 
};
 
 
int main()
{
	setlocale (0,"rus");
    kniga n1;
 
    n1.set();
    n1.show();
 
 
    system("pause");
    return 0;
}
