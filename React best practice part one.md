## Soft Skills Tips
1. Always professionally present your work.

2. Always be on time for meetings and on your deliverables.

3. Make the best out of you when you deliver something, the higher the quality you deliver the more you will be appreciated.

4. Sports, Sports, Sports, it's a must to have a healthy body to have a healthy mind, at least 30 minutes a day, if not then at least 3 times a week.

## Tips & Tricks for React best practices
1. Naming Files And Folders

     - Make sure to name the file as component name.

     - use PascalCase for file names.

     - use kebab-case for hooks, classes (es6) and helper files.

     - If the component may contain nested components, wrap it in a folder with an index.ts file.

2. Callbacks

     - DO NOT use inline callbacks in jsx, i.e onClick={() => doSomething()} as much as possible.

     - If the callback will just call a function, then pass the function directly, i.e onClick={doSomething} instead of onClick={() => doSomething()}.

     - If the callback needs to pass arguments but not taken from the event callback, use higher order functions i.e onClick={doSomething(value)} instead of onClick={() => doSomething(value)} where doSomething is a function that takes a value as an argument.
