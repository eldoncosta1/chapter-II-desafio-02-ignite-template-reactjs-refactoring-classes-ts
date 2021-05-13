# 💻 Sobre o desafio

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS

Essa será uma aplicação já funcional onde o seu principal objetivo é realizar dois processos de migração: de Javascript para Typescript e de Class Components para Function Components.


### Preparando ambiente Typescript

- Instalar o Typescript

``yarn add typescript -D``

``yarn add @types/react -D
``

- Criar um arquivo de configuração tsconfig.json

- É preciso criar um arquivo `react-app-env.d.ts` com o conteúdo:

```tsx
/// <reference types="react-scripts" />
```