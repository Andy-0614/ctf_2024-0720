### ME:
#### c
```c
#include <stdio.h>

int main() {
    int n=9,m=9;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=m;j++){
            printf("%dx%d=%d  ",i,j,i*j);
        }
        printf("\n");
    }
    return 0;
}
```
#### cpp
```cpp 
#include<bits/stdc++.h>
using namespace std;

int main(){
    int n=9,m=9;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=m;j++){
            cout << i << "x" << j << "=" << i*j << " ";
        }
        cout << endl;
    }
    return 0;
}
```
### AI:
#### c
```c
#include <stdio.h>

int main() {
    for (int i = 1; i <= 9; i++) {
        for (int j = 1; j <= 9; j++) {
            printf("%dx%d=%d\t", i, j, i * j);
        }
        printf("\n");
    }

    return 0;
}
```
#### cpp
```cpp
#include <iostream>

int main() {
    for (int i = 1; i <= 9; i++) {
        for (int j = 1; j <= 9; j++) {
            std::cout << i << "x" << j << "=" << i * j << "\t";
        }
        std::cout << std::endl;
    }

    return 0;
}
```
