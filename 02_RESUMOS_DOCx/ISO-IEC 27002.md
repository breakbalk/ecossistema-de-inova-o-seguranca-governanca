# **ISO/IEC 27002/2022: Governança, Controles e Alinhamento Regulatório no Ecossistema de Segurança da Informação**


A publicação da norma ISO/IEC 27002:2022 em 15 de fevereiro de 2022 marcou o início de uma nova era na gestão da segurança da informação, substituindo a versão anterior de 2013 após um ciclo de revisão de aproximadamente nove anos. Esta atualização não representa apenas uma mudança incremental, mas uma reestruturação fundamental projetada para enfrentar a complexidade das ameaças cibernéticas contemporâneas, a onipresença da computação em nuvem e as exigências crescentes de privacidade de dados. Renomeada como "Segurança da informação, segurança cibernética e proteção à privacidade — Controles de segurança da informação", a norma expandiu seu escopo para além da segurança da informação tradicional, integrando de forma explícita conceitos de defesa cibernética e governança de dados pessoais. 

A transição da versão de 2013 para a de 2022 reflete o amadurecimento do mercado global. Enquanto a edição anterior era centrada em domínios de controle, a nova estrutura é temática e orientada por atributos, permitindo que as organizações criem visualizações personalizadas de seus controles de acordo com suas necessidades específicas de risco e conformidade.  

**Evolução Estrutural e a Transição dos Domínios para Temas**


A mudança mais visível na ISO/IEC 27002:2022 é a redução do número total de controles de 114 para 93 e a substituição dos antigos 14 domínios por apenas quatro temas principais. Essa consolidação foi alcançada através de um esforço concentrado para eliminar redundâncias, resultando na fusão de 57 controles da versão 2013 em apenas 24 controles na versão atual. Além disso, 58 controles foram revisados e atualizados para melhor se alinharem ao ambiente atual de segurança, enquanto 11 controles inteiramente novos foram introduzidos para preencher lacunas críticas identificadas na última década. 

A lógica por trás dessa reorganização temática visa simplificar a implementação e a atribuição de responsabilidades dentro das organizações. Ao agrupar os controles em categorias de fácil compreensão (Organizacional, Pessoas, Físico e Tecnológico), a norma facilita o diálogo entre o departamento de segurança e as demais áreas de negócio. 

|   |   |   |   |
|---|---|---|---|
|Característica|ISO/IEC 27002:2013|ISO/IEC 27002:2022|Natureza da Mudança|
|Quantidade de Controles|114|93|Consolidação e Eficiência|
|Estrutura de Agrupamento|14 Domínios|4 Temas|Simplificação Temática|
|Foco do Controle|Objetivos de Controle|Propósitos Individuais|Orientação a Resultados|
|Terminologia|Código de Prática|Controles de Segurança|Expansão de Escopo|
|Integração de Atributos|Não existia|5 Categorias|Metadados para Gestão|

A transição de "objetivos de controle" para o conceito de "propósito" individual por controle é uma mudança sutil, mas poderosa. Na versão 2013, um grupo de controles compartilhava um objetivo comum; na versão 2022, cada controle possui um propósito claramente definido, permitindo que os gestores de risco identifiquem com precisão por que uma medida específica está sendo implementada para tratar um risco determinado. 

**O Tema Organizacional (Cláusula 5)** 

Com 37 controles, este tema abrange as políticas, processos e estruturas de governança que sustentam o Sistema de Gestão de Segurança da Informação (SGSI). Ele trata de questões como a organização interna da segurança, o inventário de ativos, a gestão de relacionamentos com fornecedores e a conformidade legal. A inclusão de controles como a inteligência de ameaças (5.7) e a segurança em serviços de nuvem (5.23) neste tema destaca que a segurança da informação é, acima de tudo, uma disciplina de gestão estratégica e não apenas uma função técnica. 

**O Tema Pessoas (Cláusula 6)** 

Composto por 8 controles, este tema foca no ciclo de vida do colaborador e na cultura de segurança. Ele aborda desde o recrutamento (triagem) e termos de contratação até a conscientização, treinamento e o processo de desligamento ou mudança de função. A ênfase aqui está na redução do risco humano, que continua sendo um dos principais vetores de incidentes de segurança. Controles como o de trabalho remoto e acordos de confidencialidade são fundamentais neste tema, refletindo as necessidades de um mercado de trabalho cada vez mais descentralizado. 

**O Tema Físico (Cláusula 7)** 

