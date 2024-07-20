# 20240720
## 0720 ~ 0721 東台灣高中職資安盛會

### GenAI - 生成式AI
- [ChatGPT 4o](https://chatgpt.com/)
- [Gemini](https://gemini.google.com/)
- [Claude](https://claude.ai/)
- [Copilot](https://www.bing.com/chat)

### 題目
#### [prompt提示詞1](prompt1.md) 文字===>文字
```
CIA TRIAD:Confidentiality, Integrity, and Availability
你是專家,請用十頁簡報說明CIA TRIAD
```

#### [prompt提示詞2](prompt2.md) 文字===>圖片
```
請為李白的將近酒畫一幅水墨畫
```

#### [prompt提示詞3](prompt3.md) 文字===>程式
##### ME:
```c
#include <stdio.h>

int main() {
    int n=9,m=9;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=m;j++){
            printf("%dx%d=%d\t",i,j,i*j);
        }
        printf("\n");
    }
    return 0;
}
```
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
##### AI:
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
