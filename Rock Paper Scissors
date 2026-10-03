package Passcode;

import java.util.Scanner;

class Main {
	
    public static void main(String[] args) {
    	
    	
    	int x = (int)(Math.random() * 3); // RPS
    	
    	String computerchoice = "";
    	
    	if(x == 0) {
    		computerchoice = "Rock";
    	} else if(x == 1) {
    		computerchoice = "Scissors";
    	} else if(x == 2) {
    		computerchoice = "Paper";
    	}
    	
    	
    	System.out.println();
    	
    	Scanner input = new Scanner(System.in);
    	
    	String userinput = input.nextLine();
    	
    	input.close();
    	
    	System.out.println(userinput);
    	
    	System.out.println(computerchoice);
    	
    	if(computerchoice.equalsIgnoreCase("Rock")) {
    		if(userinput.equalsIgnoreCase("Scissors")) {
    			System.out.println("Computer WIN");
    		}
    	}
    	
    	if(computerchoice.equalsIgnoreCase("Scissors")) {
    		if(userinput.equalsIgnoreCase("Rock")) {
    			System.out.println("User WIN");
    		}
    	}
    	
    	if(computerchoice.equalsIgnoreCase("Paper")) {
    		if(userinput.equalsIgnoreCase("Rock")) {
    			System.out.println("Computer WIN");
    		}
    	}
    	
    	if(computerchoice.equalsIgnoreCase("Rock")) {
    		if(userinput.equalsIgnoreCase("Paper")) {
    			System.out.println("User WIN");
    		}
    	}
    	
    	if(computerchoice.equalsIgnoreCase("Scissors")) {
    		if(userinput.equalsIgnoreCase("Paper")) {
    			System.out.println("Computer WIN");
    		}
    	}
    	
    	if(computerchoice.equalsIgnoreCase("Paper")) {
    		if(userinput.equalsIgnoreCase("Scissors")) {
    			System.out.println("User WIN");
    		}
    	}
    	
    	if(computerchoice.equalsIgnoreCase(userinput)) {
    		System.out.println("Tie");
    	}

    }
}
