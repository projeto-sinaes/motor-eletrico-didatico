
# Motor Didático Desmontável

> Projeto vinculado ao SINAES – Soluções Inclusivas para Necessidades de Aprendizagem Específicas.

## Apresentação

O estudo do Eletromagnetismo e da Eletrodinâmica frequentemente esbarra na abstração de seus conceitos, já que os motores elétricos do nosso cotidiano são tratados como "caixas pretas" industriais fechadas, limitando o aprendizado à memorização passiva de fórmulas no quadro de giz. Para romper essa barreira, desenvolvemos o Motor Elétrico Didático Desmontável. Trata-se de um protótipo com design totalmente aberto e modular, controlado em tempo real por um ESP32 para regular sua velocidade de rotação. Alinhado aos princípios do Desenho Universal para a Aprendizagem (DUA), o projeto materializa forças magnéticas invisíveis em movimento físico palpável, transformando a sala de aula em um laboratório altamente prático, lúdico e inclusivo para todos os estudantes

## Objetivo geral e objetivos específicos

### Objetivo geral

Esclarecer o funcionamento de motores elétricos escovados por meio da vizualização e interação.

### Objetivos específicos

Para alcançar esses objetivos, o projeto prevê inicialmente o desenvolvimento de uma estrutura física totalmente mecânica, modular e desmontável, garantindo que componentes essenciais como as bobinas, o eixo e os ímãs fiquem visíveis e seguros para o manuseio dos estudantes em sala de aula. Em seguida, será feita a integração eletrônica com a programação de um microcontrolador ESP32 para realizar o controle digital e preciso da velocidade de rotação do motor em tempo real. Por fim, o protótipo passará por testes práticos de funcionamento em diferentes velocidades para análise de comportamento e sua eficiência pedagógica será avaliada e documentada por meio de demonstrações interativas diretamente com o público durante a IX IFTECH.

## Público-alvo e possibilidades de aplicação

- **Público-alvo:** Alunos do ensino médio e superior.
- **Áreas ou componentes curriculares:** disciplinas que envolvam física, circuitos e máquinas elétricas.
- **Conteúdos favorecidos:** física, campo elétrico, campo magnético, eletrodinâmica e eletromagnetismo.
- **Possibilidades de aplicação:** Aulas, oficinas, eventos, laboratórios, formação docente e formação técnica

## Resultados esperados

Com o desenvolvimento deste projeto, espera-se obter um protótipo funcional de um **motor elétrico do tipo DC escovado**, estruturalmente aberto, modular e totalmente desmontável, utilizando materiais de fácil acesso como filamento termoplástico impresso em 3D para o chassi, além de componentes comerciais visíveis como fios de cobre esmaltado para as bobinas de indução, ímãs permanentes de neodímio e conectores metálicos para o sistema de escovas. Esse recurso pedagógico visa favorecer significativamente a aprendizagem ao transformar teorias abstratas de eletromagnetismo e eletrodinâmica em experiências concretas, permitindo que os alunos manipulem o sistema e observem em tempo real a relação direta entre a corrente elétrica, a variação do campo magnético e a geração de torque. Por fim, as possibilidades de utilização e compartilhamento do material serão ampliadas por meio de uma documentação técnica detalhada, contendo esquemas eletrônicos e códigos-fonte, o que facilitará a replicação do projeto por outros educadores, sua adaptação para diferentes níveis de ensino e a ampla aplicação de protótipos semelhantes.

## Fundamentação e integração de conhecimentos

### Conhecimentos curriculares relacionados ao projeto

Campo elétrico, campo magnético, eletrodinâmica, eletromagnetismo e linhas de indução, força magnética e Lei de Lorentz, comutação em motores dc escovados

### Conhecimentos pedagógicos e metodológicos

