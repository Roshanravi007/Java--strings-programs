package pak2_revision;

public class Pallindrome {
	public static void main(String[]arg) {
		String s1= "bob";
		String s2="";
		//int i=0;
		for(int i=s1.length()-1; i>=0; i--) {
			s2= s2 + s1.charAt(i);
			
			
		}
		if(s2.equals(s1)) {
			System.out.println("It is pallindrom");
		}else {
			System.out.println("It is not pallindrome");
		}
	}

}

