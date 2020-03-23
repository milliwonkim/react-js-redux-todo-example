- ./src/components/TodoList.js
  - import
    - React from 'react';
    - PropTypes from 'prop-types'
    - Todo from './Todo'
  - const TodoList = ({ todos, toggleTodo }) => ()
    - <ul></ul>
      - { todos.map(todo => ()) }
        - <Todo />
          => key={todo.id}
          => { ...todo }
          => onClick={() => toggleTodo(todo.id)}
