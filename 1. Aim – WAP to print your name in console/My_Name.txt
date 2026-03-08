
// Date:- 07/Feb/2026
// WAP to print your name in java console
/*
	Steps to execute via console
		Note:- I'm using PowerShell for code compilation and  execution
	1. Open PowerShell is same Dir
	2. Check Java compiler & JRE config, it should be of same version, or config your system for with correct java versions.
		PS E:\Learn_Java\Java_Practice> javac -version
			javac 22.0.1
		PS E:\Learn_Java\Java_Practice> java -version
			java version "22.0.1" 2024-04-16
			Java(TM) SE Runtime Environment (build 22.0.1+8-16)
			Java HotSpot(TM) 64-Bit Server VM (build 22.0.1+8-16, mixed mode, sharing)

	3. Write your code in a .txt file and save it with a name, like- My_Name.txt
	4. Now save My_Name.txt as My_Name.java.
	5. Now compile My_Name.java via PowerShell
		PS E:\Learn_Java\Java_Practice> javac My_Name.java
	
	6. Do ls for verification, code compiled successfully, and a new file crated with code's class name, like my_Name.class
		PS E:\Learn_Java\Java_Practice> ls
		Directory: E:\Learn_Java\Java_Practice

		Mode                 LastWriteTime         Length Name
		----                 -------------         ------ ----
		-a----          3/7/2026  11:42 PM            426 my_Name.class
		-a----          3/7/2026  11:41 PM           1607 My_Name.java
		-a----          3/7/2026  11:40 PM           1607 My_Name.txt


	7. Now run your code via final class file created from compilation process.
		PS E:\Learn_Java\Java_Practice> java my_Name
		I'm HyperGenX-24
*/

class my_Name
{
	public static void main(String args[])
	{
		System.out.println("I'm HyperGenX-24");
	}
}