# git-clone-https-github.com-example-repository.git-cd-repository



public class ModularProgram {

    public static void printMessage() {
        System.out.println("Welcome to Software Construction!");
    }

    /**
     * Calculates and returns the sum of two integers.
     *
     * @param a First integer
     * @param b Second integer
     * @return Sum of a and b
     */
    public static int calculateSum(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        printMessage();
        int result = calculateSum(10, 20);
        System.out.println("Sum: " + result);
    }
}
