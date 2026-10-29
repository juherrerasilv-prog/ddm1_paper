
# react_paper2

Aplicativo multiplataforma criado com Expo e React Native. Atualmente, o projeto contém a estrutura inicial do Expo e uma tela de exemplo em `App.js`.

## Tecnologias

- Expo SDK 58
- React 19
- React Native 0.88
- JavaScript

## Requisitos

- Node.js e npm
- Expo Go em um dispositivo móvel, ou um emulador Android/iOS para executar a versão nativa
- Navegador para executar a versão web

## Como executar

Instale as dependências:

```bash
npm install
```

Inicie o servidor de desenvolvimento:

```bash
npm start
```

Também é possível iniciar diretamente em uma plataforma:

```bash
npm run android
npm run ios
npm run web
```

Para usar um dispositivo físico, abra o Expo Go e leia o QR code exibido pelo servidor Expo. A execução em simuladores pode exigir a instalação e configuração das ferramentas da respectiva plataforma.

## Estrutura do projeto

```text
.
├── App.js       # Componente principal
├── index.js     # Registro da aplicação no Expo
├── app.json     # Configurações do aplicativo
└── assets/      # Ícones e outros recursos visuais
```

## Desenvolvimento

Edite `App.js` para desenvolver a tela principal. As configurações de nome, orientação, ícones e plataformas ficam em `app.json`.