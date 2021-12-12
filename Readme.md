# Ethereum Todo list Dapp
When you get serious about your productivity!

# Why we use React?
- It is a Js library to build user interfaces
- Component based library
- Compnonetm is the basic unit in react
- State management

# Dependencies
    - web3
    - react-bootstrap
    - bootstrap 
    ```
    import 'bootstrap/dist/css/bootstrap.css'; 
    ````
        // Add the above import in index.js file
    
 
# Interacting with the blockchain using console
    1. taskCount = todo.taskCount().then((result) => { return result.toNumber() });
    2. task = todo.tasks(1).then((result) => { return result; });

# How the App works?
- Login to Metamask account and enable the extension
- Connect metamask to the website
- Enter the todo task 
![EnteringTask]('/screenshots/enteringtask.png')
- Confirm the Metamask transaction
![EnteringTask]('/screenshots/confirmentermetamask.png')
- The New Todo will be added with the visualisers
![EnteringTask]('/screenshots/newTodoAdded.png')
- Toggle a Task by giving the Task Number
![EnteringTask]('./screenshots/toggleTask.png')
- Confirm the Toggling of Task Metamask
![EnteringTask]('./screenshots/toggleConfirmMetamask.png')
- Toggle Task Update at the Home Screen with visualisers
![EnteringTask]('./screenshots/toggleHome.png')
- This is how the App works

