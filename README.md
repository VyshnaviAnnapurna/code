name:Lakkimsetti R S B N Sri Vyshnavi Annapurna
email id:vyshnavil2005@gmail.com
domain:python internship
duration:two months
mentor name:sravani gouni
Description:This Python script implements a simple to-do list application with basic functionality such as adding tasks, marking tasks as completed, removing tasks, and viewing all tasks. Here's a breakdown of the script:

1. **`tasks` Dictionary**: An empty dictionary is defined to store tasks. Each task will be stored as a dictionary containing the task description and its completion status.

2. **`add_task(task)` Function**: This function takes a task description as input and adds it to the `tasks` dictionary with a unique task number. By default, the task is marked as not completed.

3. **`complete_task(task_number)` Function**: Given a task number, this function marks the corresponding task as completed by setting its completion status to `True`.

4. **`remove_task(task_number)` Function**: Removes a task from the `tasks` dictionary based on the provided task number.

5. **`display_tasks()` Function**: This function displays all tasks stored in the `tasks` dictionary, along with their task numbers and completion statuses.

6. **`main()` Function**: The main function contains a while loop that continuously displays a menu of options for the user to interact with the to-do list. The user can add tasks, mark tasks as completed, remove tasks, view all tasks, or exit the program.

7. **User Interaction**: When the program is run, the main function is executed. It displays the menu options, prompts the user for input, and calls the corresponding functions based on the user's choice.

8. **`if __name__ == "__main__":`**: This line ensures that the `main()` function is only executed if the script is run directly, not if it is imported as a module into another script.

Overall, this script provides a simple command-line interface for managing a to-do list.
conclusion:In conclusion, the provided Python script offers a straightforward implementation of a to-do list application with essential functionalities. Users can interact with the application through a command-line interface, where they can add tasks, mark tasks as completed, remove tasks, and view the list of tasks. 

The script maintains tasks in a dictionary, with each task having a unique task number and associated details such as the task description and completion status. Through modular functions, the script ensures clear organization and readability, facilitating maintenance and potential future expansions.

By encapsulating the main functionality within a `main()` function and utilizing a menu-driven approach, the script enhances user experience by providing intuitive navigation. Additionally, the script includes error handling to manage scenarios such as invalid user input or tasks not found.

Overall, this script serves as a functional starting point for a basic to-do list application, offering users a simple yet effective tool for managing tasks in a command-line environment.
