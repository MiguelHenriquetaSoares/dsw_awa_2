# Projeto: dsw_ava_2
 
**Nome:** Miguel Henriqueta Soares
**Data:** 06/05/2025  
**Unidade Curricular:** Desenvolvimento serviços Web
 
## O que é uma API REST?
 
É uma interface de comunicação que segue padrões HTTP e permite que sistemas interajam entre si de forma simples e padronizada.
 
## Códigos de status HTTP
 
- **200 OK:** Requisição bem-sucedida.  
- **404 Not Found:** Recurso não encontrado.  
- **500 Internal Server Error:** Erro inesperado no servidor.  
 
## Diferença entre JSON, Texto Plano e XML
 
- **JSON:** Formato leve, usado com frequência em APIs.
- **Texto Plano:** Apenas texto sem formatação estruturada.
- **XML:** Formato estruturado com marcações, mais verboso que JSON.
 
## Como testar este projeto
 
1. Execute `composer install` para instalar as dependências.
2. Rode o servidor embutido com:  
   `php -S localhost:8080 index.php`
3. Acesse os endpoints:
   - `http://localhost:8080/uma-api`
   - `http://localhost:8080/codigos`
   - `http://localhost:8080/erro`
 
