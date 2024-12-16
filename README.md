Estrutura recomendada para o projeto final do módulo 15:

epbjc/
├── migracao/
│   ├── 
│   ├── 
│   ├── 
│   └── 
├── sqlite-database/
│   ├── epbjc.db
│   ├── epbjc_backup_1.db
│   ├── epbjc_backup_2.db
│   └── epbjc_backup_3.db
├── src/
│   ├── app/
│   │   └── main.py - Criação da tabela mãe escola e as tabelas filhas alunos, professores, materiais com o query CREATE
│   ├── create/
│   │   ├── alunos_create.py - Aqui foram inseridos os dados na tabela usando uma seleção de nomes escolhidos por um random, e uma idade escolhida também por um random
│   │   ├── materiais_create.py - Aqui foram inseridos dados apenas usando o query INSERT
│   │   └── professores_create.py - Aqui foram inseridos os dados na tabela usando uma seleção de nomes escolhidos por um random, e uma idade escolhida também por um random
│   ├── read/
│   │   ├── alunos_delete.py - Neste ficheiro o programa apaga todos os inserts Joel
│   │   ├── materiais_delete.py -  Neste ficheiro o programa apaga todos os inserts note
│   │   └── professores_delete.py - Neste ficheiro o programa apaga todos os inserts Sandra
│   ├── update/
│   │   ├── alunos_read.py - Lê todos os dados da tabela alunos
│   │   ├── materiais_read.py - Lê todos os dados da tabela materiais
│   │   └── professores_read.py - Lê todos os dados da tabela professores
│   └── delete/
|       ├── alunos_update.py - Atualiza o nome para teste onde id é 3 usando os querys SET WHERE E UPDATE
|       ├── materiais_update.py - Atualiza a marca para teste onde id é 3 usando os querys SET WHERE E UPDATE
|       └── professores_update.py - Atualiza o nome para teste onde id é 3 usando os querys SET WHERE E UPDATE
├── testes/
│   ├── 
│   ├── 
│   ├── 
│   └── 
└── README.md
