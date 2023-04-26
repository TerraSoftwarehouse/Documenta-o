<span id="topo">

<h1 align="center">Sprint 2</h1>
<p>
</p>

<p align="center">
    <a href="#objetivos"><b>Objetivo</b></a> &nbsp |&nbsp &nbsp
    <a href="#desenvolvimento"><b>Desenvolvimento</b></a> &nbsp |&nbsp &nbsp
    <a href="#planejamento"><b>Planejamento</b></a> &nbsp |&nbsp &nbsp
    <a href="#desenvolvimentosite"><b>Desenvolvimento do site</b></a> &nbsp |&nbsp &nbsp
    <a href="#sprintreview"><b>Sprint Review</b></a>
</p>
    
<h2>Objetivos Sprint</h2>


<br>🔴 **Prioridade Alta:** Início da formatação do conteúdo
<br>🔴 **Prioridade Alta::** Definição do modelo de avaliação
<br>🟡 **Prioridade Média:** Atualização da Documentação no Repositório
<br>🟡 **Prioridade Média:** Finalização do protótipo navegável
<br>🟢 **Prioridade Baixa:** Inserção de Sugestão do Front-end (Menu)
<br>🟢 **Prioridade Baixa:** Inserção do Modelo de Avaliação

<span id="entregas">
        
## Controle Presença
Foi feito um controle mais lúdico (utilizando as cores de cada um) de presença com o objetivo da equipe visualizar quanto tempo faltava para terminar o prazo e se reorganizar, caso necessário, a fim de cumprir as atividades dentro do prazo.

<figcaption>Controle de Presença</figcaption>
<figure>
   <img src="imagens/Controle presença.jpg" width="800" height="400" 
</figure>



## Sprint Review
Após a reunião da Sprint Review referente a Sprint 1 (13/04/2023) e definição das dificuldades encontradas na primeira sprint, foi decidida a mudança do kanban do trello para o Git Hub.

<figcaption>Kanban-Git Hub</figcaption>

<figure>
    <img src="imagens/Kanban-GitHub.jpg" alt="Kanban-GitHub"
</figure>
</center>


## Design
A equipe de design iniciou a busca por referências de páginas de apresentação de equipes, plataformas de apresentação de conteúdos esteticamente agradáveis e referências de formatos adaptáveis de Layout para as apresentações.
Após, foi feito o desenvolvimento do primeiro modelo para a página de apresentação da equipe.

## Front-end
Foi feita a pesquisa para deixar site responsivo e o início dos testes usando o bootstrap.
<b>A equipe de front encontrou dificuldade no uso do bootstrap e focou no estudo do mesmo para dar continuidade no processo.</b>
Foram feitos os ajustes do CSS e tela principal e os ajustes da página principal (módulos). O bootstrap foi adicionado no formulário de avaliação dos usuários.

<br>
<figcaption>Módulos - início</figcaption>
<figure><img src="imagens/Modulos inicial.png" width="700" height="402" alt="Módulos - início"</figure>
<p>

<br>
<figcaption>Módulos - responsivo</figcaption>
<figure><img src="imagens/Modulos - responsivo.png" width="800" height="402" alt="Módulos - responsivo"</figure>
</p>    
    
    


<br>
### ❄️ RF 03: Cadastro das estações, parâmetros e usuários

Este requisito se trata do cadastro de estações e usuários, o que significa permitir o CRUD completo de usuários além de criar, listar e acessar dados de estações. Para isso, foi desenvolvido o fluxo de usuários (desde login até exclusão de conta) e o dashboard de estações, porém, como o acordado entre time e cliente, o cadastro das estações será automático (entre a estação e o backend), sem parte interativa presente no frontend, mas sua automatização (do cadastro e recebimento dos dados de estações) serão desenvolvidos a partir da próxima sprint.

<div align="center">

