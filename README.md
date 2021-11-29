# C-whileloop
my first repository (1st sem exam at coc)

contents:

firstName
lastName
yearlevel
subjects
sum
average

#include<iostream>
using namespace std;
int main()
{
    //declare used variables
    string isfirstName, islastName, isyearlevel;
    int eng, math, sci, pe, fil, his;
    int sum;
    float average;
    
     //condition
    while (average>=1){
     
    
	//ask user's details
    cout << "\nFirst Name:\n"<<endl;
    getline(cin, isfirstName) ;
    
    cout << "\nLast Name:\n"<<endl;
    getline(cin, islastName);
    
    cout << "\nYear and Level: \n"<<endl;
    getline(cin, isyearlevel);
    
    
    //ask user to input grades in every subject
    cout << "\nInput grade in English:  \n"<<endl;
    cin >> eng;
    
    cout << "\nInput grade in Math: \n"<<endl;
    cin >> math;
    
    cout << "\nInput grade in Science: \n"<<endl;
    cin >> sci;
    
    cout << "\nInput grade in PE:  \n"<<endl;
    cin >> pe;
    
    cout << "\nInput grade in Filipino:  \n"<<endl;
    cin >> fil;
    
    cout << "\nInput grade in History: \n"<<endl;
    cin >> his;
    
    //print result
    cout << "\nStudent Record: ";
    cout << "\n Name: " <<isfirstName<<islastName ;
    
     /*//Calculation
    sum=eng+math+sci+pe+fil+his;*/
    
    sum+=average;
    
    cout <<average<<"is the average";
    
    
    }
    return 0;
}
