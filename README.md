# React

How to write react

## Components

### Name

React component name is in PascalCase, for example `MyAwesomeComponent`.

```tsx
export const MyAwesomeComponent = ({ title }: MyAwesomeComponentProps) => {
  ...
}
```

### Props

Every component have props named as `{COMPONENT_NAME}Props`, for example `MyAwesomeComponentProps`.

```tsx
type MyAwesomeComponentProps= {
  title: string
}

export const MyAwesomeComponent = ({ title }: MyAwesomeComponentProps) => {
  ...
}
```

### Exporting

Export React component with `export`, not with `export default`.

## Hooks

### Name

React hook name starts with `use` and is written in camelCase, for example `useMyAwesomeHook`.

```ts
export const useMyAwesomeHook = ({ title }: MyAwesomeHookProps) => {
  ...
}
```

### Props

Every component have props named as `{COMPONENT_NAME}Props`, for example `MyAwesomeHookProps`.

```tsx
type MyAwesomeHookProps= {
  title: string
}

export const useMyAwesomeHook = ({ title }: MyAwesomeHookProps) => {
  ...
}
```

### Exporting

Export React hook with `export`, not with `export default`.

## Functions

### Name 

Every function is written in camelCase.

### Args

Functions have args, not props. The args are named as `{FUNCTION_NAME}Args`, for example `MyAwesomeFunctionArgs`.

```ts
type MyAwesomeFunctionArgs = {
  title: string
}

export const myAwesomeFunction = ({ title }: MyAwesomeFunctionArgs) => {
  ...
}
```

### Exporting

Export function with `export`, not with `export default`.

## File structure

Every file should export only one function. There should not be file like `utils.ts` with many exports.

## Classes

## Name

Every class name is written in PascalCase.

### Args

Classes have args, not props. The args are named as `{CLASS_NAME}Args`, for example `MyAwesomeClassArgs`.

```ts
type MyAwesomeClassArgs = {
  title: string
}

export class MyAwesomeClass {
  constructor(args: MyAwesomeClassArgs) {
    ...
  }
}
```

### Exporting

Export class with `export`, not with `export default`.
