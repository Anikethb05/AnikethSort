
## Java Implementation

import java.util.Scanner;

class AnikethSort {
    public static void main(String[] args) {
        System.out.print("Enter size of array: ");
        Scanner scanner = new Scanner(System.in);
        int len = scanner.nextInt();
        int[] arr = new int[len];
        System.out.println("Enter elements: ");
        for (int i = 0; i < len; i++) {
            arr[i] = scanner.nextInt();
        }

        // Aniketh's Sorting Algorithm
        for (int i = 0; i < len; i++) {
            for (int j = 0; j < len; j++) {
                if (arr[j] > arr[i]) {
                    int temp = arr[j];
                    arr[j] = arr[i];
                    arr[i] = temp;
                }
            }
        }

        System.out.print("Sorted array: ");
        for (int i : arr) {
            System.out.print(i + " ");
        }
    }
}
