
# Motor Didático Desmontável

> Protótipo vinculado ao projeto SINAES – Soluções Inclusivas de Apoio ao Ensino e à Aprendizagem.

## Apresentação

O estudo do Eletromagnetismo e da Eletrodinâmica frequentemente esbarra na abstração de seus conceitos, já que os motores elétricos do nosso cotidiano são tratados como "caixas pretas" industriais fechadas, limitando o aprendizado à memorização passiva de fórmulas no quadro de giz. Para romper essa barreira, desenvolvemos o Motor Elétrico Didático Desmontável. Trata-se de um protótipo com design totalmente aberto e modular, controlado em tempo real por um ESP32 para regular sua velocidade de rotação. Alinhado aos princípios do Desenho Universal para a Aprendizagem (DUA), o projeto materializa forças magnéticas invisíveis em movimento físico palpável, transformando a sala de aula em um laboratório altamente prático, lúdico e inclusivo para os estudantes de nível médio e superior.

## Objetivo geral e objetivos específicos

### Objetivo geral

Esclarecer o funcionamento de motores elétricos escovados por meio da visualização e interação.

### Objetivos específicos

Para alcançar esses objetivos, o projeto prevê inicialmente o desenvolvimento de uma estrutura física totalmente mecânica, modular e desmontável, garantindo que componentes essenciais como as bobinas, o eixo e os ímãs fiquem visíveis e seguros para o manuseio dos estudantes em sala de aula. Em seguida, será feita a integração eletrônica com a programação de um microcontrolador ESP32 para realizar o controle digital e preciso da velocidade de rotação do motor em tempo real. Por fim, o protótipo passará por testes práticos de funcionamento em diferentes velocidades para análise de comportamento e sua eficiência pedagógica será avaliada e documentada por meio de demonstrações interativas diretamente com o público durante a IX IFTECH.

## Público-alvo e possibilidades de aplicação

- **Público-alvo:** alunos do ensino médio e superior.
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
- **O conteúdo será apresentado por meio de:** objetos tridimensionais (peças), cores com indicações, som do motor em movimento e controles.
- **O estudante poderá demonstrar o que aprendeu por meio de:** montagem prática dos componentes do motor (rotor, estator, escovas e bobinas), testes ativos, além de explicações orais ou demonstrações no protótipo.
### Conhecimentos técnicos mobilizados

- **Programação:** Sistema de controle de velocidade por ESP32.
- **Modelagem:** Empregada no design (CAD) de todas as partes do protótipo, como o chassi de suporte do motor, o carretel do rotor para o enrolamento das bobinas, as garras de fixação dos ímãs de neodímio e o mecanismo de alinhamento das escovas de contato.
- **Impressão 3D:** Para realizar a manufatura das peças previamente modeladas (CAD) e garantindo uma estrutura modular leve, robusta, desmontável e sob medida para o acoplamento das partes do motor.
- **Corte CNC:** Corte da base do motor e do circuito elétrico.

### Integração dos conhecimentos na solução

A solução concreta surgiu da união direta entre a ciência, a engenharia e a pedagogia para abrir a "caixa preta" dos motores convencionais. O ponto de partida foi o currículo de física: as equações abstratas de eletromagnetismo e a Lei de Lorentz foram usadas para calcular e dimensionar as bobinas e os ímãs, transformando a teoria física no princípio ativo que gera o movimento do rotor. Para tirar essa ciência do papel, a tecnologia entrou como ferramenta de viabilização: a modelagem e a impressão 3D materializaram um motor DC escovado com estrutura totalmente exposta e desmontável, enquanto a eletrônica de potência e a programação no ESP32 garantiram o controle preciso de velocidade em tempo real. Por fim, toda essa engenharia foi moldada sob a perspectiva pedagógica do Desenho Universal para a Aprendizagem (DUA), resultando em um recurso altamente inclusivo, visual e tátil, onde o estudante deixa de ser um espectador passivo e passa a compreender a física na prática — tocando, montando, testando e vendo a ciência acontecer diante de seus olhos.

### Diferentes formas de aprendizagem

- **Formas de representação:** O eletromagnetismo deixa de ser uma teoria abstrata e assume características multissensoriais. Visualmente, o design aberto do motor DC escovado expõe o comutador e as escovas em movimento, enquanto cores contrastantes diferenciam os polos magnéticos; tatilmente, o aluno manipula a estrutura impressa em 3D e sente a atração física dos ímãs; e auditivamente, a frequência do som emitido pelo protótipo fornece um feedback imediato sobre a sua velocidade.
- **Formas de participação e interação:** O estudante atua como protagonista e investigador ativo do próprio aprendizado. Com o equipamento desligado, ele pode montar e desmontar os componentes para compreender a função mecânica de cada peça no sistema; ao ligá-lo, interage diretamente com o controle digital via ESP32, alterando os parâmetros e observando em tempo real como o motor e o campo magnético respondem à variação de potência aplicada.
- **Formas de ação e expressão:** A validação do conhecimento ocorre de maneira flexível, rompendo com as avaliações escritas tradicionais. O aluno demonstra o que aprendeu de forma prática, seja ao alinhar e montar o hardware corretamente para fazê-lo funcionar, ao operar o sistema de controle na bancada, ou ao explicar o fenômeno por meio de apresentações orais e desenhos esquemáticos do fluxo magnético.

### Referências consultadas

- HALLIDAY, David; RESNICK, Robert; WALKER, Jearl. Fundamentos de Física: Eletromagnetismo (Volume 3). Rio de Janeiro: LTC. 

- FITZGERALD, A. E.; KINGSLEY JR., Charles; UMANS, Stephen D. Máquinas Elétricas. Porto Alegre: AMGH.

