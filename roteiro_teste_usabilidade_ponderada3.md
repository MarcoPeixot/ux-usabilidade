# Roteiro de Teste de Usabilidade — Atividade Ponderada 3

Aluno: Marco Ruas  
Grupo: G05  
Data: 06/04/2026

## 1. Tela(s) analisada(s)

O fluxo analisado pertence ao sistema FireData, usado para acompanhar ocorrências e apoiar a resposta operacional. Neste teste, o foco é observar se o usuário consegue encontrar uma ocorrência ainda não respondida e abrir seus detalhes.

Tela 1 — Home / Dashboard

Tela inicial do sistema, com mapa, indicadores e atalhos de navegação. Ela é o ponto de partida do fluxo até a visualização das ocorrências.

Tela 2 — Lista de Ocorrências Ativas

Tela que reúne as ocorrências cadastradas, com informações como local, prioridade, operador, status, recursos atribuídos e ações. É nela que o usuário precisa reconhecer qual ocorrência ainda está aguardando resposta.

Tela 3 — Modal de Detalhes da Ocorrência

Modal aberto a partir da lista com os principais dados da ocorrência selecionada, como ID, local, prioridade e operador. Essa etapa mostra se o usuário chegou ao item correto e entendeu o contexto da ocorrência.

Print da tela ou fluxo do projeto:

- Tela 1: `/Users/marcoruas/Desktop/fase1.png`
- Tela 2: `/Users/marcoruas/Desktop/fase2.png`
- Tela 3: `/Users/marcoruas/Desktop/fase3.png`

## 2. Tipo de teste

Tipo: Tarefa do usuário

O teste avalia a tarefa de acessar os detalhes de uma ocorrência não respondida. A ideia é verificar se o caminho até essa informação é claro e se os elementos da interface ajudam o usuário a tomar a decisão certa sem esforço excessivo.

## 3. Conjunto de perguntas usando a técnica do Funil

Lógica do funil: começam pela leitura geral da interface, passam pela identificação da ocorrência correta dentro da lista e terminam na ação específica de abrir seus detalhes.

| # | Pergunta | Nível do funil | Justificativa |
|---|---|---|---|
| 1 | "O que essa tela inicial te mostra e por onde você começaria se quisesse consultar uma ocorrência?" | Amplo | Serve para entender como o usuário interpreta o dashboard e se a navegação até a lista parece óbvia logo no primeiro contato. |
| 2 | "Ao chegar na lista, o que você observa para diferenciar uma ocorrência respondida de uma que ainda não foi respondida?" | Intermediário | Verifica se os elementos visuais da tabela, como status e resposta gerada, comunicam bem a situação de cada ocorrência. |
| 3 | "Qual ocorrência desta lista você entende que está aguardando resposta? Como você chegou a essa conclusão?" | Intermediário | Ajuda a identificar se o usuário consegue interpretar corretamente os sinais usados pela interface. |
| 4 | "Depois de escolher essa ocorrência, onde você clicaria para ver os detalhes dela?" | Específico | Avalia se a ação necessária está visível e faz sentido para o usuário dentro do fluxo. |
| 5 | "Depois de abrir o modal, você sente que está com a ocorrência certa na tela? O que te faz ter certeza disso?" | Específico | Mostra se o conteúdo exibido no modal ajuda o usuário a confirmar que acessou a ocorrência correta. |

## 4. Objetivo do teste

O objetivo do teste é verificar se o usuário consegue localizar uma ocorrência não respondida e acessar seus detalhes com segurança. Também busca identificar se há confusão na leitura dos status, na compreensão da tabela ou na identificação da ação correta.

## 5. Ação ou entendimento esperado

Espera-se que o usuário consiga sair do dashboard, acessar a lista de ocorrências, identificar uma ocorrência com status de aguardando e abrir seu modal de detalhes. Ao final, ele deve entender que a ocorrência ainda não foi respondida e confirmar que acessou o item correto.
