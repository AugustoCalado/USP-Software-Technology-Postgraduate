# Assessment Review

## Question 1 - O que é qualidade de software?

Em minha opinião, qualidade de software é a caracteristica onde atende-se a maioria dos requisitos (funcionais e não funcionais) que representam as necessidades do usuário de maneira eficiente e eficaz, mitigando a quantidade de defeitos existentes, além das perspectivas dos stakeholders.

## Question 2 - O que é um processo? (`***`)
Processo é um conjunto de atividades que se relacionam e que a partir de um ou mais input geram um output e resultados esperado.

`(entrada --> processamento --> saída)`

## Question 3 - Quais são os pontos positivos e negativos do modelo agil para qualidade?
Um ponto positivo que podemos comentar é o feedback contínuo do usuário (graças a entrega incremental). Um ponto negativo é a dificuldade de é estimar o prazo do projeto baseado em numero de sprints.

## Question 4 - Defina uma métrica
> - descrição == "oque eu quero medir"
> - método == "onde eu vou para pegar esse valor?"

### Solução 1
Nome: Grau de dependencia externa de uma programa/aplicação
Descrição: Medir a quantidade de dependências externas (diretas e indiretas) que um programa/aplicação.
Unidade de medida: número de integrações com serviços e aplicações externas que uma aplicação possui (ni).
Método de coleta de medidas: Contabilização do número de chamadas e invocações de aplicações externas.
Periodicidade das coletas: A cada nova release da aplicação.
Divulgação: Desenvolvedores, QAs e SREs da aplicação que se está sendo medida.

### Solução 2
Nome:  Deslocamento Casa-Trabalho
Descrição: A métrica que mede o tempo gasto com uso de transporte público desde a estação/ponto de ônibus inicial até a estação/ponto de ônibus final. O propósito é ter uma média de tempo de deslocamento dos funcionários de uma empresa.
Unidade de medida: Horas
Método de coleta de medidas:Leitura de um cronômetro ativado no início e desativado no fim do deslocamento. O cronômetro mantém-se ativado mesmo durante a baldeação entre um ônibus e trem e vice-versa.
Periodicidade das coletas: Durante o dia útil da semana somente na ida de casa ao trabalho.
Divulgação (público-alvo): Gerência de RH da empresa.

## Question 5 - O que é teste de unidade, integração e validação (objetivos)? 
- Modelo V: linhas horizontais indicam os propósitos de verificação de cada teste.
- Assim:
  - Teste de Unidade tem por objetivo verificar se a especificação de módulos/classes está atendida.
  - Teste de Integração tem por objetivo verificar se a especificação da arquitetura representada pelo diagrama de classes está atendida
  - Teste de Validação tem por objetivo verificar se a especificação de requisitos representada pelos casos de uso está atendida.

## Question 6 - Conceitue Maturidade de Processos
Maturidade de um processo é caracterizado quando ele é:
- Definido
- Gerenciado
- Medido
- Controlado
- Efetivo (rotina).

Entende-se por Maturidade de Processos o grau/nível de excelência no qual uma organização realiza as suas atividades alinhadas com boas práticas de engenharia de software.

## Question 7 - Qual a relação entre nível de capacidade e nível de maturidade do CMMI?
- O nível de **capacidade** envolve o **grau em que um processo é executado seguindo as boas práticas do modelo**.
- O nível de **maturidade** envolve o **grau em que um conjunto de processos pré-definidos alcançam seu nível de capacidade correspondente**.

## O que é Qualidade de Software?
- É o resultado de um esforço planejado e constantemente avaliado.
- "não é de graça, não cai do céu"
- Deve atender às necessidades do usuário/cliente
  - Usuário: Facilidade
  - Clientes: Atendimento das necessidades 
  - Gerentes: Custo e prazo
  - Analista/Projetistas: Boas práticas
