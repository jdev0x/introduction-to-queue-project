# Queue

### Objective

In this project, we will cover the fundamentals of the queue.

### Problem
Store the invoice number using a queue.

### Implementation

Write the `queue` class implementation to store the invoice number.

1. Create a `queue `class that contains three methods: enqueue, dequeue, and display.
2. The `enQueue` method allows to add a new element.
3. The `display` method prints all elements in the queue.

> Run the main method to verify the implementation.

````Java
public class Main {
  /*add your code here*/
  public static void main(String[] args) {
        Queue que = new Queue();

        que.enqueue(100);
        que.enqueue(101);
        que.enqueue(102);
        que.dequeue();
        que.display();
    }
}
````

> * Once you complete this project, Create an issue with the title "Completed [your-username]".
> * You can use either Queue Array or Queue Linked List, to complete this project.
> * Create an issue of your questions, If you face any trouble solving the project.
