# Podcast manager

### Descrição 
Um app ao estilo netflix, aonde possa centralizar diferentes episódios podcasts separados por categoria.

### Domínio

Podcasts feitos em vídeo.

### Features

- Listar os episódios em sessões de categorias:
    - [ Saúde, Bodybuilder, Mentalidade, Humor]
- Filtrar episódios por nome de podcast

## Como 

- Listar os episódios em sessões de categorias 

### Como vou implementar

GET: retorna lista de episódios

Vou retornar em uma API REST o nome podcast, nome do episódio, imagem de capa, link, category.

```js 
[
    {
        podcastname: "flow",
        episode: "CBUM - Flow #319",
        videoID:"pQSuQmUfS30",
        cover: "https://i.ytimg.com/vi/pQSuQmUfS30/maxresdefault.jpg",
        link: "https://www.youtube.com/watch?v=pQSuQmUfS30",
        categories: ["saúde", "bodybuilder"]
    }
]
```

GET: retorna lista de episódios baseado em um parâmetro enviado pelo cliente do nome do podcast.



