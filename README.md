Projeto Cadastro Employees 

Curso Completo Programação C# - 05/09/2024 

 

Contexto: 
Criar um cadastro de funcionários onde contenha os campos id, nome e salário. Depois criar uma funcionalidade onde seja possível aplicar um aumento em percentual no salário. 

 

Requisitos: 
Conter as informações de Id, Nome e salário 
A chave exclusiva será o Id 
Possibilidade de inclusão, exclusão e alteração do cadastro 
Criar uma funcionalidade de calculo para informar o percentual de aumento em cima do salário. Para isso o programa deve ler o Id,  e o percentual de aumento. 
Ao finalizar o cadastro o programa deve retornar a lista de todos os funcionários cadastrados, da seguinte forma: Id, Nome, salário 
Todo o programa deve ser escrito em Inglês 
Caso não tenha o Id, informar uma mensagem para abortar a operação. 

 

Refinamento técnico: 

Entradas: 
How many employees will be registered? 3 
Emplyoee #1: 
Id: 333 
Name: Maria Brown 
Salary: 4000.00 
Enter the employee id that will have salary increase : 536 
Enter the percentage: 10.0 


Saídas: 
Updated list of employees: 
333, Maria Brown, 4000.00 
536, Alex Grey, 3300.00 
772, Bob Green, 5000.00 

Classes: 
Emplyees 
Atributos privados 
Atributo públicos 
   Nome 
   Id 
   Salário 

Propriedades auto implementadas 
  Nome  
  Id 
  Salario (pivate) 

Construtores 
  Employees (salario, id, nome) para aceitar todos os campos.  

Propriedades customizadas 

Outros métodos da classe 
  IncreaseSalary (percentage : double) 
  Void : Salary x increase 
  Tostring 

 

 

 

 

 

 
