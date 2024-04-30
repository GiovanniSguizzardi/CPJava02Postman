# CP-02 JavaAdvanced 
Repositório criado para armazenar todos os arquivos e explicar sobre o cp-02 de java.

## Participantes
- RM551261 - Giovanni Sguizzardi;
- RM98057 - Nicolas E. Inohue;
- RM99841 - Marcel Prado Soddano;
- RM99577 - Guilherme Dias Gomes

## Documentação
Foram criados dentro da aplicação 5 diferentes métodos de consulta, criação e delete de dados, e são eles:
- listarBrinquedos(); 
- criarBrinquedo();
- atualizarBrinquedo();
- excluirBrinquedo();
- buscarBrinquedoPorId();
- generateNextId() método que gera um ID na classe **"criarBrinquedo()"**.

| Atributo ORACLE            | Atributo JAVA          |
| -------------------------- | ---------------------- |
| B_ID (NUMBER)              | id (Long)              |
| B_NOME (VARCHAR2)          | nome (String)          |
| B_TIPO (VARCHAR2)          | tipo (String)          |
| B_CLASSIFICACAO (VARCHAR2) | classificacao (String) |
| B_TAMANHO (VARCHAR2)       | tamanho (String)       |
| B_PRECO (NUMBER)           | preco (Double)         |


Aqui está a print da configuração final do SpringInitializr e respectivas 
dependências:

![image](https://github.com/GiovanniSguizzardi/CPJava02Postman/assets/125572342/09ad579b-a0e3-4116-a5a2-c8dafe7daac8)

## Prints dos END-POINTS (C.R.U.D)
- Print do método listarBrinquedos()
```bash
GET http://localhost:8080/brinquedos
```
![image](https://github.com/GiovanniSguizzardi/CPJava02Postman/assets/125572342/07743642-b54d-47c6-8b46-9886530d55e6)

- Print do método criarBrinquedo()
```bash
POST http://localhost:8080/brinquedos/add
```
![image](https://github.com/GiovanniSguizzardi/CPJava02Postman/assets/125572342/fd2b6491-3440-4a14-865b-3d09ee405933)

- Print do método buscarBrinquedoPorId()
```bash
GET http://localhost:8080/brinquedos/buscarid/id
```
![image](https://github.com/GiovanniSguizzardi/CPJava02Postman/assets/125572342/93e12c59-b710-4a32-a29e-b03fe568dd85)

- Print do método excluirBrinquedo()
```bash
DELETE http://localhost:8080/brinquedos/delete/id
```
![image](https://github.com/GiovanniSguizzardi/CPJava02Postman/assets/125572342/e89a84d9-3dac-4836-82f9-949fd9c76b8d)

- Print do método atualizarBrinquedo()
```bash
PUT http://localhost:8080/brinquedos/atualizar/id
```
![image](https://github.com/GiovanniSguizzardi/CPJava02Postman/assets/125572342/456b90e2-c588-4325-a8fe-9c2282cce679)
