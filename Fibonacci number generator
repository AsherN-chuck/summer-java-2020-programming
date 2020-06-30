class HelloWorld{

     public static void main(String []args){
         //Integer threeNumbers is used so the first three numbers are stated before the formula begins.
         //Integer amount is used to make sure the amount of numbers doesn't go past 100.
         //Integer first is the first number in the sequence. 
         //Integer second is the second number in the sequence.
         //Integer thrid is the third number in the sequence. 
         //first, second, and third are also used in a formula to create the next numbers in the sequence. 
         int threeNumbers=0;
         int amount=0;
         double first=0;
         double second=1;
         double thrid=1;
         
         //This is the if statement for the first three numbers
             if (threeNumbers==0){
                System.out.println("1=" + first);
                System.out.println("2=" + second);
                System.out.println("3=" + thrid);
                amount=amount+3;
                threeNumbers=1;
             }
             
         while (amount<=100){
             
            first=second+thrid;
            amount=amount+1;
            System.out.println(amount + "=" + first);
            
            //Used a break sequence since it would have had 2 extra numbers otherwise. 
            if(amount==100){
                break;
            }
            
            second=first+thrid;
            amount=amount+1;
            System.out.println(amount + "=" + second);
            
            thrid=first+second;
            amount=amount+1;
            System.out.println(amount + "=" + thrid);
         }
        
     }
}