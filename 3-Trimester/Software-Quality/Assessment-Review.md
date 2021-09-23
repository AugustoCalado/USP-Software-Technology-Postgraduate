

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
