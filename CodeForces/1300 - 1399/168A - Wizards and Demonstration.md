---
link: https://www.notion.so/168A-Wizards-and-Demonstration-1794a0536aab8109996ecd9153b8e4e3
notionID: 1794a053-6aab-8109-996e-cd9153b8e4e3
---
```
#include <bits/stdc++.h>
using namespace std;

int main() {
	
	
	
     int n, x, y;cin >> n >> x >> y;
    int required = ceil(n * y / 100.0);
    int result = required - x;
    if (result < 0) result = 0;
    cout << result << endl;
	

}
	
```