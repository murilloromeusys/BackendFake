# BackendFake
Arquivo API para simular uma consulta ao banco de dados utilizados para testes do frontend

clone o repositorio este repositorio

yarn ou npm i para instalar a lib

yarn server ou npm run server para subir o servidor

endopoints

Funcionarios

get http://localhost:2345/funcionarios/
( busca todos os funcionarios)

get http://localhost:2345/funcionarios/id
( busca um unico funcionarios *no lugar do id colocar o numero do id )

post http://localhost:2345/funcionarios/
( criar um funcionario * necessario configurar o header como Content-Json(application/json) )

put http://localhost:2345/funcionarios/id
( atualiza um funcionario * necessario configurar o header como Content-Json(application/json) )

patch http://localhost:2345/funcionarios/id
( atualiza uma informação do funcionario * necessario configurar o header como Content-Json(application/json) )

delete http://localhost:2345/funcionarios/id
(Apaga um funcionario )

Plantões Diurnos

get http://localhost:2345/plantoesDiurnos/
( busca todos os plantoesDiurnos)

get http://localhost:2345/plantoesDiurnos?funcionarioId=funcionarioId
( busca plantão por funcinario )

post http://localhost:2345/plantoesDiurnos/
( criar um registro de platão diurno * necessario configurar o header como Content-Json(application/json) )

put http://localhost:2345/plantoesDiurnos/id
( atualiza um registro de platão diurno * necessario configurar o header como Content-Json(application/json) )

patch http://localhost:2345/plantoesDiurnos/id
( atualiza uma informação do registro de platão diurno * necessario configurar o header como Content-Json(application/json) )

delete http://localhost:2345/plantoesDiurnos/id
(Apaga um registro de platão diurno )

Plantões Noturnos

get http://localhost:2345/plantoesNoturnos/
( busca todos os plantoesNoturnos)

get http://localhost:2345/plantoesNoturnos?funcionarioId=funcionarioId
( busca plantão por funcinario )

post http://localhost:2345/plantoesNoturnos/
( criar um registro de platão noturno * necessario configurar o header como Content-Json(application/json) )

put http://localhost:2345/plantoesNoturnos/id
( atualiza um registro de platão noturno * necessario configurar o header como Content-Json(application/json) )

patch http://localhost:2345/plantoesNoturnos/id
( atualiza uma informação do registro de platão noturno * necessario configurar o header como Content-Json(application/json) )

delete http://localhost:2345/plantoesNoturnos/id
(Apaga um registro de platão noturno )
