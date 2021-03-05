# goit-react-hw-07-asynchronous-redux

1. npx create-react-app . --use-npm
2. npm i prop-types
3. линтинг npm install --save-dev prettier husky lint-staged
4. Проверяем настройки VSCode(autoSeve - onFocusChange; formatOnSave - вкл;
   codeActionsOnSave - all)
5. Добавляем настройки в
   проект(https://github.com/goitacademy/react-lint-config)
6. настраиваем абсолютные импорты
   (https://create-react-app.dev/docs/importing-a-component/#absolute-imports)
   (создаем файл jsconfig.json,вставляем... после чего можно писать import
   Button from 'components/Button'; без ../../../)
7. Ставим пакет [https://reactrouter.com/core/guides/quick-start] - (npm install
   react-router-dom)
8. Анимированная стилизация npm install react-transition-group
9. Redux - npm i redux
10. React-redux - npm i react-redux
11. Redux DevTools (http://extension.remotedev.io/) - npm install --save-dev
    redux-devtools-extension
12. В файл с редьюсером import { createStore, applyMiddleware } from 'redux';
    import { composeWithDevTools } from 'redux-devtools-extension'; const store
    = createStore(reducer, composeWithDevTools());
13. npm install @reduxjs/toolkit
14. npm install json-server
15. npm i axios

16. 0.02 Удаляем сохранение туду в локалСторедж
17. 0.05 Redux middleware
18. 0.13 Еще одна прослойкаб которая работает с НТТР-запросами - (thunk)
19. 0.22 addTodo with axios in todos-actions
20. 0.31 Импорты
21. 0.34 Добавляем loading в reducer
22. 0.37 Переписываем deleteTodo на асинхронный
23. 0.44 Переписываем toggleCompleted на асинхронный
24. 0.54 fetchTodos
25. 1.00 loader
26. 1.02 error
27. 1.02 Переписываем fetchTodos на асинхронный

28. Вебинар 12 Selectors
29. 0.09 Пишем todos-selectors
30. 0.13 Переписываем getVisibleTodos
31. 0.24 CounterButton
32. 0.35 Мемоизированные селекторы, переписываем getVisibleTodos
33. 0.39 Мемоизируем getCompletedTodosCount
34. 0.45 Для 2х компонентов мемоизированный селектор работать не будет. Видео
    фабрики
35. index.js for redux folder
