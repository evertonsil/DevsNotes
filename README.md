<h2>DevsNotes: (Sistema de Anotações)</h2>

Este projeto foi desenvolvido com base no curso de PHP do B7Web, a partir das aulas sobre API.
Com uma interface gráfica com Bootstrap possibilitando criar, editar e excluir anotações via API, interagindo com o banco de dados.
Utilizado PHP 7 e MySql 8.

O que o proejeto precisa fazer?
  
    - Listar as anotações;
    - Pegar informações de uma anotação;
    - Inserir nova anotação;
    - Atualizar uma anotação;
    - Deletar uma anotação.

Qual a estrutura de dados?

    - Local para armazenar as anotações (BD?)
        - ID;
        - Title;
        - Body (anotação).

Quais os endpoints?

    - (MÉTODO) /url (PARÂMETROS) 
    - (GET) /api/notes  -- Listar todas as anotações
    - (GET) /api/note/id  -- Informações de uma anotação 
    - (POST) /api/note/ (title, body)  --  Inserir nova anotação
    - (PUT) /api/note/id (title, body)  --  Atualizar anotação
    - (DELETE) /api/note/id  --  Deletar anotação

No PHP Estruturado

    - (MÉTODO) /url (PARÂMETROS) 
    - (GET) /api/notes  -- /api/getall.php
    - (GET) /api/note/id  -- /api/get.php?id=123
    - (POST) /api/note/ (title, body)  --  /api/insert.php (title, body)
    - (PUT) /api/note/id (title, body)  --  /api/update.php (id, title, body)
    - (DELETE) /api/note/id  --  /api/delete.php (id)