- **O estudante poderá:** observar, tocar, desmontar e montar (com ele desligado), testar, ouvir e movimentar
- **O material ajuda a compreender:** conversão de energia elétrica em mecânica, indução de campos magnéticos, torque e sistema de comutação.
- **A dificuldade que procura reduzir é:** a abstração teórica de motores elétricos comerciais vedados, combatendo a memorização puramente mecânica de fórmulas ao tornar visíveis os fenômenos eletromagnéticos.
- **O conteúdo será apresentado por meio de:** objetos tridimencionais (peças), cores com indicações, som do motor em movimento e controles.
- **O estudante poderá demonstrar o que aprendeu por meio de:** montagem prática dos componentes do motor (rotor, estator, escovas e bobinas), testes ativos, além de explicações orais ou demonstrações no protótipo.
### Conhecimentos técnicos mobilizados

- **Programação:** Sistema de controle de velocidade por ESP32.
- **Modelagem:** Empregada no design (CAD) de todas as partes do protótipo, como o chassi de suporte do motor, o carretel do rotor para o enrolamento das bobinas, as garras de fixação dos ímãs de neodímio e o mecanismo de alinhamento das escovas de contato.
- **Impressão 3D:** Para realizar a manofatura das peças previamente modeladas (CAD) e garantindo uma estrutura modular leve, robusta, desmontável e sob medida para o acoplamento das partes do motor.
- **Corte CNC:** Corte da base do motor e do circuito elétrico.

### Integração dos conhecimentos na solução

A solução concreta surgiu da união direta entre a ciência, a engenharia e a pedagogia para abrir a "caixa preta" dos motores convencionais. O ponto de partida foi o currículo de física: as equações abstratas de eletromagnetismo e a Lei de Lorentz foram usadas para calcular e dimensionar as bobinas e os ímãs, transformando a teoria física no princípio ativo que gera o movimento do rotor. Para tirar essa ciência do papel, a tecnologia entrou como ferramenta de viabilização: a modelagem e a impressão 3D materializaram um motor DC escovado com estrutura totalmente exposta e desmontável, enquanto a eletrônica de potência e a programação no ESP32 garantiram o controle preciso de velocidade em tempo real. Por fim, toda essa engenharia foi moldada sob a perspectiva pedagógica do Desenho Universal para a Aprendizagem (DUA), resultando em um recurso altamente inclusivo, visual e tátil, onde o estudante deixa de ser um espectador passivo e passa a compreender a física na prática — tocando, montando, testando e vendo a ciência acontecer diante de seus olhos.

### Diferentes formas de aprendizagem

[Explique como o projeto contempla diferentes formas de representação, participação, interação ou expressão da aprendizagem.]
- **Formas de representação:** O eletromagnetismo deixa de ser uma teoria abstrata e assume características multissensoriais. Visualmente, o design aberto do motor DC escovado expõe o comutador e as escovas em movimento, enquanto cores contrastantes diferenciam os polos magnéticos; tatilmente, o aluno manipula a estrutura impressa em 3D e sente a atração física dos ímãs; e auditivamente, a frequência do som emitido pelo protótipo fornece um feedback imediato sobre a sua velocidade.
- **Formas de participação e interação:** O estudante atua como protagonista e investigador ativo do próprio aprendizado. Com o equipamento desligado, ele pode montar e desmontar os componentes para compreender a função mecânica de cada peça no sistema; ao ligá-lo, interage diretamente com o controle digital via ESP32, alterando os parâmetros e observando em tempo real como o motor e o campo magnético respondem à variação de potência aplicada.
- **Formas de ação e expressão:** A validação do conhecimento ocorre de maneira flexível, rompendo com as avaliações escritas tradicionais. O aluno demonstra o que aprendeu de forma prática, seja ao alinhar e montar o hardware corretamente para fazê-lo funcionar, ao operar o sistema de controle na bancada, ou ao explicar o fenômeno por meio de apresentações orais e desenhos esquemáticos do fluxo magnético.

### Referências consultadas

- HALLIDAY, David; RESNICK, Robert; WALKER, Jearl. Fundamentos de Física: Eletromagnetismo (Volume 3). Rio de Janeiro: LTC. 

