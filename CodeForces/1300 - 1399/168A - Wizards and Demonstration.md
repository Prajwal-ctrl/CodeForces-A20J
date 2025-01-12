---
link: https://www.notion.so/168A-Wizards-and-Demonstration-1794a0536aab81f49722d9fb49f488a0
notionID: 1794a053-6aab-81f4-9722-d9fb49f488a0
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