# Resenha capítulo 6 Padrões de Projeto e Arquitetura de Software

Introduz o conceito de Padrões de Projeto, que são soluções reutilizáveis para problemas recorrentes no design de software, visando criar sistemas mais flexíveis e extensíveis, sendo uma funcionando como soluções já testada para sistemas que estão sendo montados, e soluções já conhecidas as para novos usuários do sistestema, Inspirados nas ideias de Christopher Alexander e adaptados pela "Gangue dos Quatro" (GoF), tendo algumas idéias que vieram depois, os padrões de projeto também servem como um vocabulário comum entre desenvolvedores.

### São apresentados no capítulo 6 os seguintes padrões de software:

- **Fábrica**: Centraliza a criação de objetos, permitindo que o código seja independente das classes concretas instanciadas.

- **Singleton**: Garante que uma classe tenha apenas uma instância e fornece um ponto global de acesso a ela.

- **Proxy**: Introduz um objeto intermediário que controla o acesso a outro objeto, podendo adicionar funcionalidades como cache ou segurança.

- **Adaptador**: Converte a interface de uma classe para outra esperada pelos clientes, permitindo a integração entre classes incompatíveis.

- **Fachada**: Fornece uma interface simplificada para um conjunto complexo de interfaces em um subsistema, facilitando seu uso.

- **Decorador**: Adiciona dinamicamente novas responsabilidades a um objeto sem alterar sua estrutura, oferecendo uma alternativa flexível à herança.

- **Strategy**: Define uma família de algoritmos intercambiáveis, permitindo que o algoritmo usado por uma classe seja selecionado em tempo de execução.

- **Observador**: Estabelece uma relação um-para-muitos entre objetos, onde mudanças no estado de um objeto (sujeito) são notificadas a todos os seus observadores.

- **Template Method**: Define o esqueleto de um algoritmo na classe base e permite que subclasses personalizem certos passos do algoritmo sem alterar sua estrutura geral.

- **Visitor**: Separa algoritmos das estruturas de dados, permitindo adicionar novas operações sem modificar as classes dos elementos sobre os quais opera.

> O capítulo enfatiza que, embora úteis, os padrões de projeto não são uma "bala de prata" e devem ser aplicados com critério. O uso excessivo ou inadequado pode complicar desnecessariamente o sistema. É crucial avaliar se a aplicação de um padrão realmente agrega valor ao projeto.

# Resenha capítulo 7 Arquitetura de Software

Introduz o conceito de Arquitetura de Software, enfatizando sua importância como conjunto de decisões críticas que moldam um sistema e são difíceis de reverter, enquanto discute diferentes definições de arquitetura, destacando que vai além da organização de classes, envolvendo escolhas estratégicas que impactam profundamente o software.

### Em seguida, o capítulo explora os seguintes padrões arquiteturais:

- **Arquitetura em Camadas**: Promove a organização hierárquica do sistema, onde cada camada só se comunica com a imediatamente inferior, facilitando manutenção e evolução.

- **Arquitetura MVC (Model-View-Controller)**: Separa a aplicação em modelo, visão e controlador, melhorando a modularidade e permitindo múltiplas interfaces para o mesmo modelo.

- **Microsserviços**: Defende a decomposição do sistema em serviços independentes, favorecendo escalabilidade e implantação contínua, mas alerta sobre a complexidade adicional e desafios em sistemas distribuídos.

- **Arquiteturas Orientadas a Mensagens e Publish/Subscribe**: Abordam o desacoplamento entre componentes via comunicação assíncrona, aumentando a robustez e escalabilidade do sistema.

O autor também discute outros padrões e alerta para o anti-padrão Big Ball of Mud, caracterizado pela ausência de uma arquitetura clara, resultando em sistemas difíceis de manter.

A resenha deste capítulo destaca a abordagem equilibrada do autor, que apresenta os padrões arquiteturais não apenas em teoria, mas também considerando seus benefícios e limitações práticas. Ao enfatizar a necessidade de escolhas conscientes e contextuais, o capítulo incentiva profissionais a refletirem criticamente sobre as melhores soluções arquiteturais para seus projetos, evitando a aplicação indiscriminada de tendências e reconhecendo que não há soluções universais em arquitetura de software.