Este tema agrupa 14 controles relacionados à proteção de áreas, equipamentos e instalações. Ele inclui a definição de perímetros de segurança física, controles de entrada, proteção contra ameaças ambientais e o monitoramento de segurança física (7.4). A atualização deste tema reconhece que, embora a digitalização seja predominante, a segurança da infraestrutura física continua sendo um pilar essencial para garantir a disponibilidade e a integridade dos dados. 

**O Tema Tecnológico (Cláusula 8)** 

Contendo 34 controles, este tema lida com as salvaguardas técnicas implementadas em sistemas, redes e aplicações. Ele abrange criptografia, gestão de vulnerabilidades, segurança de rede, configuração de sistemas e desenvolvimento seguro de software. Novos controles como mascaramento de dados (8.11) e prevenção de vazamento de dados (8.12) estão situados aqui, refletindo a necessidade de proteção técnica profunda contra exfiltração de dados e acessos não autorizados. 

**O Sistema de Atributos: Metadados para Gestão de Riscos** 

Uma das inovações mais disruptivas da ISO/IEC 27002:2022 é a introdução de um esquema de taxonomia baseado em atributos. Cada controle agora é acompanhado por cinco atributos que funcionam como "tags" ou metadados, permitindo que as organizações filtrem, classifiquem e visualizem os controles sob diferentes perspectivas. Esse sistema é particularmente útil para o mapeamento entre diferentes frameworks e regulamentações, como o NIST Cybersecurity Framework, CIS Controls e legislações de proteção de dados. 

|   |   |   |
|---|---|---|
|Atributo|Descrição|Valores Possíveis|
|Tipo de Controle|Perspectiva de quando e como o controle modifica o risco.|Preventivo, Detetive, Corretivo|
|Propriedades de SI|Qual característica da informação o controle preserva.|Confidencialidade, Integridade, Disponibilidade|
|Conceitos de Cibersegurança|Alinhamento com as funções do framework ISO/IEC TS 27110/NIST CSF.|Identificar, Proteger, Detetar, Responder, Recuperar|
|Capacidades Operacionais|Visão do profissional de segurança sobre as capacidades necessárias.|Governança, Gestão de Ativos, Proteção da Informação, Segurança Física, etc.|
|Domínios de Segurança|Perspectiva de governança e resiliência organizacional.|Governança e Ecossistema, Proteção, Defesa, Resiliência|

O uso desses atributos permite uma análise de lacunas (gap analysis) muito mais sofisticada. Por exemplo, uma organização pode filtrar seus controles pelo atributo "Tipo de Controle" para verificar se possui controles "Detetives" suficientes para identificar ataques em progresso, ou pelo atributo "Conceitos de Cibersegurança" para garantir que possui uma cobertura equilibrada em todas as fases de uma invasão, desde a identificação até a recuperação. Além disso, a norma incentiva as organizações a criarem seus próprios atributos personalizados, adaptando o framework ao seu contexto de negócio específico. 

**Aplicação Prática dos Atributos** 

Considere o novo controle de Filtragem Web (8.23). Sob o novo sistema, ele é classificado com os seguintes atributos: Tipo de Controle: #Preventivo; Propriedades de SI: #Confidencialidade, #Integridade, #Disponibilidade; Conceitos de Cibersegurança: #Proteger; Capacidade Operacional: #Segurança de sistemas e redes; Domínio de Segurança: #Proteção. Essa rotulagem permite que o CISO reporte rapidamente à diretoria quais medidas preventivas estão protegendo a rede contra malware de origem web, integrando essa informação diretamente em painéis de monitoramento de riscos e conformidade. 

**Análise Detalhada dos 11 Novos Controles** 

A inclusão de 11 novos controles é a resposta direta da ISO às mudanças tecnológicas e comportamentais da última década, como o trabalho remoto em massa e a migração acelerada para infraestruturas híbridas e multi-nuvem. 

|   |   |   |   |
|---|---|---|---|
|ID|Nome do Controle|Tema|Implicação Estratégica|
|5.7|Inteligência de Ameaças|Organizacional|Transição para uma postura proativa e preditiva de segurança.|
|5.23|SI para Uso de Serviços em Nuvem|Organizacional|Gestão da responsabilidade compartilhada e governança de terceiros.|
|5.30|Prontidão de TIC para Continuidade de Negócios|Organizacional|Foco na resiliência digital e tempos de recuperação (RTO/RPO).|
|7.4|Monitoramento de Segurança Física|Físico|Integração de sistemas de vigilância e detecção de intrusão física.|
|8.9|Gestão de Configuração|Tecnológico|Prevenção de vulnerabilidades por má configuração de ativos e sistemas.|
|8.10|Exclusão de Informações|Tecnológico|Alinhamento com o direito ao esquecimento e minimização de dados.|
|8.11|Mascaramento de Dados|Tecnológico|Proteção de dados sensíveis em ambientes de teste e desenvolvimento.|
|8.12|Prevenção de Vazamento de Dados (DLP)|Tecnológico|Detecção e bloqueio de exfiltração não autorizada de informações críticas.|
|8.16|Atividades de Monitoramento|Tecnológico|Visibilidade contínua de eventos anômalos em toda a infraestrutura.|
|8.23|Filtragem Web|Tecnológico|Controle de acesso a conteúdos maliciosos para reduzir riscos de phishing e malware.|
|8.28|Codificação Segura|Tecnológico|Inclusão da segurança no ciclo de vida de desenvolvimento de software (SDLC).|