- FITZGERALD, A. E.; KINGSLEY JR., Charles; UMANS, Stephen D. Máquinas Elétricas. Porto Alegre: AMGH.

- ESPRESSIF SYSTEMS. ESP-IDF Programming Guide / ESP32-S3 Technical Reference Manual. Disponível na página oficial da Espressif.

## Percurso metodológico do projeto SINAES

Os projetos vinculados ao SINAES adotam como referência o Processo de Desenvolvimento de Protótipos Acadêmicos, metodologia sistematizada pela proponente a partir da experiência acumulada na orientação e no acompanhamento de projetos acadêmicos voltados à criação de materiais didáticos e protótipos tecnológicos. A metodologia foi construída com base em práticas aplicadas, observadas e progressivamente aperfeiçoadas em projetos anteriores. Sua finalidade é oferecer aos estudantes um percurso acessível para organizar a identificação do problema, o planejamento técnico, a construção, os testes e a documentação das soluções. Embora dialogue com princípios do Processo de Desenvolvimento de Produtos apresentado por Rozenfeld et al. (2006), o percurso adotado pelo SINAES possui finalidade e organização próprias, adequadas ao contexto educacional e ao desenvolvimento de protótipos acadêmicos. 

O Processo de Desenvolvimento de Protótipos Acadêmicos está organizado em quatro etapas: 
1. **Geração do Conceito:** compreender o problema ou desafio de aprendizagem, identificar o público e definir a ideia inicial, a finalidade e as características gerais da solução.
2. **Planejamento e Especificação:** organizar o desenvolvimento do projeto, definir responsabilidades, identificar capacitações necessárias e selecionar materiais, tecnologias, ferramentas e recursos, considerando requisitos, cronograma e orçamento.
3. **Desenvolvimento Incremental:** construir a solução em partes, módulos ou versões sucessivas, realizando testes durante o processo e registrando dificuldades, decisões e modificações.
4. **Validação e Aperfeiçoamento:** verificar o funcionamento técnico e a contribuição da solução para a aprendizagem, analisar sua utilização por diferentes públicos, incorporar melhorias e organizar a documentação necessária ao compartilhamento e à replicação.

Essas etapas constituem uma orientação geral, e não uma sequência rígida. Conforme as características e necessidades de cada projeto, poderão ocorrer simultaneamente, ser retomadas ou receber procedimentos complementares. As adaptações realizadas deverão ser justificadas e registradas pelas equipes, com o acompanhamento dos professores responsáveis. 

A adoção desse percurso comum busca: 
- auxiliar os estudantes na organização do desenvolvimento;
- facilitar o acompanhamento dos projetos;
- registrar decisões, dificuldades e alterações;
- favorecer a integração entre conhecimentos curriculares e técnicos;
- orientar os testes e o aperfeiçoamento das soluções;
- padronizar a documentação sem eliminar a autonomia das equipes;
- facilitar o compartilhamento e a replicação dos resultados.

## Cronograma das etapas do desenvolvimento

| Etapa do PDP | Período planejado | Período realizado | Atividades desenvolvidas | Alterações, retornos ou sobreposições |
|---|---|---|---|---|
| Geração do conceito | [Data/período] | [Data/período] | [Atividades] | [Registre mudanças ou relação com outras etapas] |
| Planejamento e especificação | [Data/período] | [Data/período] | [Atividades] | [Registre mudanças ou relação com outras etapas] |
| Desenvolvimento incremental | [Data/período] | [Data/período] | [Atividades] | [Registre mudanças ou relação com outras etapas] |
| Validação e aperfeiçoamento | [Data/período] | [Data/período] | [Atividades] | [Registre mudanças ou relação com outras etapas] |

## Capacitações, tecnologias, materiais e orçamento

