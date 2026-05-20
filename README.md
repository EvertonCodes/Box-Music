# 🎵 Box Music

O Box Music é um aplicativo desenvolvido com Ionic + Angular Standalone com o objetivo de apresentar álbuns musicais brasileiros em uma interface moderna e organizada.

---

# 🛠️ Tecnologias Utilizadas

- Ionic
- Angular Standalone
- HTML
- SCSS
- TypeScript

---

# 📂 Estrutura do Projeto

O projeto possui 3 páginas principais:

- Home
- Página do álbum AmarElo — Emicida
- Página do álbum Nada Como Um Dia Após o Outro Dia — Racionais MC's

---

# 🎨 Funcionalidades

- Navegação entre páginas utilizando `RouterLink`
- Cards estilizados para os álbuns
- Barra de pesquisa
- Botões interativos do Ionic
- Interface responsiva
- Organização visual utilizando SCSS

---

# 🧠 Conceitos Utilizados

## HTML
Responsável pela estrutura da página:
- textos
- imagens
- botões
- divisões da tela

## SCSS
Responsável pela estilização:
- cores
- sombras
- bordas arredondadas
- espaçamentos

## TypeScript
Responsável pela lógica da aplicação:
- importação de componentes
- organização da página
- navegação entre telas

## RouterLink
Utilizado para realizar a navegação entre páginas do aplicativo.

Exemplo:

```html
routerLink="/racionais"
```

Quando o usuário clica no botão, o Angular abre outra página do aplicativo.

---

# 🧩 Explicação do ion-button

```html
<ion-button
  expand="block"
  class="botao-album"
  routerLink="/emicida">
```

| Código | Função |
|---|---|
| ion-button | Cria um botão do Ionic |
| expand="block" | Faz o botão ocupar toda largura |
| class="botao-album" | Liga o HTML ao CSS |
| routerLink | Faz navegação entre páginas |

---

# ▶️ Como Executar o Projeto

## 1. Instalar o Node.js

Antes de tudo, é necessário possuir o Node.js instalado no computador.

Verificar versão:

```bash
node --version
```

---

## 2. Instalar o Ionic

No terminal, execute:

```bash
npm i -g @ionic/cli
```

Verificar instalação:

```bash
ionic --version
```

---

## 3. Entrar na Pasta do Projeto

```bash
cd box-music
```

---

## 4. Instalar Dependências

```bash
npm install
```

---

## 5. Rodar o Projeto

```bash
ionic s
```

O projeto abrirá automaticamente no navegador.

---

## 6. Live Reload

Sempre que um arquivo for salvo, o Ionic atualizará automaticamente o aplicativo no navegador.

---

# 👨‍💻 Minha Responsabilidade no Projeto

Fiquei responsável por:

- Interface visual
- Estrutura HTML
- Estilização SCSS
- Organização dos cards
- Navegação entre páginas com RouterLink

---

# 🎤 Explicação da Apresentação

> “Fiquei responsável pela interface visual do aplicativo utilizando Ionic e SCSS. Também implementei a navegação entre páginas utilizando RouterLink.”

---

# 🚀 Projeto Acadêmico

Projeto desenvolvido para fins educacionais na disciplina de Mobile utilizando Ionic + Angular.
