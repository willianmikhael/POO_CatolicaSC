 <div align="center">
 <img src="https://user-images.githubusercontent.com/111321384/225424307-c1475755-8810-4fd3-aa1f-64c7f67c6f65.png" />
 </div>

### Disciplina: Programação Orientada a Objetos
### Professor: [Glauco Scheffel](https://www.linkedin.com/in/glaucoscheffel/)
### Aluno: [Willian Mikhael da Cunha](https://www.linkedin.com/in/willianmikhael/)

#### 15/03/2023

### ⚠️ Atenção isso é um experimento, todas as respostas são provenientes do [ChatGPT](https://chat.openai.com/chat)
#

## O que é programação orientada a objetos?
Programação Orientada a Objetos (POO) é um paradigma de programação que se concentra na criação de objetos que têm propriedades e métodos que permitem interagir com outros objetos. Esses objetos podem ser vistos como entidades independentes que têm um estado e um comportamento, e podem interagir com outros objetos por meio de mensagens ou chamadas de método.

Na POO, a ênfase é colocada na organização e estruturação do código, tornando-o mais modular e fácil de entender e manter. Os objetos são criados a partir de classes, que funcionam como modelos ou planos para a criação dos objetos. Dessa forma, a POO permite que o código seja reutilizável e escalável, permitindo a criação de programas mais complexos e sofisticados.

## Quais são os pilares da programação orientada a objetos?
Os pilares da Programação Orientada a Objetos (POO) são quatro: Abstração, Encapsulamento, Herança e Polimorfismo.

A Abstração permite que os objetos representem conceitos do mundo real, abstraindo os detalhes irrelevantes e se concentrando nas características que são importantes para a solução do problema. O Encapsulamento protege os dados e comportamentos internos do objeto, permitindo que ele possa ser utilizado de forma segura e consistente. A Herança permite que uma classe herde características e comportamentos de outra, tornando o código mais eficiente e permitindo a criação de hierarquias de classes. Já o Polimorfismo permite que um objeto possa ser tratado de formas diferentes, dependendo do contexto em que ele é utilizado, aumentando a flexibilidade e a reutilização do código. Juntos, esses pilares são fundamentais para a criação de programas robustos, modulares e flexíveis.

## O que é uma classe em Java?
Em Java, uma classe é um modelo ou plano para a criação de objetos. Ela é definida por meio de variáveis de instância, que representam o estado do objeto, e métodos, que definem o comportamento do objeto. Cada objeto criado a partir de uma classe é chamado de instância ou objeto daquela classe.

Uma classe em Java é composta por três partes principais: declaração de variáveis de instância, construtores e métodos. As variáveis de instância representam o estado do objeto, como nome, idade, endereço, etc. Os construtores são métodos especiais que são usados para criar novas instâncias da classe, inicializando suas variáveis de instância. Os métodos são usados para definir o comportamento do objeto, como calcular uma média, exibir uma mensagem, ou realizar qualquer outra ação que seja relevante para o objeto.

## Como criar um objeto a partir de uma classe em Java?
Para criar um objeto a partir de uma classe em Java, é necessário seguir alguns passos simples. Primeiro, deve-se criar uma instância da classe usando a palavra-chave "new" e o construtor da classe. O construtor é um método especial que é chamado no momento da criação do objeto e é responsável por inicializar as variáveis de instância.

Por exemplo, suponha que temos uma classe chamada "Pessoa" com variáveis de instância para o nome e a idade. Para criar um objeto dessa classe, podemos fazer o seguinte:
```java
Cria uma instância da classe Pessoa
Pessoa pessoa1 = new Pessoa();

Define o nome e a idade da pessoa
pessoa1.nome = "João";
pessoa1.idade = 30;
```
Neste exemplo, a variável "pessoa1" é uma instância da classe "Pessoa" e foi criada usando a palavra-chave "new" e o construtor padrão da classe. Em seguida, as variáveis de instância da classe são definidas usando a notação de ponto. É importante lembrar que as variáveis de instância devem ser definidas como públicas (public) para que possam ser acessadas fora da classe.

## O que faz a palavra new no Java?

Em Java, a palavra-chave "new" é usada para criar uma nova instância de uma classe. Quando usada, ela reserva um espaço de memória na área heap para a nova instância e chama o construtor da classe para inicializar as variáveis de instância.

