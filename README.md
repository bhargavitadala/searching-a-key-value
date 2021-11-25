# searching-a-key-value
searching a key value using c language
#include<stdio.h>
int main(){
    int i,k,n,flag=0;
    int a[]={1,3,5,6,8,9};
    scanf("%d",&k);
    for(i=0;i<n;i++){
        if(a[i]==k){
            flag=1;
            break;
        }
    }
    if(flag==1){
        printf("%d",i);
    }
    else{
        printf("doesnot exist");
    }
}
