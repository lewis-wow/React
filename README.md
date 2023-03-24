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