O operador "new" é usado para criar objetos e instanciar classes em Java. Ele é geralmente seguido pelo nome da classe e pelos parênteses, que podem ou não conter parâmetros para o construtor da classe. A palavra-chave "new" é uma das mais importantes em Java, pois permite que os objetos sejam criados dinamicamente durante a execução do programa.

## Quais as semelhanças entre Java e C?

Java e C são duas linguagens de programação que possuem algumas semelhanças em sua sintaxe e funcionalidades. Ambas são linguagens de programação imperativas, compiladas e tipadas estaticamente, o que significa que o tipo das variáveis deve ser definido no momento da sua declaração e não pode ser alterado durante a execução do programa.

Além disso, ambas as linguagens possuem estruturas de controle de fluxo semelhantes, como loops e condicionais, bem como suporte a operações aritméticas e lógicas. No entanto, enquanto C é uma linguagem de baixo nível, que exige que o programador gerencie manualmente a alocação de memória e outros detalhes de implementação, Java é uma linguagem de alto nível que possui recursos como gerenciamento automático de memória e suporte a orientação a objetos.

## Quais as diferenças entre Java e C?

Java e C são duas linguagens de programação com algumas diferenças importantes. Enquanto C é uma linguagem de baixo nível, que exige que o programador gerencie manualmente a alocação de memória e outros detalhes de implementação, Java é uma linguagem de alto nível que possui recursos como gerenciamento automático de memória e suporte a orientação a objetos.

Outra diferença importante é que o código em Java é executado em uma máquina virtual (JVM), enquanto o código em C é compilado diretamente para o sistema operacional. Isso significa que programas em Java são mais portáteis e podem ser executados em qualquer plataforma que possua uma JVM, enquanto programas em C precisam ser compilados separadamente para cada plataforma de destino. Além disso, Java possui bibliotecas padrão mais extensas e suporte a recursos como multithreading e segurança de rede, que não estão disponíveis em C.

## O que é a classe AtividadeCinco.InputReader e qual é a sua função no programa?

A classe AtividadeCinco.InputReader é uma classe auxiliar que permite ler valores de entrada do usuário por meio do console. Sua função no programa é fornecer um método para ler um valor double com uma mensagem de prompt para o usuário.

## Qual é a finalidade do método readDouble na classe AtividadeCinco.InputReader?

O método readDouble() imprime a mensagem de prompt no console e, em seguida, lê um valor double digitado pelo usuário e retorna esse valor. O construtor da classe AtividadeCinco.InputReader inicializa um objeto Scanner para ler a entrada do usuário a partir do console.
## O que é a interface AtividadeCinco.PaymentType e como ela é utilizada no programa?

A interface AtividadeCinco.PaymentType é uma interface que define um contrato para implementações de tipos de pagamento. A interface possui dois métodos: getName(), que retorna o nome do tipo de pagamento, e isValid(), que retorna um booleano indicando se o tipo de pagamento é válido.

No programa, a interface AtividadeCinco.PaymentType é implementada por quatro classes: AtividadeCinco.PixPayment, AtividadeCinco.CreditPayment, AtividadeCinco.BoletoPayment e AtividadeCinco.InvalidPayment. Cada uma dessas classes implementa os métodos getName() e isValid() de acordo com as regras para o tipo de pagamento correspondente. O método selectPaymentType() da classe AtividadeCinco.PaymentTypeSelector retorna um objeto de uma dessas classes, dependendo da opção selecionada pelo usuário.

A utilização da interface AtividadeCinco.PaymentType permite que diferentes tipos de pagamento sejam facilmente adicionados ou removidos do programa, desde que sigam o contrato definido pela interface. Além disso, o uso de uma interface torna o programa mais flexível, permitindo que as implementações dos tipos de pagamento sejam trocadas sem afetar o restante do código.

## Como a classe AtividadeCinco.PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado?

A classe AtividadeCinco.PaymentTypeSelector é responsável por exibir as opções de pagamento disponíveis para o usuário e ler a escolha do usuário a partir do console.

O método selectPaymentType() da classe AtividadeCinco.PaymentTypeSelector exibe uma mensagem com as opções de pagamento e lê um valor inteiro digitado pelo usuário. Em seguida, dependendo do valor lido, o método retorna um objeto de uma das classes que implementam a interface AtividadeCinco.PaymentType: AtividadeCinco.PixPayment, AtividadeCinco.CreditPayment, AtividadeCinco.BoletoPayment ou AtividadeCinco.InvalidPayment.

