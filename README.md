# Vinheria Agnello

## 📜 Descrição do Projeto

Site oficial da **Vinheria Agnello**, criado como parte de um projeto escolar para modernizar a presença online da marca, preservando sua elegância e tradição. A vinheria atua há mais de 15 anos com uma curadoria especializada de vinhos nacionais e internacionais.

---

## 🏗️ Estrutura do Projeto

* `index.html` — **Página Inicial**: destaque visual com hero, sobre, vídeo, lista de recomendações e horários.
* `historia.html` — **História**: narrativa da vinheria com efeitos de leitura e realce.
* `produtos.html` — **Produtos**: catálogo de vinhos com hover nos cards.
* `equipe.html` — **Equipe**: apresentação dos membros com animações e ícones.
* `contato.html` — **Contato**: formulário responsivo com estilizações de foco.

Menu de navegação fixo presente em todas as páginas para facilitar o acesso.

---

## 👥 Integrantes do Grupo

| Nome                               | Página Responsável | GitHub                                                |
| ---------------------------------- | ------------------ | ----------------------------------------------------- |
| Leandro Afonso Silva Santos Júnior | Página Inicial     | [TLean07](https://github.com/TLean07)                 |
| Lucas Mesquita Massoni             | Página de Contato  | [lucasmassoni06](https://github.com/lucasmassoni06)   |
| Luigi Escudero Grigoletto          | Página de Produtos | [Lueg2007](https://github.com/Lueg2007)               |
| Guilherme Barone Milani            | Página de História | [GuilhermeBM3012](https://github.com/GuilhermeBM3012) |
| Felipe Balbino Murad               | Página da Equipe   | [FelipeM211](https://github.com/FelipeM211)           |

---

## 🔗 Links Úteis

* **Repositório GitHub:** [https://github.com/TLean07/CPHTML1](https://github.com/TLean07/CPHTML1)
* **GitHub Pages:** [https://tlean07.github.io/CPHTML1/](https://tlean07.github.io/CPHTML1/)
* **Deploy (Vercel):** [https://vinheria.vercel.app](https://vinheria.vercel.app)

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** semântico
* **CSS3** moderno e responsivo
* **Font Awesome** para ícones
* **YouTube Iframe** para vídeo institucional
* **Formulário** com validação básica

---

## 🎨 Efeitos Visuais por Página

### 1. Página Home (`index.html`)

* **Pulsar no logo**: `animation: pulsarLogo 4s ease-in-out infinite`.
* **Underline animado no menu**: pseudo-elemento `::after` cresce ao `:hover` em `.nav-menu a`.
* **Efeito "ripple" no botão da hero**: `::before` desliza brilho sobre `.hero .btn`.
* **Entrada suave do título**: `@keyframes deslizarTitulo` no `<h2>` da hero.
* **Destaque em `<strong>`**: traço abaixo via `strong::after` no hover.
* **Listagem Top 5**: sequencial `animation-delay` em `.lista li`.
* **Zoom no vídeo**: `.video-wrapper:hover { transform: scale(1.02); }`.
* **Realce na tabela**: `tr:nth-child(odd)` e hover em `.tabela tr`.
* **Scroll suave**: `html { scroll-behavior: smooth; }`.

> Regras completas no `efeitos.css`, bloco “Home”.

### 2. Página História (`historia.html`)

* **Leitura enfatizada**: `#texto::first-letter { font-size: 40px; }`.
* **Zoom de seção**: `.historia:hover, .mundo_vinhos:hover, .mensagem_final:hover { transform: scale(1.03); }`.
* **Box-shadow e padding**: realce com `box-shadow`, `background-color` e `transition: all 1s`.

> Veja em `efeitos.css` sob “HISTÓRIA”.

### 3. Página Produtos (`produtos.html`)

* **Cards de vinho**: `.vinho-item:hover { transform: scale(1.03); }`.
* **Transição suave**: `transition: transform 0.3s ease;`.
* **Sombras e bordas**: `box-shadow` e `border-radius: 12px`.

> Regras em `style.css` (seção Produtos) e herdar scroll suave.

### 4. Página Equipe (`equipe.html`)

* **Background alternado**: `.membros .membro:nth-child(odd)` com cor suave.
* **Ícone antes do nome**: `membro h3::before { content: "🍷 "; }`.
* **Título animado**: `.equipe h2:hover { transform: scale(1.05); }`.

> Detalhes em `efeitos.css` sob “EQUIPE”.

### 5. Página Contato (`contato.html`)

* **Foco nos inputs**: `input:focus, textarea:focus { border-color: #c2a570; outline: none; }`.
* **Botão hover**: `.contato button:hover { background-color: #c2a570; transform: translateY(-2px); transition: all 0.3s; }`.
* **Transições gerais**: `transition: border-color 0.3s, background-color 0.3s, transform 0.3s`.

> Acrescente em `efeitos.css` sob “CONTATO”.

---

## 📝 Observações

* As animações e transições estão centralizadas em `efeitos.css` para fácil manutenção.
* Ajuste cores e durações conforme a identidade visual da vinheria.

---

## 📄 Licença

Projeto desenvolvido para fins acadêmicos.
