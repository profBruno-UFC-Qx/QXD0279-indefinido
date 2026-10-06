# :mushroom: Guia Psicodélico 

Um site informativo que serve como guia sobre substâncias enteógenas (substâncias que alteram a consciência) ou psicodélicos como são comumente chamados. 

## :technologist: Membros da equipe

Luana Lopes de Amorim - 552990

## :cactus: Objetivo Geral

Um site informativo que serve como guia sobre substâncias enteógenas (substâncias que alteram a consciência) ou psicodélicos como são comumente chamados. O site terá uma listagem de substâncias, como, por exemplo, algumas variedades de cogumelos e suas informações. Será possível adicionar, excluir, editar.  Também penso em colocar talvez algumas indicações de livros ou material audiovisual (filmes ou episódios de podcasts) e, também, talvez colocar relatos de uso retirados do Erowid e Reddit. Como acho que isso tudo seria muita coisa, além das substâncias, talvez opte por colocar só os relatos ou só os livros e/ou material audiovisual.

## :eyes: Público-Alvo
Não tem extensão.

## :star2: Impacto Esperado
Não tem extensão.

## :people_holding_hands: Papéis ou tipos de usuário da aplicação

- Administrador/Moderador
- Visitante

> Tenha em mente que obrigatoriamente a aplicação deve possuir funcionalidades acessíveis a todos os tipos de usuário e outra funcionalidades restritas a certos tipos de usuários.

## :triangular_flag_on_post:     Principais funcionalidades da aplicação

Descreve ou liste brevemente as principais funcionalidades da aplicação que será desenvolvida. Destaque a funcionalidades que serão acessíveis a todos os usuários e aquelas restritas a usuários logados.

- Adicionar substâncias/livros/relatos: Admin/Moderador
- Remover substâncias/livros/relatos: Admin/Moderador
- Editar: Admin
  
- Visitante: pode ler/ver e adicionar relato/substância/livro ou material audiovisual. Para ser mais explicativo: (lembrando que quero implementar só 2 coisas: substâncias e relatos OU substâncias e materiais(livro/audiovisual/podcast/etc), mas o que for adicionado passaria para o Admin aprovar. Esse usuário NÃO teria login e o preenchimento para cadastro do item (relato/substância/etc) seria similar à um forms de comentários em um blog: pode optar por colocar nome, email OU postar anonimamente, além disso a descrição e mais itens que dependeriam do que esse visitante fosse cadastrar. Após isso, o que for cadastrado passará por uma supervisão do Admin/Moderador, apenas para se certificar que não é troll e que não contém discurso de ódio ou afins...


## :spiral_calendar: Entidades ou tabelas do sistema

- Administrador:
  - Atributos: id, nome, email, senha

- Substâncias: 
  - Atributos: id, nome, tipo (natural, sintético, etc), descrição, efeitos

- Relato / Indicação de livro / Seja lá o que for
  - data, nome, nome de quem cadastrou (caso tenha sido feito por um visitante que se identificou), id
