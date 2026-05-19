Fúria Fitness — Sistema de Gestão para Academia
1. Introdução

O projeto Fúria Fitness consiste em um sistema web desenvolvido para auxiliar no gerenciamento de academias, oferecendo funcionalidades voltadas ao controle de usuários, monitoramento de frequência e acompanhamento do desempenho dos alunos.

A aplicação foi desenvolvida utilizando tecnologias web no frontend, Java no backend e MySQL como sistema gerenciador de banco de dados, permitindo uma comunicação estruturada entre interface, regras de negócio e armazenamento de informações.

2. Objetivo do Projeto

O principal objetivo do sistema é facilitar o gerenciamento interno da academia, automatizando processos como cadastro de alunos, autenticação de acesso, controle de entrada e saída por catraca e cálculo do nível do aluno com base no tempo acumulado de permanência na academia.

Além disso, o sistema busca proporcionar uma interface simples, organizada e responsiva, permitindo uma experiência prática tanto para administradores quanto para alunos.

3. Funcionalidades Implementadas

O sistema possui as seguintes funcionalidades principais:

Cadastro de usuários (alunos e administradores);
Sistema de login com autenticação;
Controle de acesso por meio de catraca;
Registro de horas de permanência dos alunos;
Classificação automática de níveis conforme o tempo acumulado;
Interface web responsiva e de fácil utilização.
4. Tecnologias Utilizadas
Frontend
HTML5
CSS3
Backend
Java
Servlets ou Spring Boot (dependendo da implementação)
Banco de Dados
MySQL
Comunicação com Banco
JDBC
5. Estrutura de Funcionamento

O sistema realiza a comunicação entre frontend, backend e banco de dados através de uma arquitetura baseada em requisições web. O usuário interage com a interface gráfica, enquanto o backend em Java é responsável pelo processamento das informações e pelas operações realizadas no banco de dados MySQL.

O controle de horas é realizado a partir do registro de entrada e saída dos alunos, permitindo o cálculo do tempo acumulado dentro da academia.

6. Sistema de Níveis

Os alunos são classificados automaticamente conforme a quantidade de horas registradas no sistema.

Nível	Tempo Acumulado
Iniciante	Até 10 horas
Intermediário	Entre 11 e 30 horas
Avançado	Acima de 30 horas
7. Execução do Projeto

Para executar o projeto localmente, siga os passos abaixo:

Importar o projeto em uma IDE Java, como Eclipse ou IntelliJ IDEA;
Configurar a conexão com o banco de dados MySQL;
Criar as tabelas necessárias no banco;
Iniciar o servidor de aplicação (Tomcat ou equivalente);
Executar o sistema e acessar pelo navegador.
8. Considerações Finais

O projeto Fúria Fitness foi desenvolvido com o propósito de aplicar conceitos de desenvolvimento web, integração com banco de dados e organização de sistemas em camadas. A aplicação permite simular um ambiente real de gerenciamento de academias, reunindo funcionalidades essenciais para controle e acompanhamento de usuários.
