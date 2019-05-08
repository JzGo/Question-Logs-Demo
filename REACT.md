
| Question      | Answer        | Additional Resources |
| ------------- | ------------- | -------------------- |
| Is it better to have more or fewer components?  | More is better. UIs broken into smaller reusable functionality are more flexible and end up letting the page perform better (faster). |
| When do you know you need to build a component?  | When you know that a piece of UI will be reused and if that piece also has specific responsibilities.  |
| What does the && do in the render? | You might be thinking about condtional rendering ({condition && <ui>}) . It's a nice tool that reads: if a condition is true, render this. | [React Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html#inline-if-with-logical--operator)
| How do you know you need to use a component with state? | A very general rule of thumb is: If your component is a new page (as indicated by a distinct url), your component will require state. But this becomes variable depending of the complexity of the app and its requirements. |