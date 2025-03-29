# 🏦 Modern Bank  

Este projeto é uma **Landing Page** moderna para um banco digital, com um design responsivo e atrativo, focado em destacar os serviços e vantagens do banco.  

## 🔥 Funcionalidades  

✅ Layout moderno e responsivo  
✅ Seção de serviços e benefícios do banco  
✅ Design otimizado para experiência do usuário  
✅ Interface intuitiva e acessível  

## 🖼️ Screenshot  

![Screenshot da aplicação](Bank.png)  


## 🚀 Tecnologias Utilizadas  

- **HTML, CSS e JavaScript** para a estrutura e interatividade  
- **Design responsivo para diferentes dispositivos**  
- **Estilização moderna e animações suaves**  

## ⚡ Como Executar  

Você pode acessar a aplicação diretamente pelo link:  

🔗 **[Modern Bank](https://modernbankhoo.netlify.app)**  

Ou, para rodar localmente:  

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default tseslint.config({
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChecked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

```js
// eslint.config.js
import react from 'eslint-plugin-react'

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } },
  plugins: {
    // Add the react plugin
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
