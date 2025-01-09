```
#include <iostream>
using namespace std;

int main() {
    long long n ; 
    cin >> n ;

    long long currentPassenger =  0 , currentMax = 0 ; 
    
    while (n --){
        long long ai, bi ; 
        cin >> ai >> bi ; 
        
        currentPassenger += (bi - ai)  ; 
        currentMax = max (currentMax, currentPassenger) ; 
    }
    
    cout << currentMax ; 

}
```