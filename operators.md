# Operators

## || or ??

### ||

> By using logic operator OR it will return the first "truthy" (not falsy) value found.

```javascript
function getTheme() {
  const theme = null;
  return theme || "light";
}

getTheme();
```

### ?? (nullish coalescing)

> Accepts some falsy values

```javascript
const theme = null;
const finalTheme = theme ?? "light"; // it will only return light if theme is null or undefined
```

## &&

```javascript
true && "Hello"; // returns "Hello"
false && "Hello"; // returns false
```

If we put the value into a variable

```javascript
const var1 = true && "Hello";
const var2 = false && "Hello";
```

In the first case var1 will be a string, in the second var2 will be a boolean, but the operator && does not transform the value into a pure boolean.
