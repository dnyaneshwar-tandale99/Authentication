import java.util.*;
import java.util.function.Predicate;

public class Main
{
    class User{
        private String User_name;
        private String password;
    }
    class User(String User_name,String password)
    {
        this.User_name=User_name;
        this.password=password;
    }
	public static void main(String[] args) {
	    Predicate<User>p=u->u.User_name.equals("Mauli")&&u.password.equals("Mauli@123");
	    Scanner sc=new Scanner(System.in);
	    System.out.println("Please enter User name");
	     Username=sc.next();
	     System.out.println("Plrase Enter Your Password");
	     Password=sc.next();
	     User user=new User();
	     if(p.test(user))
	     {
	         System.out.println("Welome to onBoard");
	     }
	     else{
	         System.out.println("Invali UserName or Paaword Please try again");
	     }
		
	}
}
