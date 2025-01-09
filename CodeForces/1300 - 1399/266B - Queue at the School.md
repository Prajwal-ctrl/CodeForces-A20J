```
#include <bits/stdc++.h>

using namespace std;

int main() {
    long long n, t;
    cin >> n >> t;

    string s;
    cin >> s;
    while (t--) {
        for (int i = 0; i < n; i++) {
            if (s[i] == 'B' && s[i + 1] == 'G') {
                swap(s[i], s[i+1]);
                i++ ; 
            }
        }
    }

    cout << s << endl;

}
```

In this you should realize the given process. You should _t_ times swap elements _i_ and _i_ + 1 if on the place _i_ was a girl and on the place _i_ + 1 was a boy. You should not push some girl to the left multiple times at once. The solution can be written using _O_(_N_·_T_) time.