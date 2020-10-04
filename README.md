#include<iostream>
using namespace std;
int main()
{
	const int n = 2;
	int a[n][n];
	for (int i = 0; i < n; i++)
		for (int j = 0; j < n; j++) {
			cout << "a[" << i << "][" << j << "]\t ->";
			cin >> a[i][j];
		}
	system("cls");
	for (int i = 0; i < n; i++, cout << endl)
		for (int j = 0; j < n; j++)
			cout << a[i][j] << ' '; 
	cin.get(); cin.get();
	return 0;
}
