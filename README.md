
public class Inky{
    public Inky(String pinky){
        System.out.println(pinky);
    }
    public Inky(String pinky,String blinky,String rinky){
        System.out.println(blinky + " " + pinky);
        System.out.println(pinky + " " + rinky);
        System.out.println(blinky + " " + pinky + " " + rinky);
    }

    public static void main(String args[]){
        String pinky = "Donky";
        String blinky = "Pinky";
        String rinky = "Monkey";

        Inky ponky = new Inky(pinky);

        Inky ponky2 = new Inky(pinky,blinky,rinky);
    }
}