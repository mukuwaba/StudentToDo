using System;

class StudentToDo{
    static void Main(string[] args) {
        
        // Create empty/ container string to store tasks
        string tasks = "";
        
        // Loop to collect tasks
        while (true){
            
            Console.Write("Enter a task (type 'stop' to finish): ");
            
            string task = Console.ReadLine();//store user input
            
            //Stop loop is user types "stop"
            
            if (task == "stop"){
                 break;//Exit loop
            
                
            }//End: if

            // Add the task to the string with a newline
            tasks = tasks + "- " + task + "\n";
            //Form a list of tasks and store in the container variable
       
        }//End: while

        //Display heading
        Console.WriteLine("\nTodo List:");
        
        //Output values stored in "tasks" to user
        Console.WriteLine(tasks);
        
    }//End: main
}//End: class
