---
link: https://www.notion.so/270A-Fancy-Fence-1794a0536aab814bb725c105b89e3a73
notionID: 1794a053-6aab-814b-b725-c105b89e3a73
---
```
#include <iostream>
using namespace std;

int main() {
    int t;
    cin >> t;  
    
    while (t--) {
        int a;
        cin >> a; 
        
        int n = 360 / (180 - a);
        
        if ( 360 % (180 - a) == 0 &&n >= 3) {
            cout << "YES" << endl;
        } else {
            cout << "NO" << endl;
        }
    }
    
    return 0;
}
```