```
#include <bits/stdc++.h>

using namespace std;
#define ll long long


int main() {

    string s;
    cin >> s;
    ll l = s.size();

    string word = "";
    for (int i = 0; i < l; i++) {
        if (s[i] == 'W' && s[i + 1] == 'U' && s[i + 2] == 'B') {
            i += 2;
            word += " ";

        } else {
            word += s[i]; // Add character to the current word
        }
    }


    cout << word << endl;



}
```