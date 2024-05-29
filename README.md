# ProjetoA3_AgriculturaSustentavel
Integrantes:
- Leonardo Pultrini do Amaral Araujo  823214515
- Matheus Mayca Melo Kemerich  824147116
- Davi Mendes de Oliveira  82412708
- Vinicius de Paiva Ferreira  82327374
- Guilherme Costeira Braganholo  824135940
- Diego Wilder Choquehuanca Yujra  824155812
- Kaique Fernando Santos de Souza  824147722

Descrição do Projeto:
O projeto foi elaborado visando a carência da existência de ferramentas que auxiliem agricultores e até mesmo pessoas que desejam ter um cultivo próprio em seus terrenos como hortas caseiras, buscando trazer sustentabilidade  que integra a gestão de água e agrícola que seja de fácil entendimento para estimular a participação de um número maior de pessoas,  trazendo uma maior qualidade de vida tanto nutricional quanto ambiental, desse modo, teve-se como objetivo desenvolver um aplicativo web de suporte à tomada de decisão de plantio e cultivo de hortaliças, leguminosa entro outros alimentos agrícolas, trazendo  a época de plantio, formas de cultivos e manutenção diária, fundamentada em um sistema de indicadores denominado (NOME DO PROJETO). A metodologia utilizada para o desenvolvimento do sistema foi o uso de ferramentas de desenvolvimento WEB com a linguagem de programação JAVA. Foi utilizado um banco de dados MySQL como biblioteca para visualização de dados que possui funções versáteis que viabilizam a personalização de acordo com a intenção do programador. Além disso, o painel da ferramenta também conta com o apoio de tabelas interativas, para que a procura dos dados referentes à sustentabilidade hídrica e de cultivo seja de maneira simples e rápida. Portanto, espera-se que esse aplicativo web, ainda em construção, possibilitará uma maior acessibilidade de informações e o incentivo à participação de um publico fora do meio agrícola, trazendo uma maior sustentabilidade ambiental e acesso a alimentos de qualidade.

Ambiente de desenvolvimento:
Vamos utilizar o NetBeans como IDE para desenvolver o código em JAVA e o banco de dados utilizado vai ser o MySQL.

Estrutura do projeto: 
O package vai ser composto pelas classes: CONEXÃO para fazer a integração com o banco de dados MySQL, USUARIO para fazer o cadastro e o controle dos usuarios, VEGETAÇÃO para fazer a inclusão de plantas(legumes, hortaliças, verduras e outros) e pode acessar o banco de dados com as informação refente a cada uma delas, SOLO para fazer o cadastro e controle dos tipos de solo,DOENÇAS para incluir e controlar os tipos de doenças e problemas, TRATAMENTO para fazer a inclusão de tipos de tratamento e exibir o tratamento necessário para cada doença ou praga.

Dependências:
java.sql.Connection;
java.sql.DriverManager;
java.sql.SQLException;
javax.swing.JOptionPane;
java.sql.PreparedStatement;
