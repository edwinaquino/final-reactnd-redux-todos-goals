# Final reactnd-redux-todos-goals

This is a very simple state management app that implements the 4 parts that a store must contain:
* The state
*Get the state.
*Listen to changes on the state.
*Update the state


## Installation

To run the app, you will need node.js - Start with the app with the following commands:

```bash
git clone https://github.com/edwinaquino/final-reactnd-redux-todos-goals.git
cd final-reactnd-redux-todos-goals
npm install
```

## Usage
To run the application simply execute the following node.js command:
```bash
node app.js
```

## Output

```
The new state is:  {
  todos: [ { id: 0, name: 'Walk the dog', complete: false } ],
  goals: []
}
The new state is:  {
  todos: [
    { id: 0, name: 'Walk the dog', complete: false },
    { id: 1, name: 'Wash the car', complete: false }
  ],
  goals: []
}
The new state is:  {
  todos: [
    { id: 0, name: 'Walk the dog', complete: false },
    { id: 1, name: 'Wash the car', complete: false },
    { id: 2, name: 'Go to the gym', complete: true }
  ],
  goals: []
}
The new state is:  {
  todos: [
    { id: 0, name: 'Walk the dog', complete: false },
    { id: 2, name: 'Go to the gym', complete: true }
  ],
  goals: []
}
The new state is:  {
  todos: [
    { id: 0, name: 'Walk the dog', complete: true },
    { id: 2, name: 'Go to the gym', complete: true }
  ],
  goals: []
}
The new state is:  {
  todos: [
    { id: 0, name: 'Walk the dog', complete: true },
    { id: 2, name: 'Go to the gym', complete: true }
  ],
  goals: [ { id: 0, name: 'Learn Redux' } ]
}
The new state is:  {
  todos: [
    { id: 0, name: 'Walk the dog', complete: true },
    { id: 2, name: 'Go to the gym', complete: true }
  ],
  goals: [ { id: 0, name: 'Learn Redux' }, { id: 1, name: 'Lose 20 pounds' } ]
}
The new state is:  {
  todos: [
    { id: 0, name: 'Walk the dog', complete: true },
    { id: 2, name: 'Go to the gym', complete: true }
  ],
  goals: [ { id: 1, name: 'Lose 20 pounds' } ]
}
```

## Contributing
If you are interested in contributing, please go to the main Udacity distribition at:
https://github.com/udacity/reactnd-redux-todos-goals
