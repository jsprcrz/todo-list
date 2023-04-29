<br />
<div align="center">
  <a>
    <img src="https://cdn-icons-png.flaticon.com/512/579/579703.png" style="width: 200px; height: 200px;">
  </a>

  <h3 align="center">To-do Tracker</h3>

  <p align="center">
  A simple app for planning and scheduling your tasks.
  </p>
</div>

## About 
One of the first projects I created with React to help learn the basics, including components, state management, and props. 

<p align="center">
  <img src="https://imgur.com/tKnFeBD.png" alt="addingItem" style="height: 200px;">
</p>

It uses <code>useState</code> and <code>useEffect</code> to manage state and local storage to store to-do items. The app components are created in separate files for modularity and readability. 
<ol>
    <li> The <code>NewForm</code> functional component exports a form for adding new items to the to-do list.
    <li> The <code>TodoList</code> functional component takes in three props: <code>todos</code>, <code>toggleTodo</code>, and <code>deleteTodo</code>. 
    It returns a list of to-do items using the <code>map</code> function on the <code>todos</code> array and renders each item using another component called <code>TodoItem</code>. 
    <li> The <code>TodoItem</code> functional component takes in props of <code>completed</code>, <code>id</code>, <code>title</code>, <code>toggleTodo</code>, and <code>deleteTodo</code>. It returns a list item with a label containing a checkbox and the title of the todo item.
</ol>

## Features
<ul>
  <li>Add new to-do items
  <li>Mark to-do items as completed
  <li> Delete to-do items
</ul>

