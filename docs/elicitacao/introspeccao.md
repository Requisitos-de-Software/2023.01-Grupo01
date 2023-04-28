# Introspecção

## Introdução

A introspecção é uma técnica de elicitação de requisitos que consiste em, por meio de uma análise pessoal e profunda, levantar o que é indispensável para software de tal natureza. Sendo assim, o responsável por realizar essa estratégia deve devanear uma situação hipotética na qual se realizaria uma determinada tarefa.Isso posto, os requisitos elicitados estão demonstrados na Tabela 1 e na Tabela 2.

## Metodologia de Aplicação

O processo de introspecção foi realizado individualmente pelos alunos [Arthur de Melo](https://github.com/arthurmlv) e [Gabriel Campello](https://github.com/G16C). Após esse desenvolvimento individual os requisitos elicitados foram integrados em duas tabelas, Tabela 1 para Requisitos Funcionais e Tabela 2 para Requisitos não Funcionais.  No fim desse processo revisitamos o aplicativo escolhido pelo grupo e avaliamos se os requisitos elicitados estavam, ou não, presentes.

### Arthur de Melo

Para a execução desse método, imaginei-me em uma situação na qual eu desejasse participar de um evento na minha cidade. Portanto, eu, enquanto usuário e sem visualizar o aplicativo, imaginei as funções que seriam necessárias para a realização dessa tarefa. Também mantive em mente as possíveis dificuldades enfrentadas e o que o aplicativo deveria ofertar para a solução dessas.

### Gabriel Campello

O processo de introspecção para elicitação de requisitos consiste em imaginar-se na posição de usuário de certo produto sem vizualizá-lo. Quando o processo de elicitação é iniciado precisamos ter em mente quais requisitos (funcionais e não funcionais) o produto em questão deve apresentar. Tendo em vista que o produto escolhido para a disciplina trata-se de um aplicativo para compra de ingressos, imaginei-me como usuário, e tendo a noção prévia de aplicativos concorrentes,
iniciei o exercício. 

## Requisitos elicitados

### Funcionais
                            Tabela 1 - Requisitos Funcionais
| Tipo |             Descrição            |   ID   | Implementado |
|------|----------------------------------|--------| -----------|
| RF01 | O aplicativo filtra os eventos por Estado e por Município. | IS01 | Sim |
| RF02 | O aplicativo filtra os eventos por data e horário.  | IS02 | Não |
| RF03 | O aplicativo filtra os eventos por idade mínima de entrada.  | IS03 | Não |
| RF04 | O aplicativo permite realizar a compra do ingresso.  | IS04 | Sim |
| RF05 | O aplicativo permite o cadastro e o login do usuário.  | IS05 | Sim |
| RF06 | O aplicativo permite excluir cadastro.  | IS06 | Sim |
| RF07 | O aplicativo permite cadastrar métodos de pagamento.  | IS07 | Sim |
| RF08 | O aplicativo permite cancelar compras.  | IS08 | Sim |
| RF09 | O aplicativo possui um mecanismo de busca.  | IS09 | Sim |

### Não funcionais
                            Tabela 2 - Requisitos não Funcionais

| Tipo |             Descrição            |   ID   | Implementado
|------|----------------------------------|--------| ----- |
| RNF01 |  Deve possuir uma página que explicita os eventos da região selecionada.  | IS10 | Sim |
| RNF02 |  Todo evento disponibilizado na tela de busca deve aparecer a data, o local e o preço do ingresso.   | IS11 | Não |
| RNF03 |  Deve possuir uma tela de dúvidas frequentes e uma central de ajuda.  | IS12 | Sim |
| RNF04 |  Deve possuir uma tela de aviso sobre o início/fim de venda de ingressos para um dado evento.  | IS13 | Não |
| RNF05 |  Deve possuir espaço para a solicitação de atendimento especial para idosos/deficientes durante o processo de compra de ingressos.  | IS14 | Não |
| RNF06 |  Deve possuir uma tela para cadastro e login.  | IS15 | Sim |
| RNF07 |  Deve possuir uma área para os usuários reportarem erros de funcionamento do aplicativo.  | IS16 | Não |

## Histórico de Versões

Versão  | Data | Descrição | Autor(es) | Revisor(es)
---------- | -----  | ------ | ---------- | ----------
 1.0 | 26/04/2023 | Introdução e requisitos iniciais | [Arthur de Melo](https://github.com/arthurmlv) | [Gabriel Campello](https://github.com/G16C)
 1.1 | 26/04/2023 | Requisitos atualizados | [Gabriel Campello](https://github.com/G16C) | [Arthur de Melo](https://github.com/arthurmlv)
 1.2 | 27/04/2023 | Metodologia usada e verificação de requisitos | [Gabriel Campello](https://github.com/G16C) | [Arthur de Melo](https://github.com/arthurmlv)


## Bibliografia

>SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. **UnB Gama**, Brasília, 2023. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 26/04/2023.