# entregaSprint

## Sprint x

### User Story

- **DoD**: Será negociada com a empresa o que precisa ser entregue para que esta User Story seja satisfeita.
- **DoR**: Deve conter os detalhes mínimos do produto (seja documentação, guias, ou telas de protótipo) que indiquem que aquela User Story está pronta para o desenvolvimento.

## Professor importa uma tabela contendo informações dos alunos para poupar tempo e padronizar o envio, cadastrando vários alunos de uma única vez

- **DoD**:
- **DoR**:
    - Duas telas no JavaFX:
        - Tela de login para que o usuário selecione se ele é aluno ou professor;
        - Tela do professor para cadastrar equipe contendo um botão para adicionar um arquivo .csv. Deve haver um botão para confirmar o envio. Após o envio, a tela apresenta a equipe cadastrada.

    - Backend que:
        -  Recebe as informações, e depois realiza o INSERT no banco de dados;
        -  Após realizar o cadastro, o programa irá realizar um SELECT no banco de dados, trazendo as informações para a aplicação.
    - Banco de dados contendo:
        -  Tabela de equipe;
        -  Tabela de usuário.

## Aluno avalia outros integrantes da equipe a cada sprint para facilitar a visualização, facilitar o envio da avaliação e automatizar parte do processo

- **DoD**: 
- **DoR**:
  - Tela no JavaFX:
      - Após selecionar aluno na primeira tela, o usuário terá que colocar o seu email e, caso esteja cadastrado, terá uma tela contendo os outros alunos de seu grupo, que serão sujeitos à sua avaliação.
  - Backend que:
      -  Recebe as informações, e depois realiza o INSERT no banco de dados;
  - Banco de dados contendo:
      -  Tabela de notas.
