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
![EnteringTask](/screenshots/enteringtask.png)
- Confirm the Metamask transaction
![EnteringTask](/screenshots/confirmentermetamask.png)
- The New Todo will be added with the visualisers
![EnteringTask](/screenshots/newTodoAdded.png)
- Toggle a Task by giving the Task Number
![EnteringTask](/screenshots/toggleTask.png)
- Confirm the Toggling of Task Metamask
![EnteringTask](/screenshots/toggleConfirmMetamask.png)
- Toggle Task Update at the Home Screen with visualisers
![EnteringTask](/screenshots/toggleHome.png)
- This is how the App works

# Using the Dapp
- Clone the repository
```
git clone https://github.com/Sidangore/Eth-Todo.git
```
- Deploy the Contract on your Locally Hosted Ganache
    1. Start Ganache
    2. At Root level of folder
    ``` 
    truffle migrate --reset
    ```
    3. Copy the ABI and Address of Contract from ./build/contracts/Todo.json
    4. Paste the Respectives at ./client/config.js        
- Start the Client Server
```
cd client/
npm install
npm start
```
- Visit localhost:3000 to start using the Dapp on your machine