- ESPRESSIF SYSTEMS. ESP-IDF Programming Guide / ESP32-S3 Technical Reference Manual. Disponível na página oficial da Espressif.

## Cronograma das etapas do desenvolvimento

| Etapa do PDP | Período planejado | Período realizado | Atividades desenvolvidas | Alterações, retornos ou sobreposições |
|---|---|---|---|---|
| Geração do conceito | novembro/2025 | novembro/2025 | Conversa com professor de física | definir a ideia inicial |
| Planejamento e especificação | maio/2026 | junho/2026 | desenvolvimento de esboços e reuniões com a equipe que está realizando o projeto | mudança para um motor DC escovado  |
| Desenvolvimento incremental | segundo semestre 2026 |  | montagem do protótipo |  |
| Validação e aperfeiçoamento | segundo semestre 2026 |  | aperfeiçoamento do protótipo |  |

## Capacitações, tecnologias, materiais e orçamento

| Capacitação | Finalidade no projeto | Período | Situação |
|---|---|---|---|
| Aulas ESP-IDF | Introduzir e ensinar os alunos a programar o ESP32 por meio do VS Code usando a ESP-IDF | abril,maio/2026 | Concluída |
| Aula soldagem eletrônica | Ensinar a base da soldagem em componentes eletrônicos e placas de prototipação | junho/2026 | Concluída |
| Aula Impressão 3D | Ensinar fatiamento e comandos básicos com impressora 3D | junho/2026 | Concluída |
| Aula CNC | Ensinar a comandar e operar CNC | agosto/2026 | Prevista |

### Tecnologias, ferramentas e equipamentos

| Tecnologia, ferramenta ou equipamento | Finalidade no projeto | Forma de acesso |
|---|---|---|
| Impressora 3D | Impressão de partes do projeto | Disponível no campus |
| Fusion360 | Modelar as peças para impressão 3D ou corte CNC | Disponível no campus |
| CNC | Corte da base em MDF | Disponível no campus |
| VS Code | Programar usando a ESP-IDF por meio dele | Disponível sem custo |

### Materiais e orçamento


| Material ou componente | Quantidade | Finalidade | Disponibilidade | Valor estimado |
|---|---:|---|---|---:|
| ESP32 | 1 | Controle de velocidade | Adquirido na 1ª edição do projeto | |
| Fio de cobre esmaltado | 200g | Enrolamento bobina (rotor) | Adquirido na 1ª edição do projeto | |
| Filamento PETG | 500g | Impressão dos componentes | Adquirido na 1ª edição do projeto | |
| Ímã Neodímio 60x10x5 | 6 | Estator magnético | Adquirido na 1ª edição do projeto | |
| Chapa de mdf | 150x250x15 | base motor | Adquirido na 1ª edição do projeto |  |
| Rolamento | 1 | Segurar eixo | Adquirido na 1ª edição do projeto |  |
| inserts de latão | 6 | possibilitar utilização de parafusos | Adquirido na 1ª edição do projeto |  |
| parafusos | 6 | prender a estrutura a base | Adquirido na 1ª edição do projeto |  |
| Fonte | 1 | Alimentar a energia ao circuito | Adquirido na 1ª edição do projeto |  |
| **Total estimado** |  |  |  |  |

## Artefatos do projeto

| Artefato | Descrição | Formato ou localização | Situação |
|---|---|---|---|
| Apresentação do projeto | Motor elétrico didático desmontável | [`apresentacao/`](apresentacao/) | Disponível |
| Código-fonte | Controle de velocidade por esp | [`codigos/`](codigos/) | Em elaboração |
| Modelo 3D | Modelos 3Ds das diversas partes do motor | [`modelos-3d/`](modelos-3d/) | Em elaboração |
| Imagens | Fotos do motor e seu funcionamento | [`imagens/`](imagens/) | Previsto |
| Resultados | Exposição no IX IFTECH | [`resultados/`](resultados/) | Previsto |

> [!NOTE]
> **Possibilidades de replicação:** Ao término do projeto todos os materiais, modelos e códigos serão disponibilizados gratuitamente para replicação mediante a devida creditação, sem necessidade de licença ou autorização.
> **Créditos:** Informe a autoria dos arquivos, modelos, códigos, imagens e materiais externos utilizados.

## Produções e participação em eventos

- Inscrição na XIV IFTECH Campus Paranavaí, em outubro de 2026.
 
# Equipe

| Categoria | Nome | Curso, setor ou instituição | Participação no projeto |
|---|---|---|---|
| Estudante | Arthur Barbiratto Costa | Mecatrônica | Bolsista, estudante mentor do projeto |
| Estudante | Augusto Germano Ramos Meyer | Mecatrônica | Voluntário, estudante mentor do projeto |
| Estudante | João Baladelli Silva Knoll Cimardi | Mecatrônica | Desenvolvedor |
| Estudante | Maria Eduarda Gomes dos Santos | Mecatrônica | Desenvolvedor |
| Estudante | Mariana Vitória Gonçalves de Sá | Mecatrônica | Desenvolvedor |
| Estudante | Nadime Abdallah Borges | Mecatrônica | Desenvolvedor |
| Servidor | Eduardo Augusto Castelli Astrath | Docente E.B.T.T. – Núcleo da Base Nacional Comum/Física | Orientador/Demandante |
| Servidor | Daniela Eloise Flôr  | Docente E.B.T.T. – Informação e Comunicação/Informática | Coordenadora |

**Instituto Federal do Paraná – Campus Paranavaí**

---

*Este repositório está em desenvolvimento. Os conteúdos serão atualizados conforme o andamento das atividades.*
