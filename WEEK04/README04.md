## 第四周正課

struct 結構 (定義/宣告、使用)
```c
#include <stdio.h>

struct POINT {
    float x,y;
};

int main()
{
    struct POINT a;
}
```
![week04-1](https://user-images.githubusercontent.com/71545492/111721008-0844cd80-889a-11eb-80ee-476265fd441b.png)


```c
#include <stdio.h>

struct POINT {
    float x,y;
};

int main()
{
    struct POINT a = {4.1,3.2};
    printf("%f %f\n",a.x,a.y);
}
```
![week04-2](https://user-images.githubusercontent.com/71545492/111722247-712d4500-889c-11eb-9869-a90d1842add5.png)


```c
#include <stdio.h>

struct POINT {
    float x,y;
};

int main()
{
    struct POINT a = {4.1,3.2};
    printf("%f %f\n",a.x,a.y);

    a.x=1;
    a.y=2;
    printf("%f %f\n",a.x,a.y);
}
```
![week04-3](https://user-images.githubusercontent.com/71545492/111722786-7f2f9580-889d-11eb-818e-9c8ca7eeaf0f.png)
