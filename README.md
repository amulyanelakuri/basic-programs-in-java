# basic-programs-in-java
// Java program to find sum of the numbers Enter by the count
import java.util.*;

public class Main {
    public static void main(String[] args) {
      int count;
      Scanner sc = new Scanner(System.in);
      System.out.println("Enter the count of the numbers :");
      int num,sum=0;
      for(int i =0;i<count;i++){
        num = sc.nextInt();
        sum = num+sum;
      }
      System.out.println("Sum of all of these numbers : " +sum);
  }
}
// java program to find sum of the numbers by user
import java.util.Scanner;

public class Main {
    public static void main(String[] args) 
    {
      int num1,num2;
      Scanner sc = new Scanner(System.in);
      num1 = sc.nextInt();
      System.out.println("Enter a num1 value :");
      num2 = sc.nextInt();
      System.out.println("Enter a num2 value :");
      System.out.println("Sum of these numbers is:"+ (num1+num2));
  }
}
// java program on the find the averages numbers entered by user
import java.util.*;

public class Main {
    public static void main(String[] args) {
      int count;
      Scanner sc = new Scanner(System.in);
      System.out.println("Enter the count of the numbers : ");
      count =sc.nextInt();
      int num,sum=0;
      float average = 0;
      for(int i=0;i<count;i++)
      {
        num=sc.nextInt();
        sum = sum+num;
        average = sum/count;
      }
      System.out.println("average of the numbers :"+average);
  }
}
// sum the array in java
public class Main {
    public static void main(String[] args) {
      int[] array={1,2,3,4,5};
      int length = array.length;
      int sum = 0;
      for(int i = 0;i<length;i++){
        sum = sum+array[i];
      }
      System.out.println("enter the sum of the array : "+sum);
      float average = (float)sum/length;
      System.out.println("Enter the avg of th array :"+average);
  }
}
// find the maximum number in array  
public class Main
{
	public static void main(String[] args) {
	    int[] arr = {1,2,3,4,5};
	    int max = arr[0];
	    for(int i =0;i <arr.length;i++){
	        if(arr[i]>max)
	          max = arr[i];
	    }
	    System.out.println("Largest element in the array :"+max);
	    
	}
		
}

// find the minimum number in array

public class Main
{
	public static void main(String[] args) {
	    int[] arr = {1,2,3,4,5};
	    int min = arr[0];
	    for(int i =0;i >arr.length;i++){
	        if(arr[i]<max)
	          min = arr[i];
	    }
	    System.out.println("Largest element in the array :"+min);
	    
	}
		
}
// sorting in the array 

public class Main {
    public static void main(String[] args) {
     int[] array = {21,45,12,67,34,43,25};
     Arrays.sort(array);
     for(int i=0;i<array.length;i++)
     {
       System.out.println(array[i]);
     }
    }
}  


