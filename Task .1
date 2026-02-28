import os

FILE_NAME = "tasks.txt"

# Load tasks from file
def load_tasks():
    if not os.path.exists(FILE_NAME):
        return []
    with open(FILE_NAME, "r") as file:
        tasks = file.readlines()
    return [task.strip() for task in tasks]

# Save tasks to file
def save_tasks(tasks):
    with open(FILE_NAME, "w") as file:
        for task in tasks:
            file.write(task + "\n")

# Display tasks
def view_tasks(tasks):
    if not tasks:
        print("\nNo tasks found!\n")
        return
    print("\nYour To-Do List:")
    for i, task in enumerate(tasks, 1):
        print(f"{i}. {task}")
    print()

# Add task
def add_task(tasks):
    task = input("Enter new task: ")
    tasks.append("[ ] " + task)
    save_tasks(tasks)
    print("Task added successfully!\n")

# Update task
def update_task(tasks):
    view_tasks(tasks)
    try:
        task_no = int(input("Enter task number to update: "))
        if 1 <= task_no <= len(tasks):
            new_task = input("Enter updated task: ")
            tasks[task_no - 1] = "[ ] " + new_task
            save_tasks(tasks)
            print("Task updated successfully!\n")
        else:
            print("Invalid task number!\n")
    except ValueError:
        print("Please enter a valid number!\n")

# Delete task
def delete_task(tasks):
    view_tasks(tasks)
    try:
        task_no = int(input("Enter task number to delete: "))
        if 1 <= task_no <= len(tasks):
            tasks.pop(task_no - 1)
            save_tasks(tasks)
            print("Task deleted successfully!\n")
        else:
            print("Invalid task number!\n")
    except ValueError:
        print("Please enter a valid number!\n")

# Mark task as completed
def mark_completed(tasks):
    view_tasks(tasks)
    try:
        task_no = int(input("Enter task number to mark as completed: "))
        if 1 <= task_no <= len(tasks):
            tasks[task_no - 1] = tasks[task_no - 1].replace("[ ]", "[✔]")
            save_tasks(tasks)
            print("Task marked as completed!\n")
        else:
            print("Invalid task number!\n")
    except ValueError:
        print("Please enter a valid number!\n")

# Main menu
def main():
    tasks = load_tasks()

    while True:
        print("====== TO-DO LIST MENU ======")
        print("1. View Tasks")
        print("2. Add Task")
        print("3. Update Task")
        print("4. Delete Task")
        print("5. Mark Task as Completed")
        print("6. Exit")

        choice = input("Enter your choice (1-6): ")

        if choice == "1":
            view_tasks(tasks)
        elif choice == "2":
            add_task(tasks)
        elif choice == "3":
            update_task(tasks)
        elif choice == "4":
            delete_task(tasks)
        elif choice == "5":
            mark_completed(tasks)
        elif choice == "6":
            print("Goodbye!")
            break
        else:
            print("Invalid choice! Try again.\n")

if __name__ == "__main__":
    main()
