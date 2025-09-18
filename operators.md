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
