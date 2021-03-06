# GerenciaTurma
Gerenciador de turmas de uma escola
*Necessário instalar o WindowBuilder no eclipse para utilizar as telas
## Versão 0.9
### Adicionado uma classe para fazer os logs
- Classe Espiao

### Removido erros de execução no método alterar
- Aluno_Turma
- Professor_Disciplina
- Relacao

### Corrigido problema do método Listar
- Aluno_Turma
- Professor_Disciplina
- Relacao

### Adição do script do DataBase e Arquivo Log

## Versão 0.8.1
### Correção de bugs que ocorriam em algumas telas
- Não pegar os dados digitados
- Não carregar previamente a tabela Relacao
- Mostrar dados incorretos na tabela Consulta

## Versão 0.8
### Adição da tela de Consulta personalizada para a tabela Relacao
#### Adição das seguintes classes
- ConsultaRelacao
- ConsultaRelacaoDAO
- TabelaConsultaRelacao

## Versão 0.7.7

### Telas refeitas para JFrame (v0.7.6 - Window)
- GuiTurma
- GuiAluno_Turma
- GuiDisciplina
- GuiProfessor_Disciplina
- Relação

### Modificado algumas partes da relação
- Codificação
- Adição do método atualizaTabela, para atualizar a tabela relação ao executar os comandos Inserir, Alterar e deletar.

## Versão 0.7.6

### Correção da forma que foi criado as telas
- De Window para Frame - Turma e Disciplina

## Verção 0.7.5

### Alteração do layout da Tela Principal e correção de bugs das telas GuiTurma e GuiDisciplina

## Versão 0.7

### Adicionado Manipulador da Relação
- Classes Relacao, RelacaoDAO, tabelaRelacao
- Classe TabelaProfessor_DisciplinaNome
- Adicionada a pasta doc

### Adicionado o comando de listar apenas o nome para o professor e disciplina

## Versão 0.6

### Adição do Manipulador Aluno_Turma
- GuiAluno_Turma
- Classe Aluno_Turma
- Classe Aluno_TurmaDAO
- Classe TabelaAluno_Turma
- Classe TabelaAlunoMini

## Versão 0.5

### Adição do manipulador do aluno
- GuiAluno
- Classe Aluno
- Classe AlunoDAO
- Classe TabelaAluno

### Adição do manipulador Professor_Disciplina
- GuiProfessor_Disciplina
- Classe Professor_Disciplina
- Classe Professor_DisciplinaDAO
- Classe TabelaProfessor_Disciplina
- Classe TabelaProfessorMini

## Versão 0.4
### Adicionado os arquivos referentes a tabela Professor:
- Tela para manipulação da tabela Professor (GuiProfessor)
- Arquivos de testes (Incluir, alterar, listar e deletar)
- Modelo de tabela para a tabela Professor
> Além de ter sido retirado códigos que não estavam sendo utilizados.

## Versão 0.3
- Ajustado o escalamento das telas GuiTurma e GuiDisciplina
- Removido as mensagens de teste das telas principais
- Removido a necessidade de colocar o código para a inserção de dados. O código é gerado automaticamente pelo BD.

## Versão 0.2
- Foi adicionada novas telas, conexão com o banco de dados e feito o CRUD com turma e disciplina
- Foi removida a tabela telas, foram todas migradas para a tabela view
