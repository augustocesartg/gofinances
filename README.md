# GoFinances

Projeto web para controle de transações financeiras. Transações são carregadas a partir de um arquivo .CSV, 
que são enviadas para o back-end e armazenadas em um banco postgres.
<br><br>

### Tecnologias utilizadas
#### Back-end
  - @types/csv-parse
  - csv-parse
  - dotenv
  - express
  - express-async-errors
  - multer
  - pg
  - reflect-metadata
  - typeorm

#### Front-end
  - axios
  - filesize
  - history
  - polished
  - react
  - react-dom
  - react-dropzone
  - react-router-dom
  - react-scripts
  - styled-components
  - typescript
<br><br>

### Como executar
Baixar ou clonar projeto e executar comando <b>```yarn```</b>, tanto na pasta do back-end como do front-end, para baixar todas as dependencias.
<br><br>
#### Back-end
  - Criar banco de dados postgres e cofigurar a conexão no arquivo <b>```ormconfig.json```</b>
  - Executar comando <b>```yarn typeorm migration:run```</b> para executar as migrations.
  - Executar comando <b>```yarn dev:server```</b> para iniciar o servidor na porta <b>3333</b>.
<br>

#### Front-end
  - Executar comando <b>```yarn start```</b> para iniciar aplicação, que vai ser executada no browser.
