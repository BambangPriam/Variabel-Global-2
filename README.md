# Variabel-Global-2

    #include <stdio.h>
    #include <conio.h>

    int c = 4;
    int m = 3;

    void lokal(){
    int a = 5;
    int b = a+2;
    printf("lokal a = %d\n", a);
    printf("lokal b = %d\n", b);
    printf("global c = %d\n", c);

    }
    void main(){
        int a = 1;
        int b = 2;
        int c = 3;
        lokal();
        printf("main a = %d\n", a);
        printf("main b = %d\n", b);
        printf("main c = %d\n", c);
        printf("global m = %d\n", m);
        _getch();
    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Variabel-Global-2/master/Variabel%20Global%202.png)
