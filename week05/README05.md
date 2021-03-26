## 第五周正課

```c
#include <stdio.h>
int main()
{
    char line[10]="decline";
    char line2[10]={'p','r','o','p','e','r','\0'};

    printf("%s\n",line);
    printf("%s\n",line2);

    char line3[]="majority";
    printf("%s\n",line3);
    char line4[]={'m','a','j','o','r','i','t','y'};
    printf("line4:==%s==\n",line4);
}
```
![week05-1](https://user-images.githubusercontent.com/71545492/112566602-44d47400-8e1a-11eb-82a4-873d265e3687.png)

```c
#include <stdio.h>
int main()
{
    char line[5][10]={"decline","proper","majority","bullet","shop"};

    for(int i=0;i<5;i++)
    {
        printf("%s\n",line[i]);
    }
}
```
![week05-2](https://user-images.githubusercontent.com/71545492/112568174-05f3ed80-8e1d-11eb-8efc-585775f6450d.png)
