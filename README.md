# Site Temático Responsivo: Defensores de Marvel (Universidade / IFCE)

## 👥 Integrantes
* Iarley Freitas
* Gabriel Dourado

---

## 🦸‍♂️ Tema do Projeto
Desenvolvimento de um site multipágina responsivo focado nos heróis urbanos da Marvel (**Homem-Aranha**, **Demolidor** e **Cavaleiro da Lua**), criado como parte da atividade avaliativa de Desenvolvimento Web.

---

## 🚀 Como Executar o Projeto
1. Clone este repositório ou baixe o arquivo ZIP.
2. Certifique-se de que a estrutura de pastas está correta (com os arquivos `.html` na raiz e a pasta `img/` contendo as imagens).
3. Abra o arquivo **`index.html`** diretamente em qualquer navegador moderno (Google Chrome, Firefox, Edge).
4. Utilize o menu de navegação superior para transitar entre as páginas dos heróis.

---

## 🗺️ Mapa do Checklist de Requisitos CSS
Conforme exigido pelo escopo do trabalho, abaixo está o mapeamento técnico de onde cada requisito foi implementado:

| Requisito CSS | Arquivo | Seletor / Classe |
| :--- | :--- | :--- |
| **Flexbox** | `style.css` | `.menu ul` / `.chamada-nelson-murdock` / `.chamada-clarim` |
| **CSS Grid** | `style.css` | `.cards-grid` |
| **Media Queries** | `style.css` | `@media (max-width: 768px)` |
| **CSS Variables** | `style.css` | `:root` (`--preto`, `--vermelho-marvel`, etc.) |
| **Animations (@keyframes)** | `style.css` | `@keyframes pulsarSentidoRadar`, `@keyframes flashCamera`, etc. |
| **Backgrounds** | `style.css` | `.destaque`, `.poder-lua`, `.chamada-clarim` |
| **CSS Units** | `style.css` | `px`, `%`, `rem`, `fr` usados de forma consciente |
| **Pseudo-classes** | `style.css` | `:hover` (em `.menu a`, `.img-modal`, `.selo-contrato`) |
| **Position + z-index** | `style.css` / Estrutura | Controle de sobreposição e fixação do menu/cabeçalho |

---

## 🤖 Uso de Inteligência Artificial
Seguindo as diretrizes da disciplina, a IA generativa (Gemini) foi utilizada como ferramenta de apoio e estudo para:
* Auxiliar na estruturação lógica de layout com Flexbox e CSS Grid.
* Compreender e aplicar propriedades avançadas como `object-fit` e o comportamento de seletores.
* Depurar trechos de código e estruturar as animações com `@keyframes`.
Todo o código gerado foi revisado, compreendido e adaptado pela dupla.