// printing array through function in c++

#include <iostream>
using namespace std;
void printarray(int arr[],int size)
{
	for(int i=0;i<size;i++){
		cout<<arr[i];
	}
}

int main() {
	int number[10];
	printarray(number,10);
	
	
	
	return 0;
}


