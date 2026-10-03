# MoveUp

## 1. Nome do projeto

**MoveUp**

O MoveUp é uma plataforma voltada para atividades físicas, criada para apresentar diferentes modalidades de exercícios, desafios, planos e conteúdos relacionados à prática de atividades físicas.

---

## 2. Descrição do projeto

O MoveUp foi desenvolvido como um site para reunir informações sobre atividades físicas em um único lugar.

A página apresenta atividades como musculação, corrida, ciclismo, alongamento e funcional. Também possui áreas destinadas ao acompanhamento da evolução, descoberta de novos desafios, planos de acesso, depoimento de usuário e conteúdos em formato de blog.

---

## 3. Objetivo

O objetivo do MoveUp é proporcionar uma experiência simples para que o usuário possa:

- Conhecer diferentes atividades físicas;
- Explorar novos desafios;
- Criar uma rotina de atividades;
- Acompanhar sua evolução;
- Conhecer os planos disponíveis;
- Acessar conteúdos relacionados à prática de exercícios.

---

## 4. Público-alvo

O site é direcionado a pessoas interessadas em atividades físicas, exercícios e melhoria da rotina de treinos.

O conteúdo pode ser utilizado por pessoas que desejam conhecer novas atividades, criar uma rotina de exercícios ou acompanhar sua evolução.

---

## 5. Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- **HTML5** — estruturação das páginas e conteúdos;
- **CSS3** — estilização e identidade visual;
- **Bootstrap 5** — utilização do sistema de grid e componentes responsivos;
- **Phosphor Icons** — utilização de ícones na interface.

### Dependências externas

O projeto utiliza:

- Bootstrap 5 via CDN;
- Phosphor Icons via CDN.

---

## 6. Estrutura do site

O site é organizado nas seguintes seções:

### Início

Apresenta a proposta principal do MoveUp, com o título **"Seu movimento começa agora."**, uma breve descrição e botões de acesso às atividades.

### Atividades

Apresenta diferentes modalidades de atividades físicas:

- Musculação;
- Corrida;
- Ciclismo;
- Alongamento;
- Funcional.

Cada atividade possui um ícone e uma breve descrição.

### Acompanhe sua evolução

Seção que apresenta a possibilidade de registrar atividades, acompanhar treinos e visualizar a evolução.

### Encontre seu próximo desafio

Área destinada à descoberta de atividades e novos desafios.

### Depoimento

Apresenta um depoimento de usuário sobre a utilização da plataforma e o acompanhamento da evolução.

### Planos

O site apresenta três opções de planos:

- **Básico** — gratuito;
- **Plus** — R$ 49,90 por mês;
- **Pro** — R$ 79,90 por mês.

Os planos apresentam diferentes recursos relacionados às atividades, rotinas e acompanhamento da evolução.

### Chamada para ação

A página possui uma seção com a mensagem **"Pronto para começar?"**, incentivando o usuário a iniciar sua experiência na plataforma.

### Blog

O site apresenta conteúdos relacionados a exercícios, saúde e motivação, incluindo:

- **Como começar uma rotina de exercícios**;
- **A importância de manter o corpo em movimento**;
- **Encontre uma atividade que combine com você**.

### Rodapé

O rodapé apresenta:

- Logo do MoveUp;
- Descrição da plataforma;
- Links de navegação;
- Recursos;
- Informações da empresa;
- Campo para newsletter;
- Redes sociais;
- Direitos autorais.

---

## 7. Organização dos arquivos

A estrutura principal do projeto é organizada da seguinte forma:

```text
MoveUp/
│
├── index.html
├── style.css
│
├── Logo MoveUp.png
├── Principal.jpg
├── Funcionalidades-01.jpg
├── Funcionalidades-02.jpg
├── Depoimento-usuario.jpg
├── Chamada.jpg
├── Blog-01.jpg
├── Blog-02.jpg
└── Blog-03.jpg
```

O arquivo `index.html` contém a estrutura e os conteúdos do site, enquanto o `style.css` concentra a estilização da interface. As imagens e a logo são utilizadas diretamente nas diferentes seções da página.

---

## 8. Responsividade

O projeto utiliza o sistema de grid do **Bootstrap** para adaptar a organização dos elementos a diferentes tamanhos de tela.

São utilizadas classes responsivas como:

- `col-12`;
- `col-sm-6`;
- `col-md-6`;
- `col-lg-4`;
- `col-lg-6`;
- `order-2`;
- `order-lg-1`.

Permitindo que a página seja exibida adequadamente em dispositivos móveis.

---

## 9. Acessibilidade

Alguns recursos de acessibilidade foram utilizados no desenvolvimento da página, como:

- Definição do idioma da página como `pt-BR`;
- Uso de textos alternativos (`alt`) nas imagens;
- Utilização de uma estrutura organizada de títulos e seções;
- Uso de atributos `aria-label` em elementos que precisam de identificação adicional;
- Utilização de textos visualmente ocultos para auxiliar na identificação dos controles do carrossel.

Esses recursos ajudam a tornar a estrutura da página mais compreensível e acessível.

---

## 10. Decisões de UX

Durante a construção da interface, algumas decisões foram utilizadas para melhorar a experiência de navegação:

- **Navegação no topo:** facilita o acesso às principais áreas do site;
- **Botões de ação em destaque:** direcionam o usuário para ações como começar e explorar atividades;
- **Cards de atividades:** organizam as modalidades de forma visual e objetiva;
- **Separação por seções:** facilita a compreensão dos diferentes conteúdos;
- **Planos apresentados lado a lado:** facilita a visualização dos recursos disponíveis em cada opção;
- **Imagens ao longo da página:** ajudam a tornar o conteúdo mais visual;
- **Efeitos de interação:** elementos como botões e cards possuem efeitos visuais ao passar o cursor;
- **Identidade visual consistente:** utilização predominante de branco, tons neutros e laranja como cor de destaque.

A cor principal utilizada no projeto é o laranja `#f97316`, enquanto o texto principal utiliza `#171717`.

---

## 11. Dificuldades encontradas

Durante o desenvolvimento do site, alguns pontos exigiram atenção:

- Organizar uma quantidade significativa de informações em uma única página;
- Estruturar as diferentes seções utilizando o sistema de grid do Bootstrap;
- Adaptar a organização dos elementos para diferentes tamanhos de tela;
- Organizar imagens, textos, cards, planos e demais componentes de maneira visualmente equilibrada.

---

## 12. Melhorias futuras

Como possíveis melhorias para uma versão futura do projeto, podem ser implementados:

- Sistema real de login;
- Cadastro de usuários;
- Sistema de assinatura dos planos;
- Gerenciamento de rotinas de exercícios;
- Acompanhamento detalhado da evolução;
- Sistema de desafios;
- Links funcionais para as redes sociais;
- Sistema de gerenciamento de conteúdo.

Atualmente, alguns links e botões do projeto utilizam `href="#"`, funcionando como elementos visuais da interface e não como funcionalidades conectadas a sistemas reais.
