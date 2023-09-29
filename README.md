# activity-v2-8
# include<iostream>
using namespace std;

int main(){
	
	string x;
	int y;
	char z;
	
	cout<<"Enter a string: ";
	getline(cin,x); // Name
	cout<<"Enter a number:";
	cin>>y;// number that you want to change the words
	cout<<"Enter a letter:"; //letters
	cin>>z;
	
	
	x[y] = z;
	cout << x;
	
	return 0;
}
