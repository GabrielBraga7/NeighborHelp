+++
author = "Cityhub team"
title = "Gestão de recursos humanos do projeto"
date = "2022-11-24"
description = "Gestão de recursos humanos do projeto"
tags = [
    "recursos",
]
+++

## Objetivo deste documento
Este documento tem como objetivo listar e detalhar todos os cargos e posições possíveis a serem ocupados pela equipe do projeto, bem como demonstrar, de maneira visual, como se dá a hierarquia destes cargos e posições, através de um esquema hierárquico.

{{< csv-table >}}
Cargo/posição,Responsabilidades,Autoridade
QA,"Em nosso projeto, além de garantir a qualidade do software desenvolvido, realizando testes ao navegar pelo software como um usuário, ele terá uma responsabilidade importante envolvida com um risco do projeto, que é o de detecção de falsos avisos na plataforma, ou seja, será responsável por alertar sobre o acontecimento de tais avisos. Além disso, será responsável também por feedbacks de engajamento, um fator essencial para nosso produto, e por realizar o monitoramento de tal métrica.", Gerente do projeto
Gerente do projeto,"Será o responsável por se manter ciente e atualizado de todas as frentes do projeto, desde o desenvolvimento de código até estar a par das questões legais, porém não necessariamente executando-as. É o responsável figurativo na ocorrência de problemas do projeto, e deve manter a coesão da equipe, exercendo o papel de guia e líder, garantindo a conexão da equipe",Methodology master
Gerente(s) de comunicações,"É o responsável por manter contato com as partes interessadas do projeto, bem como garantir parcerias-chave, como o fundo social. Por isso, é o responsável por manter contato com os órgãos públicos, e por coletar informações, mesmo que de forma mais superficial, sobre a integração com os serviços públicos, e repassar para o gerente do projeto e equipes de desenvolvimento. Além disso, tem a responsabilidade de realizar a comunicação com o público e coletar dados de, por exemplo, engajamento do público. ",Gerente do projeto
Methdology master,"Responsável por garantir a aplicação da metodologia de desenvolvimento de projeto adotada pela equipe, realizar o monitoramento do processo, sendo necessária a participação (mesmo que como espectador) deste em todos os processos, e, por fim, propor melhorias e sugestões ao final de um ciclo.",Nenhuma
LGPD Master,"É o responsável por garantir o cumprimento da LGPD, e participar ativamente das questões de desenvolvimento de software que envolvem-a.",Gerente do projeto
Devops,"Possui como atribuição principal garantir o funcionamento, consistência e confiabilidade da plataforma de infraestrutura sob a qual o sistema estará hospedado. É responsável também por realizar processos envolvidos com o gerenciamento e provisionamento da infraestrutura por meio de códigos, o infra-as-code, que permite que a infraestrutura seja recriada facilmente caso ocorra algum problema.",Gerente de projeto
Desenvolvedor backend,"Desenvolvedor que realizará o desenvolvimento da estrutura lógica, implementação de regras de negócios e API do produto.",Gerente de projeto
Desenvolvedor frontend,"Desenvolvedor que realizará o desenvolvimento da estrutura lógica e visual das interfaces de usuário.",Gerente de projeto
DBA,"Realizará toda a gerência do banco de dados, como definição de SGBD junto da equipe, criação de tabelas e lógica da base de dados, definição de tipagem, criação de views, procedures, dentre outras tarefas relacionadas.",Gerente de projeto
Pessoa desenvolvedora mobile,"Responsável por desenvolver a aplicação mobile, desde a questão lógica das telas até sua implementação visual. Responsável também pela integração com o backend desenvolvido concomitantemente.",Gerente de projeto
{{< /csv-table >}}
##### Observação 1:
Como o cargo de gerente de comunicações abrange várias responsabilidades, pode-se dividi-lo em cargos mais específicos, de acordo com a demanda.
### Esquema hierárquico
Esquema hierárquico visual dos cargos/posições. Nele, os desenvolvedores estão conectados por necessitarem estar em constante contato, o LGPD master está acima do desenvolvedor backend por determinar e impor restrições no processo de desenvolvimento, e a pessoa QA está acima dos desenvolvedores por determinar e influenciar no desenvolvimento de cada um, pois o controle de qualidade exerce esse impacto.

{{<img-custom link = "/img/esquema_hierarquico.png">}}
{{</img-custom>}}



