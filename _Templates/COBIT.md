# (Framework COBIT (Governança e Gestão de TI))

**Fonte Bruta:**

- **Referência Base:** [[Cobit 2019 Tudo que você precisa saber.pdf]].
    
- **Status:** Constitui um resumo estruturado e exatual sobre o principal framework global para a Governança e Gestão de TI empresarial. O modelo consolida diretrizes para alinhar a tecnologia da informação aos objetivos estratégicos de negócios, mitigando riscos e otimizando a entrega de valor.
    
---

### 1. Diretrizes Conceituais e Fundamentação do Framework

O COBIT não é um manual técnico de infraestrutura ou desenvolvimento, mas sim um modelo de **Governança Corporativa de TI (EGIT)**. Ele parte do princípio de que a informação e a tecnologia tornaram-se o próprio coração das organizações modernas, exigindo uma camada de controle que garanta que os investimentos em TI tragam o retorno esperado e mitiguem os riscos associados.

Diferencia-se de frameworks como o ITIL (focado no gerenciamento de serviços e operação) por se posicionar no nível estratégico. O COBIT atua como o "guarda-chuva" que dita **o que** a organização precisa controlar, avaliar e monitorar, enquanto outros modelos explicam _como_ executar essas tarefas operacionalmente.

### 2. A Separação entre Governança e Gestão como Pressuposto Vinculante

O elemento balizador e obrigatório para compreender o COBIT é a clara e rígida separação conceitual e organizacional entre duas instâncias:

- **Governança (EDM - Avaliar, Dirigir e Monitorar):** Responsabilidade do Conselho de Administração e da alta liderança. Suas atribuições consistem em **Avaliar** as necessidades das partes interessadas, **Dirigir** a estratégia por meio de políticas e prioridades, e **Monitorar** o desempenho e a conformidade dos resultados.
    
- **Gestão (APO, BAI, DSS, MEA - Planejar, Construir, Executar e Monitorar):** Responsabilidade da gerência executiva e operacional. Suas atribuições consistem em planejar, construir, executar e monitorar as atividades diárias alinhadas às diretrizes traçadas pela governança para atingir os objetivos organizacionais.
    

### 3. Estruturação dos Domínios e Objetivos de Controle (Os 5 Domínios)

O modelo central do COBIT é subdividido em **5 domínios** que agrupam os objetivos de governança e gestão, cobrindo o ciclo de vida ponta a ponta da tecnologia na empresa:

```
      [ GOVERNANÇA: EDM (Avaliar, Dirigir e Monitorar) ]
    ┌─────────────────┬────────────┴───────────┬─────────────────┐
    ▼                                    ▼                                                 ▼                                    ▼
[ GESTÃO: APO ]      [ GESTÃO: BAI ]                       [ GESTÃO: DSS ]          [ GESTÃO: MEA ]
Alinhamento,              Construção,                                Entrega,                 Monitoramento,
Planejamento e          Aquisição e                                 Serviço e                 Avaliação e
Organização             Implementação                             Suporte                  Análise
```

- **EDM (Evaluate, Direct and Monitor):** O único domínio focado estritamente em Governança.
    
- **APO (Align, Plan and Organize):** Domínio de gestão que trata dos aspectos estratégicos, estrutura organizacional, gestão de riscos e inovação.
    
- **BAI (Build, Acquire and Implement):** Domínio de gestão focado na materialização das soluções, desenvolvimento, gerenciamento de projetos e mudanças.
    
- **DSS (Deliver, Service and Support):** Domínio de gestão voltado para a operação diária, segurança cibernética, suporte a usuários e continuidade de negócios.
    
- **MEA (Monitor, Evaluate and Assess):** Domínio de gestão que audita o próprio sistema de controle interno, conformidade legal e desempenho da TI.
    

### 4. Fatores de Design e Personalização do Sistema

Uma das grandes inovações da versão mais recente do framework é o conceito de **Fatores de Design**. O COBIT reconhece que "um tamanho único não serve para todos" e utiliza essas variáveis para que cada empresa desenhe seu próprio sistema de governança:

- **Variáveis de Customização:** Estratégia empresarial (liderança em custos, inovação, etc.), metas corporativas, perfil de risco da organização, cenário de ameaças cibernéticas, requisitos de conformidade regulatória, tamanho da empresa e modelo de adoção de TI (Cloud vs. On-premise).
    
- **Foco no Valor (Cascata de Objetivos):** O COBIT utiliza uma cascata que traduz as necessidades dos _stakeholders_ em objetivos empresariais que, por sua vez, geram os objetivos de TI e determinam quais processos específicos devem receber maior nível de maturidade e investimento.
    

### 5. O que NÃO é o COBIT

Para evitar desvios de finalidade e falhas de implementação, o framework enfatiza que:

- Não é um modelo estático de auditoria punitiva, mas sim uma ferramenta de melhoria contínua de processos;
    
- Não dita arquiteturas de redes, códigos de programação ou escolhas específicas de fornecedores de hardware e software;
    
- Não substitui a gestão corporativa global, funcionando como uma extensão desta voltada para os ativos de informação;
    
- Não deve ser implementado de forma cega ou integral (todas as dezenas de objetivos com força máxima), ignorando a realidade e o orçamento da empresa.
    

### Conexões e Desdobramentos

- **Modelo CERNE (Eixo Incubadora/Processos):** O COBIT conecta-se à governança do modelo CERNE ao garantir que os sistemas de informação e o suporte de TI fornecidos pela incubadora às startups estejam rigidamente alinhados aos objetivos estratégicos de desenvolvimento e inovação regional.
    
- **Boas Práticas ITIL (Operação e Transição):** Dialoga diretamente com o COBIT nos domínios de gestão **BAI** e **DSS**. Enquanto o COBIT estabelece as metas de governança para a entrega de serviços e segurança, o ITIL entra com o detalhamento operacional dos processos de Gerenciamento de Incidentes, Problemas e Mudanças.
    
- **Lei Geral de Proteção de Dados (LGPD) / Compliance:** Conecta-se diretamente ao domínio **MEA** e ao objetivo de controle de segurança do **DSS**. O COBIT fornece o framework de processos estruturado para mapear, auditar e assegurar que a governança de dados da empresa atenda aos rigorosos requisitos de privacidade impostos pela legislação.
    
- **Encomendas Tecnológicas (ETECs) e Estudos Preliminares:** O COBIT atua na fase de estruturação de grandes projetos tecnológicos públicos (como as ETECs) através do domínio **APO** (Alinhamento, Planejamento e Organização), garantindo que os investimentos estatais em P&D de base digital possuam indicadores claros de risco e viabilidade técnica mapeados desde o início.
    
- **Frameworks de Projetos (PMBOK / Scrum):** Alinha-se ao objetivo de controle de gerenciamento de programas e projetos dentro do domínio **BAI**, oferecendo a governança corporativa que valida os portfólios, enquanto o Scrum e as metodologias ágeis executam as Sprints no nível operacional de desenvolvimento.