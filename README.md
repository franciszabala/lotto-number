# lotto-number

import java.util.Random;

class wenax {
	public static void main (String []arg){
		Random lotto = new Random();
		int number;
		for (int counter=1 ; counter <7; counter++){
			number = lotto.nextInt(46);
			System.out.println("the lucky number:   " + number );
		}
	   }
   }
