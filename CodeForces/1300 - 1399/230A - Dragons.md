---
link: https://www.notion.so/230A-Dragons-1794a0536aab81949176da0c53633a3e
notionID: 1794a053-6aab-8194-9176-da0c53633a3e
---
```
#include <bits/stdc++.h>

using namespace std;

int main() {


    long long s, n;
    cin >> s >> n;

    vector < pair < int, int >> v;

    for (long long  i = 0; i < n; i++) {
        long long  xi, yi;
        cin >> xi >> yi;
        v.push_back({
            xi,
            yi
        });

    }

    sort(v.begin(), v.end());

    for (auto i: v) {
        if (i.first >= s) {
            cout << "NO";
            return 0;
        }
        else s += i.second;
    }

    cout << "YES" << endl;
}


```