| Fluxo de usuário comum                                                                                                | 
| :-------------------------------------------------------------------------------------------------------------------- |
| ![user_simple](https://user-images.githubusercontent.com/69374340/190942583-50d5ea43-d5a7-4ee2-a57c-7874c0b18f6d.gif) |

| Fluxo de usuário administrador                            |
| :-------------------------------------------------------- |
| ![user_admin](./user_admin.gif) |

| Fluxo de estações                  |
| :--------------------------------- |
| ![station](./station.gif) |

</div>

### 🌪 RF 05: Dashboards para visualização dos parâmetros meteorológicos

Este requisito se trata do modo de visualização dos dados emitidos pelas estações meteorológicas cadastradas. Na estrutura que foi implementada, qualquer usuário (fazendo login ou não, até o momento) pode acessar todos os dados disponíveis de estações existentes, como nome, localização e os dados enviados por seus sensores, observando-os em forma de gráficos de linha (onde o eixo horizontal é sempre o tempo e o vertical muda de unidade a cada tipo de sensor analisado, podendo representar milímetros de água, no caso do pluviômetro, graus Celsius, no caso do sensor de temperatura, entre outras unidades de medida possíveis).

<div align="center"><img src="https://user-images.githubusercontent.com/69374340/190942988-3b7975c7-95ab-4ff4-b2da-7840ffe30f0a.png" alt="Demonstração da dashboard de estações"></img></div>

### ☔️ RNF 08: Implementar CI/CD

Este requisito não funcional se trata da implementação de práticas de Integração e Entrega Contínua ("CI/CD") a pedido da FATEC. Prevê a aplicação de pipelines, realização de deploys, utilização de boas práticas com versionamento de código (como nomenclatura de branches, GitFlow, Conventional Commits, entre outros) além da criação de casos de teste que futuramente serão integrados ao sistema. Em relação a nomenclatura de branches é possível observar na documentação [desta tarefa](https://github.com/The-Bugger-Ducks/cloud-fox-documentation/issues/9), já os deploys se pode conferir pelos links abaixo:

- Backend: [https://cloud-fox.onrender.com/](https://cloud-fox.onrender.com/)
- Frontend: [https://cloud-fox.netlify.app/](https://cloud-fox.netlify.app/)

### ⚡️ RNF 09: Documentação

Este requisito se trata da criação de uma documentação acerca dos endpoints criados, seus parâmetros e retornos para facilitação do consumo da API e visibilidade das funcionalidades criadas. Para tal detalhamento foi utilizada a ferramenta [Swagger](https://swagger.io/), onde se pode realizar requisições e observar as rotas existentes através [deste link](https://cloud-fox.onrender.com/api-docs/#/).

→ [Voltar ao topo](#topo)

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Em prol de um melhor aproveitamento das habilidades de cada integrante, o time foi separado em duas frentes: frontend e backend, onde, na primeira sprint, o time de frontend ficou responsável pela confecção do protótipo, projeto frontend e integração de funcionalidades enquanto o time de backend ficou responsável pela criação dos endpoints necessários e pesquisas sobre o tema do desafio, procurando implementar a melhor arquitetura possível. 
- O acompanhamento de atividades, de responsabilidade da Scrum Master, se encontra na imagem adiante, que contém o gráfico Burndown gerado pela equipe (onde o eixo X são os dias trabalhados na sprint e os valores do eixo Y representam as entregas e esforços realizados com o passar do tempo), incluindo as atividades desenvolvidas e seus responsáveis.
    
<div align="center">
    
![Burndown](https://user-images.githubusercontent.com/69374340/190932337-40f6e8a8-0b5c-4139-8083-0108c77fad6e.png)
</div>
    
<span id="links">
    
## :link: Links úteis

- Site do projeto: [https://cloud-fox.netlify.app/](https://cloud-fox.netlify.app/)
- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - Repositório do site: [clique aqui para acessar "cloud-fox-web"](https://github.com/The-Bugger-Ducks/cloud-fox-web)
  - Repositório da API: [clique aqui para acessar "cloud-fox-back"](https://github.com/The-Bugger-Ducks/cloud-fox-back)

→ [Voltar ao topo](#topo)