Assim, a classe AtividadeCinco.PaymentTypeSelector é responsável por traduzir a escolha do usuário em um objeto do tipo AtividadeCinco.PaymentType, que é utilizado posteriormente para identificar o tipo de pagamento selecionado e validar a opção escolhida. Essa abordagem permite que diferentes tipos de pagamento sejam facilmente adicionados ou removidos do programa, sem a necessidade de modificar o restante do código.

## Qual é a relação entre a classe AtividadeCinco.PaymentTypeSelector e as classes AtividadeCinco.PixPayment, AtividadeCinco.CreditPayment e AtividadeCinco.BoletoPayment?

A classe AtividadeCinco.PaymentTypeSelector é responsável por criar objetos das classes AtividadeCinco.PixPayment, AtividadeCinco.CreditPayment e AtividadeCinco.BoletoPayment. Ela utiliza um switch para identificar a opção escolhida pelo usuário e, a partir disso, retorna um objeto do tipo AtividadeCinco.PaymentType correspondente. Cada uma dessas classes implementa a interface AtividadeCinco.PaymentType e fornece uma implementação para os métodos getName() e isValid() definidos na interface.

Assim, a relação entre a classe AtividadeCinco.PaymentTypeSelector e as classes AtividadeCinco.PixPayment, AtividadeCinco.CreditPayment e AtividadeCinco.BoletoPayment é que a AtividadeCinco.PaymentTypeSelector utiliza essas classes para criar objetos que representam os diferentes tipos de pagamento disponíveis. Cada uma dessas classes encapsula a lógica necessária para validar o tipo de pagamento e retornar o nome correspondente, o que permite que o programa possa facilmente adicionar ou remover tipos de pagamento sem alterar a lógica principal do programa.

## O que é polimorfismo e como ele é utilizado no programa?

Polimorfismo é um conceito fundamental da orientação a objetos que permite que objetos de classes diferentes possam ser tratados de forma uniforme, utilizando uma interface comum. Isso significa que objetos de diferentes classes podem ser referenciados pela mesma classe ou interface, possibilitando um código mais genérico, flexível e reutilizável.

No programa apresentado, o polimorfismo é utilizado por meio da interface AtividadeCinco.PaymentType, que define um conjunto de métodos que as classes AtividadeCinco.PixPayment, AtividadeCinco.CreditPayment, AtividadeCinco.BoletoPayment e AtividadeCinco.InvalidPayment implementam. O método selectPaymentType() da classe AtividadeCinco.PaymentTypeSelector retorna um objeto do tipo AtividadeCinco.PaymentType, que pode ser uma instância de qualquer uma dessas classes, e é tratado de forma uniforme em outras partes do código, sem a necessidade de conhecer a implementação específica de cada classe.

Dessa forma, o polimorfismo permite que o código do programa seja mais genérico e flexível, possibilitando a inclusão de novas classes que implementem a interface AtividadeCinco.PaymentType sem que isso afete o restante do código. O uso de polimorfismo também facilita a manutenção e evolução do programa, uma vez que a lógica relacionada a cada tipo de pagamento pode ser alterada independentemente da lógica principal do programa.

## Qual é a finalidade do método getName na interface AtividadeCinco.PaymentType e nas classes que a implementam?

O método getName na interface AtividadeCinco.PaymentType e nas classes que a implementam tem como finalidade retornar o nome do tipo de pagamento. Cada classe que implementa a interface AtividadeCinco.PaymentType tem sua própria implementação para o método getName, que retorna o nome específico do tipo de pagamento que a classe representa.

A finalidade desse método é permitir que o nome do tipo de pagamento seja exibido ao usuário, facilitando a interação com o programa e tornando a saída mais informativa. Além disso, a utilização do método getName em conjunto com o polimorfismo permite que o código do programa seja mais genérico e flexível, já que o nome do tipo de pagamento pode ser obtido de forma uniforme para qualquer objeto que implemente a interface AtividadeCinco.PaymentType. Dessa forma, é possível adicionar ou remover tipos de pagamento sem alterar a lógica principal do programa, e o código do programa é mais fácil de ser mantido e evoluído.

