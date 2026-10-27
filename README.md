# Lumen · Clone de plataforma de streaming com HTML e CSS

Projeto do desafio final da trilha de CSS da [DIO](https://www.dio.co). A proposta era reproduzir a interface de um site de streaming (o HBO Max, no projeto de referência) usando apenas HTML e CSS, aplicando tudo o que foi estudado na formação.

Em vez de copiar a marca original, criei uma identidade própria: **Lumen**, uma plataforma fictícia de filmes e séries, com fundo azul-noite e destaque em um gradiente de aqua para rosa. Os títulos, preços e textos são inventados.

> Substitua esta linha por um print da página (por exemplo, `![Prévia do projeto](./preview.png)`).

## Referências

- Repositório da instrutora: [micheleambrosio/hbomax](https://github.com/micheleambrosio/hbomax)
- Site de referência do desafio: [HBO Max](https://www.hbomax.com/br/pt)

## Features

- Menu de navegação (abre e fecha no celular sem JavaScript)
- Cabeçalho com animação de gradiente
- Lista de filmes e séries, com efeito 3D ao passar o mouse
- Cards com os planos de assinatura animados
- Formulário de login com tratamento de campos inválidos
- Rodapé com links importantes
- Interface responsiva (Mobile First)

*As features são visuais e não têm integração com nenhuma API.*

## Conceitos de CSS aplicados

| Tema | Onde aparece |
| --- | --- |
| Fundamentos e variáveis CSS | Cores, gradientes e espaçamentos definidos em `:root` |
| Flexbox | Menu, barra superior, botão do menu, itens do checkbox e dos pôsteres |
| Grid Layout | Grade de pôsteres, cards de planos, rodapé e centralização do login |
| Responsividade | Mobile First com `min-width` em 768px e 1024px, `clamp()`, `viewport` e unidades relativas |
| Pseudo-classes | `:hover`, `:focus`, `:focus-visible`, `:focus-within`, `:checked`, `:valid`, `:invalid`, `:placeholder-shown`, `:not()`, `:nth-child()` |
| Pseudo-elementos | `::before` e `::after` (marcas, selos, sublinhado do menu), `::placeholder`, `::selection`, `::-webkit-scrollbar` |
| Transformações 2D | `translate`, `rotate` e `scale` (ícone do menu, botões, checkbox) |
| Transformações 3D | `perspective`, `rotateX` e `rotateY` nos pôsteres |
| Transições | Botões, cards, links, campos do formulário e checkbox |
| Animações | `@keyframes fluxo` (gradiente do topo) e `@keyframes brilho` (selo do plano popular) |
| Campos inválidos | Borda e mensagem de erro só aparecem depois de o usuário digitar |
| Acessibilidade | Foco visível, rótulos nos campos e `prefers-reduced-motion` |

## Estrutura do projeto

```
lumen-streaming/
├── index.html
├── entrar.html
├── style.css
└── README.md
```

## Como rodar

Não há dependências. Basta clonar o repositório e abrir o `index.html` no navegador:

```bash
git clone https://github.com/DestroyerIG/lumen-streaming-desafiodio.git
cd lumen-streaming-desafiodio
```

Para testar a responsividade, abra as ferramentas do desenvolvedor (`F12`) e use o modo de dispositivo (`Ctrl + Shift + M`).

## Possíveis melhorias

- Pôsteres com imagens reais
- Página de detalhes de cada título
- Tema claro
- Validação do formulário com JavaScript e envio para uma API

## Autor

**Itallo Gabriel**

- GitHub: [DestroyerIG](https://github.com/DestroyerIG)
- LinkedIn: [itallogoncalves](https://www.linkedin.com/in/itallogoncalves)
