using System;

class StudentToDo{
    static void Main(string[] args) {
        
        // Create empty string to store tasks
        string tasks = "";
        
        // Loop to collect tasks
        while (true)
        {
            Console.Write("Enter a task (type 'stop' to finish): ");
            string task = Console.ReadLine();

            if (task == "stop")
            {
                break;
            }

            // Add the task to the string with a newline
            tasks = tasks + "- " + task + "\n";
        }

        // Display all tasks
        Console.WriteLine("\nTodo List:");
        Console.WriteLine(tasks);
    }
}
