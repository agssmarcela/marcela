# Marcela — Portfólio

Portfólio pessoal de design com foco em **UX/UI**, **identidade visual** e **social media**.

O site é uma página única em HTML, CSS e JavaScript puros, sem frameworks e sem etapa de build. Ele reúne apresentação, habilidades, projetos e contato.

---

## ✦ Seções

| Seção | O que mostra |
|---|---|
| **Sobre** | Nome, texto de apresentação e foto |
| **Habilidades** | Programas que eu domino: Premiere Pro, DaVinci Resolve, Illustrator, After Effects, Photoshop e Canva |
| **Projetos** | Lista dos cases. Cada projeto abre em uma página própria |
| **Contato** | WhatsApp, e-mail e LinkedIn |

### Projetos

- **Agatah — velas aromáticas**: identidade visual completa, com logotipo (versões vertical e horizontal), motion da logo, paleta de cor, tipografia e mockups.
- **Habitare — Pet Club Hotel**: site para hotel e daycare de cães, com versão desktop e mobile navegáveis dentro de molduras de navegador e de celular.

---

## ✦ Tecnologias

- HTML5 semântico
- CSS3: Grid, Flexbox, `clamp()` para tipografia fluida, animações e media queries
- JavaScript puro:
  - navegação entre projetos por hash (`#agatah`, `#habitare`)
  - animações de entrada com `IntersectionObserver`
  - cópia dos códigos de cor da paleta com um clique
- Fontes do Google Fonts: **Anton**, **Archivo**, **Inter** e **Great Vibes**

---

## ✦ Estrutura

```
.
├── index.html                # página completa (HTML, CSS e JS)
├── README.md
└── assets/
    ├── foto.jpg
    ├── agatah-motion.mp4       # motion da logo Agatah
    ├── agatah-motion-poster.jpg
    ├── logo-v-*.jpg            # logos verticais (rosa, mostarda, roxo)
    ├── logo-h-*.jpg            # logos horizontais (rosa, mostarda, roxo)
    ├── tipografia.jpg
    ├── mk-*.jpg                # mockups (adesivos, tags, cartões, velas, sacolas)
    ├── habitare-web.jpg        # site Habitare, versão desktop
    └── habitare-mobile.jpg     # site Habitare, versão mobile
```

---

## ✦ Como rodar localmente

Não precisa instalar nada. Basta clonar o repositório e abrir o `index.html` no navegador:

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
cd SEU-REPOSITORIO
```

Se o vídeo ou as fontes não carregarem abrindo o arquivo direto, rode um servidor local simples:

```bash
# com Python
python -m http.server 8000

# ou com Node
npx serve .
```

Depois é só acessar `http://localhost:8000`.

---

## ✦ Publicar no GitHub Pages

1. Suba os arquivos para o repositório, com o `index.html` na raiz.
2. No GitHub, vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
5. Em alguns minutos o site fica disponível em `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`.

---

## ✦ Contato

- **WhatsApp:** (27) 99942-4328
- **E-mail:** agss.marcelaa@gmail.com
- **LinkedIn:** [linkedin.com/in/marcelagomes2](https://www.linkedin.com/in/marcelagomes2/)

---

© 2026 Marcela. Todos os direitos reservados. Os projetos e imagens deste repositório são de autoria própria e não podem ser reutilizados sem autorização.# marcela