## O que é a classe Scanner e como ela é utilizada no programa?

A classe Scanner é uma classe da biblioteca padrão do Java que permite ler dados de entrada a partir de um objeto InputStream. Ela é utilizada no programa para ler entradas do usuário, tanto no método readDouble da classe AtividadeCinco.InputReader quanto no método selectPaymentType da classe AtividadeCinco.PaymentTypeSelector.

No método readDouble, a classe Scanner é utilizada para ler um valor decimal digitado pelo usuário. Já no método selectPaymentType, ela é utilizada para ler uma opção digitada pelo usuário a partir do console. Ao chamar o método nextInt da classe Scanner, o programa espera que o usuário digite um número inteiro, que é então utilizado para selecionar o tipo de pagamento a ser utilizado. Em ambos os casos, a classe Scanner permite que o programa leia dados de entrada a partir do console de forma fácil e eficiente, sem a necessidade de implementar código de leitura de entrada personalizado.

## O que é uma exceção e como ela é tratada no método selectPaymentType da classe AtividadeCinco.PaymentTypeSelector?

Uma exceção é um evento que ocorre durante a execução de um programa que interrompe o fluxo normal de execução. Ela pode ser causada por diversos fatores, como erros de programação, erros de entrada ou falhas no sistema. Quando uma exceção é lançada, o programa deve lidar com ela para evitar que o programa pare de funcionar inesperadamente ou produza resultados incorretos.

No método selectPaymentType da classe AtividadeCinco.PaymentTypeSelector, uma exceção pode ser lançada se o usuário digitar uma opção inválida ao selecionar o tipo de pagamento. Nesse caso, a exceção será lançada pelo método nextInt da classe Scanner, que espera que o usuário digite um número inteiro. Para lidar com essa exceção, o método selectPaymentType utiliza um bloco try-catch, que captura a exceção e retorna um objeto da classe AtividadeCinco.InvalidPayment, que implementa a interface AtividadeCinco.PaymentType e representa um tipo de pagamento inválido. Dessa forma, o método selectPaymentType garante que sempre retornará um objeto da classe AtividadeCinco.PaymentType, evitando que o programa pare de funcionar inesperadamente ou produza resultados incorretos.

## Como seria possível adicionar um novo tipo de pagamento ao programa?

Para adicionar um novo tipo de pagamento ao programa, seria necessário criar uma nova classe que implemente a interface AtividadeCinco.PaymentType. Essa classe deveria definir os métodos getName e isValid de acordo com as regras de negócio do novo tipo de pagamento.

Em seguida, seria necessário modificar o método selectPaymentType da classe AtividadeCinco.PaymentTypeSelector para incluir uma nova opção no menu de seleção. O número correspondente à nova opção seria adicionado ao switch case, juntamente com a criação de um novo objeto da classe do novo tipo de pagamento.

Finalmente, seria necessário atualizar o método main da classe Main para exibir a nova opção no menu e utilizar o objeto retornado pelo método selectPaymentType para executar as operações correspondentes ao novo tipo de pagamento.

## Qual é a importância de utilizar interfaces no desenvolvimento de sistemas orientados a objetos?

As interfaces são importantes no desenvolvimento de sistemas orientados a objetos porque permitem definir um contrato comum para classes que implementam a mesma interface. Isso significa que as classes que implementam uma interface concordam em seguir o mesmo conjunto de regras definidas pela interface, o que facilita a interoperabilidade entre diferentes componentes do sistema.

Além disso, as interfaces permitem a implementação de polimorfismo, que é a capacidade de um objeto assumir várias formas diferentes. Isso significa que um objeto pode ser tratado como um objeto de um tipo de interface comum, independentemente da sua classe concreta. Isso torna o código mais flexível e reutilizável, permitindo que o sistema seja facilmente estendido e modificado sem afetar outras partes do código.

## Qual é a diferença entre uma classe abstrata e uma interface?

Tanto as classes abstratas quanto as interfaces são usadas para definir contratos comuns para um grupo de classes relacionadas em um sistema orientado a objetos. No entanto, existem algumas diferenças importantes entre elas.

Uma classe abstrata é uma classe que não pode ser instanciada, mas que pode ser estendida por outras classes concretas. Ela pode conter campos, métodos e construtores, e pode fornecer uma implementação padrão para alguns métodos, que podem ser substituídos pelas classes que a estendem. Já uma interface é uma coleção de métodos abstratos (sem implementação) e constantes que define um conjunto de operações que uma classe deve implementar. Uma classe pode implementar múltiplas interfaces, mas só pode estender uma classe abstrata.

