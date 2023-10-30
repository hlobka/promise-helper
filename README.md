# promise-helper
promise helper

## Installation:
As a dependency in your npm package:
- `npm install @hlobka/promise-helper`

Examples:
- Example 1:
    - ```typescript
      new PromiseList<void>([
        Promise.resolve(),
        Promise.resolve()
      ]).all()
        .then(() => {
          console.log("Hello World");
        });
    ```
