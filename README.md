NwDoctrineMigrations
====================

Binario responsavel para criar as migrações do banco de dados para Zend Framework 2

Comandos
--------

*   **bin/doctrine migrations:status** - Verifica o status da migração e informa se ha nova migrações.
    
*   **bin/doctrine migrations:generate** - Cria novos arquivos de migrações.
    
*   **bin/doctrine migrations:migrate [NUM_VERSION]** - Atualiza o banco de dados na ordem das migrações até o numero da versão informada, caso seja omitida efetua migração de todas as versões diponiveis.
    
*   **bin/doctrine migrations:execute [NUM_VERSION]** - Executa uma migração especifica
    
*   **bin/doctrine migrations:version** - Mostra a versão atual do database
