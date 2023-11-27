#include <iostream>
#include <math.h>
using namespace std;
float tong(int n){
	float sum=0;
	for (int i=1;i<=n;i++){
		sum+=(float)1/(n*(n+1));
	}
	return sum;
}
int main (){
	int n;cin >> n;
	cout  << tong(n);
	return 0;
}