Em resumo, as classes abstratas são usadas para definir comportamentos comuns e compartilhar código entre classes relacionadas, enquanto as interfaces são usadas para definir um contrato comum que as classes que as implementam devem seguir, sem fornecer qualquer implementação. Em geral, as classes abstratas são mais adequadas para situações em que existe uma hierarquia de classes relacionadas, enquanto as interfaces são mais adequadas para definir comportamentos comuns entre classes não relacionadas.

## O que é encapsulamento e como ele é aplicado no programa?

Encapsulamento é um princípio da programação orientada a objetos que consiste em esconder os detalhes de implementação de um objeto, fornecendo uma interface pública clara e bem definida para os usuários. Em outras palavras, o encapsulamento permite que o objeto proteja seus dados e comportamentos internos, tornando-os acessíveis apenas através de métodos públicos. Isso torna o código mais seguro e mais fácil de manter, pois as alterações na implementação do objeto não afetam a forma como ele é usado externamente.

No programa em questão, o encapsulamento é aplicado através da criação de métodos públicos que permitem a interação com os objetos AtividadeCinco.InputReader e AtividadeCinco.PaymentTypeSelector, enquanto os detalhes de implementação dessas classes são mantidos privados. Por exemplo, o método readDouble na classe AtividadeCinco.InputReader é público e pode ser acessado de fora do objeto, mas o objeto Scanner que ele utiliza é mantido privado e só é acessado internamente. Da mesma forma, o método selectPaymentType na classe AtividadeCinco.PaymentTypeSelector é público e permite que o usuário selecione um tipo de pagamento, mas os detalhes de implementação, como a inicialização do objeto Scanner e a lógica de seleção do tipo de pagamento, são mantidos privados.

## Como seria possível melhorar a legibilidade do programa?

Para melhorar a legibilidade do programa, é possível utilizar comentários para explicar trechos de código que possam não ser tão claros. Isso ajuda a tornar o código mais compreensível para outras pessoas que possam vir a trabalhar nele. Além disso, é possível utilizar nomes mais descritivos para variáveis, métodos e classes, facilitando a compreensão do código. Também é importante seguir boas práticas de programação, como manter a indentação correta e evitar linhas de código muito extensas.

Outra maneira de melhorar a legibilidade do programa é dividir o código em métodos menores e mais específicos, cada um responsável por uma única tarefa. Isso ajuda a tornar o código mais modular e mais fácil de entender. Também é possível utilizar padrões de design para organizar o código de forma mais clara e concisa, como o padrão MVC (Model-View-Controller) ou o padrão Strategy.

## Qual é a finalidade da classe Main no programa?

A classe Main é a classe principal do programa e contém o método main(), que é o ponto de entrada para a execução do programa. Ela é responsável por inicializar os objetos necessários para a execução do programa e por coordenar a interação entre esses objetos.

No programa em questão, a classe Main é responsável por instanciar um objeto da classe AtividadeCinco.InputReader e utilizar esse objeto para obter um valor numérico digitado pelo usuário. Em seguida, a classe Main instancia um objeto da classe AtividadeCinco.PaymentTypeSelector e utiliza esse objeto para obter o tipo de pagamento escolhido pelo usuário. Com base no tipo de pagamento escolhido, a classe Main imprime uma mensagem indicando a opção selecionada ou indicando que a opção selecionada é inválida.

## O que é um construtor padrão e quando ele é utilizado?

Um construtor padrão é um construtor sem parâmetros que é fornecido pelo compilador Java por padrão se a classe não tiver nenhum outro construtor definido explicitamente. Ele é utilizado para criar um objeto da classe com os valores padrão para os seus campos e atributos, sem que seja necessário passar parâmetros para o construtor. O construtor padrão é útil em situações em que o desenvolvedor não precisa configurar explicitamente nenhum estado inicial do objeto no momento da sua criação.

É importante notar que, se uma classe tiver pelo menos um construtor definido explicitamente, o construtor padrão não será mais fornecido pelo compilador e, portanto, não estará disponível para uso. Em alguns casos, pode ser desejável definir explicitamente um construtor padrão, mesmo que a classe já tenha outros construtores, para garantir que sempre haja um construtor disponível sem parâmetros e que possa ser usado por outras classes que dependem dessa classe.