| Capacitação | Finalidade no projeto | Período | Situação |
|---|---|---|---|
| [Capacitação] | [Por que foi necessária] | [mm/aaaa] | [Prevista / Em andamento / Concluída] |
| [Capacitação] | [Por que foi necessária] | [mm/aaaa] | [Prevista / Em andamento / Concluída] |

### Tecnologias, ferramentas e equipamentos

| Tecnologia, ferramenta ou equipamento | Finalidade no projeto | Forma de acesso |
|---|---|---|
| [Software, impressora, máquina, instrumento etc.] | [Como será utilizado] | [Disponível no campus / Empréstimo / Aquisição / Outro] |
| [Software, impressora, máquina, instrumento etc.] | [Como será utilizado] | [Forma de acesso] |

### Materiais e orçamento

<!-- Preencha os valores somente quando houver necessidade de aquisição. -->

| Material ou componente | Quantidade | Finalidade | Disponibilidade | Valor estimado |
|---|---:|---|---|---:|
| [Item] | [Quantidade] | [Como será utilizado] | [Disponível / Necessita aquisição] | R$ [valor] |
| [Item] | [Quantidade] | [Como será utilizado] | [Disponível / Necessita aquisição] | R$ [valor] |
| **Total estimado** |  |  |  | **R$ [total]** |

## Artefatos do projeto

[Relacione os arquivos, documentos e demais produtos gerados durante o desenvolvimento. Acrescente ou exclua linhas conforme necessário.]

| Artefato | Descrição | Formato ou localização | Situação |
|---|---|---|---|
| Apresentação do projeto | [Breve descrição] | [`apresentacao/`](apresentacao/) | [Previsto / Em elaboração / Disponível] |
| Documentação | [Relatórios, fichas técnicas ou orientações] | [`documentacao/`](documentacao/) | [Situação] |
| Material didático | [Descrição do material] | [`materiais-didaticos/`](materiais-didaticos/) | [Situação] |
| Código-fonte | [Descrição do código] | [`codigos/`](codigos/) | [Situação] |
| Modelo 3D | [Descrição do modelo] | [`modelos-3d/`](modelos-3d/) | [Situação] |
| Imagens | [Registros autorizados] | [`imagens/`](imagens/) | [Situação] |
| Resultados | [Testes, avaliações ou evidências] | [`resultados/`](resultados/) | [Situação] |
| Outros | [Descrição] | [Arquivo, pasta ou endereço] | [Situação] |

> [!NOTE]
> **Possibilidades de replicação:** [Explique quais artefatos e orientações serão disponibilizados e como o material poderá ser reproduzido, utilizado ou adaptado por outras pessoas, escolas ou instituições. Indique também se a replicação exige equipamentos, materiais, conhecimentos técnicos ou condições específicas.]
> **Créditos e licenças:** [Informe a autoria dos arquivos, modelos, códigos, imagens e materiais externos utilizados.]

## Produções e participação em eventos

- [Evento, publicação, apresentação ou produção relacionada]
 
# Equipe
[Apresente as pessoas e instituições envolvidas e descreva objetivamente a participação de cada uma. Acrescente ou exclua linhas conforme necessário.]

| Categoria | Nome | Curso, setor ou instituição | Participação no projeto |
|---|---|---|---|
| Estudante | [Nome] | [Curso] | [Atividades e responsabilidades] |
| Estudante | [Nome] | [Curso] | [Atividades e responsabilidades] |
| Servidor | [Nome] | [Setor, área ou função institucional] | [Função no projeto] |
| Servidor | [Nome] | [Setor, área ou função institucional] | [Função no projeto] |
| Colaborador | [Nome] | [Instituição ou área de atuação] | [Forma de colaboração] |
| Instituição parceira | [Nome da instituição] | [Município ou setor] | [Forma de participação no projeto] |



## Instituição

**Instituto Federal do Paraná – Campus Paranavaí**

**Projeto SINAES – Soluções Inclusivas para Necessidades de Aprendizagem Específicas**

---

*Este repositório está em desenvolvimento. Os conteúdos serão atualizados conforme o andamento das atividades.*
