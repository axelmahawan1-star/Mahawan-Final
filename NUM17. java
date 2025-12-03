public class Number17 {
    public static void main(String[] args) {

        int[] arr = { 12, 35, 1, 10, 34, 1 };

        System.out.print("Array: ");
        for (int i = 0; i < arr.length; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();

        int highest, secondHighest;
        if (arr[0] > arr[1]) {
            highest = arr[0];
            secondHighest = arr[1];
        } else {
            highest = arr[1];
            secondHighest = arr[0];
        }

        for (int i = 2; i < arr.length; i++) {
            if (arr[i] > highest) {
                secondHighest = highest;
                highest = arr[i];
            } else if (arr[i] > secondHighest && arr[i] != highest) {
                secondHighest = arr[i];
            }
        }

        System.out.println("The second highest number is: " + secondHighest);
    }
}
