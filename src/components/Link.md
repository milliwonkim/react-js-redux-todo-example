- ./src/components/Link.js
  - import
    - React from 'react';
    - PropTypes from 'prop-types'
  - const Link = ({ active, children, onClick }) => ()
    - <button></button>
      => onClick={onClick}
      => disabled={active}
      => style={{ marginLeft: '4px' }}
      - { children }
  - Link.propTypes = {}
    - active: PropTypes.bool.isRequired
    - children: PropTypes.node.isRequired
    - onClick: PropTypes.func.isRequired
