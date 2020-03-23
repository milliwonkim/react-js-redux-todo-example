- ./src/components/Todo.js => TodoList.js에 import
  - import
    - React from 'react'
    - PropTypes from 'prop-types'
  - const Todo = ({ onClick, completed, text }) => ()
    - <li></li>
      => onClick={onClick}
      => style={{
        textDecoration: completed ? 'line-through' : 'none'
      }}
      - { text }
  - Todo.propTypes = {}
    - onClick: PropTypes.func.isRequired
    - completed: PropTypes.bool.isRequired
    - text: PropTypes.string.isRequired
