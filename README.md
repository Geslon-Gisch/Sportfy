# Sportfy

Sportfy é um aplicativo desktop desenvolvido em Electron que fornece notificações em tempo real, calendários de jogos e resultados para o Campeonato Brasileiro de Futebol. O aplicativo permite que os usuários selecionem seus times favoritos e recebam alertas personalizados sobre jogos e resultados.

## Funcionalidades

- **Notificações em Tempo Real**: Receba notificações 15 minutos antes do início das partidas do seu time favorito.
- **Calendário de Jogos**: Visualize o calendário completo das partidas do Campeonato Brasileiro.
- **Resultados de Partidas**: Acompanhe os resultados das partidas em tempo real.
- **Seleção de Times Favoritos**: Personalize o aplicativo selecionando seus times favoritos para receber notificações específicas.

## Tecnologias Utilizadas

- [Electron](https://www.electronjs.org/): Para o desenvolvimento da interface desktop.
- [API-Football](https://www.api-football.com/): Para obter dados de jogos e notificações.
- [React](https://reactjs.org/): Para construir a interface do usuário.
- [TypeScript](https://www.typescriptlang.org/): Para um desenvolvimento mais seguro e escalável.
- [Node.js](https://nodejs.org/): Para o backend e gerenciamento das notificações.

## Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/futebolapp.git
   ```
2. **Instale as dependências:**
   ```bash
   cd futebolapp
   npm install
   ```
3. **Configure as variáveis de ambiente:**
   Crie um arquivo `.env` na raiz do projeto e adicione sua chave de API do API-Football:
   ```
   REACT_APP_API_FOOTBALL_KEY=your_api_key_here
   ```
4. **Inicie o aplicativo:**
   ```bash
   npm start
   ```

## Uso

Após iniciar o aplicativo, você poderá:
- Selecionar seus times favoritos nas configurações.
- Visualizar o calendário de jogos na aba "Calendário".
- Receber notificações em tempo real sobre os jogos do seu time favorito.

