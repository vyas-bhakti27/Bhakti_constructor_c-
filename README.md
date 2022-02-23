// c++ constructor code 

#include<iostream>
using namespace std;

class demoConst{
    private: int i=10;
    public: 
           void setval()
           {
             i=100;
             cout <<"Inside the setvalue(),i="<< i << endl;
           } // end of setval()
            demoConst() {
            cout << "Inside the contructor\n" << endl;
           }


};
int main(){
 demoConst demo1,demo2;
 demo1.setval();
 return 0;
}
