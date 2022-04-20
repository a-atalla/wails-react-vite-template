# Wails 2.0 react,vite and typescript template

## About
This is Wails 2.0 + ReactJS Template created by vite+typescript

To create a project using this template run: 
```
wails init -n [Your Appname] -t https://github.com/a-atalla/wails-react-vite-template
```
## Live Development

To run in live development mode, run `wails dev` in the project directory.

The frontend dev server will run on http://localhost:34115. and it will be connected to the Go backend, test from the browser console with 

```
window.go.main.App.Greet("Wails 2.0").then(console.log)
```

also vite is configured to rebuild/reload the frontend on every change

## Building
To build a redistributable, production mode package, use `wails build`.
