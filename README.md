# podcast-manager

## 🚀 Aplicação estilo Netflix para podcasts em vídeo com Node.js

Episódios de podcasts em vídeo, organizados por **categorias** e com suporte a **filtro por nome do podcast**.

---

### 📋 Pré-requisitos

- Instalar o **Node.js**:  
  https://nodejs.org/en/download

---

### 🔧 Instalação

#### Passos:

- Copie a URL do repositório (HTTPS ou SSH):  
  `https://github.com/pablomattos/node-ts-without-frameworks-podcast-menager.git`  
- Abra o Terminal ou Git Bash no seu computador  
- Altere o diretório de trabalho atual para o local onde deseja clonar o repositório  
- Digite o comando abaixo:

```bash
git clone https://github.com/pablomattos/node-ts-without-frameworks-podcast-menager.git
```

#### Na IDE:

- Abra o terminal
- Acesse a pasta do projeto clonado
- Execute:

```bash
npm install
```

- Para iniciar o servidor em modo desenvolvimento:

```bash
npm run start:dev
```

- Para rodar em modo observação contínua:

```bash
npm run start:watch
```

---

### ▶️ Como funciona

A aplicação disponibiliza uma API REST com os seguintes endpoints:

#### `GET /api/episodes`

Retorna todos os episódios organizados por categoria.

#### `GET /api/episode?p=nomeDoPodcast`

Retorna episódios filtrados por nome do podcast informado na query.

##### Exemplo de resposta:

```json
[
  {
    "podcastname": "flow",
    "episode": "CBUM - Flow #319",
    "videoID": "pQSuQmUfS30",
    "cover": "https://i.ytimg.com/vi/pQSuQmUfS30/maxresdefault.jpg",
    "link": "https://www.youtube.com/watch?v=pQSuQmUfS30",
    "categories": ["saúde", "bodybuilder"]
  }
]
```

---

## 🛠️ Construído com

- [VS Code](https://code.visualstudio.com/download)  
  > *Você pode utilizar qualquer editor de sua preferência*

### Tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/)
- [TSX](https://github.com/esbuild-kit/tsx)
- [Tsup](https://tsup.egoist.dev/)

---

## ✒️ Autor

**Pablo Moraes De Mattos**  
[LinkedIn](https://www.linkedin.com/in/pablomoraesdemattos/)
[GitHub](https://github.com/pablomattos)