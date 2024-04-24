# Ponderada-MVC

As baseado nas imagens fornecidas, aqui está uma descrição detalhada e uma explicação didática dos conteúdos:

### Primeira Imagem: Diagrama MVC

O Modelo-Visão-Controlador (MVC) é uma estrutura conceitual que divide uma aplicação em três componentes interconectados.

- **Modelo (Model)**: Contém a lógica de dados da aplicação. No diagrama, há duas entidades principais:
  - **Usuário (User)**: Com atributos como ID, Nome, E-mail, Senha, Idade, Local, Gênero, Pontos, e Customização do mascote liberadas ao completar tasks.
  - **Publicação (Post)**: Com atributos como ID do post, Título, Conteúdo publicado, Anexos (Categoria da ação e em qual ONG foi realizada) e UserID.

- **Visão (View)**: É a interface de usuário da aplicação, onde os dados do modelo são apresentados ao usuário. No diagrama, há duas visões principais:
  - **Login**: Onde os usuários entram em suas contas.
  - **Publicações**: Onde os usuários veem, publiquem e interagem com as publicações.

- **Controlador (Controller)**: Contém a lógica de controle que responde às ações do usuário, manipula os dados do modelo e seleciona a visão a ser apresentada. As ações no diagrama incluem:
  - **Login do Usuário**: Inclui operações como Verificar se a conta já existe, Cadastrar, e Apresentar as informações para login.
  - **Publicações**: Inclui operações como Criar, Apresentar as informações da publicação e Deletar.

### Segunda Imagem: Tecnologias Utilizadas

Esta imagem ilustra as tecnologias selecionadas para desenvolver diferentes aspectos da aplicação MVC.

- **Banco de dados relacionais**: Tecnologias para gerenciamento de dados.
  - **PostgreSQL**: Um sistema de banco de dados relacional.
  - **DBeaver**: Uma ferramenta de interface gráfica para gerenciar bancos de dados.
  - **Render**: Pode referir-se a um serviço de hospedagem ou renderização de banco de dados.

- **Backend**: Onde a lógica de negócios é processada, e a interação com o banco de dados ocorre.
  - **Node.js**: Uma plataforma de servidor para executar JavaScript.
  - **Sails.js**: Um framework MVC para Node.js que facilita a construção de aplicações de servidor personalizadas.

- **Frontend**: A parte da aplicação com a qual os usuários interagem diretamente.
  - **HTML**: Linguagem de marcação usada para estruturar páginas na web.
  - **CSS**: Linguagem de estilo usada para descrever a apresentação de um documento escrito em HTML.
  - **JavaScript**: Linguagem de programação usada para criar conteúdo dinâmico na web.
  - **Bootstrap**: Um framework de front-end para desenvolver sites e aplicações web responsivas.

A combinação dessas tecnologias sugere uma abordagem moderna, robusta e escalável para o desenvolvimento de aplicações web, utilizando práticas e ferramentas atuais.
