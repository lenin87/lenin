
## bubbole sort

###### var arr = [36,25,45,5,7,89,62,31,100];
###### var length = arr.length-1;
###### for (var i =0; i< length;  i++) {

###### for (var j = 0; j <= length; j++) {
###### if (arr[j] > arr[j+1]) {
###### var tmp = arr[j];
###### arr[j] = arr[j+1];
###### arr[j+1] = tmp;
###### }
###### }
###### }
###### console.log(arr);
output :  [5, 7, 25, 31, 36, 45, 62, 89, 100]



## selection sort

###### var arr = [36,25,45,5,7,89,62,31,100,1]; 
###### var length = arr.length;
###### var min;
###### for(var i=0; i<length;i++){
###### min =i;
###### for(j=i+1;j<length;j++){
###### if(arr[j]< arr[min]){
###### min=j;
###### }
###### }
###### var tmp = arr[min];
###### arr[min]= arr[i]
###### arr[i]=tmp;
###### }
###### console.log(arr);

output : [1, 5, 7, 25, 31, 36, 45, 62, 89, 100]