A introdução da Inteligência de Ameaças (5.7) exige que as organizações não apenas respondam a incidentes, mas busquem ativamente informações sobre agentes de ameaças, vetores de ataque e vulnerabilidades emergentes no mercado. Já o controle de Segurança da Informação para Uso de Serviços em Nuvem (5.23) formaliza a necessidade de acordos de nível de serviço (SLAs) claros e verificações de segurança robustas para provedores SaaS, PaaS e IaaS, reconhecendo que a segurança da nuvem é uma responsabilidade compartilhada. 

Do ponto de vista da privacidade, os controles 8.10 (Exclusão de Informações) e 8.11 (Mascaramento de Dados) são cruciais para a conformidade com regulações como a LGPD no Brasil. Eles asseguram que os dados pessoais não permaneçam nos sistemas por mais tempo do que o necessário e que as informações identificáveis sejam protegidas contra exposição acidental ou deliberada durante processos operacionais. 

**Relação entre ISO/IEC 27001 e ISO/IEC 27002 no Processo de Certificação** 

É fundamental compreender que as organizações buscam a certificação na ISO/IEC 27001, não na ISO/IEC 27002. A ISO/IEC 27001 é o padrão que estabelece os requisitos obrigatórios para um Sistema de Gestão de Segurança da Informação (SGSI), definindo o "que" deve ser feito através de suas cláusulas 4 a 10. Por outro lado, a ISO/IEC 27002 atua como o manual de implementação detalhado para os controles listados no Anexo A da ISO/IEC 27001, explicando o "como" realizar cada medida de segurança. 

A publicação da ISO/IEC 27002:2022 forçou uma atualização correspondente na ISO/IEC 27001, resultando na versão ISO/IEC 27001:2022. Esta nova versão do padrão de certificação incorporou integralmente a nova lista de 93 controles em seu Anexo A, alinhando-se à estrutura de quatro temas e introduzindo o sistema de atributos. 

**Linha do Tempo e Prazos de Transição** 

As organizações que possuem certificações ativas na versão 2013 da ISO 27001 enfrentam um cronograma rigoroso para atualizar seus sistemas. O período de transição começou em 31 de outubro de 2022 e terminará em 31 de outubro de 2025. Após essa data, todos os certificados baseados na versão de 2013 perderão a validade. 

|   |   |   |
|---|---|---|
|Evento|Data Limite|Implicação para a Organização|
|Publicação da ISO 27001:2022|Outubro de 2022|Início oficial do período de transição de 36 meses.|
|Início das Auditorias Obrigatórias (Nova Versão)|1º de Maio de 2024|Todas as novas certificações e recertificações devem usar a versão 2022.|
|Limite para Auditorias de Transição|31 de Julho de 2025|Prazo recomendado para realizar a auditoria de mudança de versão.|
|Expiração Final da Versão 2013|31 de Outubro de 2025|Certificados da versão 2013 são retirados ou expiram.|

Durante este processo, a Declaração de Aplicabilidade (Statement of Applicability - SoA) deve ser totalmente reformulada para refletir a nova estrutura de controles. A falha em atualizar a SoA é um dos erros mais comuns identificados por auditores, pois demonstra que a transição não foi devidamente planejada ou compreendida pela gerência. 

**Adoção no Brasil: ABNT NBR ISO/IEC 27002 e a Convergência com a LGPD** 

No território brasileiro, a norma internacional é traduzida e oficializada pela Associação Brasileira de Normas Técnicas como ABNT NBR ISO/IEC 27002:2022. Para as empresas brasileiras, a implementação desta norma deixou de ser uma vantagem competitiva opcional para se tornar um pilar estratégico de conformidade com a Lei Geral de Proteção de Dados (LGPD - Lei nº 13.709/2018). A LGPD exige que os agentes de tratamento adotem medidas de segurança, técnicas e administrativas aptas a proteger os dados pessoais de acessos não autorizados e de situações acidentais ou ilícitas de destruição, perda, alteração, comunicação ou difusão. 

