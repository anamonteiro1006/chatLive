# 💬 Live Chat Real-Time (Mensagens Coletivas)

![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Este é um sistema de **Chat Ao Vivo** desenvolvido para demonstrar o poder da comunicação em tempo real. Utilizando a tecnologia de WebSockets, todas as mensagens enviadas são distribuídas instantaneamente para todos os usuários conectados simultaneamente.

## 🚀 Dinâmica de Funcionamento

Diferente de uma aplicação de mensagens privada, este sistema funciona como uma **sala de transmissão aberta**:

* **Envio Global:** Toda mensagem enviada por um cliente é processada pelo servidor e retransmitida via *broadcast*.
* **Recebimento Instantâneo:** Todos os usuários conectados recebem a atualização no DOM (tela) no momento exato em que a mensagem chega ao servidor.
* **Sem Refresh:** A interface é atualizada dinamicamente sem que o usuário precise recarregar a página.


## 🛠️ Tecnologias e Conceitos Aplicados

* **Socket.io:** Gerenciamento de túneis de comunicação (WebSockets).
* **Node.js & Express:** Servidor back-end que atua como o "centralizador" das mensagens.
* **Front-end Dinâmico:** Manipulação do DOM com JavaScript para renderizar o histórico do chat em tempo real.


## 🔰Como inicializar o projeto

- Faça o download do arquivo pelo github e abra a pasta no terminal.
- Instalar o node pelo link: 
- Você pode verificar se o node ja está instalado com o comando no terminal; <br>
``` 
npm- -v 
```

- Executar o seguinte comando no terminal para instalar os node-modules:
``` 
npm install json-server express 
``` 

- Executar o seguinte comando no terminal para instalar o socket.io
```
npm install socket.io express
```

- Iniciar o programa com o comando:
``` 
node server.js
```
