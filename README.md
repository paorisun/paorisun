// N번 입력받아 누적 합을 구하는 알고리즘.

#include <stdio.h>
int total = 0;
int add(int num);
int add(int num){
    
    total = total+num;
    return total;

}
int main(){

    int num;
    for(int i = 0; i<3; i++){
        printf("Input int 4byte data %d번째 입력 : \n",i+1);
        scanf("%d",&num);
        printf("SUM : %d\n",add(num));
    }

}
