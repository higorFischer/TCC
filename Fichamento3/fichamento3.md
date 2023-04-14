`Atenção: Este template deve ser EXCLUÍDO do seu repositório.`


`No início do fchamento, você deve incluir, o título do Artigo sobre o qual o fichamento está sendo feito, exemplo:`

#  A Methodology for Refactoring Legacy Code

`Aqui deve-se colocar uma linha com a referência completa do artigo, exemplo:`

Kaur, Amandeep, and Manpreet Kaur. "Analysis of code refactoring impact on software quality." MATEC Web of Conferences. Vol. 57. EDP Sciences, 2016.

## 1. Fichamento de Conteúdo

`Aqui deve-se incluir uma análise geral do artigo em um parágrafo de  8 a 15 linhas. É um texto corrido nas palavras da pessoa que está fazendo o fichamento (não deve ter cópia literal de conteúdo do artigo). Pode conter opinião do leitor a partir do texto. Idealmente deve mencionar o contexto tratado pelo artigo, o problema que ele tenta resolver, o(s) método(s) que ele emprega e o(s) resultado(s) que obtém. O texto deve ser uma forma simples que resume o que se entendeu do artigo. Exemplo:`

O artigo mostra como a refatoração de código é importante e como isso afeta a segurança do código. É dito que não se tem muitos estudos em cima das refatorações voltadas a segurança após as mudanças. É mostrado todos os 68 tipos de refatoração e após isso foi escolhido somente 5 para poder fazer a validação dos dados. As métricas escolhidas para poder entender a vulnerabilidade que uma refatoração pode gerar são:
*Classified Operation Accessibility (COA)*; *Classified Instance Data Accessibility (CIDA)*; and *Classified ClassData Accessibility (CCDA)*. Essas métricas são testadas em cima das seguintes refatorações: *Extract Method (EM)*; *Inline Method (IM)*; *Encapsulate Field (EF)*; *Remove Setting Method (RSM)*; *Hide Method (HM)*. Após serem feitas as validações, é chegada a conclusão que os desenvolvedores não podem chegar executando e fazendo cegamente refatorações e sim que é necessário tirar um tempo para poder avaliar os prós e contras, além dos metodos de refatoração, já que isso irá lhes dar um melhor entendimento do problema e poderá diminuir o custo de manutenção e outros problemas que possam ser causados. 
 
## 2. Fichamento Bibliográfico 

`Nesta parte, ideias e conceitos que aparecem no artigo devem ser organizados e descritos com as palavras do leitor, e, idealmente, devem ser indicadas as páginas onde aparecem no texto. Deve-se incluir de 3 a 6  itens. Exemplo:`
• Extract Method (EM): This technique creates a new method from a complex and long method by 
extracting a set of statements that can be put together into the new method.
• Inline Method (IM): This technique is used when a method body is more obvious than the method 
itself. It Replace calls to the method with the method’s content and delete the method itself.
• Encapsulate Field (EF): This technique is used to restrict the access to the data by changing the 
accessibility for the public fields. It changes the public field to the private filed and provides two accessors’ 
methods.
• Remove Setting Method (RSM): It is used to removes any setting method for a particular field.
• Hide Method (HM): It is used to change the visibility of a method by making the method private.

## 3. Fichamento de Citações 

`Aqui devem ser adicionadas as frases mais importantes que aparecem no artigo. Deve ser uma transcrição exata de como estão escritas no artigo, devem ficar entre aspas. Esse fichamento é importante para que possa identificar facilmente como o autor do artigo descreveu um conceito, teoria, método, resultado etc. Deve-se incluir de 3 a 6  itens. Exemplo:`
• "COA = CPM/CM (1)
COA is calculated by dividing a number of Classified Public Methods (CPM) by the total number of 
Classified Methods (CM) in a class. "
• "CIDA= CIPA/CA (2)
CIDA is calculated by dividing a number of Classified Instance Public Attributes (CIPA) by the total number 
of Classified Attributes (CA) in a class."
• "CCDA= CCPA/CA (3)
CCDA is calculated by dividing the number of Classified Class Public Attributes (CCPA) into the total 
number of Classified Attributes (CA) in a class."