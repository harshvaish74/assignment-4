public class SwapBubble
{
        static void bubbleSort(int[] arr) {  
        int n = arr.length;  
        int temp = 0;  
        int cont = 0;
         for(int i=0; i < n; i++){  
                 for(int j=1; j < (n-i); j++){  
                          if(arr[j-1] > arr[j]){  
                                 //swap elements  
                                 temp = arr[j-1];  
                                 arr[j-1] = arr[j];  
                                 arr[j] = temp;  
                                 cont += 1;
                         }  
                          
                 }  
         } 
         System.out.println("Cuenta de swap " + cont);
    }  
    public static void main(String[] args) {  
                //int arr[] ={3,60,35,2,45,320,5};
                //int arr[] ={2,1,4,6,3};
                int arr[] ={123, 21, 34, 45, 25, 675, 23, 44, 55, 900};
                System.out.println("Array antes de Bubble Sort");  
                for(int i=0; i < arr.length; i++){  
                        System.out.print(arr[i] + " ");  
                }  
                System.out.println();  
                  
                bubbleSort(arr);//sorting array elements using bubble sort  
                 
                System.out.println("Array despues de Bubble Sort");  
                for(int i=0; i < arr.length; i++){  
                        System.out.print(arr[i] + " ");  
                }  
    }     
}
