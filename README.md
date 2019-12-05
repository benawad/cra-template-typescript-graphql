# cra-template-typescript-graphql

To use this template, add `--template typescript-graphql` when creating a new app.

For example:

```sh
npx create-react-app my-app --template typescript-graphql

# or

yarn create react-app my-app --template typescript-graphql
```
## Usage

1. Put your queries/mutations in .graphql files anywhere in the src folder
2. Edit the url in `codegen.yml` and `src/index.tsx` if your graphql endpoint is not `http://localhost:4000`
3. Generate hooks by running `yarn gen` or `npm run gen`
4. Use the generated hooks in your code

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.
