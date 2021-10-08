#include<iostream>
#include<cstdlib>
#include<ctime>
using namespace std;

int main(){
	
	int n1 = 0;
	srand(time(NULL));
	
	n1 = rand() % 6;
	cout << n1;
	
	return n1;
}
