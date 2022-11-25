+++
author = "Cityhub team"
title = "Gestão de riscos do projeto"
date = "2022-11-24"
description = "Gestão de riscos do projeto"
tags = [
    "riscos",
]
+++

Riscos que podem ocorrer durante o desenvolvimento e operação do projeto.

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

## Matriz RACI

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