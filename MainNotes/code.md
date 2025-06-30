```cpp
/*

There're always cheaters whether you like or not.

So just enjoy the game.

*/

#include <bits/stdc++.h>

  

using ll = long long;

using ull = unsigned long long;

using i128 = __int128;

using u128 = __uint128_t;

  

int n;

  

void slv(){

    std::cin >> n;

    std::vector<int> a(n);

    for (int i = 0; i < n; i++) {

        std::cin >> a[i];

    }

    std::sort(a.begin()+1, a.end()-1);

    int cur = a[0], final = a[n-1];

    int b = 0, e = n - 1;

    int ans = 2;

    while(cur * 2 < final) {

        int l = b, r = e;

        while(l != r - 1) {

            int mid = (l + r) / 2;

            if(a[mid] <= cur * 2) {

                l = mid;

            } else {

                r = mid;

            }

        }

        if(l == b) {

            std::cout << "-1\n";

            return;

        }

        cur = a[l];

        ans++;

        b = l;

    }

    std::cout << ans << '\n';

}

  

int main(){

    std::ios::sync_with_stdio(false); std::cin.tie(nullptr);std::cout.tie(nullptr);

    int t; std::cin >> t;

    //int t; scanf("%d", &t);

    while(t--) slv();

}
```

