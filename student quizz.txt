import java.util.Scanner;


public class Main
{
	
public static void main(String[] args){
        
String myobj =""; 
String myobj1 =""; 
String myobj2 =""; 
String myobj3 =""; 
String myobj4 ="";


 
    

 
        
        
int answer = 0;

int wrong_answer = 0;
        
int question = 5;
	    
Scanner reader = new Scanner(System.in);
		

System.out.println("what is the capital of india?");
		
System.out.println("a: delhi");
		
System.out.println("b: mumbai");
	
		 
myobj = reader.nextLine();
		

String result = (myobj.equals("a") ? "correct.": "wrong...The correct answer is - a: delhi");

System.out.println(result);

if(myobj.equals("a"))
{
    answer+=1;
}
else
{
    wrong_answer+=1;
}

System.out.println("-----------------------------------------------------------------------");



System.out.println("who is developer in c program?");

System.out.println("a: bjarne stroustrup");

System.out.println("b: dennis ritchi");
	
myobj1 = reader.nextLine();

String result1 = (myobj1.equals("b") ? "correct.": "wrong...The correct answer is - b: dennis ritchi");

System.out.println(result1);

if(myobj1.equals("b"))
{
    answer+=1;
}
else
{
    wrong_answer+=1;
    
}


System.out.println("-----------------------------------------------------------------");


System.out.println("SQL stands is_________?");

System.out.println("a: structure query language");

System.out.println("b: standard query language");
	
myobj2 = reader.nextLine();

String result2 = (myobj2.equals("a") ? "correct.": "wrong...The correct answer is - a: structure query language ");

System.out.println(result2);

if(myobj2.equals("a"))
{
    answer+=1;
}
else
{
    wrong_answer+=1;
}


System.out.println("----------------------------------------------------------------------");


System.out.println("what is capital of tamilnad?");

System.out.println("a: bangalore");

System.out.println("b: chennai");
	
myobj3 = reader.nextLine();

String result3 = (myobj3.equals("b") ? "correct.": "wrong...The correct answer is - b: chennai");

System.out.println(result3);

if(myobj3.equals("b"))
{
    answer+=1;
}
else
{
    wrong_answer+=1;
}


System.out.println("-----------------------------------------------------------------");


System.out.println("who is microsoft founder?");

System.out.println("a: bill gates");

System.out.println("b: steve jobs");
	
myobj4 = reader.nextLine();

String result4 = (myobj4.equals("a") ? "correct.": "wrong...The correct answer is - a: bill gates");

System.out.println(result4);

if(myobj4.equals("a"))
{
    answer+=1;
}
else
{
    wrong_answer+=1;
}

System.out.println("--------------------------------------------------------------------");


System.out.println("Total Question is:" + question);
System.out.println("correct answer is:" + answer);
System.out.println("wrong answer is:" + wrong_answer);



}
}

