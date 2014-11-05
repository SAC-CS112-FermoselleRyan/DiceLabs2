DiceLabs2
=========
import java.util.*;

public class DiceLab{
	public class PairOfDice {
        
        public int die1;  
        public int die2;   
        
        public PairOfDice() {
                
            roll();  
        }
        
        public void roll() {
                
            die1 = (int)(Math.random()*6) + 1;
            die2 = (int)(Math.random()*6) + 1;
        }

		public String getDie1() {
			
			return null;
		}

		public String getDie2() {
			// TODO Auto-generated method stub
			return null;
		}

		public int getTotal() {
			// TODO Auto-generated method stub
			return 0;
		}
        
    } 
	


public class PairOfDice1 {

   private int die1;   
   private int die2;   
   
   public PairOfDice1() {
           
       roll();  
   }
   
   public void roll() {
           
          
       die1 = (int)(Math.random()*6) + 1;
       die2 = (int)(Math.random()*6) + 1;
   }
            
   public int getDie1() {
        
      return die1;
   }
   
   public int getDie2() {
         
      return die2;
   }
   
   public int getTotal() {
         
      return die1 + die2;
   }
   
}  

