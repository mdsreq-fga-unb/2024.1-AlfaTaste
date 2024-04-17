<center>

# Processos de Desenvolvimento de Software

</center>

---

## Metodologias


<center style="margin: 0 auto; width: fit-content;">

_Tabela 1 - Metodologia_

| Abordagem | Ágil               |
|-----------|--------------------|
| Ciclo de vida | Iterativo e Incremental |
| Processo  | ScrumXP            |


Fonte: Autores(2023)
</center>

<p style="text-indent: 2cm; text-align: justify;">Nossas decisões são influenciadas pela natureza do projeto e pela gestão do tempo. Além disso, a adaptação aos requisitos é um elemento fundamental para o sucesso de nosso projeto, sendo um processo dinâmico que favorece a interação entre os membros da equipe. Esse foram alguns critérios para a escolha:</p>

* Adaptação aos requisitos do projeto.
* Ênfase na colaboração e no trabalho em equipe.
* Entrega rápida e contínua.
* Qualidade do produto final.

<p style="text-indent: 2cm; text-align: justify;">Ainda utilizamos o framework do Sommerville para termos mais clareza na hora de fazer a nossa escolha.</p>

<p style="text-indent: 2cm; text-align: justify;">Sommerville (2018) sugere que ao decidir sobre o equilíbrio entre abordagens, é necessário responder a uma série de perguntas que abrangem três áreas distintas, porém complementares:</p>

* Técnicas: relacionadas ao sistema em desenvolvimento.
* Humanas: envolvendo a equipe de desenvolvimento.
* Organizacionais: ligadas à organização que está desenvolvendo e/ou adquirindo o sistema.

---

## Questões Técnicas

1. Qual é o tamanho do sistema que está sendo desenvolvido?
    - Será um sistema de pequeno porte.

2. Que tipo de sistema está sendo desenvolvido?
    - Aplicação Web de complexidade média.

3. Qual é a vida útil prevista para o sistema?
    - A vida útil será média, com previsão de disponibilidade em um ano.

4. O sistema está sujeito a controle externo?
    - Sim.

---

## Questões Humanas

1. Qual é o nível de competência dos projetistas e programadores do time de desenvolvimento?
    - Os projetistas e programadores são juniores e têm competências diversas.

2. Como está organizado o time de desenvolvimento?
    - É um grupo pequeno e todos os envolvidos irão trabalhar em todas as áreas.

