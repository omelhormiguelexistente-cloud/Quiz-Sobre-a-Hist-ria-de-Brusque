#  Quiz: Cultura de Brusque!

> Um jogo educativo e interativo sobre a história, cultura e culinária de Brusque — SC.

---

##  Sobre o projeto

O **Quiz: Cultura de Brusque!** é um jogo de perguntas e respostas desenvolvido para estudantes que queiram aprender (ou testar seus conhecimentos) sobre a cidade de Brusque, em Santa Catarina. O projeto foi criado com HTML, CSS e JavaScript puro — sem frameworks ou bibliotecas externas — tornando o código simples, leve e fácil de entender.

---

##  Como funciona

Ao abrir o jogo, o jogador informa seu **nome**, **escola** e **idade** antes de começar. Em seguida, enfrenta **15 perguntas divididas em 3 categorias**:

| Categoria | Perguntas | Tema |
|-----------|-----------|------|
|  Culinária | 5 | Pratos típicos da região, como o Marreco Recheado, Cuca e Strudel |
|  Cultura | 5 | Festas, monumentos, indústria e a identidade cultural de Brusque |
|  História | 5 | Fundação da cidade, colonização alemã e personagens históricos |

Entre cada categoria, uma **tela de transição** aparece com o resultado parcial e uma mensagem de incentivo antes de continuar.

Ao responder cada pergunta, o jogador recebe um **feedback imediato** — com uma explicação sobre a resposta correta — antes de avançar para a próxima.

No final, é exibida uma **tela de resultado** com a pontuação total e por categoria, além de uma mensagem personalizada com o nome do jogador. É possível também ver um **resumo detalhado** de cada resposta dada.

---

##  Estrutura do projeto

```
quiz-brusque/
└── quiz-brusque-completo.html   # Arquivo único com todo o jogo (HTML + CSS + JS)
```

O jogo inteiro está em um único arquivo `.html`, sem dependências externas além da fonte do Google Fonts carregada via CDN.

---

## Funcionalidades

- 15 perguntas com imagens reais (Wikimedia Commons)
- Dois tipos de questão: texto e imagem nas opções
- Feedback visual animado a cada resposta (✅ acerto / ❌ erro)
- Barra de progresso colorida por categoria
- Tela de transição entre seções com placar parcial
- Tela de resultado final com pontuação por categoria
- Tela de desempenho detalhado por pergunta
- Suporte à tecla Enter nos campos de texto
- Fundo animado com sol, nuvens e flores
- Layout responsivo para celular e computador
- Reinicialização completa do jogo sem recarregar a página

---

##  Como usar

Não é necessário instalar nada. Basta abrir o arquivo no navegador:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/quiz-brusque.git

# Abra o arquivo no navegador
cd quiz-brusque
start quiz-brusque-completo.html      # Windows
open quiz-brusque-completo.html       # macOS
xdg-open quiz-brusque-completo.html   # Linux
```

Ou simplesmente faça o download do arquivo `.html` e clique duas vezes para abrir.

---

##  Tecnologias utilizadas

- **HTML5** — estrutura das telas e elementos
- **CSS3** — estilização, animações e layout responsivo
- **JavaScript (ES6)** — lógica do jogo, troca de telas e geração dinâmica das perguntas
- **Google Fonts** — fontes Baloo 2 e Nunito
- **Wikimedia Commons** — imagens de domínio público usadas nas perguntas

---

##  Telas do jogo

| Tela | Descrição |
|------|-----------|
| Início | Apresentação das categorias e campo de nome |
| Escola / Idade | Coleta de dados do jogador |
| Pergunta | Exibe a questão com imagem e opções de resposta |
| Feedback | Mostra se acertou ou errou, com explicação |
| Transição | Resumo da categoria concluída antes de avançar |
| Resultado | Placar final com pontuação por categoria |
| Desempenho | Lista detalhada de acertos e erros por pergunta |

---


##  Licença

Este projeto é de uso educativo e livre para adaptação. Sinta-se à vontade para usar em escolas, eventos ou projetos culturais sobre Brusque e região.

---
