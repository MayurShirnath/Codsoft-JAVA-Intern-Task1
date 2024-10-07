package com.company;
import java.util.Scanner;
import java.util.Random;
public class NumberGame {
    static Scanner guess = new Scanner(System.in);
    static Random random = new Random();
    int guess_number = 0;
    static int max_attempts = 5;
    static int attempts = 0;

    static int random_number = random.nextInt(100) + 1;
    
    public static void main(String[] args) {

        System.out.println("Enter your guess number :");
        int guess_number = guess.nextInt();
        attempts++;
        while (attempts < max_attempts && guess_number != max_attempts) {
            if (guess_number < random_number) {
                System.out.println("Your guess is too low!!");
            } else if (guess_number > random_number) {
                System.out.println("Your guess is too high!!");
            } else {
                System.out.println("Congratulation!!. You won the game in " + attempts + "attempts");
            }
            if (guess_number != random_number) {
                System.out.println("You have use all your attemps. The correct number is" + random_number);
            }
        }

    }
}