- Afeta
  - os custos de desenvolvimento
  - os prazos de entrega
  - a satisfação do usuário/cliente
 - Conformidade com:
  - necessidades (requisitos explícitos) do cliente
  - padrões de desenvolvimento
  - requisitos implícitos (boas práticas)
  - prazos e custos (estimativas)

### Mitos sobre a Qualidade
- As falhas de software são inevitáveis
- Os testes conduzem à qualidade
- A qualidade custa dinheiro

### Obstáculos para a Qualidade
- Cultura organizacional
- Complexidade das soluções
- Clientes não identificados e não esclarecidos
- Custos e prazos mal definidos
- Planejamento de projetos inexistente
- Dados de histórico de projetos inexistentes
- Processos de projeto inexistentes

### Fatores de Qualidade de Software
GOTO

### Qualidade x Produtividade
**TODO** Slide 18-1

## Qualidade do Produto
 - Conformidade com:
  - necessidades (requisitos explícitos) do cliente
  - padrões de desenvolvimento
  - requisitos implícitos (boas práticas)
  - prazos e custos (estimativas)

## Garantia de Qualidade
- Métodos
- Padrões
- Procedimentos
- Documentos
- Revisões
- Auditorias

## Gerência de Configuração
- Controles de mudanças
- Baselines

## Melhoria Contínua
- Foco no processo
- Prevensão de defeitos
- Kaizen (gerenciamento, desenvolvimento, evolução do software)

## Safisfação do Cliente
- Qualidade 
  - Conformidade com os requisitos do cliente
- Custo
  - Tão baixo quanto possível
- Defeitos
  - Disponibilidade e confiabilidade previstas
- Entrega
  - Dentro do prazo

## Engenharia de Software
- Métodos
- Técnicas 
- Ciclos de vida
- Gerenciamento
- Garantia de qualidade
- Testes

### Manutenção de Software
- Rastreabilidade
- Previsibilidade
- Qualidade da Mudanças

<br>

> Modificação de um produto de software após sua implantação para corrigir defeitos, melhorar o desempenho e outros atributos, ou adaptá-lo a novos ambientes.
>
> \- (ANSI / IEEE 1983)

#### Problemas Relacionados a Manutenção
- Pouca informação em relação ao processo de desenvolvimento
- Pouca informação em relação às manutenções anteriores
- **Dificuldade de entender os programas** feitos por outra pessoa
- **Baixa qualidade de documentação**
- Software não projetado para sofrer mudanças
- A manutenção não traz satisfação pessoa

#### Fatores de Manutenibilidade (Fatores que Contribuem ou Precisam Existir para Haver Manutenibilidade)
- Disponibilidade de pessoal qualificado
- Estrutura compreensível do sistema
- Operabilidade do sistema
- Uso de linguagens de programação
- adronizadas (c/regras de boa programação)
- Uso de sistemas operacionais padronizados
- Estrutura padronizada de documentação
- Disponibilidade de casos de testes

#### Processo de Manutenção
**GOTO**

#### Distribuição de Esforços
- Evolutiva : 50%
- Adaptativa : 25%
- Corretiva : 21%
- Preventiva : 4%

#### Modelos de Manutenção de Software
**GOTO**

### Testes
- Planos e especificações de testes
- Ambientes de teste
- Grupos de teste

### Modelos de Ciclo de Vida
- Principais tipos de modelo
  - Clássico ou Cascata
  - Modelo V
  - Prototipação
  - Espiral
  - XP
  - SCRUM

## Qualidade do Processo
- Atividades definidas
- Repetição
- Gerenciamento
- Dados de Processo

## Processo Genérico
- Inputs:
  - "entrada"
  - Regras: métodos, políticas, norma, diretrizes etc
  - Recursos: Materiais e Humanos

### Por que usamos processos?
- Melhoria do desempenho das organizações de software

### O que é um processo?
- Conjunto de passos (fases) para realizar uma tarefa
- Cada **fase tem critérios (regras)** específicos de entrada e saída
- As **fases definem as tarefas** e como desem ser realizadas

