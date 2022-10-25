+++
author = "Cityhub team"
title = "Termo de abertura do projeto"
date = "2022-10-24"
description = "Termo de abertura do projeto"
tags = [
    "Abertura", "Termo"
]
+++

## Controle de versão

| Data       | Versão | Descrição           | Autor        |
| ---------- | ------ | ------------------- | ------------ |
| 2022-10-18 | 1      | Elaboração inicial. | Edgard Taver |

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

## Riscos

Riscos que podem ocorrer durante o desenvolvimento do projeto.

- **Risco 1**: o capital levantado com o Fundo Social pode não ser suficiente para cobrir todo o desenvolvimento.
    - **Impacto**: o projeto pode ser interrompido antes do término do desenvolvimento.
    - **Prevenção**: acompanhar o andamento do projeto e seus custos com frequência, para saber com antecedência caso o capital não seja suficiente.
    - **Mitigação**: as seguintes ações podem ser consideradas:
        - Buscar outros investidores.
        - Reduzir o time de desenvolvimento.
        - Reduzir o escopo do projeto.

- **Risco 2**: o desenvolvimento do aplicativo pode ser mais complexo do que o esperado, levando a um atraso no lançamento. A parte mais sujeita a isso é a integração com os sistemas dos órgãos públicos.
    - **Impacto**: o projeto pode ser interrompido antes do término do desenvolvimento.
    - **Prevenção**:
        - Antes de iniciar o desenvolvimento do aplicativo, pesquisar qualquer documentação existente com relação a plataformas da prefeitura e garantir uma linha de contato com os órgãos públicos previamente.
        - Iniciar o desenvolvimento do aplicativo atacando primeiramente a parte de integração. Como as outras funcionalidades esperadas são mais triviais, elas podem ser implementadas com mais confiança sabendo que a integração foi resolvida.
    - **Mitigação**:
        - Reduzir o escopo do projeto removendo a funcionalidade de integração com os órgãos públicos. Neste caso, o projeto ficaria mais focado na conexão entre os moradores de uma mesma região, permitindo que os usuários se comuniquem entre si para resolver ou evitar problemas.
        - Planejar algum tipo de processo manual para levar avisos aos órgãos públicos, assim garantido uma funcionalidade chave do aplicativo, ainda que elevando os custos da operação.

- **Risco 3**: o projeto pode não ser bem recebido pelos órgãos públicos, que podem não ter interesse em atuar em cima dos avisos enviados pelos usuários do aplicativo.
    - **Impacto**: o aplicativo perderia uma das suas funcionalidades chave.
    - **Prevenção**: garantir contato direto com os órgãos públicos, para apresentar o projeto e medir o interesse, antes do desenvolvimento do aplicativo.
    - **Mitigação**: remover a funcionalidade de integração com os órgãos públicos, como descrito no risco 2.

- **Risco 4**: os usuários podem fazer mal uso do aplicativo gerando avisos falsos.
    - **Impacto**: a credibilidade e percepção do valor do projeto pode ser prejudicada.
    - **Prevenção**:
        - Garantir que, durante a operação do projeto, seja feito um processo de analisar dados dos avisos gerados e buscar por padrões de mal uso (exemplo: usuário gerando múltiplos avisos em um intervalo muito curto de tempo).
        - Pedir feedback constante dos usuários para entender se _spam_ é um problema ou não durante a operação.
    - **Mitigação**: desenvolver uma funcionalidade para analisar e remover _spam_ automaticamente.

_Outros riscos serão descritos com mais detalhes no documento específico de Gestão de Custos._

## Orçamento

O orçamento está descrito em detalhes [aqui](/docs/custos).

Em resumo:

- **Custos de desenvolvimento inicial**: são os custos para criar o aplicativo do zero, até entregar todos os requisitos mínimos e o mesmo se encontrar pronto para os primeiros usuários testes. Essa fase levará **6 meses** e terá o custo total de **R$ 409.199,90**.

- **Custos de operação**: são os custos para manter o aplicativo funcionando, com eventuais desenvolvimentos adicionas (como a funcionalidade de "indique um amigo") e correções de problemas. Essa fase foi planejada também por **6 meses** e terá o custo total de **R$ 723.914,60**.

## Aprovações

| Participante            | Assinatura | Data       |
| ----------------------- | ---------- | ---------- |
| Patrocinador do projeto |            | 2022-11-17 |
| Gerente do projeto      |            | 2022-11-17 |

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