- ./src/index.js
  - import
    - {render} from 'react-dom';
    - {createStore} from 'redux';
    - { Provider } from 'react-redux';
    - App from './components/App';
    - rootReducer from './reducers';
  - store 정의 => createStore(rootReducer)
  - render()
    - <Provider store={store}> => <App /> component위에 Provider를 이용해서 redux store로 감싸기

action은 함수형태로 => 다른 component에서 redux를 쓰고싶을때 일반 함수같이 쓴다. (함수와 payload)
reducer는 action과같은 actionTypes가 불려졌을때, 그 액션을 불렀던 component에서 직접 실행되는 로직