### Processos de Software
- Waterfall Model (Royce, 1970)
- Spiral Model (Boehm, 1988)
- Modelo de Reuso (Reifer, 1997)

#### Por que um processo de software é importante?
- Melhorar continuamente os processos através do aprendizado de novos métodos;
- Construir sistemas mais complexos e maiores no futuro; e
- Estruturar uma base histórica de projetos.

### Processo de Manutenção de Software
- Objetivo : Alterar o software existente e estender a sua vida enquanto for economicamente possível
- Características :
  - Inicia após a implantação do software.
  - Pode ser realizado por muitos anos.

## Modelos de Manutenção de Software
### Modelo de Boehm
- Entendimento do software existente
- Modificação do software existente
- Revalidação do software modificado

### Modelo de Osborn
- Determinação da necessidade de mudança
- Submissão do pedido de mudança
- Análise de requisitos
- Aprovação/rejeição do pedido de mudança
- Programação da atividade
- Projeto
- Codificação
- Revisão de código
- Teste
- Atualização da documentação
- Auditoria
- Instalação
- Aceitação do usuário
- Revisão pós-instalação
- Encerramento da atividade

### Modelo Orientado a Pedido
- **Controle de Pedidos**
  - Classificação dos pedidos
  - Análise de custo/benefício
  - Priorização
- **Controle de Mudanças**
  - Seleção e reprodução do problema
  - Análise de especificações e códigos
  - Projeto de mudanças e testes
  - Garantia de qualidade
- **Controle de Versões**
  - Determinação da versão
  - Construção da nova versão (edição, configuração, garantia de qualidade)
  - Testes especiais
  - Distribuição
  - Aceitação

## Software Quality Assurance (SQA)
- Um padrão planejado e sistematizado de todas as ações necessárias para fornecer **confiança** adequada a um item ou produto de acordo com **os requisitos especificados**.
- Um conjunto de atividades projetadas para avaliar o processo pelo qual os produtos são desenvolvidos

### Abrangência de SQA
- Métodos e ferramentas (análise, projeto, codificação, teste)
- Revisões técnicas formais (em todas as fases)
- Estratégias de teste (várias fases)
- Controle de documentação de software (geração e alteração)
- Procedimentos para garantir a adequação aos padrões de desenvolvimento de software
- Mecanismos de medição e divulgação

## Software Configuration Management (SCM)
- É um conjunto de atividades desenvolvido para administrar as mudanças em todo o ciclo de vida do software

### Ciclo de SCM
- Identificar a mudança
- Controlar a mudança
- Garantir que a mudança esteja sendo implementada adequadamente
- Relatar a mudança ás pessoas interessadas

### Configuração de Software
- Programas (fonte executável)
- Estrutura de dados (internos, externos)
- Documentos

### Baseline
- É definida como um marco de referência no desenvolvimento de software, **caracterizado pela entrega e aprovação de Itens de Configuração de Software (SCI)**.
- Os SCI podem sofrer mudanças, mas serão feitas através de um procedimento específico e formal para avaliar e verificar cada mudança.

### Itens de Configuração de Software (SCI)
- Especificação de Sistema
- Plano de Projeto de Software
- Especificação de Requisitos de Software (+protótipo)
- Manual Preliminar do usuário
- Especificação do projeto
- Listagem de código fonte
- Plano e procedimentos de teste
- Manuais (operação, sistema, manutenção, treinamento, instalação)
- Programa executável 
- relatórios (operações, testes, Manutenção)
- Padrões e procedimentos (Eng. Software)

### Processos de Controle de Mudança
- A necessidade de mudança é reconhecida
- O usuário submete um Pedido de Mudança
- O desenvolvedor avalia
- É gerado um Relatório de Mudança
- O gerente de configuração toma decisão
- Alternativa 1: O pedido de mudança é rejeitado
  - o usuário é informado
