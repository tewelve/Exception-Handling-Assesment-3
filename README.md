# Exception-Handling-Assesment-3

public class NullpointerExceptionEx
{
	public static void main(String[]args)
	{
		try
		{
			String s1=null;
			System.out.println(s1.charAt(1));
		}
		catch(NullPointerException e)
		{
			System.out.println("Null pointer Exception");
			
		}
			
	}
}
	
