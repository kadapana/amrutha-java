public class MergeSort {
    public static void main(String[] args) {
        int[] arr = {64, 25, 12, 22, 11};  

        System.out.println("Original Array:");
        printArray(arr);

        mergeSort(arr, 0, arr.length - 1);

        System.out.println("\nSorted Array in Ascending Order:");
        printArray(arr);
    }

  
    public static void mergeSort(int[] arr, int left, int right) {
        if (left < right) {
          
            int mid = (left + right) / 2;

          
            mergeSort(arr, left, mid);
            mergeSort(arr, mid + 1, right);

        
            merge(arr, left, mid, right);
        }
    }

    
