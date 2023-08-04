# BubbleSortnew
here is a code of BubbleSort in java.

public class Bubblesort {
    public static void BubbleSort(int array[]){
        for(int turn=0;turn<array.length-1;turn++){
            for(int j=0;j<array.length-1-turn;j++){
                if(array[j]>array[j+1]){
                    int temp = array[j];
                    array[j] = array[j+1];
                    array[j+1] = temp;
                } 
            }
        }
    }
public static void printarray(int array[]) {
    for(int i=0;i<+array.length;i++){
        System.out.print(array[i]+ " ");
    }
System.out.println();
}
public static void main(String[] args) {
    int array[] = {3,2,5,6,7};
BubbleSort(array);
printarray(array);
}
}


