

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

