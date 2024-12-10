Chat App com Envio de Imagens e Reações (Emojis)
Este é o meu projeto de aplicativo de chat, onde você pode enviar mensagens de texto, imagens e até reagir às mensagens com emojis! A ideia é criar uma experiência divertida e interativa para quem usa o app, deixando as conversas mais interessantes.

Funcionalidades Implementadas
1. Envio de Imagens
Agora você pode compartilhar imagens no chat! O app tem as seguintes funcionalidades:

Escolher uma imagem diretamente da galeria ou tirar uma foto usando a câmera do celular.
As imagens são enviadas para o Firebase Storage, que é onde ficam armazenadas de forma segura.
A URL da imagem é salva no Firestore e a imagem aparece automaticamente no chat.
2. Reações com Emojis
Além das mensagens de texto, agora você pode reagir às mensagens usando emojis! Ao lado de cada mensagem, há um botão para escolher um emoji e reagir. Isso torna a conversa ainda mais interativa e divertida.

Tecnologias Utilizadas
Aqui estão as tecnologias que usei para construir o app:

React Native: Framework principal para desenvolver o app.
Expo: Ferramenta que facilita o desenvolvimento com o React Native, principalmente para testes rápidos.
TailwindCSS (NativeWind): Usado para deixar a interface bonita, limpa e responsiva.
Firebase (Firestore e Storage): Usado para armazenar as mensagens, imagens e as reações dos usuários.
Como Rodar o Projeto
Se você quiser testar o projeto no seu celular ou computador, siga os passos abaixo:

Clone o repositório: No seu terminal, digite o seguinte comando para clonar o repositório do GitHub:

bash
Copiar código
git clone https://github.com/profjacques/chat.git
Instale as dependências: Navegue até a pasta do projeto e instale as dependências com:

bash
Copiar código
npm install
Configure o Firebase: Crie um projeto no Firebase e configure o Firestore e o Storage. Depois, adicione suas credenciais no arquivo firebase-config.js (você pode seguir as instruções na documentação oficial do Firebase para isso).

Rodar o app: Para rodar o app no seu celular ou emulador, use o comando:

bash
Copiar código
expo start
Isso abrirá o Expo no seu navegador, onde você pode escanear o QR code com o app Expo Go no seu celular ou usar um emulador para ver o aplicativo funcionando.

Como Funciona
1. Envio de Imagens
Clique no ícone para escolher uma imagem da galeria ou tire uma foto com a câmera do celular.
O app vai fazer o upload da imagem para o Firebase Storage.
A URL da imagem é salva no Firestore e, em seguida, a imagem aparece diretamente no chat.
2. Reações com Emojis
Ao lado de cada mensagem, existe um botão para enviar um emoji.
O emoji escolhido será enviado para o Firestore e aparecerá como uma reação na mensagem.
