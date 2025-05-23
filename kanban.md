# Fluxo do Board Trello - Payer Board (Christian edition)

Esta recomendação simplifica e adapta o nosso fluxo Trello para refletir a prática cotidiana da equipe, reduzindo etapas que nem todos seguem e propondo um formato mais claro e ágil. É uma sugestão para experimentarmos e testarmos, sem fechar portas para ajustes futuros.

---

## O Time

Não existe "time técnico" existe O TIME todos somos um único time com o mesmo objetivo. 

Como somos um único time, o procedimento deve ser único e simples,  gerar sub-procedimentos para processos especificos deixa apenas o processo cobfuso e burocrático sem necessidade. Não gera nenhum ganho prático.

---

## Por que manter o fluxo enxuto de 5 colunas

Backlog → To Do → Doing → Validate* (opcional) → Done

* Simplicidade operacional: o quadro cabe inteiro na tela, todos enxergam onde cada tarefa está sem rolagem nem burocracia extra.

* Especialistas sem pares diretos: cada dev domina uma área (C++, Flutter, etc.), portanto code review cruzado muitas vezes não é viável; o fluxo curto permite que o próprio especialista leve o cartão de ponta a ponta.

* Sobreposição só no PO: nosso Product Owner acumula Scrum Master e faz testes funcionais básicos em itens críticos/bugs. Tornar Validate opcional reflete exatamente esse cenário — o PO usa quando precisa validar, mas a etapa não bloqueia o restante do time.

* Agilidade e foco: uma tarefa por vez, no máximo três movimentos (To Do → Doing → Done) quando a validação formal não se aplica, reduzindo filas e garantindo entregas rápidas.

* Flexibilidade visual: impedimentos esporádicos são marcados pela etiqueta Bloqueada; se, na prática, isso não der visibilidade suficiente, podemos facilmente inserir uma coluna Blocked entre Doing e Validate para destacar cards travados, sem alterar o restante do fluxo.

* Escalável: se no futuro houver QA dedicado ou mais desenvolvedores na mesma stack (para code review mútuo), basta adicionar colunas como Code Review ou tornar Validate obrigatória — sem recriar o processo.

O fluxo detalhado que tivemos como padrão até agora traz boas práticas, mas hoje adiciona etapas que nem todos utilizam por falta de papéis e tempo. Adotar o modelo enxuto garante clareza, velocidade e alinhamento com a realidade atual, mantendo a porta aberta para incorporar fases extras quando (e se) o time realmente precisar delas.

---




## 📝 Colunas do Board (Fluxo Enxuto)

| Ordem | Coluna | Objetivo | Quando mover? |
|-------|--------|----------|---------------|
| 1 🔙|  **Backlog** | Espaço para **ideias e demandas ainda não priorizadas**. Aqui refinamos a descrição, anexamos documentação e avaliamos dependências. | Assim que um item tem prioridade definida para a próxima entrega. |
| 2 📋|  **To Do** | Lista de **tarefas comprometidas para a sprint**. Cada card já possui responsável(eis) designado(s). | Quando o responsável inicia a execução efetiva. |
| 3 ✏️|  **Doing** | **Execução ativa** – codificação, testes unitários, documentação, prototipação ou pesquisa. Um item deve ficar aqui **até ser concluído pelo mesmo responsável**. | Quando a entrega está pronta para validação ou, caso não seja necessária, direto para **Done**. |
| 4 ✔️|  **Validate** <br>*(opcional)* | Validação funcional feita pelo Product Owner ou por outro colega quando for realmente necessário. Use apenas se houver alguém diferente do executor realizando o teste. | Quando a validação estiver concluída ou aprovada. |
| 5 🟢|  **Done** | Entrega finalizada: PR revisado/mergeado, deploy em produção (ou equivalente) concluído. | Fim de fluxo. |

### Coluna opcional

| Ordem | Coluna | Objetivo | Quando usar? |
|-------|--------|----------|--------------|
| – ⛔|  **Blocked** *(se necessário)* | Destaque visual para **tarefas impedidas** (dependência externa, bug crítico, falta de acesso, etc.). Só crie se a etiqueta **Bloqueada** não der visibilidade suficiente. | Volta a **Doing** assim que o impedimento for resolvido. |

---

### 🔖 Etiquetas sugeridas

- **Bloqueada** – item impedido temporariamente.  
- **Bug / Hotfix** – correção de erro emergencial.  
- **Backend / Frontend / DevOps / Design** – natureza da tarefa.  
- **Prioridade Alta** – se algo precisar furar a fila.

Use as etiquetas para classificar ou sinalizar urgência sem poluir o título.

---

## ✅ Observações
* Gostei muito do canal de notificações no Slack, mais util que a notificações do proprio trello.
* O sistema de notificação do Trello não é bom! por isso ao citar um membro é recomendado que o adicione como membro do card para que ele tenha visualzição do mesmo se ele filtrar as suas tarefas. Depois se ele quiser ele mesmo pode se remover do card que não quiser seguir acompanhando ele.
* Evitar texto em Capslock causa ansiedade pois parece que vc fez algo errado e esta tomando um "esporro".

## 💔 Sentimento pessoal sobre o processo hoje e devaneios da madrugada.

* Sem desmerecer nenhuma coluna, a quantidade atual faz o board deixar de caber na tela — num mural físico ele seria perfeito, no monitor perco a visão de conjunto
* Para uma equipe pequena, cada coluna extra vira um obstáculo; só de pensar em qual usar já perco ritmo, e isso faz com que várias nunca sejam sequer usadas
* Para um time enxuto, certas colunas não se justificam; elas introduzem complexidade sem retorno concreto. As vezes perco mais tempo pensando em que coluna colocar o card do que estar fazendo algo efetivamente com ele
* Grafico de Burndown é dos meus ‘chart-porn’ favoritos: sei que costuma ser mais enfeite do que ferramenta, mas gosto de pontuar as tarefas e ver a curva descendo; vira uma pequena gamificação da sprint, divertida de analisar depois.
* O óbvio não existe, por isso algumas coisas precisam ser ditas explicitamente—é como o aviso nas embalagens de shampoo alertando que não deve ser ingerido. Pode parecer evidente, mas se precisou ser escrito, é porque alguém já tentou.
* Todos tem notebook e webcam entáo,  ligar a câmera nas reuniões é importante porque ninguém gosta de falar com uma letra ou uma tela vazia. Ver o rosto de quem fala reduz a impessoalidade e ajuda a criar conexão. Não precisa de cenário perfeito, só precisa aparecer. pelo menos durante a sua vez.
* Não sou contra processos; apenas defendo que sejam menos burocráticos e mais voltados à execução.
* Desculpem se pareço ranzinza;  o cansaço e o estresse pode fazer isso transparecer na minha atitude.
* Já atuei como “equipe de uma pessoa só” — backend, frontend, deploy, manutenção, design e documentação. Por isso, às vezes acabo me envolvendo em outras partes do processo. Se em algum momento ultrapassei limites, peço desculpas; meu objetivo é apenas compartilhar experiências que considero úteis.