3. Quais são as tecnologias disponíveis para apoiar o desenvolvimento do sistema?
    - [Tecnologias](https://mdsreq-fga-unb.github.io/2024.1-AlfaTaste/#/./Documentacao/visaoProduto?id=tecnologias-a-serem-utilizadas)

---

## Questões Organizacionais

1. É importante ter uma especificação e um projeto (design) bem detalhados antes de passar para a implementação — talvez por motivos contratuais?
    - Não, porque a natureza do projeto entende que deve ser uma construção interativa e com entregas contínuas, não dependendo de detalhes que possam atrasar o mesmo.

2. É realista uma estratégia de entrega incremental, na qual o software é entregue aos clientes ou outros stakeholders e um rápido feedback é obtido?
    - Sim, seria bom para o nosso cliente ter pequenas entregas para validar o produto.

3. Os representantes do cliente estarão disponíveis e dispostos a participar do time de desenvolvimento?
    - Não, os representantes do cliente não participarão diretamente no desenvolvimento do produto, mas vão fornecer feedback durante as etapas de construção do produto.

4. Existem questões culturais que possam afetar o desenvolvimento do sistema?
    - Sim, o nosso produto pode ser influenciado pela cultura dos usuários.

<center style="margin: 0 auto; width: fit-content;">

_Tabela 2 - Ferramenta-Método_

| Nome da Atividade         | Método                          | Ferramenta                      | Entrega                                                 |
|---------------------------|---------------------------------|---------------------------------|---------------------------------------------------------|
| Elicitação e Descoberta   | Reuniões periódicas com o cliente | Teams, Azure Devops, Discord | Diagrama Espinha de Peixe                               |
| Análise e Consenso        | Reunião de equipe               | Teams, Azure Devops, Discord | Documentação da validação do cliente. Backlog da Sprint |
| Declaração                | USs (Histórias de usuário)    | Teams                       | Definição das USs e Backlog dos requisitos              | 
| Representação             | Design do produto (prototipação) | Figma                |                  Protótipo                                       |
| Verificação e Validação   | Conversa com o cliente, reuniões de equipe e testes de validação | Forms, Teams, Azure Devops | Documentação dos testes                                 |
| Organização e Atualização | Listagem dos requisitos, reunião com o cliente | Teams, Notion                  | Documentação atualizada, Aplicação atualizada           |



Fonte: Autores(2023)
</center>

---

## Adequações aos processos escolhidos:

### SCRUM

<center style="margin: 0 auto; width: fit-content;">

_Tabela 3 - Práticas Scrum_

| Práticas do Scrum      | Descrição                                                                                                                  | Ferramenta    |
|------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------|
| Sprints                | Ciclos de desenvolvimento para o projeto, cada sprint terá 1 semana.                                                       | Azure DevOps  |
| Reuniões semanais      | As reuniões servirão para marcar o início e o fim de cada sprint e para alinhar o projeto entre a equipe, elas acontecerão às terças e quintas de 20h15 às 22h15. | Discord       |
| Reunião com o cliente  | As reuniões com o cliente acontecem a cada 15 dias.                                                                       | Discord       |
| Product Backlog        | Lista dos requisitos do produto, ordenadas pela prioridade, que precisam ser desenvolvidos para atender aos objetivos do projeto. | Azure DevOps  |
| Sprint Review, Planning e Retrospectiva | Reuniões aos sábados que serão usadas para apresentar os resultados das sprints.                                   | Discord       |


Fonte: Autores(2023)
</center>

### XP - eXtreme Programming

<p style="text-indent: 2cm; text-align: justify;">As práticas do XP a serem utilizadas ao longo do projeto estão listadas na tabela abaixo.</p>

<center style="margin: 0 auto; width: fit-content;">

_Tabela 4 - Práticas XP_

| Práticas do XP         | Descrição                                                                                                 |
|------------------------|-----------------------------------------------------------------------------------------------------------|
| Histórias de Usuário (US) | Documentos resumidos que descrevem os requisitos do sistema a ser implementado                          |
| Planejamento da Release   | O Planejamento de Release servirá para determinar quais USs ou melhorias serão incluídas na release com base nas necessidades dos usuários |
| Planning Poker           | Método utilizado para estimar as histórias de usuário                                                     |
| Programação em Pares     | Dois programadores trabalham juntos na tarefa de codificação. Essa prática permite a transferência de conhecimento e a melhoria da qualidade do código |
| Integração Contínua      | Os desenvolvedores integram regularmente suas alterações de código, se possível todos os dias            |
| Refatoração              | Envolve fazer melhorias no código existente sem alterar seu comportamento externo                        |


Fonte: Autores(2023)
</center>

---

## Fluxo de Trabalho (ScrumXP)

<center>
    <img alt="Marcio" src="https://github.com/mdsreq-fga-unb/2024.1-AlfaTaste/blob/main/docs/assets/FluxoTrabalho/img.png?raw=true" style="border-radius: 10%;width: 40%;"/>
    <img alt="Marck" src="https://github.com/mdsreq-fga-unb/2024.1-AlfaTaste/blob/main/docs/assets/FluxoTrabalho/img2.png?raw=true" style="border-radius: 10%; width: 40%; ">
</center>

---

## Referências Bibliográficas

* Material da disciplina disponivel no aprender.

---

<div style="margin: 0 auto; width: fit-content;">

## Versionamento

| Data       | Versão | Descrição            | Autor                                                                                                |
|------------|--------|----------------------|------------------------------------------------------------------------------------------------------|
| 17/04/2024 | 0.1    | Criação do documento | Cássio Reis; Felipe Motta; Hugo de Melo; João Antonio; Letícia Rodrigues; Márcio Costa; Yago Santos. |

</div>