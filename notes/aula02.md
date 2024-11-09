# Aula 02 - Instalando TypeScript e compilando via tsc 
  1. Iniciar um projeto yarn 
  ```yarn init -y```

  2. Iniciar o TypeScript localmente como uma depêndencia de desenvolvimento
  ```yarn add typescript --dev```

  3. Gerar arquivo de transpilação do TypeScript (tsconfig.json)
  ```yarn tsc --init```

  4. No arquivo `tsconfig.json` alterar a especificação `outDir` de `./` para `./dist`

  5. Criar um arquivo `.ts`

  6. Testar se o processo de compilação esta correto
  ```yarn tsc```