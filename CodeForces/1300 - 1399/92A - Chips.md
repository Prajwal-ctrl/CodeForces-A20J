---
link: https://www.notion.so/92A-Chips-1794a0536aab81c5a214d8826bb46465
notionID: 1794a053-6aab-81c5-a214-d8826bb46465
---
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