
class Arithmetic{
	String name;
	public void inc(int a)
	{
		System.out.println(++a);
	}
	public void dec(int a)
	{
		System.out.println(--a);
	}
	
}
public class Jala {

	public static void main(String[] args) {
		
		Arithmetic var = new Arithmetic();
		
		var.inc(5);
		var.dec(5);
	}

}
