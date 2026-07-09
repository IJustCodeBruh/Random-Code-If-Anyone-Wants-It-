using System;

class RandomProgram {
    static void Main() {
        // Generate a random number between 1 and 100
        Random random = new Random();
        int randomNumber = random.Next(1, 101);
        
        Console.WriteLine("Random number: " + randomNumber);
        
        // Generate a random string
        string[] colors = { "Red", "Blue", "Green", "Yellow", "Purple" };
        int randomIndex = random.Next(colors.Length);
        Console.WriteLine("Random color: " + colors[randomIndex]);
        
        // Generate a random double between 0 and 1
        double randomDouble = random.NextDouble();
        Console.WriteLine("Random double: " + randomDouble);
    }
}
