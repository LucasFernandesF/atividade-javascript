# Repositório para a Realização da Atividade

## Entender o funcionamento do JavaScript dos sites

### Site 1: [Amazon](https://www.amazon.com.br/)

#### Área 1: Carrinho de compras da Amazon
- O JavaScript está atuando na manipulação de carrinhos de compras, exibindo produtos em tempo real e atualizando os itens do carrinho e o total de todas as suas compras. Para fazer isso, são utilizadas funções assíncronas para não parar o funcionamento para o usuário, podendo ser para chamar APIs ou realizar manipulações no DOM.

#### Área 2: Cep da Amazon
- Atuando para puxar o formulário de login/cadastro se não estiver logado ou permitindo colocar o número do CEP, puxando para fazer o cálculo de frete das lojas. Para fazer isso, utilizou a chamada para APIs e usou o armazenamento local para puxar as preferências do usuário se já estiver logado.

---

### Site 2: [Instagram](https://www.instagram.com/explore/)

#### Área 1: Explorar Instagram
- O JavaScript pode ser responsável pela atualização dinâmica do explorar e pela interação do usuário com postagens.
- Utilizando WebSockets para comunicar em tempo real, processar as informações e utilizando algum framework para renderizar rapidamente e atualizar o explorar de acordo com a interação do usuário.

#### Área 2: Funcionamento do Reels
- O JS pode estar atuando na reprodução de vídeos, controles personalizados e na interação do usuário com os Reels.
- Utilizando provavelmente APIs de mídia e com certeza utilizando a manipulação do DOM para expandir o vídeo quando clicado, ou a recomendação dinâmica do rolamento dos Reels e também para criar controles personalizados.

---

### Site 3: [LinkedIn](https://www.linkedin.com/)

#### Área 1: Feed de Notícias do LinkedIn
- O JavaScript é responsável por carregar dinamicamente o conteúdo do feed de notícias à medida que o usuário rola a página, sem a necessidade de recarregá-la para ver mais publicações.
- Atua na manipulação do DOM para inserir novos elementos, utilizando funções assíncronas e APIs para buscar dados de posts no servidor, sem precisar recarregar a página. Também utiliza "Event Listeners" para monitorar o evento do usuário e disparar mais conteúdo, se necessário.

#### Área 2: Sistema de Mensagens
- O sistema de mensagens funciona em tempo real, permitindo que os usuários enviem e recebam mensagens instantâneas dentro da plataforma.
- Provavelmente utiliza WebSockets para a comunicação em tempo real e manipulação do DOM para atualização da interface e inserção de novas mensagens.

---

### Site 4: [Gmail](https://mail.google.com/)

#### Área 1: Caixa de Entrada do Gmail
- A interface da caixa de entrada carrega e atualiza dinamicamente as mensagens de e-mail sem a necessidade de recarregar a página.
- Também utiliza funções assíncronas, como AJAX, para buscar novos e-mails sem recarregar a página, manipulando o DOM para atualizar a lista de e-mails e utilizando promises para lidar com as requisições.

#### Área 2: Redação de Novo E-mail (Compose)
- Ao clicar em "Escrever" para compor um novo e-mail, um editor de texto é aberto dinamicamente, permitindo escrever e enviar o e-mail para outro usuário do Gmail.
- O DOM é manipulado para criar uma interface interativa de texto, e, com "Event Listeners", monitora-se o texto do usuário e suas interações com outros botões, como o de enviar e-mail ou anexar arquivos.
