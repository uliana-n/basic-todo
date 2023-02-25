# Basic Todo List 

This code defines a to-do list application with an input form, an unordered list (ul) for displaying the list items, and a JavaScript code for adding and removing items from the list.

The renderTodos() function is responsible for rendering the to-do list. It first clears the list (todoList.innerHTML = '') and then loops through the todos array, creating a list item (li) for each todo item and adding a delete button (button) to it. The forEach() method of the todos array is used to iterate through the list of items.

The addEventListener() method is used to listen for the submit event on the todo form. When the form is submitted, the preventDefault() method is called to prevent the default form submission behavior. The text input from the form is retrieved using the value property of the todoInput element. If the input is not empty, it is added to the todos array using the push() method. Finally, the renderTodos() function is called to update the todo list with the new item.

The delete button is implemented using an event listener attached to each button element. When a delete button is clicked, the corresponding item is removed from the todos array using the splice() method and the renderTodos() function is called to update the list.
