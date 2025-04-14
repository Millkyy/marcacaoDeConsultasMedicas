
# 📅 Marcação de Consultas Médicas

Este projeto é um aplicativo mobile desenvolvido com React Native e TypeScript, que permite aos usuários visualizar e gerenciar consultas médicas de forma simples e intuitiva.

## 🧾 Descrição do Projeto

A proposta é oferecer uma interface prática para registrar, exibir e atualizar consultas médicas diretamente pelo celular. A persistência dos dados é feita localmente utilizando o `AsyncStorage`, garantindo que as informações estejam disponíveis mesmo após o fechamento do aplicativo.

Além disso, o projeto foi estruturado com foco na escalabilidade e organização do código, utilizando o princípio de separação de responsabilidades. Os tipos TypeScript foram segregados em arquivos específicos por domínio funcional, o que facilita a manutenção e a leitura do código.

## ✅ Funcionalidades

- Exibição das consultas salvas na tela inicial.
- Cadastro e atualização de consultas pelo usuário.
- Armazenamento persistente de dados com `AsyncStorage`.
- Organização modular dos tipos TypeScript.

## 🧱 Estrutura do Projeto

```
📁 assets/                 # imagens, ícones e outros recursos estáticos
📁 src/                    # Pasta principal com o código-fonte
 ┣ 📁 components/          # Componentes reutilizáveis (botões, inputs, cards, etc.)
 ┣ 📁 routes/              # Configuração de rotas com React Navigation
 ┣ 📁 screens/             # Telas do app (ex: Home, Cadastro)
 ┣ 📁 services/            # Serviços de API e lógica de persistência (ex: AsyncStorage)
 ┣ 📁 styles/              # Estilos globais e centralizados para consistência visual
 ┗ 📁 types/               # Tipos TypeScript organizados por domínio funcional

📄 App.tsx                 # Arquivo principal, ponto de entrada do app
📄 index.ts                # Responsável por registrar o app
📄 app.json                # Configurações do app no Expo (nome, ícones, permissões)
📄 package.json            # Lista de dependências e scripts do projeto
📄 tsconfig.json           # Configurações do compilador TypeScript
📄 .gitignore              # Arquivos e pastas ignorados pelo Git
```

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/marcacaoDeConsultasMedicas.git
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Execute o projeto:
   ```bash
   npx expo start
   ```

## 🛠️ Tecnologias Utilizadas

- React Native
- TypeScript
- Styled-components
- AsyncStorage (via Expo)

## 🔗 Autor

Camilly Ishida - RM 551474

  **Millkyy** – [GitHub Profile](https://github.com/Millkyy)

---

Este aplicativo foi desenvolvido como parte de um estudo prático de desenvolvimento mobile, com foco em boas práticas de organização e persistência de dados.
