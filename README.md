# 🛡️ A Jornada dos Números — A Corrida dos Decimais e Frações

Jogo de RPG educativo para turmas do **6º ano do Ensino Fundamental**. Os alunos atravessam três reinos, derrotam chefões resolvendo desafios de **frações e números decimais**, ganham XP, sobem de patente, desbloqueiam conquistas e trocam o ouro do jogo por **prêmios reais** definidos pelo professor.

🎮 **[Jogar a versão online](https://ewerton-cg.github.io/corrida-decimais-fracoes/)** · ou abra o arquivo `index.html` no navegador (não precisa instalar nada).

---

## 🎯 Objetivos pedagógicos e BNCC
* **Habilidades:** `EF06MA07` a `EF06MA11`: comparação e equivalência de frações, relação entre frações e decimais, fração de uma quantidade e operações com números racionais positivos.
* **Três reinos, três níveis:**
  * 🌲 **Floresta das Frações (fácil):** leitura de decimais, valor posicional, partes de um inteiro, frações equivalentes. Chefão: Troll da Ponte.
  * 🏔️ **Montanhas dos Decimais (médio):** adição e subtração com vírgula, fração de uma quantidade, comparações, frações decimais. Chefão: Gigante de Pedra.
  * 🏰 **Castelo do Dragão (difícil):** multiplicação e divisão de decimais, operações com frações e problemas do dia a dia. Chefão final: Dragão Ancião.
* A dificuldade também cresce dentro de cada reino (casas 1–6, 7–13 e 14–19).
* **Perguntas que não se repetem:** banco fixo com 32 questões, mais geradores automáticos que criam questões novas com números sorteados. As alternativas são embaralhadas a cada pergunta e todas as respostas trazem uma explicação.

## 🕹️ Mecânicas de jogo
* **Dado + desafio:** acertou, avança; errou ou o tempo acabou, perde 1 ❤️ (sem corações, perde a próxima vez).
* **Casas especiais:** 💰 Baú (ouro), 🌀 Portal (+2), 🕸️ Armadilha (−2), 🍺 Taverna (+XP e cura) e ☠️ **Chefão** na casa 20.
* **XP e patentes:** Aprendiz, Escudeiro, Cavaleiro, Mestre e Lenda. Respostas rápidas e **combos** de acertos seguidos rendem mais XP.
* **13 conquistas**, como Relâmpago, Reino Perfeito, Mestre das Frações e Matador de Dragões.
* **Salão dos Heróis:** ranking da turma com nível, acertos e conquistas.

## 🎁 Prêmios reais
1. O aluno junta ouro jogando e resgata um prêmio na **Loja do Mercador**.
2. O jogo gera um **cupom com código** (ex.: `JN-7K3-Q9P`), que o aluno mostra ao professor.
3. No **Painel do Professor** (PIN inicial `1234`, troque no primeiro acesso), o professor confere o código, marca como entregue ou cancela e devolve o ouro.

No painel também dá para editar prêmios e preços, dar ou tirar ouro de alunos, ajustar o tempo das perguntas e o multiplicador de ouro, e exportar ou importar um backup.

> ⚠️ **Limitações:** os dados ficam salvos **no navegador de cada aparelho** (localStorage). Não há servidor nem senha por aluno, então um aluno pode jogar com o nome de outro ou mexer nos dados pelas ferramentas do navegador. Antes de entregar o prêmio, confira o cupom no painel e o nome do aluno. Faça backup pelo painel com frequência.

## 👨‍🏫 Como usar em sala de aula
* **Projetor (modo Equipes):** de 2 a 4 equipes revezando na mesma tela.
* **Celular ou computador (modo Herói solo):** o aluno joga contra dois rivais controlados pelo computador. Usando sempre o mesmo nome, o progresso fica salvo no aparelho.
* **Atalhos:** teclas `1`–`4` ou `A`–`D` para responder.

## 🛠️ Tecnologias
* HTML5, CSS3 e JavaScript puro, num único arquivo e sem dependências (só as fontes do Google Fonts).
* Web Audio API para os efeitos sonoros sintetizados.
* Canvas para as animações de confete.

---

**Desenvolvido por Ewerton Conceição Grigorio**
*Licenciando em Matemática | Desenvolvimento de Materiais Didáticos & Tecnologia Educacional*
