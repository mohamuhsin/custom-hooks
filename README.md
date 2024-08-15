# Custom Hooks:
Building custom hooks in React allows you to encapsulate or wrap and reuse logic across multiple components

In this app we created custom hook to handle fetching logic so that we can use it in different parts of the app that need that logic.

# Rules of Hooks:

1.Only call hooks inside of a component function.

2. Hooks must not be nested inside if statements, nested functions and loops
   
3. Hooks may be used in a component function or inside another hook.

# Why Hooks:

1. Code Reusability: Custom hooks enable you to extract and reuse complex logic across different components, making your code more DRY (Don’t Repeat Yourself).

2. Separation of Concerns: By moving logic out of the components into custom hooks, you keep your component code clean and focused on rendering the UI.

3. Improved Readability: Custom hooks give meaningful names to chunks of logic, making your code easier to read and understand.

4. Testability: Extracting logic into custom hooks can make it easier to test that logic in isolation.

5. Stateful Logic Sharing: When you have stateful logic that needs to be shared between multiple components, custom hooks are an efficient way to manage it without using context or higher-order components (HOCs).

6. Avoiding Code Duplication: If multiple components need to perform the same side effects or calculations, a custom hook can prevent the duplication of code.

