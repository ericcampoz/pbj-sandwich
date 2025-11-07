import java.util.Scanner;

public class PBJ {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.println("Do you have bread? (yes/no)");
        String bread = input.nextLine();

        System.out.println("Do you have peanut butter? (yes/no)");
        String peanutButter = input.nextLine();

        System.out.println("Do you have jelly? (yes/no)");
        String jelly = input.nextLine();

        if(bread.equals("yes") && peanutButter.equals("yes") && jelly.equals("yes")) {
            System.out.println("Step 1: Take two slices of bread.");
            System.out.println("Step 2: Spread peanut butter on one slice.");
            System.out.println("Step 3: Spread jelly on the other slice.");
            System.out.println("Step 4: Press the slices together and enjoy.");
        } 
        else {
            System.out.println("You are missing ingredients. No sandwich today.");
        }

        input.close();
    }
}
