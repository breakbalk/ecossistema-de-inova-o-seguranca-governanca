# (Manual da Fab Academy – Diretrizes e Governança da Rede Fab Lab  (Fab Foundation))

**Fonte Bruta:**

- **Arquivo Original:** [[FabAcademyHandbook.pdf]]
    

- **Status:** Trata-se do manual oficial de governança, critérios pedagógicos e operação técnica da Fab Academy, a plataforma educacional global coordenada pelo Center for Bits and Atoms (CBA) do MIT e pela Fab Foundation. O documento funciona como um guia de padronização para estudantes, instrutores locais e "Gurus", estabelecendo os requisitos de infraestrutura para os laboratórios e a matriz de competências necessárias para a obtenção do Fab Diploma.  
    
---

## 🏛️ 1. Conceitos Fundamentais e o Propósito da Fab Academy 

O manual define a Fab Academy como o ecossistema central de formação técnica e disseminação da cultura Maker no mundo:

- **Formação de Lideranças**: O papel principal da Fab Academy é iniciar, orientar e treinar tecnicamente novos estudantes para participarem e assumirem papéis de liderança na comunidade global da Rede Fab Lab, funcionando essencialmente como a escola de formação dos próprios professores da rede.
    
- **Imersão em Fabricação Digital**: O programa oferece uma exposição rápida e intensiva a uma ampla variedade de práticas — incluindo fabricação digital, eletrônica, moldagem, fundição e compósitos — consolidando competências técnicas avançadas em um curto período (tipicamente 19 semanas).
    
- **Princípio de Compartilhamento**: O ecossistema se baseia no princípio fundamental de que os Fab Labs devem compartilhar capacidades essenciais idênticas, permitindo que tanto as pessoas quanto os projetos técnicos sejam intercambiáveis e reproduzíveis em qualquer lugar do mundo.
    

## 🛠️ 2. Requisitos de Infraestrutura e Logística das Máquinas

Para que um laboratório seja homologado como um sítio apto a ministrar as aulas da Fab Academy, ele deve, obrigatoriamente, possuir o inventário padrão padronizado:

- **Máquinas de Corte**: Exige-se uma cortadora a laser controlada por computador (para montagem por encaixe de estruturas 3D a partir de peças 2D) e uma cortadora de vinil (_signcutter_) para produzir máscaras de impressão, circuitos flexíveis e antenas.
    
- **Usinagem e Subtração**: É obrigatória uma fresadora CNC de grande formato ($4^{\prime} \times 8^{\prime}$) voltada para a fabricação de peças estruturais (tamanho de móveis e casas), além de uma fresadora de precisão (resolução micrométrica) para confeccionar moldes tridimensionais e placas de circuito impresso de montagem em superfície (SMD).
    
- **Insumos e Cadeia de Suprimentos**: Os laboratórios devem manter estoque antecipado (com pelo menos 4 semanas de antecedência) de itens específicos como placas de fenolite FR1 (para fresagem de circuitos), componentes eletrônicos SMD, ferramentas de programação, materiais de moldagem e compósitos.
    

## ⚙️ 3. Governança Humana: Grupos de Trabalho, Instructors e Gurus 

A estrutura pedagógica introduz papéis bem delimitados para garantir o suporte técnico e evitar a sobrecarga de mentoria:

- **Massa Crítica de Aprendizado**: É considerada quase impossível a conclusão do curso de forma isolada; por isso, exige-se um grupo de trabalho local composto por um instrutor e no mínimo 3 estudantes, garantindo um ambiente colaborativo onde a forte competência de um aluno compense a fraqueza de outro.
    
- **Limites de Atendimento**: Recomenda-se o teto de 10 alunos por instrutor para evitar sobrecarga de orientação semanal. Se o laboratório possuir mais de um instrutor, o limite logístico recomendado é de 15 alunos por laboratório, devido à disputa pelo tempo de uso das máquinas.
    
- **Instrutores Locais vs. Gurus**: Os formados na Fab Academy atuam como Instrutores Locais (com supervisão obrigatória no Ano 1 e autônomos a partir do Ano 2). Já os "Gurus" são instrutores seniores (com 3 ou mais anos de experiência de ensino na Academia) aptos a monitorar laboratórios e mentorar alunos de forma remota, assumindo a postura de suporte moral e técnico e adotando a filosofia de transparência ("Eu não sei, mas vou descobrir").
    

## 📂 4. Diretrizes Pedagógicas e Exigências para Estudantes 

