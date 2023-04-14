`Atenção: Este template deve ser EXCLUÍDO do seu repositório.`


`No início do fchamento, você deve incluir, o título do Artigo sobre o qual o fichamento está sendo feito, exemplo:`

# Prioritising Refactoring using Code Bad Smells

Zhang, Min, et al. "Prioritising refactoring using code bad smells." 2011 IEEE Fourth International Conference on Software Testing, Verification and Validation Workshops. IEEE, 2011.

## 1. Fichamento de Conteúdo

Cada vez mais temos problemas mais complexos para ser resolvidos por meio de software. Com isso, profissionais que saibam criar códigos bons e a prova de erro são indispensáveis. Mas, como todos erram, precisamos achar formas cada vez mais faceis e intuitivas de encontrar possiveis problemas que possam acontecer com os códigos escritos. Esse artigo entra em alguns caminhos para poder encontrar possíveis pontos de falhas no código. Ele mostra 5 "bad smells". Estes são codigos com alguns padrões já mostrados por fowler, entre eles a duplicação de código. É utiliada duas bases de código para poder fazer as comparações e pesquisas. A base do Eclipse, *IDE (Integrated Software Environment)* Java, e Apache Commons, ambos em escrito em Java. No fim do artigo, é possível encontrar o melhor caminho para se começar a fazer a refatoração de código para que se resolva o problema mais crítico e "simples" de resolver.

## 2. Fichamento Bibliográfico 

- Fowler et al. [4] indentify 22 Code Bad Smells as indicators of refactoring (Pg. 1)
- This paper focuses on investigating six of Fowler et al.’s [4] Code Bad Smells. These six Code Bad Smells include Duplicate Code which is indicated by Fowler et al. [4] as the “number one in the stink parade”, and the other five Code Bad Smells (Data Clumps, Switch Statements, Speculative Generality, Message Chains, and Middle Man) which have never been studied in details by previous studies according to the results of our recent systematic literature review on Code Bad Smells [7]
- We used the CPD (Copy/Paste Detector) function of the PMD open source tool [12] to identify Duplicated Code from source code samples
- SVN is used to perform version control and JIRA is applied to trace bugs

## 3. Fichamento de Citações 

- "We applied a pattern-based Code Bad Smells detection tool, developed by ourselves, to detect the other five Code Bad Smells (Data Clumps, Switch Statements, Speculative Generality, Message Chains, and Middle Man)"
- Source code containing Duplicated Code should be refactored as a first priority. 
- Source code either containing more than one instance of locally created Message Chains or containing at least one locally created Message Chain whose length is more than 2 should be refactored as a second priority. 
- Source code containing the other types of Message Chains should then be considered for refactoring. 
- Source code containing only one of the Data Clumps, Switch Statements, Speculative Generality, or Middle Man Bad Smell should be refactored as a low priority. 