- Alternativa 2: O pedido é aceito
  - Uma ordem de mudança de engenheria é gerada
  - Pessoas são designadas aos objetos de configuração (partes constituintes dos SCI)
  
  ### Controle de Sincronização e Acesso
  ![image](https://user-images.githubusercontent.com/17462762/134663255-72abf1c4-ddb1-40d0-b318-49b3a28231f8.png)

## Computer Aided Software Engineering - CASE
- As ferramentas CASE envolvem:
  - Cada etapa do processo de engenharia de software
  - Atividades que são aplicadas em todo o processo

### Tipos de CASE
- Administrativos
  - Planejamento de sistemas comerciais (workflow)
  - Gerenciamento de projetos
  - Planejamento de projetos (esforço, custos e programação)

- Técnicos
  - Análise, projeto, codificação, teste
  - Integração, prototipação
  - Manutenção (eng. reversa e reengenharia)

### Características Gerais dos CASE
- Fracionamento da complexidade
- Adequação a um público diversificado
- Mais baratas que a construção em si
- Verificáveis (rastreabilidade)
- De fácil manutenção (especificação e
- rojetos)
- Orientação gráfica

## Métricas de Software
- O software é medido para:
  - Indicar a qualidade do produto
  - Avaliar a produtividade das pessoas
  - Avaliar os benefícios (produtividade e qualidade) derivados de novos métodos e ferramentas de software
  - Formar uma linha básica de estimativas
  - Ajudar a justificar os pedidos de novas ferramentas ou treinamento adicional

- Métrica
  - Caracterização quantitativa do software baseada na teoria de medições (descrição matemática de escalas, medidas e métodos de medições). Tal teoria deve esclarecer se uma medida específica é apropriada em cada situação. (Henderson-Sellers, B. “Object-Oriented Metrics - Measures of Complexity” - Prentice Hall, 1996.)
- Medida
  - Grandeza determinada que serve de padrão para avaliação de outras grandezas. (Dicionário)
  - Fornece uma indicação quantitativa de algum atributo de um produto ou processo. (Pressman)
- Medição
  - Ato ou efeito de medir
  - Ato de determinar uma medida (Pressman)

### Medidas Diretas
- Custo e esforço despendido
- Linhas de código
- Velocidade de execução
- Tamanho de memória
- Número de defeitos

### Medidas Indiretas
- Funcionalidade
- Complexidade
- Eficiência
- Confiabilidade
- Manutenibilidade
- Qualidade

### Function Point 
**TODO**
- https://www.javatpoint.com/software-engineering-functional-point-fp-analysis
- https://www.geeksforgeeks.org/software-engineering-calculation-of-function-point-fp/

### McCabe Metric
- É uma métrica que dá uma medida quantitativa da complexidade lógica de um programa
- Baseia-se na complexidade ciclomática dado por um grafo de programa. (Nº de caminhos através de um programa)
- O grafo descreve o fluxo de controle

![image](https://user-images.githubusercontent.com/17462762/134666051-a059628c-83bd-4387-8d67-149cf3d19059.png)

- Em um grafo G fortemente conectado, V(G) é igual ao número máximo de caminhos linearmente independentes
- V(G) = 10 (limite máximo na prática)

#### Propriedades
- V (G) >= 1
- V (G) é o nº máximo de caminhos linearmente independentes em G; é o tamanho de um conjunto básico de caminhos
- Inserindo ou retirando statements funcionais em G não afeta V(G)
- G tem somente um caminho see V (G) = 1
- Inserindo um novo ramo em G, V (G) aumenta um (1)
- V (G) depende somente da estrutura de decisão (fluxo de controle) de G

## Fatores de Qualidade de Software
- Os fatores de qualidade se dividem em:
  - Os que podem ser medidos diretamente (nº de erros/linhas de código, etc.)
- Os que só podem ser avaliados indiretamente (usabilidade, manutenibilidade, etc.)

### Revisão Técnica Formal
- RTF é uma atividade de garantia de qualidade de software executada por profissionais de engenharia de software
- Em qualquer fase do ciclo de vida do software
- **Objetivos**
  - **Descobrir** **defeitos** de função, lógica ou implementação em qualquer representação do software
  - Verificar se o software que se encontra sob revisão **atende aos requisitos**
  - Garantir que o software tenha sido representado de acordo com padrões pré-definidos
  - Obter um software que seja desenvolvido uniformemente
  - Tornar os projetos mais administráveis
- Registro de Revisão
  - Lista de questões de revisão
  - identifica as áreas problemáticas do produto
  - serve como um “checklist” de itens de ação que irá orientar o produtor quando as correções forem feitas
- Decisões
  - Os participantes aceitam o produto sem modificações adicionais
  - Os participantes rejeitam o produto devido a defeitos graves
  - Os participantes aceitam provisoriamente (defeitos menores foram encontrados e devem ser corrigidos)

#### Roteiro para uma RTF
- Atribuições do Líder
  - Preparação
  - Agendamento
  - Realização
  - Encerramento
- Recomendações para os Revisores
  - Esteja preparado
  - Seja cooperativo
  - Observe a linguagem
  - Seja educado
  - Levante questões, não os resolva
  - Evite discussões de estilo
- Recomendações para os Revisores
  - Considere o padrão de projeto utilizado em relação ao estabelecido pela Organização
  - Considere questões técnicas
  - Não avalie o(s) produtor(es)
- Recomendações para o Líder
  - Destaque os objetivos, regras e procedimentos da revisão
  - Destaque os resultados da revisão anterior
  - Eleja uma equipe qualificada para a revisão
  - Destaque a importância da preparação prévia dos revisores
  - Coordene a obtenção de infraestrutura adequada para a revisão
  - Anote em separado os pontos que estejam fora do escopo da revisão
  - Desencoraje comportamentos inadequados dos revisores
  - Destaque o resultado das revisões
  - Distribua uma cópia do registro da revisão o mais rápido possível para os revisores 

## O que são Defeitos?
- São injetados no programa por pessoas
- através de sus erros/enganos
- Algo que está errado no programa
  - Sintaxe
  - digitação
  - pontuação
  - instrução de comando

### Onde o defeito pode ocorrer?
- Programas
- Arquitetura do programa
- Requisitos
- Especificações
- Documentos em geral

### Natureza do Defeito
- Pode ser identificado
- Pode ser descrito
- Pode ser contado

### Modelo de Ampliação de Defeitos - IBM
**TODO** -  Slide 106-1

## Validação e Verificação (V&V)
- A atividade de teste é um elemento dentro de um conceito mais amplo chamado V&V
- Verificação: "Estamos construindo certo o produto?"
- Validação: "Estamos construindo o produto certo?"
- Verificação
  - Tentativa de achar defeitos através da execução de um programa por teste ou ambuiente simulado (Myers)
- Validação 
  - Tentativa de achar defeitos através da execução de um programa em ambiente real
- Depuração: Diagnóstico da natureza precisa de um defeito conhecido e então corrigi-los
- Abrange muitas atividades de SQA:
  - Revisões técnicas formais
  - Auditorias de configuração e qualidade
  - Monitoração de desempenho
  - Simulação
  - Estudo de viabilidade
  - Revisão de documentação
  - Testes em geral

### Teste
- Um bom caso de teste é aquele que tem uma elevada probabilidade de revelar um defeito ainda não descoberto
- Um teste bem-sucedido é aquele que revela um defeito ainda não descoberto
- Teste
  - Processo de execução de um programa (ou parte) com a intenção de achar defeitos (Myers)
- Dijkstra (1969)
  - "Program testing can be used to show the presence of bugs, but never their absence"
- "Não se pode testar qualidade"
- "Se ela não estiver lá antes de se iniciar os testes, não estará lá ao seu término"

### Visão geral dos testes
![image](https://user-images.githubusercontent.com/17462762/134670067-b8f22d5d-abff-4206-adc5-9338eb4de9ef.png)

### Documentos Para Realização de Testes

