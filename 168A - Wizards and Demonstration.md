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