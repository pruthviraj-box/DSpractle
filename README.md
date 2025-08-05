# DSpractle
progrm of DS



1 .# include <stdio.h>
int main(){
    int arr[5]= {1,2,3,5,6};
    int sum=0;
    int length=sizeof(arr)/sizeof(arr[0]);
    for (int i = 0; i<length ;i++)
    {sum = sum+arr[i];
    }
    printf("sum of all element of array is %d ",sum);
    return 0;
    
}



2
# include <stdio.h>
int main (){
int n;
printf("enter the number in an array : ");
scanf("%d",&n);
int arr[n];
printf("Enter %d in the array .",n);
for (int i=0; i<n;i++){
    scanf ("%d",&arr[i]);
}
printf ("all number are even \n");
for (int i=0; i<n;i++){
    if (arr[i]%2==0){
        printf(" %d ",arr[i]);
    }
}
printf("\nAll numbe are odd\n ");
for (int i ; i<n ;i++){
    if (arr[i]%2==1){
        printf(" %d ",arr[i]);
    }
}
