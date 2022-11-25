+++
author = "Cityhub team"
title = "Termo de abertura (v2) do projeto"
date = "2022-11-24"
description = "Termo de abertura (v2) do projeto"
tags = [
    "Abertura", "Termo","v2"
]
+++

TermoDeAbetura.md
Hoje
22:38

Edgard van Tol Taver editou 1 item
Texto
TermoDeAbetura.md
14:39

Edgard van Tol Taver fez o upload de 1 item
Texto
TermoDeAbetura.md
# Termo de Abertura do Projeto

## Sumário

- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Sumário](#sumário)
  - [Controle de versão](#controle-de-versão)
  - [Equipe do projeto](#equipe-do-projeto)
  - [Objetivo deste documento](#objetivo-deste-documento)
  - [Justificativa do projeto](#justificativa-do-projeto)
  - [Descrição do projeto](#descrição-do-projeto)
  - [Principais requisitos](#principais-requisitos)
  - [Critérios de sucesso do projeto](#critérios-de-sucesso-do-projeto)
  - [Objetivos SMART do projeto](#objetivos-smart-do-projeto)
    - [Objetivo 1: Garantir financiamento](#objetivo-1-garantir-financiamento)
    - [Objetivo 2: Entregar o aplicativo](#objetivo-2-entregar-o-aplicativo)
    - [Objetivo 3: Garantir uma operação saudável](#objetivo-3-garantir-uma-operação-saudável)
  - [Premissas](#premissas)
  - [Restrições](#restrições)
  - [Estrutura analítica do projeto (EAP)](#estrutura-analítica-do-projeto-eap)
  - [Marcos](#marcos)
  - [Cronogramas](#cronogramas)
  - [Riscos](#riscos)
    - [Descrição dos riscos](#descrição-dos-riscos)
    - [Matriz RACI](#matriz-raci)
  - [Orçamento](#orçamento)
    - [Custos de desenvolvimento inicial](#custos-de-desenvolvimento-inicial)
    - [Custos de operação](#custos-de-operação)
  - [Qualidade](#qualidade)
    - [Lista de parâmetros de qualidade](#lista-de-parâmetros-de-qualidade)
  - [Comunicações](#comunicações)
    - [Definição de ferramentas de comunicação](#definição-de-ferramentas-de-comunicação)
    - [Tipo de trabalho](#tipo-de-trabalho)
    - [Tipo e frequência das reuniões](#tipo-e-frequência-das-reuniões)
    - [Definição do 6W2H das informações](#definição-do-6w2h-das-informações)
    - [Matriz de Responsabilidades (Matriz RACI)](#matriz-de-responsabilidades-matriz-raci)
  - [Recursos Humanos](#recursos-humanos)
    - [Descrição dos cargos](#descrição-dos-cargos)
      - [Gerente do projeto](#gerente-do-projeto)
      - [QA](#qa)
      - [Gerente(s) de comunicações](#gerentes-de-comunicações)
      - [Methodology master](#methodology-master)
      - [LGPD Master](#lgpd-master)
      - [Devops](#devops)
      - [Desenvolvedor backend](#desenvolvedor-backend)
      - [Desenvolvedor frontend](#desenvolvedor-frontend)
      - [DBA](#dba)
      - [Pessoa desenvolvedora mobile](#pessoa-desenvolvedora-mobile)
      - [_Observação 1_](#observação-1)
    - [Esquema hierárquico](#esquema-hierárquico)
  - [Partes interessadas](#partes-interessadas)
  - [Aquisições](#aquisições)
    - [Desenvolvimentos](#desenvolvimentos)
    - [Aquisições](#aquisições-1)
    - [Fornecedores](#fornecedores)
  - [Aprovações](#aprovações)
  - [Anexos](#anexos)
    - [Tabela de população por bairro em São Paulo](#tabela-de-população-por-bairro-em-são-paulo)


## Controle de versão

| Data       | Versão | Descrição                        | Autor            |
| ---------- | ------ | -------------------------------- | ---------------- |
| 2022-10-18 | 1      | Elaboração inicial.              | Edgard Taver     |
| 2022-11-16 | 2      | Inclusão de riscos.              | Edgard Taver     |
| 2022-11-17 | 3      | Inclusão de comunicações.        | Rodrigo Vieira   |
| 2022-11-23 | 4      | Inclusão de recursos.            | Gabriel Oliveira |
| 2022-11-23 | 5      | Inclusão de partes interessadas. | Rodrigo Vieira   |
| 2022-11-24 | 6      | Inclusão de cronogramas.         | Felipe Escobar   |
| 2022-11-24 | 7      | Inclusão de custos.              | Rodrigo Vieira   |
| 2022-11-24 | 8      | Inclusão de aquisições.          | Felipe Escobar   |

## Equipe do projeto

| Nome                                 | Número USP |
| ------------------------------------ | ---------- |
| Edgard van Tol Taver                 | 10686575   |
| Gustavo Macedo Ribeiro               | 11366336   |
| Felipe Munhos Escobar                | 11795620   |
| Gabriel Braga Lagrotaria de Oliveira | 11796600   |
| Rodrigo Fernandes Gomes Vieira       | 11796548   |

## Objetivo deste documento

Autorizar formalmente o início do projeto _Cityhub_, contendo todas as informações necessárias para que o projeto seja apresentado, iniciado, desenvolvido e operado.

## Justificativa do projeto

Atualmente, muitas pessoas não sabem como reportar problemas de infraestrutura urbana. Com isso, se "acostumam" a eles e não se engajam numa atividade cívica para buscar melhorias. Ou então as pessoas até conhecem o procedimento (que em geral se dá por atendimento telefônico), porém acreditam que o processo será trabalhoso e gastará muito tempo, ou então não tem qualquer perspectiva de que a situação será resolvida.

Com o _Cityhub_, o processo de reportar problemas se tornará muito mais fácil e interativo, além de incentivar a conexão entre pessoas que moram numa mesma região. O aplicativo permitirá que qualquer pessoa gere um aviso, e então o sistema será responsável por repassar essa informação para a prefeitura, além de também notificar pessoas que estejam localizadas na mesma região.

## Descrição do projeto

O _Cityhub_ é um aplicativo para dispositivos móveis que permite que qualquer pessoa reporte problemas de infraestrutura urbana. O aplicativo é responsável por notificar a prefeitura e também notificar pessoas que estejam localizadas na mesma região.

Diversos tipos de problemas podem ser reportados por meio do aplicativo. Exemplos:
- buracos na rua;
- lixo acumulado em esquinas;
- focos de dengue;
- falta de sinalização, ou sinalização incompleta;
- propriedade pública vandalizada;
- entre outros.

Inicialmente, o aplicativo funcionará **apenas para a cidade de São Paulo**. O projeto compreende todo o desenvolvimento e lançamento do aplicativo, junto com um planejamento inicial para os primeiros 6 meses de operação do aplicativo.

O _Cityhub_ busca atender ao **Objetivo de Desenvolvimento Sustentável (ODS) 11: cidades e comunidades sustentáveis**. Esta ODS possui a missão oficial de "tornar as cidades inclusivas, seguras, resilientes e sustentáveis" ([fonte](https://en.wikipedia.org/wiki/Sustainable_Development_Goal_11)). Acreditamos que, ao facilitar que pessoas reportem problemas de infraestrutura na sua região, elas se sintam mais integradas à comunidade e, consequentemente, mais engajadas em buscar melhorias para a cidade.

## Principais requisitos

Aqui são apresentados os principais requisitos que o aplicativo deve implementar.

- **Cadastro de usuários**:
    - Dados simplificados, como nome, número de celular, e-mail, senha, CPF e CEP.
    - Obtenção de dados de localização do usuário.

- **Mapa interativo**:
    - Permite gerar avisos de problemas, indicando localização, tipo e descrição.
    - Permite visualizar avisos gerados por outros usuários que estejam localizados na mesma região.
        - Estes avisos podem ser votados por outros usuários, para confirmar que realmente existe um problema e indicar a gravidade deste.
        - Os usuários também podem indicar que um problema específico já foi resolvido.

- **Integrações**:
    - Integração com os sistemas pertinentes de órgãos públicos para encaminhar avisos.
    - Integração com o Google Maps para utilizar a tecnologia de geolocalização.

- **Relatórios**:
    - Relatórios sumarizando os principais problemas por região e a data em que foram reportados.

## Critérios de sucesso do projeto

* Financiamento do projeto garantido por meio de um Fundo Social.
* Aplicativo entregue dentro do prazo previsto com as funcionalidades mínimas, descritas na seção "Principais requisitos".
* Após o lançamento do aplicativo, atingir os objetivos SMART descritos na seção "Objetivos SMART do projeto".

## Objetivos SMART do projeto

Os objetivos "SMART" são dados pela seguinte definição:

- **S - Específica**: o que você quer atingir ou conquistar?
- **M - Mensurável**: como você saberá quando atingiu seu objetivo?
- **A - Atingível**: como a meta pode ser alcançada?
- **R - Relevante**: a meta atenderá às suas necessidades a curto e longo prazo?
- **T - Temporal**: em quanto tempo a meta será alcançada?

Os objetivos "SMART" do Cityhub são:

### Objetivo 1: Garantir financiamento

O Cityhub, em sua fase inicial, não possuirá fontes de renda direta. Por isso, o projeto deve garantir um financiamento inicial para cobrir os custos de desenvolvimento e lançamento do aplicativo. Este financiamento pode ocorrer por meio de um **Fundo Social**, tem em vista que o projeto possui um foco maior em impacto social do que em comercializar um produto ou serviço.

Descrição detalhada do objetivo:

- **S - Específica**: garantir financiamento para o projeto.
- **M - Mensurável**: o financiamento deve ser suficiente para cobrir todo o desenvolvimento do aplicativo e pelo menos 6 meses de operação após seu lançamento.
- **A - Atingível**: o financiamento deve ser obtido por meio de um Fundo Social.
- **R - Relevante**: o financiamento é relevante para o projeto, pois sem ele não será possível desenvolver e manter o aplicativo.
- **T - Temporal**: o financiamento deve ser obtido até a data definida para o início do desenvolvimento do aplicativo.

### Objetivo 2: Entregar o aplicativo

O Cityhub deve entregar o aplicativo dentro do prazo previsto, com as funcionalidades mínimas descritas na seção "Principais requisitos".

Descrição detalhada do objetivo:

- **S - Específica**: entregar o aplicativo dentro do prazo previsto.
- **M - Mensurável**: o desenvolvimento do aplicativo deve ser acompanhado por meio do cronograma, utilizando como linha de base os marcos (principais entregas).
- **A - Atingível**: o aplicativo deve ser desenvolvido utilizando as melhores práticas de desenvolvimento de software, com o time se guiando pelo cronograma e prestando especial atenção ao caminho crítico.
- **R - Relevante**: o aplicativo é a essência do projeto.
- **T - Temporal**: o aplicativo deve ser entregue dentro do prazo previsto, com as funcionalidades mínimas implementadas e testadas até a data prevista para início das operações.

### Objetivo 3: Garantir uma operação saudável

O Cityhub deve garantir uma operação saudável do aplicativo, com uma meta para usuários ativos e uma meta de interações diárias (avisos, votos, comentários) por dia.

Definições importantes para as metas descritas a seguir:
- **usuário cadastrado**: usuário que se cadastrou no aplicativo e confirmou seu e-mail ou telefone.
- **usuário ativo**: usuário que gere ao menos 5 interações por mês. Este número é uma aproximação de cerca de 1 interação por semana.
- **interações**: denominação genérica para as ações de reporte de aviso, votação de aviso, comentário em aviso e resolução de aviso.
- **bairros mais populosos**: as métricas de usuários cadastrados devem levar em conta em qual bairro o usuário mora. O aplicativo só será efetivo se tivermos usuários dos mais variados bairros cadastrados. Portanto, cada meta leva em conta a quantidade de bairros mais populosos que devem ter usuários cadastrados.

A seguir estão descritas as metas de resultados para cada mês de operação:

| mês de operação | usuários cadastrados                          | usuários ativos                              | interações diárias totais |
| --------------- | --------------------------------------------- | -------------------------------------------- | ------------------------- |
| 1               | 100 em cada um dos 10 bairros mais populosos  | 10 nos 5 bairros mais populosos              | 10                        |
| 2               | 200 em cada um dos 15 bairros mais populosos  | 20 em cada um dos 10 bairros mais populosos  | 40                        |
| 3               | 400 em cada um dos 20 bairros mais populosos  | 40 em cada um dos 15 bairros mais populosos  | 110                       |
| 4               | 800 em cada um dos 30 bairros mais populosos  | 80 em cada um dos 20 bairros mais populosos  | 300                       |
| 5               | 1200 em cada um dos 40 bairros mais populosos | 120 em cada um dos 30 bairros mais populosos | 660                       |
| 6               | 1600 em cada um dos 50 bairros mais populosos | 160 nos 40 bairros mais populosos            | 1200                      |

O número de **usuários cadastrados** foi calculado para cada mês levando em conta o objetivo de ter, ao final dos 6 meses, uma média próxima de 1% dos moradores de cada um dos 50 bairros mais populosos de São Paulo. Conforme tabela em anexo ao final deste documento, os 50 bairros mais populosos possuem uma média de 174996 moradores. 1% deste valor representa `174996 * 0.01 = 1749.96`.

Já o número de usuários ativos é sempre uma taxa de 10% do número de usuários cadastrados, levando em conta uma quantidade levemente menor de bairros. O número de interações diárias foi calculado considerando o seguinte cálculo:

```
(usuários ativos por bairro * quantidade de bairros com usuários ativos * 5 interações por mês) / 30 dias
```

Este cálculo resulta no _número esperado de interações_ caso cada usuário ativo faça precisamente as 5 interações por dia. Como queremos que os usuários interajam cada vez mais, a meta foi fixada como sendo **10%** acima do _número de interações esperado_, aplicando também um arrendondamento do valor.

Descrição detalhada do objetivo:

- **S - Específica**: garantir uma operação saudável do aplicativo, medindo resultados dos primeiros 6 meses de operação.
- **M - Mensurável**: o número de usuários ativos e o número de interações (avisos, votos, comentários) devem ser mensurados diariamente. Os resultados esperados estão descritos na tabela acima.
- **A - Atingível**: o aplicativo deve possuir uma infraestrutura capaz de suportar a operação dentro do número de usuários especificado acima.
- **R - Relevante**: o aplicativo deve funcionar sob operação comum, e também deve contar com usuários se cadastrando e utilizando-o regularmente, já que a participação da comunidade é a essência do Cityhub.
- **T - Temporal**: a quantidade de usuários deve ser obtida nos meses de operação indicados na tabela descrita acima.

## Premissas

- O time de desenvolvimento do Cityhub contará com profissionais trabalhando em tempo integral.
- Os moradores de bairros populosos de São Paulo possuem um interesse mínimo em reclamar sobre problemas de infraestrutura que enfrentam no dia a dia.
- O aplicativo poderá contar suficientemente com divulgação boca-a-boca, incentivado por meio de gamificações, para evitar custos maiores com marketing.
- Haverá um Fundo Social interessado em investir no Cityhub.
- Os órgãos públicos possuem uma plataforma online que permite integração para receber os avisos do Cityhub.
- Os órgãos públicos destinados para receber os avisos do Cityhub terão interesse em atuar em pelo menos uma parte mínima destes avisos (pelo menos 15% dos avisos).

## Restrições

- A implementação da integração com as plataformas dos órgãos governamentais pode levar mais tempo do que o esperado, por complexidades para lidar com tecnologias antigas.
- O contato inicial com os órgãos governamentais, para apresentar o projeto, pode ser burocrático e lento.
- O desenvolvimento e a operação do projeto estão limitados ao capital que for possível levantar com o Fundo Social.
- O Fundo Social pode não ter interesse em continuar a investir no projeto após 6 meses de operação, caso o número de usuários não seja o esperado.

## Estrutura analítica do projeto (EAP)

- Desenvolvimento e operação do Cityhub.
    - Planejamento.
        - Desenvolver e refinar ideia.
        - Descrever _business canvas_.
            - Desenvolver primeira versão.
            - Apresentação primeira versão.
            - Desenvolver segunda versão a partir do feedback recebido.
        
        - Desenvolver o Termo de Abertura do Projeto (TAP):
            - Escolher modelo para TAP.
            - Preencher primeira versão do TAP a partir do modelo escolhido.
                - Descrever objetivo e justificativa do projeto.
                - Explicar requisitos e critérios de sucesso do projeto.
                - Documentar condições do projeto por meio de premissas, restrições e riscos.
                - Descrever gestão do projeto por meio de marcos (_milestones_) e orçamento inicial previsto.

            - Apresentar primeira versão do TAP.
            - Refinar TAP a partir do feedback recebido, desenvolvendo sua segunda versão.
        
        - Desenvolver documento para Gestão de Tempo do projeto.
            - Descrever tarefas de desenvolvimento a partir do EAP.
                - Mensurar tempo e recursos para cada tarefa.
                - Identificar relações de dependências entre as tarefas.
                - Identificar caminho crítico.
            
            - Montar Cronograma de Gantt a partir das tarefas e marcos (_milestones_).
        
        - Desenvolver documento para Gestão de Qualidade do projeto.
            - Descrever critérios de qualidade para cada tarefa.
            - Identificar riscos para as tarefas do projeto.

        - Desenvolver documento para Gestão de Custo do projeto.
            - Descrever custos para cada etapa do projeto.
            - Revisar orçamento previsto (conforme descrito no TAP) para o projeto a partir dos custos estimados.
        
        - Desenvolver documento para Gestão de Recursos Humanos do projeto.
            - Identificar conteúdo necessário para este documento a partir do seminário dado em aula.
            - Revisar esta parte da EAP para incluir as tarefas adequadas.

        - Desenvolver documento para Gestão de Comunicações do projeto.
            - Identificar conteúdo necessário para este documento a partir do seminário dado em aula.
            - Revisar esta parte da EAP para incluir as tarefas adequadas.

        - Desenvolver documento para Gestão de Riscos do projeto.
            - Identificar conteúdo necessário para este documento a partir do seminário dado em aula.
            - Revisar esta parte da EAP para incluir as tarefas adequadas.

        - Desenvolver documento para Gestão de Aquisições do projeto.
            - Identificar conteúdo necessário para este documento a partir do seminário dado em aula.
            - Revisar esta parte da EAP para incluir as tarefas adequadas.

        - Desenvolver documento para Gestão de Partes Interessadas e Gestão de Integração do projeto.
            - Identificar conteúdo necessário para este documento a partir do seminário dado em aula.
            - Revisar esta parte da EAP para incluir as tarefas adequadas.

        - Desenvolver documento para Prince2 do projeto.
            - Identificar conteúdo necessário para este documento a partir do seminário dado em aula.
            - Revisar esta parte da EAP para incluir as tarefas adequadas.

        - Desenvolver documento para Metodologias Ágeis do projeto.
            - Revisar esta parte da EAP para incluir as tarefas adequadas.
            - Identificar conteúdo necessário para este documento a partir do seminário dado em aula.

    - Captação de recursos.
        - Pesquisar Fundos Sociais que estão abertos para receber propostas de projetos.
            - Identificar Fundos Sociais que estão abertos para receber propostas de projetos.
            - Identificar critérios de seleção de projetos.
            - Identificar prazos para submissão de propostas.
            - Criar cronograma específico para cada Fundo Social a partir dos prazos de submissão de propostas.
        
        - Desenvolver documento (slides) para apresentação do aplicativo.
            - Descrever o _business case_ do aplicativo.
            - Descrever expectativa de usuários e impacto.
            - Descrever orçamento necessário.
            - Inscrever o projeto nos Fundos Sociais identificados na etapa anterior.

    - Desenvolvimento.
        - Estudos preliminares de tecnologias fundamentais para o aplicativo.
            - Integração com sistemas de órgãos governamentais.
                - Mapear órgãos com os quais o aplicativo deve se integrar.
                    - Abrir canal de contato com os órgãos para apresentar o projeto e identificar o interesse.
                    - Identificar APIs necessárias para integração. 
                        - Identificar se estes órgãos possuem plataformas com APIs públicas.
                        - Pesquisar e registar documentação destas APIs.
                        - Implementar integração com APIs por meio de simulações.
            
            - Integração com tecnologia de geolocalização.
                - Estudos preliminares para Google Maps API.
                    - Pesquisar e registar documentação desta API.
                    - Obter registro e permissão para uso desta API.
                    - Implementar integração com API por meio de simulações.
            
                - Baseado na experiência com Google Maps API, estudar outras APIs de geolocalização.
                    - Pesquisar e registar documentação destas APIs.
                    - Implementar integração com APIs por meio de simulações.

        - Desenvolvimento das funcionalidades do aplicativo.
            - Infraestrutura.
                - Estruturar infraestrutura para hospedagem do projeto com AWS.
                    - Criar conta na AWS.
                    - Criar instância EC2 para hospedagem do projeto.
                    - Criar instância RDS para hospedagem do banco de dados.
                    - Criar instância S3 para hospedagem de arquivos estáticos.

                - Estruturar projeto no Github.
                    - Criar repositório central para configuração da infraestrutura (_infra-as-code_).
                    - Criar repositório central para o aplicativo.
                        - Definir políticas de desenvolvimento.
                            - Frequência e tamanho de _branches_.
                            - Política de aprovação de _pull requests_.
                            - Fluxos para _continuous delivery_ e _continuous integration_.
            
            - Funcionalidades.
                - Cadastro de usuários.
                    - Backend.
                        - Criar _endpoint_ para cadastro de usuários.
                        - Criar _endpoint_ para autenticação de usuários.
                        - Criar _endpoint_ para recuperação de senha.
                        - Criar _endpoint_ para atualização de dados de usuários.
                        - Criar _endpoint_ para listagem de usuários.
                        - Criar _endpoint_ para exclusão de usuários.
                    
                    - Frontend (mobile):
                        - Criar tela de cadastro de usuários.
                        - Criar tela de autenticação de usuários.
                        - Criar tela de recuperação de senha.
                        - Criar tela de atualização de dados de usuários.
                    
                    - Frontend administrativo:
                        - Criar tela de listagem de usuários.
                        - Criar tela de detalhes de usuários.
                        - Criar tela de exclusão de usuários.

                - Mapa interativo.
                    - Backend.
                        - Estabelecer integração com API de geolocalização.
                        - Criar banco de dados para registro de avisos.
                        - Criar _endpoint_ para inserção de aviso.
                            - Inserção de dados de aviso no banco de dados.
                            - Estabelecer integração com órgãos públicos para encaminhamento do aviso.
                        - Criar _endpoint_ para atualização de aviso.
                        - Criar _endpoint_ para votar em um aviso.
                        - Criar _endpoint_ para atualizar status de um aviso.
                        - Criar _endpoint_ para listagem de avisos com filtros e ordenação.
                        - Criar _endpoint_ para exclusão de avisos.
                        - Criar sistema que gera notificações para usuários que estão próximos de onde novos avisos foram gerados.

                    - Frontend (mobile).
                        - Estabelecer integração com API de geolocalização.
                        - Criar tela de mapa interativo.
                        - Criar tela de detalhes de aviso.
                        - Criar tela de inserção de aviso.
                        - Criar tela de atualização de aviso.
                        - Criar tela de votação de aviso.
                        - Criar tela de atualização de status de aviso.
                        - Exibir notificações de novos avisos.
                    
                    - Frontend administrativo.
                        - Criar tela de listagem de avisos.
                        - Criar tela de detalhes de aviso.
                        - Criar tela de atualização e remoção de aviso.

                - Relatórios.
                    - Backend.
                        - Criar _endpoint_ para sumarizar avisos de acordo com critérios de tipo, região e frequência.

                    - Frontend (mobile).
                        - Criar tela para exibição de relatórios.
                            - Relatório com avisos mais frequentes na região do usuário.
                            - Relatório com avisos mais votados na região do usuário.
                            - Relatório com avisos mais recentes na região do usuário.

                    - Frontend administrativo.
                        - Criar tela para exibição de relatórios.
                            - Relatório com regiões com mais atividade.
                            - Relatório com tipos de avisos mais utilizados.
                            - Relatório com bairros da cidade que possuem atividade.
                            - Relatório com número diário de usuários cadastrados e usuários ativos.
        
        - Testes e observabilidade.
            - Testes de carga para garantir que o aplicativo é capaz de aguentar o tráfego esperado para os 6 meses de operação.
            - Infraestrutura de observabilidade.
                - Métricas de recursos do aplicativo.
                - Métricas de negócios do aplicativo.
                - Alertas baseados nestas métricas.
            
            - Usuários de teste.
                - Disponibilizar aplicativo para usuários de teste.
                - Refinar aplicativo com base nos feedbacks dos usuários de teste.

    - Operação.
        - Disponibilização do aplicativo de forma pública.
            - Monitoramento de uso do aplicativo.
            - Análise de métricas de negócios.
        
        - Marketing.
            - Estratégias de marketing digital.
                - Anúncios em redes sociais baseados em localização.

            - Indique um amigo.
                - Criar sistema de indicação de amigos.
                - Criar sistema de recompensa para usuários que indicarem amigos.
            
            - Relações públicas.
                - Entrevistas com meios de comunicação para divulgar o aplicativo.
                - Divulgação do aplicativo em eventos de tecnologia.
                - Divulgação do aplicativo em eventos de cidades inteligentes.

## Marcos

| Marco                                              | Previsão   |
| -------------------------------------------------- | ---------- |
| Início do planejamento do projeto                  | 2022-10-18 |
| Finalização do planejamento do projeto             | 2022-11-17 |
| Início da busca por financiamento                  | 2023-01-16 |
| Finalização com sucesso da busca por financiamento | 2023-04-30 |
| Início do desenvolvimento do aplicativo            | 2023-05-02 |
| Conclusão do desenvolvimento do aplicativo         | 2023-11-03 |
| Início da operação do aplicativo                   | 2023-11-06 |
| 6 meses da operação do aplicativo                  | 2024-05-06 |

## Cronogramas

{{<img-custom link = "/img/cronograma-geral.png">}}
{{</img-custom>}}
{{<img-custom link = "/img/cronograma-planejamento.png">}}
{{</img-custom>}}
{{<img-custom link = "/img/cronograma-captacao_recursos.png">}}
{{</img-custom>}}
{{<img-custom link = "/img/cronograma-desenvolvimento.png">}}
{{</img-custom>}}
{{<img-custom link = "/img/cronograma-operacao.png">}}
{{</img-custom>}}

## Riscos

Riscos que podem ocorrer durante o desenvolvimento e operação do projeto.

### Descrição dos riscos

- **Risco 1**: O capital levantado com o Fundo Social pode não ser suficiente para cobrir todo o desenvolvimento.
    - **Impacto**:
      - O projeto pode ser interrompido antes do término do desenvolvimento.
    - **Prevenção**:
      - Acompanhar o andamento do projeto e seus custos com frequência, para saber com antecedência caso o capital não seja suficiente.
    - **Mitigação**:
      - Buscar outros investidores.
      - Reduzir o time de desenvolvimento.
      - Reduzir o escopo do projeto.

- **Risco 2**: O desenvolvimento do aplicativo pode ser mais complexo do que o esperado, levando a um atraso no lançamento. A parte mais sujeita a isso é a integração com os sistemas dos órgãos públicos.
    - **Impacto**:
      - O projeto pode ser interrompido antes do término do desenvolvimento.
    - **Prevenção**:
      - Antes de iniciar o desenvolvimento do aplicativo, pesquisar qualquer documentação existente com relação a plataformas da prefeitura e garantir uma linha de contato com os órgãos públicos previamente.
      - Iniciar o desenvolvimento do aplicativo atacando primeiramente a parte de integração. Como as outras funcionalidades esperadas são mais triviais, elas podem ser implementadas com mais confiança sabendo que a integração foi resolvida.
    - **Mitigação**:
      - Reduzir o escopo do projeto removendo a funcionalidade de integração com os órgãos públicos. Neste caso, o projeto ficaria mais focado na conexão entre os moradores de uma mesma região, permitindo que os usuários se comuniquem entre si para resolver ou evitar problemas.
      - Planejar algum tipo de processo manual para levar avisos aos órgãos públicos, assim garantido uma funcionalidade chave do aplicativo, ainda que elevando os custos da operação.

- **Risco 3**: O projeto pode não ser bem recebido pelos órgãos públicos, que podem não ter interesse em atuar em cima dos avisos enviados pelos usuários do aplicativo.
    - **Impacto**:
      - O aplicativo perderia uma das suas funcionalidades chave.
    - **Prevenção**:
      - Garantir contato direto com os órgãos públicos, para apresentar o projeto e medir o interesse, antes do desenvolvimento do aplicativo.
    - **Mitigação**:
      - Remover a funcionalidade de integração com os órgãos públicos, como descrito no risco 2.

- **Risco 4**: Os usuários podem fazer mal uso do aplicativo gerando avisos falsos.
    - **Impacto**:
      - A credibilidade e percepção do valor do projeto pode ser prejudicada.
    - **Prevenção**:
      - Garantir que, durante a operação do projeto, seja feito um processo de analisar dados dos avisos gerados e buscar por padrões de mal uso (exemplo: usuário gerando múltiplos avisos em um intervalo muito curto de tempo).
      - Pedir feedback constante dos usuários para entender se _spam_ é um problema ou não durante a operação.
    - **Mitigação**:
      - Desenvolver uma funcionalidade para analisar e remover _spam_ automaticamente.

- **Risco 5**: os usuários podem não se engajar no uso do aplicativo caso os avisos criados não geram ação resolutiva dos órgãos responsáveis dentro de um tempo hábil. Este risco está associado ao risco 3, quando os órgãos públicos não atuam em cima dos avisos.
    - **Impacto**:
      - Perda de usuários e perda de credibilidade do projeto.
    - **Prevenção**:
      - Garantir contato direto com os órgãos públicos, para apresentar o projeto e medir o interesse, antes do desenvolvimento do aplicativo.
      - Monitorar atentamente o índice de respostas dos órgãos públicos aos avisos gerados pelos usuários.
    - **Mitigação**:
      - Reduzir o escopo do projeto removendo a funcionalidade de integração com os órgãos públicos. Neste caso, o projeto ficaria mais focado na conexão entre os moradores de uma mesma região, permitindo que os usuários se comuniquem entre si para resolver ou evitar problemas.

- **Risco 6**: Desenvolvedores podem sair da equipe antes da conclusão do projeto, ou durante sua fase de implementação.
  - **Impacto**:
    - Atraso no desenvolvimento, pela necessidade de ter que dedicar mais tempo para contratar e treinar novos desenvolvedores.
    - Gastos maiores no projeto, pelos custos de ter que aplicar mais processos de recrutamento do que o esperado.
  - **Prevenção**:
    - Acompanhar o desempenho dos desenvolvedores durante o projeto, para identificar possíveis problemas antes que eles se tornem críticos.
  - **Mitigação**:
    - Considerar a possibilidade de contratar uma empresa terceira para desenvolver determinadas partes do projeto.

- **Risco 7**: Indisponibilidade dos serviços de infraestrutura durante a operação do aplicativo.
  - **Impacto**:
    - Aplicativo ficará fora do ar, prejudicando a experiência dos usuários.
  - **Prevenção**:
    - Garantir que a infraestrutura do serviço seja configurada como _infra-as-code_, permitindo que a infraestrutura seja recriada facilmente caso ocorra algum problema.
    - Obter garantais de serviço dos provedores de infraestrutura, para que o projeto possa ser reembolsado caso ocorra algum problema.
  - **Mitigação**:
    - Disponibilizar infraestrutura alternativa para o serviço, caso o provedor principal não consiga reestabelecer o serviço.

- **Risco 8**: Vazamento de dados dos usuários.
  - **Impacto**:
    - Dano de imagem para o projeto.
  - **Prevenção**:
    - Guardar o mínimo de dados sensíveis dos usuários.
    - Evitar guardar a localização dos usuários (a localização registrada será para cada aviso criado).
    - Implementar políticas de controle de acesso aos dados dos usuários.
  - **Mitigação**:
    - Comunicar publicamente caso ocorra vazamento de dados, conforme a LGPD especifica.
    - Identificar e corrigir o problema que causou o vazamento de dados.

- **Risco 9**: Integração com API de dados geográficas pode ser mais complexado do que o esperado, levando a um tempo maior no desenvolvimento.
    - **Impacto**:
        - Atraso no desenvolvimento do projeto.
    - **Prevenção**:
        - Estudo prévio da API de dados geográficas para identificar possíveis problemas.
        - Montagem de prova de conceito para validar a integração com a API, antes de iniciar o desenvolvimento do aplicativo.
    - **Mitigação**:
        - Não é possível abandonar essa _feature_ pois ela é central para o funcionamento do aplicativo.
        - Caso o problema seja muito difícil de resolver, será necessário contratar uma equipe terceira que tenha experiência nesta área.

### Matriz RACI

{{<img-custom link = "/img/riscos.png">}}
{{</img-custom>}}

- **[1]**:
  - Justificativa Risco 7: todos os grandes provedores de infra (AWS, Microsoft, Google) possuem níveis de confiança altíssimos, então a chance é baixa. Além disso, caso ocorra, estes serviços costumam se recuperar de forma também bastante rápida. Portanto, o impacto é baixo.

- **[2]**:
  - Justificativa Risco 8: o aplicativo guardará poucos dados sensíveis dos usuários e teremos política de segurança. Ainda assim, um vazamento pode trazer danos de imagem razoáveis.
  - Justificativa Risco 9: a integração com API de dados geográficos já é bem utilizado há vários anos por inúmeros aplicativos. Então o risco de termos problemas é baixo. No entanto, caso ocorre, o impacto é razoável pois o aplicativo requer interação com mapa, de maneira indissociável. Como existem formas de mitigar, não é um risco que vai anular o projeto, mas ainda assim pode causar atrasos consideráveis.

- **[3]**:
  - Justificativa Risco 1: ficar sem dinheiro impediria a conclusão do projeto. Por outro lado, os recursos já estão super dimensionados, então a chance disso acontecer não é tão alta.

- **[4]**:
  - Justificativa Risco 2: existe incerteza quanto à integração real. Haverá uma pesquisa prévia de documentação para entender o esforço e fazer testes. Ainda assim, na prática, a integração pode acabar não saindo como planejado.

- **[5]**:
  - Justificativa Risco 3 e 5: perder o engajamento dos usuários poderia significar o fim do aplicativo, que depende necessariamente de ações dos usuários para atrair mais usuários. Da mesma forma, também depende de ter uma resposta real, uma ação real dos órgãos para que o aplicativo seja entendido com valoroso.

- **[6]**:
  - Justificativa Risco 4: comportamento de "spam" existe em qualquer lugar, então a chance de ocorrer é alta. No entanto, o aplicativo terá alguns mecanismos "naturais" para controlar spam, e no pior cenário já temos um desenvolvimento planejado de um modelo para identificar de forma mais automática o spam.
  - Justificativa Risco 6: no mercado de Tecnologia, a rotatividade de pessoas infelizmente é alta.

## Orçamento

O orçamento total foi dividido em duas etapas, sendo a primeira referente aos custos de montar o aplicativo, e a segunda referente aos custos dos primeiros 6 meses de operação do aplicativo.

### Custos de desenvolvimento inicial

| Item                                   |     | Período      |              |              |              |              |              |               |     |     |
| -------------------------------------- | --- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------- | --- | --- |
|                                        |     | Mês 1        | Mês 2        | Mês 3        | Mês 4        | Mês 5        | Mês 6        | Total         |     |     |
| **Estimativa de Recursos Humanos**     |     |              |              |              |              |              |              |               |     |     |
| Pessoa Dev Android                     |     | R$ 6.969,00  | R$ 6.969,00  | R$ 6.969,00  | R$ 6.969,00  | R$ 6.969,00  | R$ 6.969,00  | R$ 41.814,00  |     |     |
| Pessoa Dev IOS                         |     | R$ 5.717,00  | R$ 5.717,00  | R$ 5.717,00  | R$ 5.717,00  | R$ 5.717,00  | R$ 5.717,00  | R$ 34.302,00  |     |     |
| Pessoa Dev FrontEnd                    |     | R$ 5.294,00  | R$ 5.294,00  | R$ 5.294,00  | R$ 5.294,00  | R$ 5.294,00  | R$ 5.294,00  | R$ 31.764,00  |     |     |
| Pessoa QA                              |     | R$ 4.809,00  | R$ 4.809,00  | R$ 4.809,00  | R$ 4.809,00  | R$ 4.809,00  | R$ 4.809,00  | R$ 28.854,00  |     |     |
| Pessoa Dev BackEnd                     |     | R$ 6.115,00  | R$ 6.115,00  | R$ 6.115,00  | R$ 6.115,00  | R$ 6.115,00  | R$ 6.115,00  | R$ 36.690,00  |     |     |
| Pessoa DevOps                          |     | R$ 7.791,00  | R$ 7.791,00  | R$ 7.791,00  | R$ 7.791,00  | R$ 7.791,00  | R$ 7.791,00  | R$ 46.746,00  |     |     |
| Pessoa Infraestrutura                  |     | R$ 5.116,00  | R$ 5.116,00  | R$ 5.116,00  | R$ 5.116,00  | R$ 5.116,00  | R$ 5.116,00  | R$ 30.696,00  |     |     |
| Pessoa DBA                             |     | R$ 8.090,00  | R$ 8.090,00  | R$ 8.090,00  | R$ 8.090,00  | R$ 8.090,00  | R$ 8.090,00  | R$ 48.540,00  |     |     |
| Subtotal                               |     | R$ 49.901,00 | R$ 49.901,00 | R$ 49.901,00 | R$ 49.901,00 | R$ 49.901,00 | R$ 49.901,00 | R$ 299.406,00 |     |     |
| **Estimativa de Recursos Não-Humanos** |     |              |              |              |              |              |              |               |     |     |
| Notebook                               |     | R$ 5.167,00  | R$ 5.167,00  | R$ 6.500,00  | R$ 6.500,00  | R$ 6.500,00  | R$ 6.500,00  | R$ 36.334,00  |     |     |
| Auxílio Home-Office                    |     | R$ 1.200,00  | R$ 1.200,00  | R$ 1.200,00  | R$ 1.200,00  | R$ 1.200,00  | R$ 1.200,00  | R$ 7.200,00   |     |     |
| AWS                                    |     | R$ 3.243,46  | R$ 3.243,46  | R$ 3.243,46  | R$ 3.243,46  | R$ 3.243,46  | R$ 3.243,46  | R$ 19.460,76  |     |     |
| GitHub Team                            |     | R$ 206,48    | R$ 206,48    | R$ 206,48    | R$ 206,48    | R$ 206,48    | R$ 206,48    | R$ 1.238,88   |     |     |
| Integração Google Maps                 |     | R$ 733,00    | R$ 733,00    | R$ 733,00    | R$ 733,00    | R$ 733,00    | R$ 733,00    | R$ 4.398,00   |     |     |
| Subtotal                               |     | R$ 10.549,94 | R$ 10.549,94 | R$ 11.882,94 | R$ 11.882,94 | R$ 11.882,94 | R$ 11.882,94 | R$ 68.631,64  |     |     |
| **Reserva de Contingência**            |     |              |              |              |              |              |              |               |     |     |
| Afastamento de um Dev                  |     | R$ 3.000,00  | R$ 3.000,00  | R$ 3.000,00  | R$ 3.000,00  | R$ 3.000,00  | R$ 3.000,00  | R$ 18.000,00  |     |     |
| Subtotal                               |     | R$ 3.000,00  | R$ 3.000,00  | R$ 3.000,00  | R$ 3.000,00  | R$ 3.000,00  | R$ 3.000,00  | R$ 18.000,00  |     |     |
| Total                                  |     | R$ 63.450,94 | R$ 63.450,94 | R$ 64.783,94 | R$ 64.783,94 | R$ 64.783,94 | R$ 64.783,94 | R$ 386.037,64 |     |     |

| Reserva Gerencial(%) | Orçamento Parcial | Valor Total   |
| -------------------- | ----------------- | ------------- |
| 6,0                  | R$ 386.037,64     | R$ 409.199,90 |

### Custos de operação

| Item                                   |     | Período       |               |               |               |               |               |               |
| -------------------------------------- | --- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|                                        |     | Mês 7         | Mês 8         | Mês 9         | Mês 10        | Mês 11        | Mês 12        | Total         |
| **Estimativa de Recursos Humanos**     |     |               |               |               |               |               |               |               |
| Pessoa Dev Android                     |     | R$ 6.969,00   | R$ 6.969,00   | R$ 6.969,00   | R$ 6.969,00   | R$ 6.969,00   | R$ 6.969,00   | R$ 41.814,00  |
| Pessoa Dev IOS                         |     | R$ 5.717,00   | R$ 5.717,00   | R$ 5.717,00   | R$ 5.717,00   | R$ 5.717,00   | R$ 5.717,00   | R$ 34.302,00  |
| Pessoa Dev FrontEnd                    |     | R$ 5.294,00   | R$ 5.294,00   | R$ 5.294,00   | R$ 5.294,00   | R$ 5.294,00   | R$ 5.294,00   | R$ 31.764,00  |
| Pessoa QA                              |     | R$ 4.809,00   | R$ 4.809,00   | R$ 4.809,00   | R$ 4.809,00   | R$ 4.809,00   | R$ 4.809,00   | R$ 28.854,00  |
| Pessoa Dev BackEnd                     |     | R$ 6.115,00   | R$ 6.115,00   | R$ 6.115,00   | R$ 6.115,00   | R$ 6.115,00   | R$ 6.115,00   | R$ 36.690,00  |
| Pessoa Dev BackEnd                     |     | R$ 0,00       | R$ 0,00       | R$ 6.115,00   | R$ 6.115,00   | R$ 6.115,00   | R$ 6.115,00   | R$ 24.460,00  |
| Pessoa DevOps                          |     | R$ 7.791,00   | R$ 7.791,00   | R$ 7.791,00   | R$ 7.791,00   | R$ 7.791,00   | R$ 7.791,00   | R$ 46.746,00  |
| Pessoa Infraestrutura                  |     | R$ 5.116,00   | R$ 5.116,00   | R$ 5.116,00   | R$ 5.116,00   | R$ 5.116,00   | R$ 5.116,00   | R$ 30.696,00  |
| Pessoa DBA                             |     | R$ 8.090,00   | R$ 8.090,00   | R$ 8.090,00   | R$ 8.090,00   | R$ 8.090,00   | R$ 8.090,00   | R$ 48.540,00  |
| Pessoa Marketing                       |     | R$ 0,00       | R$ 0,00       | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 16.000,00  |
| Pessoa Marketing                       |     | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 24.000,00  |
| Gerente de TI                          |     | R$ 15.000,00  | R$ 15.000,00  | R$ 15.000,00  | R$ 15.000,00  | R$ 15.000,00  | R$ 15.000,00  | R$ 90.000,00  |
| Gerente de Marketing                   |     | R$ 11.900,00  | R$ 11.900,00  | R$ 11.900,00  | R$ 11.900,00  | R$ 11.900,00  | R$ 11.900,00  | R$ 71.400,00  |
| Subtotal                               |     | R$ 80.801,00  | R$ 80.801,00  | R$ 90.916,00  | R$ 90.916,00  | R$ 90.916,00  | R$ 90.916,00  | R$ 525.266,00 |
| **Estimativa de Recursos Não-Humanos** |     |               |               |               |               |               |               |               |
| Notebook                               |     | R$ 5.167,00   | R$ 5.167,00   | R$ 6.500,00   | R$ 6.500,00   | R$ 6.500,00   | R$ 6.500,00   | R$ 36.334,00  |
| Auxílio Home-Office                    |     | R$ 1.200,00   | R$ 1.200,00   | R$ 1.200,00   | R$ 1.200,00   | R$ 1.200,00   | R$ 1.200,00   | R$ 7.200,00   |
| AWS                                    |     | R$ 3.243,46   | R$ 3.243,46   | R$ 3.243,46   | R$ 3.243,46   | R$ 3.243,46   | R$ 3.243,46   | R$ 19.460,76  |
| GitHub Team                            |     | R$ 206,48     | R$ 206,48     | R$ 206,48     | R$ 206,48     | R$ 206,48     | R$ 206,48     | R$ 1.238,88   |
| Integração Google Maps                 |     | R$ 733,00     | R$ 733,00     | R$ 733,00     | R$ 733,00     | R$ 733,00     | R$ 733,00     | R$ 4.398,00   |
| Google ADS                             |     | R$ 10.840,11  | R$ 10.840,11  | R$ 10.840,11  | R$ 10.840,11  | R$ 10.840,11  | R$ 10.840,11  | R$ 65.040,66  |
| Subtotal                               |     | R$ 21.390,05  | R$ 21.390,05  | R$ 22.723,05  | R$ 22.723,05  | R$ 22.723,05  | R$ 22.723,05  | R$ 133.672,30 |
| **Reserva de Contingência**            |     |               |               |               |               |               |               |               |
| Queda dos servidores                   |     | R$ 1.000,00   | R$ 1.000,00   | R$ 1.000,00   | R$ 1.000,00   | R$ 1.000,00   | R$ 1.000,00   | R$ 6.000,00   |
| Afastamento de um Dev                  |     | R$ 3.000,00   | R$ 3.000,00   | R$ 3.000,00   | R$ 3.000,00   | R$ 3.000,00   | R$ 3.000,00   | R$ 18.000,00  |
| Subtotal                               |     | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 4.000,00   | R$ 24.000,00  |
| Total                                  |     | R$ 106.191,05 | R$ 106.191,05 | R$ 117.639,05 | R$ 117.639,05 | R$ 117.639,05 | R$ 117.639,05 | R$ 682.938,30 |

| Reserva Gerencial(%) | Orçamento Parcial | Valor Total   |
| -------------------- | ----------------- | ------------- |
| 6,0                  | R$ 682.938,30     | R$ 723.914,60 |

## Qualidade

Esta seção tem o objetivo de fornecer uma lista definindo os parâmetros de qualidade do projeto, bem como os graus que atendem os requisitos definidos

### Lista de parâmetros de qualidade

- Ações críticas que envolvem comunicação com serviços governamentais não devem passar de, aproximadamente, 1 segundo de atraso (não levando em conta o atraso do próprio sistema deles, apenas o nosso).
- Apresentação dos dados de forma iterativa para o usuário:
  - Gráficos em formato de pizza para indicação de problemas em bairros.
  - Gráficos em formato de histograma para visualização dos dados por datas/outro parâmetro.

- Relatórios devem conter um alto grau de personalização, definido por:
  - Quantidade de parâmetros modificáveis para composição do site.
  - Diferentes visualizações de gráficos.
  - Possibilidade de definição de métricas customizáveis, podendo ter um cadastro das mesmas, inserindo fórmulas ou algo semelhante que permita tal nível de customização.

- Tempo consumido para entrega do projeto.
- Satisfação do usuário:
  - Facilidade de notificar e reportar sobre um problema.
  - Facilidade de interação.
  - Facilidade de visualização gráfica (em mapa) dos problemas na área.

- Carga horária para desenvolvimento do projeto.
  - Pesquisa sobre integrações com órgãos públicos e API de geolocalização.
    - Tempo estimado: 2 meses.

## Comunicações

### Definição de ferramentas de comunicação

A principal ferramenta de comunicação será um aplicativo de conferência remoto como Zoom, Google Meets ou Microsoft Teams. Assim, teremos uma comunicação verbal por meio das reuniões, mas também teremos uma forma de comunicação não verbal por troca de mensagens, email e documentos.

### Tipo de trabalho 

O trabalho será exclusivamente remoto, no qual as reuniões ocorrerão através de ferramentas de chamada virtuais, como o zoom ou o google meets por exemplo. 

### Tipo e frequência das reuniões

As reuniões entre a equipe serão realizadas de formas frequente e com uma média de 20 minutos de duração, seguindo assim a metodologia ágil da daily, no qual usará de uma comunicação interativa para que todos consigam ouvir e expor informações.

### Definição do 6W2H das informações

- **What?** -  Descrever como está o progresso das atividades.
- **Why?** - Para que a equipe esteja atualizada sobre o progresso de cada um e do projeto como um todo.
- **Who?** - Cada membro da equipe.
- **for Who?** - Outros membros da equipe.
- **When?** - Diariamente, cerca de 20 minutos
- **Where?** - Aplicativo de chamada remoto.
- **How?** - Uma exposição do que foi realizado entre cada reunião, assim como impeditivos encontrados.
- **How Much?** - Cerca de R$210 mensais, caso optemos pelo google meets com uma integração com o drive.

### Matriz de Responsabilidades (Matriz RACI)

|                                      | Dev Mobile | Dev Frontend | Dev Backend | QA  | DevOps | DBA | Marketing | Gerente Marketing | Gerente TI |
| ------------------------------------ | ---------- | ------------ | ----------- | --- | ------ | --- | --------- | ----------------- | ---------- |
| Criar endpoints                      | C          | C            | R           | I   | C      | C   | -         | I                 | A          |
| Criar tela administrativo            | C          | R            | C           | I   | I      | I   | -         | I                 | A          |
| Criar tela mobile                    | R          | C            | C           | I   | I      | I   | -         | I                 | A          |
| Testar aplicativo                    | C          | C            | C           | R   | C      | C   | -         | I                 | A          |
| Divulgar produtos                    | -          | -            | -           | -   | -      | -   | R         | A                 | -          |
| Controle do banco                    | I          | I            | C           | I   | C      | R   | I         | I                 | A          |
| Garantir teste e integração contínua | I          | I            | I           | I   | R      | I   | -         | -                 | A          |
| Criar estratégia de divulgação       | -          | -            | -           | -   | -      | -   | C         | R                 | I          |
| Garantir as entregas e criar backlog | C          | C            | C           | C   | C      | C   | -         | I                 | R          |

## Recursos Humanos

Esta seção tem como objetivo listar e detalhar todos os cargos e posições possíveis a serem ocupados pela equipe do projeto, bem como demonstrar, de maneira visual, como se dá a hierarquia destes cargos e posições, através de um esquema hierárquico.

### Descrição dos cargos

#### Gerente do projeto

- **Responsabilidades**: será o responsável por se manter ciente e atualizado de todas as frentes do projeto, desde o desenvolvimento de código até estar a par das questões legais, porém não necessariamente executando-as. É o responsável figurativo na ocorrência de problemas do projeto, e deve manter a coesão da equipe, exercendo o papel de guia e líder, garantindo a conexão da equipe.

- **Autoridade**: Methodology master.

#### QA

- **Responsabilidades**: em nosso projeto, além de garantir a qualidade do software desenvolvido, realizando testes ao navegar pelo software como um usuário, ele terá uma responsabilidade importante envolvida com um risco do projeto, que é o de detecção de falsos avisos na plataforma, ou seja, será responsável por alertar sobre o acontecimento de tais avisos. Além disso, será responsável também por feedbacks de engajamento, um fator essencial para nosso produto, e por realizar o monitoramento de tal métrica.

- **Autoridade**: Gerente do projeto.

#### Gerente(s) de comunicações

- **Responsabilidades**: é o responsável por manter contato com as partes interessadas do projeto, bem como garantir parcerias-chave, como o fundo social. Por isso, é o responsável por manter contato com os órgãos públicos, e por coletar informações, mesmo que de forma mais superficial, sobre a integração com os serviços públicos, e repassar para o gerente do projeto e equipes de desenvolvimento. Além disso, tem a responsabilidade de realizar a comunicação com o público e coletar dados de, por exemplo, engajamento do público.

- **Autoridade**: Gerente do projeto.

#### Methodology master

- **Responsabilidades**: responsável por garantir a aplicação da metodologia de desenvolvimento de projeto adotada pela equipe, realizar o monitoramento do processo, sendo necessária a participação (mesmo que como espectador) deste em todos os processos, e, por fim, propor melhorias e sugestões ao final de um ciclo.

- **Autoridade**: Nenhuma.

#### LGPD Master

- **Responsabilidades**: é o responsável por garantir o cumprimento da LGPD, e participar ativamente das questões de desenvolvimento de software que envolvem-a.

- **Autoridade**: Gerente do projeto.

#### Devops

- **Responsabilidades**: possui como atribuição principal garantir o funcionamento, consistência e confiabilidade da plataforma de infraestrutura sob a qual o sistema estará hospedado. É responsável também por realizar processos envolvidos com o gerenciamento e provisionamento da infraestrutura por meio de códigos, o infra-as-code, que permite que a infraestrutura seja recriada facilmente caso ocorra algum problema.

- **Autoridade**: Gerente do projeto.

#### Desenvolvedor backend

- **Responsabilidades**: desenvolvedor que realizará o desenvolvimento da estrutura lógica, implementação de regras de negócios e API do produto.

- **Autoridade**: Gerente do projeto.

#### Desenvolvedor frontend

- **Responsabilidades**: desenvolvedor que realizará o desenvolvimento da estrutura lógica e visual das interfaces de usuário.

- **Autoridade**: Gerente do projeto.

#### DBA

- **Responsabilidades**: realizará toda a gerência do banco de dados, como definição de SGBD junto da equipe, criação de tabelas e lógica da base de dados, definição de tipagem, criação de views, procedures, dentre outras tarefas relacionadas.

- **Autoridade**: Gerente do projeto.

#### Pessoa desenvolvedora mobile

- **Responsabilidades**: responsável por desenvolver a aplicação mobile, desde a questão lógica das telas até sua implementação visual. Responsável também pela integração com o backend desenvolvido concomitantemente.

- **Autoridade**: Gerente do projeto.

#### _Observação 1_

Como o cargo de gerente de comunicações abrange várias responsabilidades, pode-se dividi-lo em cargos mais específicos, de acordo com a demanda.

### Esquema hierárquico

{{<img-custom link = "/img/esquema_hierarquico.png">}}
{{</img-custom>}}

## Partes interessadas

| Importância | Poder (0-Muito baixo a 5-Muito alto) | Interesse (0-Muito baixo a 5-Muito alto) | Requisitos de comunicação                                                                 | Principais responsabilidades               | Principais expectativas                                                    | Engajamento |
| ----------- | ------------------------------------ | ---------------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------ | -------------------------------------------------------------------------- | ----------- |
| 20          | 4                                    | 5                                        | Receber Informações sobre o andamento do projeto                                          | Fornecer o apoio orçamentário              | Ter em mãos um aplicativo consistente e utilitário                         | Resistente  |
| 15          | 3                                    | 5                                        | Interação direta com o aplicativo e retorno de feedback para a equipe desenvolvedora      | Utilizar o aplicativo e retornar feedbacks | Utilizar um aplicativo que impacta no seu dia-a-dia                        | Neutro      |
| 25          | 5                                    | 5                                        | Receber feedbacks e comunicar outras partes interessadas sobre o andamento do projeto     | Organizar o projeto como um todo           | Ver o projeto dando resultado                                              | Apoiador    |
| 16          | 4                                    | 4                                        | Receber o feedback do gestor e junto dele combinar as tarefas que deverão ser priorizadas | Desenvolver o aplicativo                   | Ganhar dinheiro e ver satisfação pessoal de ver seu trabalho tendo sucesso | Apoiador    |
| 12          | 3                                    | 4                                        | Receber dados de captação de usuários                                                     | Garantir que o aplicativo fique popular    | Ver o sucesso do processo de divulgação do aplicativo                      | Apoiador    |
| 10          | 5                                    | 2                                        | Receber Informações sobre o andamento do projeto                                          | Fiscalizar o projeto                       | Garantir que o projeto ajude a população e não prejudique nenhuma parte    | Resistente  |

## Aquisições

Descrição de possíveis aquisições de produtos e serviços para o projeto, além da indicação de determinadas funcionalidades que serão desenvolvidas em vez de adquiridas.

### Desenvolvimentos

- Front-end do site/aplicativo.
- Back-end do site/aplicativo.
- Testes.
- Desenvolvimento do banco de dados.
- Manutenção do site/aplicativo.

### Aquisições

- Serviço de Cloud.
- API de mapas

### Fornecedores

Análise de possíveis serviços de Cloud a serem contratados.

Possibilidades:

- AWS
- Azure
- Google Cloud Platform

Fornecedor escolhido: **GCP (Google Cloud Platform)**.

Justificativa: decidimos escolher a GCP, principalmente pelo modelo de faturamento deles se mostrar mais claro do que os concorrentes, além de oferecer preços melhores. Isso é importante para manter a previsibilidade dos custos de nosso projeto, pois, como grande parte de nossos recursos advém de fundos sociais, necessitamos gastar a menor quantidade possível de dinheiro a fim de garantir a sustentabilidade do aplicativo. Desse modo, além de gastar menos com o custo do serviço, não seria necessário aumentar o tamanho do time contratando pessoas que fossem especialistas em serviços como a AWS ou Azure (que exigem mais conhecimentos técnicos para realizar uma boa gestão de custos), o que nos fez tomar a decisão de utilizar o serviço da GCP, tendo em mente ainda que, embora mais novo, é um serviço gerido por uma grande empresa, e que deve evoluir ainda mais ao longo dos próximos anos.

## Aprovações

| Participante            | Assinatura | Data       |
| ----------------------- | ---------- | ---------- |
| Patrocinador do projeto |            | 2022-11-24 |
| Gerente do projeto      |            | 2022-11-24 |

## Anexos

### Tabela de população por bairro em São Paulo

Os dados a seguir são do Censo de 2010. [Fonte](https://pt.wikipedia.org/wiki/Lista_dos_distritos_de_S%C3%A3o_Paulo_por_popula%C3%A7%C3%A3o).

| Posição | Distrito            | População 2010 |
| ------- | ------------------- | -------------- |
| 1       | Grajaú              | 500.787        |
| 2       | Sapopemba           | 296.042        |
| 3       | Jardim Ângela       | 295.434        |
| 4       | Jaraguá             | 281.824        |
| 5       | Itaim Paulista      | 278.026        |
| 6       | Capão Redondo       | 275.230        |
| 7       | Jardim São Luís     | 267.871        |
| 8       | Cidade Ademar       | 266.681        |
| 9       | Brasilândia         | 264.918        |
| 10      | Sacomã              | 247.851        |
| 11      | Jabaquara           | 223.780        |
| 12      | Campo Limpo         | 216.098        |
| 13      | Cidade Tiradentes   | 211.501        |
| 14      | Itaquera            | 204.871        |
| 15      | Cidade Dutra        | 203.473        |
| 16      | Parelheiros         | 202.321        |
| 17      | Tremembé            | 197.258        |
| 18      | Lajeado             | 185.184        |
| 19      | Vila Jacuí          | 167.965        |
| 20      | Pirituba            | 167.931        |
| 21      | Vila Curuçá         | 162.486        |
| 22      | Pedreira            | 158.656        |
| 23      | São Mateus          | 158.533        |
| 24      | Cachoeirinha        | 157.408        |
| 25      | São Rafael          | 151.017        |
| 26      | São Lucas           | 142.347        |
| 27      | Freguesia do Ó      | 142.327        |
| 28      | Cangaíba            | 136.623        |
| 29      | Jardim Helena       | 135.043        |
| 30      | Saúde               | 130.780        |
| 31      | Vila Mariana        | 130.484        |
| 32      | Vila Medeiros       | 129.919        |
| 33      | Penha               | 127.820        |
| 34      | Iguatemi            | 127.662        |
| 35      | Vila Andrade        | 127.015        |
| 36      | Cidade Líder        | 126.597        |
| 37      | José Bonifácio      | 124.122        |
| 38      | Santana             | 118.797        |
| 39      | Rio Pequeno         | 118.459        |
| 40      | Ermelino Matarazzo  | 113.615        |
| 41      | Vila Maria          | 113.463        |
| 42      | Perdizes            | 111.161        |
| 43      | Cursino             | 109.088        |
| 44      | Vila Sônia          | 108.441        |
| 45      | Mandaqui            | 107.580        |
| 46      | Ipiranga            | 106.865        |
| 47      | Artur Alvim         | 105.269        |
| 48      | Vila Matilde        | 104.947        |
| 49      | Vila Prudente       | 104.242        |
| 50      | Guaianases          | 103.996        |
| 51      | Campo Grande        | 100.713        |
| 52      | Raposo Tavares      | 100.164        |
| 53      | Tucuruvi            | 98.438         |
| 54      | Vila Formosa        | 94.799         |
| 55      | Jaçanã              | 94.609         |
| 56      | Ponte Rasa          | 93.894         |
| 57      | Itaim Bibi          | 92.570         |
| 58      | São Miguel Paulista | 92.081         |
| 59      | Tatuapé             | 91.672         |
| 60      | Aricanduva          | 89.622         |
| 61      | Jardim Paulista     | 88.692         |
| 62      | Casa Verde          | 85.624         |
| 63      | Água Rasa           | 84.963         |
| 64      | São Domingos        | 84.843         |
| 65      | Santa Cecília       | 83.717         |
| 66      | Moema               | 83.368         |
| 67      | Carrão              | 83.281         |
| 68      | Limão               | 80.229         |
| 69      | Perus               | 80.187         |
| 70      | Santo Amaro         | 71.560         |
| 71      | Bela Vista          | 69.460         |
| 72      | Liberdade           | 69.092         |
| 73      | Parque do Carmo     | 68.258         |
| 74      | Anhanguera          | 65.859         |
| 75      | Lapa                | 65.739         |
| 76      | Pinheiros           | 65.364         |
| 77      | Mooca               | 63.133         |
| 78      | Campo Belo          | 62.530         |
| 79      | Consolação          | 57.365         |
| 80      | República           | 56.981         |
| 81      | Vila Guilherme      | 54.331         |
| 82      | Butantã             | 54.196         |
| 83      | Jaguaré             | 49.863         |
| 84      | Morumbi             | 46.957         |
| 85      | Belém               | 45.057         |
| 86      | Alto de Pinheiros   | 43.117         |
| 87      | Vila Leopoldina     | 39.485         |
| 88      | Socorro             | 37.783         |
| 89      | Cambuci             | 36.948         |
| 90      | Bom Retiro          | 33.892         |
| 91      | Brás                | 29.265         |
| 92      | Jaguara             | 24.895         |
| 93      | Sé                  | 23.651         |
| 94      | Pari                | 17.299         |
| 95      | Barra Funda         | 14.383         |
| 96      | Marsilac            | 8.258          |