Como a LGPD possui um caráter mais principiológico e não detalha as medidas técnicas específicas, a ISO/IEC 27002 serve como o "estado da arte" técnico que preenche essa lacuna regulatória. A adoção do conjunto de controles da norma é vista pela Autoridade Nacional de Proteção de Dados (ANPD) e por tribunais como evidência de diligência e boas práticas de governança. 

**Benefícios Estratégicos para o Mercado Brasileiro** 

A implementação de um SGSI baseado na NBR ISO/IEC 27001/27002 oferece vantagens que vão além do compliance jurídico. Ela transforma a segurança da informação em um diferencial competitivo, aumentando a confiança de stakeholders, investidores e parceiros internacionais que exigem padrões globais de proteção de dados. Em setores como o financeiro e de saúde, onde a sensibilidade dos dados é extrema, a certificação ISO 27001 é frequentemente um pré-requisito contratual para fornecedores. 

Órgãos públicos brasileiros também têm liderado pelo exemplo. O Guia Orientativo de Implementação da LGPD para Gestores Públicos recomenda explicitamente o uso da NBR ISO/IEC 27002 como referência para estabelecer controles de segurança e privacidade. Instituições como a Secretaria da Controladoria-Geral do Estado de Pernambuco (SCGE-PE) publicaram guias detalhando pontos de controle alinhados à ISO 27002 para orientar servidores e encarregados de dados (DPOs) no processo de adequação. 

**Ecossistema de Implementação e Educação em Goiás** 

O estado de Goiás tem se consolidado como um importante polo de tecnologia e segurança da informação no Centro-Oeste, oferecendo uma infraestrutura completa de consultoria especializada e formação acadêmica para suporte à ISO/IEC 27002. Empresas e instituições de ensino em Goiânia e Anápolis adaptaram seus portfólios para atender à demanda gerada pela atualização da norma e pela necessidade de adequação à LGPD. 

**Consultoria e Suporte Técnico Local** 

Diversas empresas goianas oferecem serviços de consultoria para implementação, auditoria interna e preparação para certificação ISO 27001/27002. Essas consultorias geralmente seguem etapas estruturadas de diagnóstico, planejamento, execução e monitoramento. 

- Intervention (Goiânia): Líder local em TI e segurança, focada em análise de vulnerabilidades e implementação de medidas de proteção alinhadas com as normas ISO e regulamentos vigentes. 
    

- RTS Technology (Goiânia): Especializada em Gap Analysis para ISO 27001/27002, análise de riscos e testes de intrusão, utilizando metodologias internacionais para reduzir a exposição a riscos das empresas goianas. 
    

- Clavis (Atuação Nacional com Suporte Regional): Oferece consultoria baseada em metodologias testadas no mercado brasileiro, auxiliando na construção de SGSI resilientes e em conformidade com a LGPD. 
    

- Consultoria ISO (Abadia de Goiás): Focada em capacitação e suporte para certificação de sistemas de gestão em qualidade e segurança da informação. 
    

**Formação Acadêmica e Treinamento em Goiás** 

Para suprir a carência de profissionais qualificados na região, diversas instituições de ensino superior em Goiás integraram as normas ISO/IEC 27001 e 27002 em seus currículos de graduação e pós-graduação. 

|   |   |   |
|---|---|---|
|Instituição|Tipo de Curso|Foco Relacionado à ISO 27002|
|SENAI Goiás (FATESG/Ítalo Bologna)|Pós-Graduação (MBA)|MBA em Governança de TI com foco em normas ISO/IEC 27001 e 27002.|
|Universidade Federal de Goiás (UFG)|Especialização|Segurança de Redes e Sistemas, cobrindo gestão de riscos (ISO 27005) e normas 27001/2.|
|UNIFAN|Graduação Tecnológica|Tecnologia em Segurança da Informação baseada em normas internacionais e conformidade com LGPD.|
|IPOG|Pós-Graduação|Gestão de segurança de dados e sistemas com foco nos pilares de CIA (Confidencialidade, Integridade, Disponibilidade).|
|Gran Faculdade|Pós-Graduação (EAD)|Especialização em Segurança da Informação abordando as normas 27001, 27002 e 27005.|

O SENAI Goiás, através do SENAI Hub, também promove um ambiente de conexão entre indústrias e institutos de tecnologia, incentivando projetos de inovação que incorporam segurança cibernética e privacidade por design, essenciais para a competitividade da indústria goiana. 

**Diretrizes Práticas para a Transição e Implementação Bem-Sucedida** 

