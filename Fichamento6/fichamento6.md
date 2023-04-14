#  A Methodology for Refactoring Legacy Code

Kaur, Amandeep, and Manpreet Kaur. "Analysis of code refactoring impact on software quality." MATEC Web of Conferences. Vol. 57. EDP Sciences, 2016.

## 1. Fichamento de Conteúdo

O artigo apresenta que conforme o código vai crescendo, cada vez mais fica difícil de manter a qualidade e uma refatoração continua. Isso faz com que a refatoração não seja sempre tão simples pois é necessário uma análise para ver os possíveis efeitos colaterais. Por isso é apresentado nesse ponto o *FaultBuster*. Essa ferramenta verifica o código de forma estática e acaba ajudando a encontrar possíveis problemas no código. É mostrado no final que esse produto ajudou a refatorar mais de 5 milhões de linha de códigos em diferentes empresas e para mais de 40 problemas diferentes. Foram resolvidos 11k problemas de códigos. Outras ferramentas similares que São citadas para outras formas são o *ReSharper* e o *CodeRusher* para o .NET. Com isso, essa ferramenta não seria possível trabalhar sozinha. São citadas *IDEs (Integrated Development Environment)* onde essas ferramentas são linkadas para poder auxiliar também no desenvolvimento continuo.
 
## 2. Fichamento Bibliográfico 
- Alguns métodos para resolver problemas são: AddEmptyString, ArrayIsStoredDirectly,AvoidReassigningParame, 
BooleanGetMethodName, MethodNamingConventions, NPathComplexity, TooManyMethods
- Existem várias ferramentas que são similares ao fault buster como ReSharper e Code Rush. Ambos para C# enquanto o faultBuster é para Java.
- Foi criado por 6 empresas e o Governo hungrariano. 

## 3. Fichamento de Citações 
- "During the design phase of the tool we consulted regularly with the developers of the participating companies about the refactoring transformations which they wanted to be available in the final product"
- "There are many IDEs available with automatic refactoring capabilities and they support typical code restructurings (e.g. renaming variables, classes) and some common refactorings from the Fowler catalog."
- "Compared to these tools, they all lack the feature of scanning the code and suggesting which refactorings to perform, which is one of the main advantages of FaultBuster"