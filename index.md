# my homepage
welcome to my github website!
<details><summary>Who is memz100?</summary>

me? im just a guy named Justin
from PA

</details>

here i try to do things called operating systems
## Projects

### OS
i call it JvmOS(Java virtual machine Operating System)

.[i hope you enjoy!](https://github.io/memz100/JvmOS)
link is broken so: 
### CURRENT VERSION: 
**JvmOS**
<details open>
<summary>JvmOS 1.25</summary>
<br>

```	
	package ar;
	import java.util.Scanner;
	import java.util.concurrent.TimeUnit;
	import java.io.IOException;
	import java.net.URI;
	import java.net.URISyntaxException;
	import java.util.Calendar;
	import java.time.format.DateTimeFormatter;  
	import java.time.LocalDateTime;
	public class Ar1 {
	public static void main(String[]args) throws IOException, URISyntaxException, InterruptedException{
	Scanner input = new Scanner(System.in);
	Calendar calendar = Calendar.getInstance();
	String jj = "";
	String notepad1 = "haha you lookin at de code here, get out";
	DateTimeFormatter dtf = DateTimeFormatter.ofPattern("yyyy/MM/dd HH:mm:ss");  
	   LocalDateTime now = LocalDateTime.now(); 
	System.out.println("JvmOS v1.2.5");
	TimeUnit.SECONDS.sleep(1);
	System.out.print("\r\n"
			+ "                                                                    \r\n"
			+ "         ,---._                               ,----..               \r\n"
			+ "       .-- -.' \\                    ____     /   /   \\   .--.--.    \r\n"
			+ "       |    |   :                 ,'  , `.  /   .     : /  /    '.  \r\n"
			+ "       :    ;   |              ,-+-,.' _ | .   /   ;.  \\  :  /`. /  \r\n"
			+ "       :        |    .---.  ,-+-. ;   , ||.   ;   /  ` ;  |  |--`   \r\n"
			+ "       |    :   :  /.  ./| ,--.'|'   |  ||;   |  ; \\ ; |  :  ;_     \r\n"
			+ "       :         .-' . ' ||   |  ,', |  |,|   :  | ; | '\\  \\    `.  \r\n"
			+ "       |    ;   /___/ \\: ||   | /  | |--' .   |  ' ' ' : `----.   \\ \r\n"
			+ "   ___ l        .   \\  ' .|   : |  | ,    '   ;  \\; /  | __ \\  \\  | \r\n"
	    	+ " /    /\\    J   :\\   \\   '|   : |  |/      \\   \\  ',  / /  /`--'  / \r\n"
			+ "/  ../  `..-    , \\   \\   |   | |`-'        ;   :    / '--'.     /  \r\n"
			+ "\\    \\         ;   \\   \\ ||   ;/             \\   \\ .'    `--'---'   \r\n"
			+ " \\    \\      ,'     '---\" '---'               `---`                 \r\n"
			+ "  \"---....--'                                                       \r\n"
			+ "                                                                    \r\n"
			+ "");
	String command = ""; 
	String tempnote = "";
	while(command.equals("")) {
		notepad1 = tempnote;
	System.out.println("please type in your command, type 'help' for a list of commands");
	command=input.next();
	 if(command.equals("time")){
			System.out.println("the day is: "+calendar.getTime());
	 }
	 if(command.equals("help")) {
		 System.out.println("'time' = show time");
		 System.out.println("'notepad' = write and save in a string format");
		 System.out.println("'calc' = calculator");
		 System.out.println("'c/notepad1' = open notepad");
		 System.out.println("'about' = displays the system");
		 System.out.println("'web' = goes to the web on your default browser(faulty!)");
		 System.out.println("'close' = terminates the entire system!");
	 }
	
	 if(command.equals("notepad")) {
		 
		 System.out.println("well, type! (previous note will be deleted! no space or else!)");
		 tempnote=input.next();
	 }
		if(command.equals("c/notepad1")) {
			System.out.println(notepad1);
		}
		if(command.equals("c/whyDidYouKillHim")) {
			while(true) {
				System.out.println("aSBkaWRudCBtZWFuIHRvLCBpdCB3YXMgTk9UIE1ZIEZBVUxUIQ==");
				System.out.println("15 Jan 1984");
			}
		}
			if(command.equals("about")) {
				System.out.println("System: Java virtual machine Operating System");
				System.out.println("processor: Java Virtual Augmentation core 4004 740 kHZ");
				System.out.println("memory: 52k DRAM");
				System.out.println("disk: 2 GB HD");
		}
			if(command.equals("calc")) {
				int n1;
				System.out.println("calc 1.0: please insert 1st number");
				n1=input.nextInt();
				System.out.println("please input your second number");
				int n2;
				n2=input.nextInt();
				System.out.println("what operation? +,-,*,/!");
				String op;
				op=input.next();
				if(op.equals("+")) {
					System.out.println(n1+n2);
				}
				if(op.equals("-")) {
					System.out.println(n1-n2);
				}
				if(op.equals("*")) {
					System.out.println(n1*n2);
				}
				if(op.equals("/")) {
					System.out.println(n1/n2);
				}
				}
			if(command.equals("web")) {
				System.out.println("Please Wait while we set up the browser...");			
				URI uri= new URI("https://www.google.com");
				java.awt.Desktop.getDesktop().browse(uri);
			}
			String close = "";
			if(command.equals("close")) {
				close = "gottem";
				System.out.println("ok...please wait");
			}
		TimeUnit.SECONDS.sleep(3);
	 command = jj;
	 while(close.equals("gottem")) {
		 System.out.println("closed");
		 System.exit(0);
	 }
	 }
	 
	 }
	
	}
```
</details>
