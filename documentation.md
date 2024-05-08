#### Tabelas e Relações

- **user**
  - **Finalidade**: Armazena informações básicas sobre todos os tipos de usuários, como estudantes, professores e outros participantes do sistema.

- **student**
  - **Finalidade**: Contém informações específicas sobre estudantes, associando-os a universidades e países, além de detalhes pessoais como gênero e contato.

- **university**
  - **Finalidade**: Guarda informações sobre as universidades, como o nome e o país onde estão localizadas.

- **country**
  - **Finalidade**: Armazena detalhes sobre os países, usado para categorizar estudantes, universidades ou outras entidades por país.

- **tutor**
  - **Finalidade**: Mantém informações sobre os tutores, vinculando-os a usuários específicos e relacionando-os a universidades e países para contextualizar sua localização e afiliação.

- **team**
  - **Finalidade**: Representa equipes dentro do sistema, que podem ser formadas por estudantes para projetos ou atividades em grupo, ligando-se aos tutores e ao cesim.

- **cesim**
  - **Finalidade**: Relacionado o Cesim, com informações sobre os períodos de início e término.

- **round**
  - **Finalidade**: Detalha rodadas dentro da simulação Cesim, especificando quando cada rodada começa e termina e a que jogo pertence.

- **student_team**
  - **Finalidade**: Associa estudantes a equipes específicas, estabelecendo relações diretas entre usuários e grupos.

- **feedback**
  - **Finalidade**: Permite usuários enviar feedback ou avaliações uns aos outros, incluindo conteúdo textual e uma nota de avaliação.

- **schedule**
  - **Finalidade**: Utilizada para agendar eventos ou atividades para as equipes, para organizar reuniões ou prazos relacionados a projetos de equipe.

- **question**
  - **Finalidade**: Armazena perguntas que podem ser feitas para realizar a categorização do tipo de perfil do usuário

- **question_answer**
  - **Finalidade**: Guarda as respostas dos usuários às perguntas listadas, ligando as respostas às perguntas e aos usuários que as responderam.

- **ticket**
  - **Finalidade**: Usado para comunicação direta entre usuários, como um sistema de mensagens ou para resolver questões de conflitos entre os integrantes.
