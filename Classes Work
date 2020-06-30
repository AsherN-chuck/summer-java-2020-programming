class Main{

     public static void main(String []args){
        Bike Redbike = new Bike("The Red bike");
        Bike Bluebike = new Bike("The Blue bike");
        Car Greencar = new Car("The Green car");
        Redbike.pedaling(); 
        Redbike.speedUp();
        Bluebike.pedaling();
        Greencar.revving();
        Greencar.speedUp();
        Redbike.slowDown();
        Greencar.turning();
        Greencar.slowDown();
        Bluebike.speedUp();
     }
}

    class Bike extends Vehicle{
        public Bike(String Startsequence){
            this.Startsequence = Startsequence;
        }
        public void pedaling(){
            System.out.println(Startsequence + " is starting to pedal.");
        }
    }
    class Car extends Vehicle{
        public Car(String Startsequence){
            this.Startsequence = Startsequence; 
        }
        public void revving(){
            System.out.println(Startsequence + " is revving up.");
        }
    }
    class Vehicle{
        String Startsequence; 
        
        public void speedUp(){
            System.out.println(Startsequence + " is speeding up.");
        }
        public void slowDown(){
            System.out.println(Startsequence + " is slowing down.");
        }
        public void turning(){
            System.out.println(Startsequence + " is turing a corner.");
        }
    }