A transição para a ISO/IEC 27002:2022 não deve ser tratada como um mero exercício de renomeação de controles existentes. Ela exige um planejamento cuidadoso e o envolvimento da alta gestão para garantir que as mudanças sejam integradas à estratégia do negócio. 

Passo 1: Análise Diferencial (Gap Analysis) 

O processo deve começar com uma comparação detalhada entre o SGSI atual (baseado na versão 2013) e os novos requisitos da versão 2022. As organizações devem avaliar cada um dos 11 novos controles quanto à sua aplicabilidade e eficácia em mitigar riscos atuais. Ferramentas automatizadas de mapeamento podem acelerar este processo, vinculando controles antigos aos novos temas. 

Passo 2: Atualização da Avaliação de Riscos 

A introdução de controles como a inteligência de ameaças e a segurança em nuvem reflete novos riscos que podem não ter sido formalmente avaliados anteriormente. A matriz de riscos deve ser revisada para incluir ameaças modernas, como ataques de ransomware sofisticados, vulnerabilidades em cadeias de suprimentos de software e riscos de privacidade decorrentes do processamento de grandes volumes de dados pessoais. 

Passo 3: Revisão da Declaração de Aplicabilidade (SoA) 

A SoA é o documento que os auditores externos revisam primeiro. Ela deve ser atualizada para listar os 93 controles da nova versão. Para cada controle, a organização deve documentar sua inclusão (com base na avaliação de riscos), sua implementação atual e as evidências que comprovam sua eficácia. A justificativa para exclusões deve ser robusta e baseada em fatos documentados. 

Passo 4: Atualização de Documentação e Políticas 

Políticas de segurança, normas e procedimentos operacionais que referenciam números de controles da versão 2013 devem ser atualizados. Isso inclui planos de resposta a incidentes, guias de configuração de sistemas e políticas de classificação da informação. Além disso, a nova Cláusula 6.3 da ISO 27001 exige que quaisquer mudanças no SGSI sejam realizadas de maneira planejada e documentada, o que se aplica diretamente ao processo de transição de versão. 

Passo 5: Treinamento e Conscientização 

A mudança para uma estrutura temática e o uso de atributos requerem que a equipe técnica e os auditores internos compreendam a nova taxonomia. Programas de treinamento devem ser realizados para explicar o propósito dos novos controles e como o sistema de atributos será utilizado para monitorar a eficácia do sistema. 

**Implicações de Terceira Ordem e o Futuro da Governança de Segurança** 

A evolução da ISO/IEC 27002:2022 sinaliza tendências profundas no campo da tecnologia e conformidade que afetarão as organizações nos próximos anos. 

**Automação de GRC e Monitoramento Contínuo** 

O sistema de atributos é o primeiro passo em direção ao "Compliance as Code". Ao rotular controles com metadados como #Detetive ou #Recuperar, as organizações podem integrar seus controles de segurança diretamente em ferramentas de monitoramento contínuo e automação de GRC (Governança, Risco e Conformidade). Isso permite que um desvio técnico em uma configuração de nuvem seja automaticamente mapeado para uma deficiência em uma capacidade operacional específica, permitindo respostas em tempo real. 

**Convergência de Segurança, Privacidade e IA** 

A ISO/IEC 27002:2022 não existe no vácuo. Ela deve ser vista como parte de uma família de normas que inclui a ISO/IEC 27701 (Extensão para Privacidade) e a nova ISO/IEC 42001 (Gestão de Inteligência Artificial). A inclusão de controles de codificação segura e mascaramento de dados prepara o terreno para a gestão de riscos em sistemas de IA, onde a proteção de dados de treinamento e a integridade dos modelos são fundamentais. 

**Foco na Resiliência Operacional em vez de Apenas Prevenção** 

A nova norma reconhece que a prevenção absoluta é impossível. O equilíbrio entre controles preventivos, detetivos e corretivos, reforçado pelo sistema de atributos, mostra que o objetivo final é a resiliência operacional. Isso alinha a ISO 27002 com outros frameworks setoriais, como o ISA/IEC 62443 para sistemas de tecnologia operacional (OT), garantindo que a segurança proteja não apenas dados, mas também a continuidade dos processos físicos de produção e serviços essenciais. 

A transição para a ISO/IEC 27002:2022 é, portanto, uma jornada de amadurecimento organizacional. Para as empresas em Goiás e no Brasil, ela representa a oportunidade de alinhar sua infraestrutura técnica às melhores práticas globais e às exigências rigorosas da LGPD, garantindo que a segurança da informação seja um motor de confiança e inovação nos negócios.