## Como é possível proteger o programa contra erros de entrada do usuário?

Para proteger o programa contra erros de entrada do usuário, é possível implementar algumas técnicas de validação de entrada. Por exemplo, no método readDouble da classe AtividadeCinco.InputReader, pode-se incluir uma verificação para garantir que o usuário informou um valor válido antes de retornar o valor lido. Além disso, pode-se adicionar tratamento de exceção para capturar erros durante a leitura de entrada e informar ao usuário a causa do problema.

Outra forma de proteger o programa é por meio da utilização de bibliotecas ou frameworks que possuem recursos para validação de entrada, como a biblioteca javax.validation do Java, que oferece anotações para validar entradas de dados de forma simples e eficiente. Dessa forma, é possível garantir que apenas dados válidos serão processados pelo programa, reduzindo a possibilidade de erros e problemas de segurança.

## Qual é a importância de utilizar nomes descritivos para as classes, métodos e variáveis?

A utilização de nomes descritivos é uma prática essencial no desenvolvimento de software, pois torna o código mais legível e facilita o entendimento das funcionalidades implementadas. A escolha de nomes adequados para as classes, métodos e variáveis ajuda os desenvolvedores a entenderem o propósito de cada elemento do programa, bem como a sua relação com outros elementos.

Nomes descritivos também facilitam a manutenção do código ao longo do tempo, uma vez que permitem que os desenvolvedores identifiquem rapidamente a finalidade de cada elemento, mesmo que tenham passado algum tempo desde sua criação. Além disso, nomes bem escolhidos também tornam mais fácil a integração de novos desenvolvedores em projetos já existentes, pois eles podem se orientar melhor na estrutura e funcionalidades do código.

## O que é herança e como ela pode ser aplicada no programa?

Herança é um mecanismo da orientação a objetos que permite criar uma nova classe a partir de uma classe existente, herdando seus atributos e métodos. A classe existente é chamada de classe pai ou superclasse, enquanto a nova classe criada é chamada de classe filha ou subclasse. A subclasse pode adicionar novos atributos e métodos e/ou sobrescrever os métodos herdados da superclasse. A herança é uma maneira eficiente de reutilizar código e organizar as classes de um programa.

No programa apresentado, é possível utilizar herança para criar classes filhas a partir da classe AtividadeCinco.PaymentType, que é uma interface. Por exemplo, se existir um tipo de pagamento que requer informações adicionais, como CPF ou número de telefone, é possível criar uma classe filha de AtividadeCinco.PaymentType e adicionar essas informações como atributos. A subclasse pode implementar os métodos da interface AtividadeCinco.PaymentType e também adicionar novos métodos específicos.

## Como é possível utilizar a sobrecarga de métodos no programa?

A sobrecarga de métodos permite que uma classe tenha vários métodos com o mesmo nome, porém com diferentes parâmetros. Isso significa que, dependendo dos argumentos passados, um método com um nome específico pode executar diferentes operações. Isso torna o código mais legível, pois os nomes dos métodos são intuitivos e descritivos. No programa, a sobrecarga de métodos pode ser utilizada para criar diferentes construtores para uma classe, por exemplo, com diferentes parâmetros e valores padrão.

<<<<<<< HEAD
Um exemplo de sobrecarga de método no programa é o construtor da classe CreditPayment, que tem três versões diferentes com diferentes parâmetros. Cada versão permite a criação de um objeto CreditPayment com diferentes informações de pagamento, como o número do cartão de crédito, a data de validade e o nome do titular. Dessa forma, o programador pode escolher qual construtor utilizar, dependendo dos dados que estão disponíveis para criar o objeto.
=======
Um exemplo de sobrecarga de método no programa é o construtor da classe AtividadeCinco.CreditPayment, que tem três versões diferentes com diferentes parâmetros. Cada versão permite a criação de um objeto AtividadeCinco.CreditPayment com diferentes informações de pagamento, como o número do cartão de crédito, a data de validade e o nome do titular. Dessa forma, o programador pode escolher qual construtor utilizar, dependendo dos dados que estão disponíveis para criar o objeto.
>>>>>>> 76d2c8a (lasy version)
