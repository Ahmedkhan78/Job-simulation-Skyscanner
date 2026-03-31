

````markdown
# Flight Schedule App

This project is a React application bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and [Skyscanner Backpack](https://backpack.github.io/) components.  
It displays a **Flight Schedule header**, a **calendar component**, and a **Continue button**.

---

## Features

- Uses **Skyscanner Backpack components** (`BpkText`, `BpkButton`, `BpkCode`, `BpkCalendar`)  
- Fully styled with Backpack **SCSS mixins**  
- Supports **selecting a date** from the calendar  
- Responsive layout for mobile and desktop

---

## Getting Started

### 1. Install dependencies

```bash
npm install
````

> Make sure you have **Node 14 or Node 16** installed.

---

### 2. Start the development server

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser. The page will reload automatically when you make changes.

---

### 3. Build for production

```bash
npm run build
```

This creates an optimized production build in the `build` folder.

---

## Scripts

| Command         | Description                                                                                 |
| --------------- | ------------------------------------------------------------------------------------------- |
| `npm start`     | Runs the app in development mode                                                            |
| `npm test`      | Launches test runner in interactive watch mode                                              |
| `npm run build` | Builds the app for production                                                               |
| `npm run eject` | Copies all config files and dependencies so you can customize the setup (one-way operation) |

---

## Project Structure

```
my-app/
  src/
    App.jsx           # Main app component
    App.scss          # SCSS styling
    index.js          # React app entry point
  package.json        # Project dependencies and scripts
```

---

## Dependencies

* `react` / `react-dom` – React 17
* `@skyscanner/backpack-web` – Backpack components
* `bpk-component-calendar` – Calendar component
* `bpk-mixins` – SCSS mixins
* `date-fns` – Date handling for calendar

---

## Customization

* **Header**: Update text inside `App.jsx`
* **Calendar**: Import `BpkCalendar` and handle date state
* **Button**: Change text or add functionality inside `App.jsx`
* **SCSS**: Modify `App.scss` for layout, spacing, and colors

---

## Notes

* All Backpack components use **CSS Modules by default**
* Make sure `date-fns` is installed; otherwise `BpkCalendar` will fail
* Use `node-sass` and `sass-loader` if SCSS compilation fails


