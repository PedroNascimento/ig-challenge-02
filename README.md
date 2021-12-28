# ig-challenge-02

Desafio 02 - **Componentizando a aplicação** - Trilha ReactJS - Iginite (*Rocketseat*)

O Objetivo desse desafio era refatorar uma página para listagem de filmes de acordo com gênero.

Nesse desafio o código da aplicação já estava totalmente funcional, porém grande parte do código estava diretamente no arquivo **App.tsx**. Para resolver a proposta do desafio era necessário dividir a aplicação em pelo menos dois conteiners principais:

* src/components/Content.tsx: Esse componente deveria possuir toda a lógica e corpo responsável pelo *header* e conteúdo da aplicação.
* src/components/SideBar.tsx: Deveria possuir toda a lógica e corpo responsável pela seção que contém o título do site e parte de navegação à esquerda da página.

A aplicação utilzou o JSON Server para simular uma API que possui as informações de gênero e filmes.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/7572825/147499562-44177090-58f4-4933-b2c1-45caff5c7f80.gif)
