```
#include <bits/stdc++.h>

using namespace std;

int main() {

    long long n;
    cin >> n;
    long long sum = 0, countFive = 0, countzero = 0;
    for (int i = 0; i < n; i++) {
        
        int temp = i ; 
        cin >> temp ;
        sum += temp;
        
        
        if (temp == 0) {
            countzero++;
        }

        if (temp == 5 && sum % 9 == 0) {
            countFive = sum / 5;
        }
        
    }
    
    // cout << countzero << endl; 
    if ( countzero == 0  ) {
        cout << -1;
        return 0; 
    }

    if (countFive < 9){
        cout << 0 ; 
        return 0; 
    }
    
    else {
        while (countFive--) {
            cout << 5;
        }
        while (countzero--) {
            cout << 0;
        }
    }


}
```