# java-built-in-function
built in function
Arthemetic exception:
class ArithmeticException_Demo {
public static void main(String args[])
    {
        try {
            int a = 30, b = 0;
            int c = a / b; // cannot divide by zero
            System.out.println("Result = " + c);
        }
        catch (ArithmeticException e) {
            System.out.println("Can't divide a number by 0");
        }
    }
}

OUT OF THE BOUND EXCEPTION
class ArrayIndexOutOfBound_Demo {
public static void main(String args[])
    {
        try {
            int a[] = new int[5];
            a[6] = 9; // accessing 7th element in an array of
            // size 5
        }
        catch (ArrayIndexOutOfBoundsException e) {
            System.out.println("Array Index is Out Of Bounds");
        }
    }
}
CLASS NOT FOUND EXCEPTION
class ArrayIndexOutOfBound_Demo {
public static void main(String args[])
    {
        try {
            int a[] = new int[5];
            a[6] = 9; // accessing 7th element in an array of
            // size 5
        }
        catch (ArrayIndexOutOfBoundsException e) {
            System.out.println("Array Index is Out Of Bounds");
        }
    }
}
