# JAVAPREP

package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("what is your name");
		String name=sc.nextLine();
		System.out.println("what is your age");
		int age=sc.nextInt();
		System.out.println(name);
		System.out.println(age);
		
		
		
	} 

} 


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("what is your name");
		String name=sc.nextLine();
		System.out.println("what is your age");
		int age=sc.nextInt();
		sc.nextLine();
		System.out.println("what is your fav food");
		String food=sc.nextLine();
		
		System.out.println(name);
		System.out.println(age);
		System.out.println(food);
		
		
		
	} 

} 



package my_first_java_Project;

public class main {

	public static void main(String[] args) {
		double x=3.14;
		double y=-10;
		double z=Math.min(x, y);
		System.out.println(z);
	} 

} 


package my_first_java_Project;

public class main {

	public static void main(String[] args) {
		double x=3.14;
		double y=-10;
		double z=Math.max(x, y); //3.14
		System.out.println(z);
	} 

} 


package my_first_java_Project;

public class main {

	public static void main(String[] args) {
		double x=3.14;
		double y=-10;
		double z=Math.sqrt(x);//1.17
		System.out.println(z);
	} 

} 


package my_first_java_Project;

public class main {

	public static void main(String[] args) {
		double x=3.14;
		double y=-10;
		double z=Math.ceil(x);// 4
		System.out.println(z);
	} 

} 


package my_first_java_Project;

public class main {

	public static void main(String[] args) {
		double x=3.14;
		double y=-10;
		double z=Math.floor(x);//3
		System.out.println(z);
	} 

} 
