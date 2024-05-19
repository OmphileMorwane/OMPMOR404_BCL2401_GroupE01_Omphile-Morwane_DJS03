# DJS03 Project Brief: Book Connect - Abstractions

Dive into the delightful world of "Book Connect," where literary adventures await at your fingertips! Browse, explore, and uncover your next great read from a vast, vibrant collection. Whether you're a fan of thrilling mysteries, epic fantasies, or heartwarming romances, "Book Connect" brings the magic of books directly to you. Happy reading! 

The "Book Connect" project provides an opportunity for students to refine a fully functional version of an application. The focus of this project is to enhance the code's maintainability, extendibility, and readability by applying concepts of objects and functions for abstraction. This will not only streamline future modifications but also consolidate students' understanding of higher-level programming concepts, including documentation, Styleguides, and abstraction principles.

![alt text](image.png)

#### Goals

- **Refactor Existing Code**: Analyse and refactor the given JavaScript and HTML code to improve its structure using objects and functions.
- **Implement Abstraction**: Use abstraction to hide the complex reality while exposing only the necessary parts. This involves creating more generic functions that can perform tasks in a more flexible way.
- **Documentation**: Write clear comments and documentation for the new code structure to explain the purpose and functionality of code blocks, functions, and objects.
- **Follow Styleguides**: Adhere to established coding conventions and Styleguides to ensure code readability and maintainability.

#### Tasks

1. **Code Analysis**: Start by understanding the current implementation of the "Book Connect" application, including its HTML structure and JavaScript functionality.
2. **Plan Refactoring**: Identify sections of the code that can be made more abstract and modular. Look for patterns and repetitive code that can be simplified.
3. **Implement Abstraction**:
   - **Objects**: Define objects to represent key elements of the application, such as books, authors, and genres. Utilise the provided data (e.g., `authors`, `genres`, `books`) to populate these objects.
   - **Functions**: Create functions that handle repetitive tasks, such as rendering the book list, handling user interactions, and applying filters.
4. **Enhance Functionality**: Ensure that the application remains fully functional after refactoring. Test all features to confirm that users can still search, filter, and view books as intended.
5. **Documentation and Comments**: Throughout the refactoring process, document your code. Provide comments that explain the purpose and functionality of objects and functions.
6. **Adherence to Styleguides**: Ensure your code follows JavaScript and HTML coding standards and best practices for readability and maintainability.

## Discussion and Reflections

After completing the tasks, prepare a brief presentation for your coaching group on the following:
- The rationale behind the refactoring decisions made, including the choice of objects and functions.
- How abstraction has made the code more maintainable and extendable.
- Any challenges faced during the refactoring process and how they were overcome.
- Reflections on how this exercise has deepened your understanding of JavaScript programming concepts.

## Discussion and Reflections

 The code has been organized into modular functions such as createBookPreview, renderBooks, updateBookList, renderGenres, renderAuthors, and event listeners. This modularization promotes separation of concerns, allowing each function to handle a specific task. For example, createBookPreview is responsible for generating the HTML for a single book preview element, while renderBooks is responsible for rendering a list of book previews. This approach makes the codebase easier to understand, debug, and modify.By encapsulating functionality into reusable functions, the code achieves a higher level of abstraction. For instance, the createBookPreview function abstracts away the details of generating HTML for a book preview, allowing the caller to simply provide a book object and receive the corresponding HTML element. Similarly, renderBooks abstracts away the process of rendering a list of book previews, making the code more readable and maintainable.

## Challenges faced

I was not really sure what I was supposed to do in this project. I used a lot of media and help from my peers to see it through, but I left still confused. I understand the conceptt of abstraction, I understand what it means and what it supposed to achieve, I am just struggling with applying it. I added a function to create a book preview element. and then my search button stopped working, I then had to debug my code to see where the problem was until I got to ake it work again.

## Reflections 
I think I have a better understanding of abstraction, but I still need to practice more to get better at it. I think I need to read more content so that I cna be able to apply it.