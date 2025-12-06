O Fokus é uma aplicação mobile desenvolvida em React Native que demonstra um fluxo completo de autenticação de usuários, incluindo tela de login com validação, controle de sessão e uma área de dashboard protegida.

Este projeto foi criado com o objetivo de apresentar boas práticas no desenvolvimento de aplicativos móveis utilizando React Native, Hooks, Context API e AsyncStorage, simulando o comportamento de um backend real.

✨ Descrição do Projeto
O Fokus simula um sistema de autenticação e gerenciamento de acesso dentro de um app mobile.
O usuário realiza login com email e senha, e, ao ser validado, é direcionado para um Dashboard protegido, acessível apenas com sessão ativa.

O projeto é ideal para demonstrar:

Estrutura de autenticação em React Native;
Uso de Context API para gerenciamento de estado global;
Armazenamento local com AsyncStorage;
Navegação protegida utilizando React Navigation.
🧩 Funcionalidades
🔐 Tela de Login:
Formulário com validação de campos (email e senha) e feedback visual de erro.

🧭 Dashboard Protegido:
Página acessível apenas por usuários autenticados.

⚙️ Simulação de Autenticação:
O serviço AuthService simula a validação de credenciais, representando a comunicação com um backend.

🔄 Persistência de Sessão:
Utiliza AsyncStorage para manter o usuário logado mesmo após fechar o app.

🚪 Logout:
Função que remove os dados de autenticação e redireciona para a tela de login.

🛠️ Tecnologias Utilizadas
React Native (Expo ou CLI)
TypeScript
React Navigation — navegação entre telas
Context API — gerenciamento global de autenticação
AsyncStorage — armazenamento local seguro
Styled Components / CSS-in-JS — estilização moderna e reutilizável
🚀 Como Executar o Projeto
Clone o repositório:
git clone https://github.com/Biglass611/focusv2

Lucas Nunes Dos Santos
