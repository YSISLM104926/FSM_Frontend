# React + TypeScript + Vite

## Live Site - [fsm-frontend](https://fsm-frontend.vercel.app)

## Backend Repository - [FSM Backend](https://github.com/YSISLM104926/FSM_backend)
---
## 🛠️ Tech Stack
- **Framework**: Vite
- **UI Libraries**: Ant Design, DaisyUI, Tailwind CSS
- **State Management**: Redux Toolkit
- **Form Handling**: React Hook Form
- **Routing**: React Router DOM
- **HTTP Requests**: Axios
- **Animation**: Framer Motion
- **Notifications**: React Hot Toast
- **Type Checking**: TypeScript
---
Feel free to reach out for any questions or feedback!


This template provides a minimal setup to get React working in Vite with Hot Module Replacement (HMR) and some ESLint rules.

## Official Plugins

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md): Uses [Babel](https://babeljs.io/) for Fast Refresh.
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc): Uses [SWC](https://swc.rs/) for Fast Refresh.

## Expanding the ESLint Configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

1. Configure the top-level `parserOptions` property as follows:

    ```javascript
    export default {
      // other rules...
      parserOptions: {
        ecmaVersion: 'latest',
        sourceType: 'module',
        project: ['./tsconfig.json', './tsconfig.node.json'],
        tsconfigRootDir: __dirname,
      },
    }
    ```

2. Replace `plugin:@typescript-eslint/recommended` with `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`.

3. Optionally, add `plugin:@typescript-eslint/stylistic-type-checked`.

4. Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list.

---