O manual estabelece uma rotina rigorosa de dedicação e entregas documentais que balizam a concessão do Fab Diploma:

- **Compromisso de Tempo**: Exige-se uma dedicação mínima de 16 horas semanais por parte dos alunos, podendo ser consideravelmente maior a depender do histórico técnico do estudante.
    
- **Documentação Obrigatória e Aberta**: Os alunos devem documentar seus processos semanalmente em formato HTML nativo dentro do repositório Mercurial da classe (sistemas PHP não são aceitos). A documentação deve conter a descrição do projeto, fotos do processo, os arquivos originais de fabricação em formatos editáveis, códigos executáveis puros (prints de tela não são aceitos) e uma reflexão sobre erros e acertos.
    
- **Política de Código Aberto**: O compartilhamento integral dos arquivos de design digital e códigos é um requisito obrigatório para a aprovação em cada unidade, sendo recomendado que o estudante defina uma licença de propriedade intelectual para o seu trabalho desde o início.
    

## 👥 5. Matriz de Avaliação Técnica (Unidades Críticas)

A avaliação dos módulos técnicos foca na autonomia e na correta compreensão das camadas de abstração da engenharia:

- **Design e Produção Eletrônica**: Os alunos aprendem a redesenhar placas de circuito (como a _echo hello-world_), soldar componentes SMD e depurar o hardware. O manual proíbe o uso puro de placas prontas como Arduinos pré-fabricados em substituição à fabricação própria. O uso de Arduinos só é aceito se conectados a _shields_ ou placas de expansão personalizadas e projetadas pelo próprio estudante, pois o objetivo central é ler os _datasheets_ e compreender os microcontroladores em nível de circuito.
    
- **Módulos de Entrada e Saída (Input/Output)**: Exige-se a fabricação de placas de sensores e atuadores, com programação em baixo nível. Se um estudante iniciante falhar em compreender como extrair, interpretar ou acionar dados sem o ecossistema facilitador do Arduino, ele falhará em progredir para o projeto final (o uso injustificado de plataformas comerciais prontas sem a devida abstração é categorizado como "FALHA" pela Academia).
    
- **Usinagem e Moldagem 3D**: Inclui o design e corte de "algo grande" na CNC router (como móveis), modelagem CAD 3D para moldes e fundição com materiais químicos (observando as normas de segurança das fichas MSDS), além de compósitos em moldes de grandes formatos.
    

## 🗺️ 6. Fluxo de Etapas (Ciclo Semanal de Desenvolvimento e Avaliação) 

A dinâmica da Fab Academy acontece em um ciclo de entrega contínuo e incremental estruturado nos seguintes passos de governança: 
1º Passo: Aula Global com Neil Gershenfeld (Quartas às 09h EST) via videoconferência MCU
2º Passo: Aprendizado prático local e instrução direta de uso de máquinas no laboratório 
3º Passo: Ciclo ágil individual (Aprender -> Projetar -> Fabricar -> Prototipar -> Testar) 
4º Passo: Documentação em HTML e push dos arquivos editáveis para o repositório Mercurial 
5º Passo: Revisão semanal de tarefas pelos Gurus e Instrutores Locais (Terças-feiras) 
6º Passo: Avaliação periódica e submissão dos aprovados ao Comitê de Avaliação Global para o Fab Diploma.
    

---

**Conexões e Desdobramentos:**

- **Metodologia de Desenvolvimento Espiral (_Spiral Development_)**: Alinha-se diretamente aos conceitos de gerenciamento de projetos do manual, onde o aluno constrói protótipos funcionais simples que ganham complexidade a cada semana, evitando falhas catastróficas no projeto final.
    
- **Sistemas de Controle de Versão Distribuídos (Mercurial/Git)**: Conecta-se à exigência de proficiência em ferramentas técnicas normais para indivíduos da área tecnológica, integrando a documentação científica com a rastreabilidade de código.
    
- **Cultura Open Source Hardware e Licenciamento**: Dialoga com as discussões sobre propriedade intelectual tratadas no módulo final, forçando o estudante a pensar em modelos de negócios, disseminação de tecnologia e escolha de licenças (Creative Commons, MIT, etc.) para proteção e compartilhamento de seus projetos.
    
- **Normas Globais de Segurança Química (MSDS)**: Vincula-se à operação de laboratórios industriais, exigindo o entendimento de riscos de poeiras (MDF/Espuma), uso de respiradores e controle de temperatura exotérmica em processos de resinas e compósitos.
    

---

