# api-escola-matheus
📚 Sistema Escolar - API + Frontend

#Aplicação web completa para gerenciamento de alunos e notas, desenvolvida com:

Node.js + Express (API REST)
HTML, CSS e JavaScript (Frontend)
Consumo de API via Fetch
Persistência em arquivos JSON
Funcionalidades
Alunos
Cadastrar aluno
Listar alunos
Remover aluno
Notas
Lançar notas
Listar notas
#Como Executar o Projeto
1. Backend (API)
cd backend
npm install
npm start

#Frontend

Abra o arquivo:

frontend/index.html
Endpoints da API
Alunos
Método	Rota	Descrição
GET	/alunos	Lista alunos
POST	/alunos	Cria aluno
DELETE	/alunos/:id	Remove aluno
Notas
Método	Rota	Descrição
GET	/notas	Lista notas
POST	/notas	Cria nota
Exemplo de JSON
Aluno
{
  "id": 123,
  "nome": "João",
  "idade": 16
}
Nota
{
  "id": 456,
  "alunoId": 123,
  "disciplina": "Matemática",
  "nota": 8.5
}
#Tecnologias Utilizadas
Node.js
Express
fs-extra
HTML5
CSS3
JavaScript (Fetch API)
Melhorias Futuras
Editar alunos e notas
Cálculo de média por aluno
Relacionar nome do aluno automaticamente nas notas
Interface com Bootstrap ou React
Deploy da aplicação
#Autor

Desenvolvido por Matheus Freitas
