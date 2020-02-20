# console.lar
Small utility to make console.lar (Log and return) calls in javascript when debug mode is enabled.

## WHAT IT DOES

```
window.DEBUG = true
> 1 + console.lar(3)
3
--> 4
```

```
window.DEBUG = false
> 1 + console.lar(3)
--> 4
```
