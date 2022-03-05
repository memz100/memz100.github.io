# my homepage
welcome to my github website!
<details><summary>Who is memz100?</summary>

me? im just a guy named Justin
from PA

</details>
<details><summary>credits</summary>
	
Justin: founder<br/>
Olivia: co-founder
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

package ar;<br/>
import java.util.Scanner;<br/>
import java.util.concurrent.TimeUnit;<br/>
import java.io.IOException;<br/>
import java.net.URI;<br/>
import java.net.URISyntaxException;<br/>
import java.util.Calendar;<br/>
import java.time.format.DateTimeFormatter;<br/>  
import java.time.LocalDateTime;<br/>
public class Ar1 {<br/>
public static void main(String[]args) throws IOException, URISyntaxException, InterruptedException{<br/>
	Scanner input = new Scanner(System.in);<br/>
	Calendar calendar = Calendar.getInstance();<br/>
	String jj = "";<br/>
	String notepad1 = "haha you lookin at de code here, get out";<br/>
	DateTimeFormatter dtf = DateTimeFormatter.ofPattern("yyyy/MM/dd HH:mm:ss");  <br/>
	   LocalDateTime now = LocalDateTime.now(); <br/>
	System.out.println("JvmOS v1.2.5");<br/>
	TimeUnit.SECONDS.sleep(1);<br/>
	String command = ""; <br/>
	String tempnote = "";<br/>
	while(command.equals("")) {<br/>
		notepad1 = tempnote;<br/>
	System.out.println("please type in your command, type 'help' for a list of commands");<br/>
	command=input.next();
	 if(command.equals("time")){<br/>
			System.out.println("the day is: "+calendar.getTime());<br/>
	 }<br/>
	 if(command.equals("help")) {<br/>
		 System.out.println("'time' = show time");<br/>
		 System.out.println("'notepad' = write and save in a string format");<br/>
		 System.out.println("'calc' = calculator");<br/>
		 System.out.println("'c/notepad1' = open notepad");<br/>
		 System.out.println("'about' = displays the system");<br/>
		 System.out.println("'web' = goes to the web on your default browser(faulty!)");<br/>
		 System.out.println("'close' = terminates the entire system!");<br/>
	 }<br/>
	<br/>
	 if(command.equals("notepad")) {<br/>
		 <br/>
		 System.out.println("well, type! (previous note will be deleted! no space or else!)");<br/>
		 tempnote=input.next();<br/>
	 }<br/>
		if(command.equals("c/notepad1")) {<br/>
			System.out.println(notepad1);<br/>
		}<br/>
			if(command.equals("about")) {<br/>

		}<br/>
		if(command.equals("calc")) {<br/>
		int n1;<br/>
		System.out.println("calc 1.0: please insert 1st number");<br/>
		n1=input.nextInt();<br/>
		System.out.println("please input your second number");<br/>
		int n2;<br/>
		n2=input.nextInt();<br/>
		System.out.println("what operation? +,-,*,/!");<br/>
		String op;<br/>
		op=input.next();<br/>
		if(op.equals("+")) {<br/>
			System.out.println(n1+n2);<br/>
		}<br/>
		if(op.equals("-")) {<br/>
			System.out.println(n1-n2);<br/>
		}<br/>
		if(op.equals("*")) {<br/>
			System.out.println(n1*n2);<br/>
		}<br/>
		if(op.equals("/")) {<br/>
			System.out.println(n1/n2);<br/>
		}<br/>
		}<br/>
		if(command.equals("web")) {<br/>
		System.out.println("Please Wait while we set up the browser...");<br/>			
		URI uri= new URI("https://www.google.com");<br/>
		java.awt.Desktop.getDesktop().browse(uri);<br/>
		}<br/>
			String close = "";<br/>
			if(command.equals("close")) {<br/>
				close = "gottem";<br/>
				System.out.println("ok...please wait");<br/>
			}<br/>
		TimeUnit.SECONDS.sleep(3);<br/>
	 command = jj;<br/>
	 while(close.equals("gottem")) {<br/>
		 System.out.println("closed");<br/>
		 System.exit(0);<br/>
	 }<br/>
	 }<br/>
	 <br/>
	 }<br/>
	<br/>
}	
</details>
