# 🏦 Modern Bank  

Este projeto é uma **Landing Page** moderna para um banco digital, com um design responsivo e atrativo, focado em destacar os serviços e vantagens do banco.  

## 🔥 Funcionalidades  

✅ Layout moderno e responsivo  
✅ Seção de serviços e benefícios do banco  
✅ Design otimizado para experiência do usuário  
✅ Interface intuitiva e acessível  

## 🖼️ Screenshot  

![Screenshot da aplicação](Banco.png)  


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

Este template fornece uma configuração mínima para fazer o React funcionar no Vite com **HMR** (Hot Module Replacement) e algumas regras do **ESLint**.  

Atualmente, dois plugins oficiais estão disponíveis:  

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) usa o [Babel](https://babeljs.io/) para **Fast Refresh**  
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) usa o [SWC](https://swc.rs/) para **Fast Refresh**  

## 🛠️ Expandindo a configuração do ESLint  

Se você estiver desenvolvendo uma aplicação para produção, recomendamos atualizar a configuração para ativar regras de lint que consideram os tipos do TypeScript:  

### 🔧 Configuração do `parserOptions`  

```js
export default tseslint.config({
  languageOptions: {
    // outras opções...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})

