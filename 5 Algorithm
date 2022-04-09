#include <iostream>
using namespace std;


int Search_Binary (int arr[], int left, int right, int key)
{
 int midd = 0;
 while (1)
 {
 midd = (left + right) / 2;
 
 if (key < arr[midd])       
 right = midd - 1;      
 else if (key > arr[midd])  
 left = midd + 1;    
 else                       
 return midd;           
 
 if (left > right)         
 return -1;
 }
}


int main()
{
    
    int A[100];
    for (int i = 0; i < 100; i++){
        A[i] = i + 1;
    }
    int key = 0;
    cout << "Input key: " << endl;
    cin >> key;
    int index = 0;
    index = Search_Binary (A, 0, 100, key);
    if (index >= 0) 
    cout << "Index: " << index << "\n\n";
    else
    cout << "This number is not in the array!\n\n";
    
    
    int C[10000];
    for (int i = 0; i < 10000; i++){
        C[i] = i + 1;
    }
    key = 0;
    cout << "Input key: " << endl;
    cin >> key;
    index = 0;
    index = Search_Binary (C, 0, 10000, key);
    if (index >= 0) 
    cout << "Index: " << index << "\n\n";
    else
    cout << "This number is not in the array!\n\n";

    return 0;
}
