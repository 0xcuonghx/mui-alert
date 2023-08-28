# mui-alert

The config `MUI-Snackbar` as Provider for convenience to show message alert in MaterialUI (error, info, success, warning)

# Usage

```jsx
<AlertProvider>
  {children}
</AlertProvider>
```

# Hooks
```jsx
const alert = useAlert()
```
## Show alert message

```jsx
// success
alert.showAlert(AlertType.SUCCESS, "Something happened.")
// error
alert.showAlert(AlertType.ERROR, "Something went wrong.")
// info
alert.showAlert(AlertType.INFO, "Something happened.")
// warning
alert.showAlert(AlertType.WARNING, "Something happened.")
```
