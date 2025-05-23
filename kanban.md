# Fluxo do Board Trello - Payer Board (Christian edition)

Este documento e minha proposta de mudanças para simplificar o fluxo pois  da forma que esta hoje ele é confuso.

reduzindo o numero de colunas faz o board caber inteiro na tela e assim deixar a visibilidade do processo mais simple.

E reflete de forma mais fidedigna o processo , pois uma tarefa esta aguardando para ser feita, ou esta sendo feita ou esta pronta

---

## O Time

Não existe "time técnico" existe O TIME todos somo um unico time com o mesmo objetivo. 

Como somos um único time, o procedimento deve ser único e simples,  gerar sub-procedimentos para processos especificos deixa apenas o processo cobfuso e burocrático sem necessidade. Não gera nenhum ganho prático.

---

## 📝 Colunas do Board

Um único fluxo simples da esquerda para direita enxuto e igual para todos os processos ( design, codificação, prototipacao, pesquisa ) e membros não há necessidade de colunas especiais 

### 🔙 Backlog
- Cartões em estágio de priorização e preparação ( descrição, documentação, checklists)
- Descrição
- Inclusão de Documentação
- Checklists, se aplicavel
- Estudo da tarefa
  - Discussões técnicas
  - Preenchimento de checklist
  - Levantamento de dependências

---

### 📋 To Do
- **Cards que serão executados na Sprint**
- Contém os cards **priorizados** para desenvolvimento.
- Os cards já possuem os seus respectivos responsaveis pela Execução, podendo inclusive conter mais de uma membro. (reduzir cards cars repetidos mudando apenas o responsavel.)

---

### ✏️ Doing
- **Etapa onde o time realaza a execução dos cards:**
- Desenvolvimenmto da tarefa de acordo com o tipo.     
  - codificação
  - teste
  - documentação   
  - pesquisa
  - prototipação
---

### ✔️ Validate
- Card em **homologação**
- Coluna opcional para não se criar cards de validação 
- Mudar o membro do card do executor para quem vai ser o validador ou adicionar a pessoa como membro do card.
- Revisado por um tester definido antes de ser considerado pronto

---

### 🟢 Done
- Execução do Card **concluído**
- PR Feito
- Merge de Develop para Master
- Fim do fluxo de desenvolvimento
- Foi para produção e está **finalizado**

---

## 🔖 Etiquetas do Trello

Utilizar as etiquetas para ajudar a classificar os cards e não poluit o titulo com classificaçãoes e elas podem e devem ser combinadas quando fizer sentido. Abaixo Algumas que me ocorreram agora, temos outros cadastradas no Trello

Por exemplo 
- [Bug] [Backend]
- [Analise] [Bug]
- [Backend] [Analise]

Vou por em inglês tudo mas podia até ser em Esperanto

### Analise
Quando a Tarefa necessita alguma verificação/Analise para gerar subsidios para o seu desenvolvimento

### Backend 
Tarefas que envolvem os Backends pois existe o backend web na AWS e o backend local das Libs e modos de integração. 

### Bloqueada
Tarefas Bloquedas que não podem processguir. Voltam para **To Do** no final da sprint se avalaia se continua na sprint ou volta para Backlog até que seja destravad

### Bug
Correções de erros encontrados na validação ou de fonte externa

### Design 
Aplicado em tarefas de UX e UI

### Devops
Para tarefas de Infraestura 

### Frontend
Tarefas que envolvem as aplicações a nivel de usuário no Desktop, Mobile ou Web

###

### Suporte
Tarefas em que algum membro do time irá usar tempo da sprint, prestando suporte avançado para clientes ou parceiros.


---

## ✅ Observações
* Gostei muito do canal de notificações no Slack
* O sistema de notificação do Trello não é bom! por isso ao citar um membro é recomendado que o adicione como membro do card para que ele tenha visualzição do mesmo se ele filtrar as suas tarefas. Depois se ele quiser ele mesmo pode se remover do card que não quiser seguir acompanhando ele.
* Evitar texto em Capslock causa ansiedade pois parece que vc fez algo errado e esta tomando um "esporro".

## 💔 Sentimento pessoal sobre o processo hoje e devaneios da madrugada.

* O óbvio não existe, por isso algumas coisas precisam ser ditas explicitamente—é como o aviso nas embalagens de shampoo alertando que não deve ser ingerido. Pode parecer evidente, mas se precisou ser escrito, é porque alguém já tentou.
* Todos tem notebook e webcam entáo,  ligar a câmera nas reuniões é importante porque ninguém gosta de falar com uma letra ou uma tela vazia. Ver o rosto de quem fala reduz a impessoalidade e ajuda a criar conexão. Não precisa de cenário perfeito, só precisa aparecer. pelo menos durante a sua vez.
* Eu pareço ser as vezes anti-processos, mas apeans acho que ele deve ser menos burocratico e focado na execução
* Eestou cansado e estressado então eu ando razinza e minha paciencia anda baixa perdão. 





