
package venkat;
import java.util.*;

public class Simpleproject1 {
	public static void main(String args[]) {
		Hashtable<Integer,String> A1 = new Hashtable<Integer,String>();
		A1.put(100,"ramesh");
		A1.put(200,"suresh");
		A1.put(300,"mahesh");		
		System.out.println("Simpleproject1");
						
	}

}
Option to remove or delete mahesh on week 2
package venkat;
import java.util.*;

public class Simpleproject1 {
	public static void main(String args[]) {
		Hashtable<Integer,String> A1 = new Hashtable<Integer,String>();
		A1.put(100,"ramesh");
		A1.put(200,"suresh");
		A1.put(300,"mahesh");		
		System.out.println("Simpleproject1");
		A1.remove(300);
		System.out.println("removed 300");
				
	}

}

================================================================================================================================
file reader
============
package venkat;
import java.io.*;

public class Filout {
	public static void main(String args[]) throws IOException{
		InputStreamReader zin =null;
		try {
			zin = new InputStreamReader(System.in);
			System.out.println("Enter character, 'q' to quit. ");
			char p;
			do {
				p = (char) zin.read();
				System.out.println("c");
				
			}while(p != 'q');
		}
		finally {
			if (zin  != null) {
				zin.close();
			}
		}
			
			
			}
			
	}
