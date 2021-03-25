# Mycodes
Special printing pattern
#include <iostream>
using namespace std;

int main() {
	int a , b ;
	cout << "Enter the number of rows :: "<<endl;
	cin>> a;
	cout << "Enter the number of columns :: "<<endl;
    cin>>b ;
    for(int i = 0 ; i < a ; i++){
       if(i== 0 or i==a-1) {
        for(int j = 0 ; j <  b ; j++){
                cout<<"* ";
            }
            
            }
        if(i>0 && i < a-1){
            cout<<"* ";
            for(int j = 1 ; j < b-1 ; j++){
                cout<<"  ";
            }
            cout<<"*" ;
        }
        cout<<endl;
    }
    
	return 0;
}
