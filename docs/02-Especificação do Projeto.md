# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto


## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.


### Requisitos Funcionais

<table>
<tbody>
<tr align=center>
<td width="100px"><b>ID</b></td>
<td width="650px"><b>Descrição</b></td>
<td width="100px"><b>Prioridade</b></td>
</tr>
<tr>
<td><b>RF-001</b></td>
<td>Deve permitir o gerente fazer login</td>
<td>Alta</td>
</tr>
<tr>
<td><b>RF-002</b></td>
<td>Deve permitir ao gerente adicionar produtos</td>
<td>Alta</td>
</tr>
<tr>
<td><b>RF-003</b></td>
<td>Deve permitir o gerente visualizar todos os pedidos realizados</td>
<td>Média</td>
</tr>
<tr>
<td><b>RF-004</b></td>
<td>Deve permitir ao cliente adicionar produtos a sua comanda  </td>
<td>Alta</td>
</tr>
<tr>
<td><b>RF-005</b></td>
<td>Deve permitir ao cliente visualizar todos os pedidos realizados da comanda</td>
<td>Alta</td>
</tr>
<tr>
<td><b>RF-006</b></td>
<td>Deve permitir ao cliente fechar o pedido para pagamento</td>
<td>Alta</td>
</tr>
<tr>
<td><b>RF-007</b></td>
<td>Deve permitir o cliente visualizar os produtos pela sua categoria</td>
<td>Média</td>
</tr>
<tr>
<td><b>RF-008</b></td>
<td>Deve permitir ao gerente dar baixa aos pedidos já pagos</td>
<td>Média</td>
</tr>
<tr>
<td><b>RF-009</b></td>
<td>Deve permitir o cliente navegar entre as páginas da aplicação</td>
<td>Alta</td>
</tr>
<tr>
<td><b>RF-010</b></td>
<td>Deve permitir a escolha de quantidade do produto que vai ser adicionado ao pedido</td>
<td>Alta</td>
</tr>
</tbody>
</table>

**Prioridade: Alta / Média / Baixa. 


### Requisitos não Funcionais

<table>
<tbody>
<tr align=center>
<td width="100px"><b>ID</b></td>
<td width="650px"><b>Descrição</b></td>
<td width="100px"><b>Prioridade</b></td>
</tr>
<tr>
<td><b>RNF-001</b></td>
<td>A aplicação deve ser responsiva para adaptar-se às telas de tablets e smartphones</td>
<td>Alta</td>
</tr>
<tr>
<td><b>RNF-002</b></td>
<td>A aplicação deve ser intuitiva para pessoas sem experiência</td>
<td>Média</td>
</tr>
<tr>
<td><b>RNF-003</b></td>
<td>A aplicação deve ser intuitiva para pessoas sem experiência</td>
<td>Alta</td>
</tr>
<tr>
<td><b>RNF-004</b></td>
<td>Deve ser desenvolvido utilizando padrão MVC com SQL Server</td>
<td>Alta</td>
</tr>
</tbody>
</table>

**Prioridade: Alta / Média / Baixa. 


## Restrições

<table>
<tbody>
<tr align=center>
<td width="100px"><b>ID</b></td>
<td width="650px"><b>Descrição</b></td>
</tr>
<tr>
<td><b>RE-001</b></td>
<td>O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 23/06/24</td>
</tr>
<tr>
<td><b>RE-002</b></td>
<td>A equipe não pode subcontratar o desenvolvimento do trabalho</td>
</tr>
<tr>
<td><b>RE-003</b></td>
<td>O sistema deve ser desenvolvido em C# .NET -> Entity Framework</td>
</tr>
</tbody>
</table>


## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
