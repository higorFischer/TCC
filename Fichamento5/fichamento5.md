#  A Methodology for Refactoring Legacy Code

Kaur, Amandeep, and Manpreet Kaur. "Analysis of code refactoring impact on software quality." MATEC Web of Conferences. Vol. 57. EDP Sciences, 2016.

## 1. Fichamento de Conteúdo

O artigo mostra dois tipos de refatorações principais. O *Replace Type Code With Subclass (SC)* e o *Replace Type code with state (ST)*. Esses métodos se utilizam de polimorfismo ao invés de condicionais para manter o código mais organizado e legíveis. É dito que é bem desafiante encontrar manualmente lugares de refatoração em projetos grandes, e que várias abordagens que temos hoje para poder encontrar refatorações ST falham por causa de restrições da abordagem. Com isso, é apresentado os desafios que são: Identificação dos locais de refatoração pois existe muitas variações e formatos que podem ser encontrados; A classificação, onde é necessário escolher qual o melhor método naquele momento para poder melhorar aquele trecho de código. Com isso, conseguimos ver na Fig4. quantas possibilidades de refatoração baseada na quantidade de lihas de código. Nesse caso, a utilidade está longe de ser muito impactante já que a quantidade de linhas de código está na casa do milhar (10K, 160K) e as oportunidades de refatoração está na casa da dezena (10, 6).
 
## 2. Fichamento Bibliográfico 

- Utilização do código em java e algumas bibliotécas como: jOcular, javaGeom.
- A identificação é uma parte complexa pois é necessário englobar todos os possíveis formatos que se pode encontrar um problema no código.
- A classificação é importante e difícil pois encontrar o melhor método de refatoração para um determinado trecho exige estudo e validações.

## 3. Fichamento de Citações 

- "Based on the chosen refactoring, the inheritance structure in the refactored code varies"
- "It is quite challenging to manually identify such refactoring opportunities in large projects. Recent works [5], [6] aim to automatically identify such opportunities"
- "Choosing the best suited refactoring between SC and ST requires checking whether the typecode is mutable [2]"
- "RCP refactoring uses two important refactorings underneath: i) replace type code with subclasses (SC), and ii) replace type code with state (ST). We now show an example to demonstrate typical RCP refactoring opportunities found in real world programs"
- " Even though object-oriented languages provide mechanisms to support polymorphism, programmers often use statechecking to simulate polymorphism, with the help of conditional (switch and if) statements. Such a practice leads to three main disadvantages :1) extendability: adding new behaviors to the subtypes requires changes to the conditional statements spread across many classes; 2) maintainability: modifying the existing behaviors or fixing bugs requires that the changes do not affect the code surrounding the state checking code; 3) readability: since the state-checking code may be spread across multiple classes, it becomes hard to reason about the behavior associated with each state"