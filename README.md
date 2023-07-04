<h2 align="center"> Projeto Final de Banco de Dados II - 2023.2 - Grupo 1 </h2>
<h2 align="center"> Sistema de Gerenciamento de Cursos </h2>

Trabalho realizado para obtenção de nota na disciplina DCC603 - BANCO DE DADOS II
## ✒️ Autores

* **João Roberto** - *Desenvolvedor Backend* 
* **Matheus Melo** - *Desenvolvedor Backend* 
* **Natália Almada** - *Desenvolvedor Frontend*
* **Ramsés Carvalho** - *Desenvolvedor Frontend* 

### 📋 Pré-requisitos
* 1 Sistema deve conter autenticação/autorização com Login e Cadastro de Usuários
* 2 Usuário root (criado junto ao criação das tabelas) do sistema que pode dar permissão para novos usuários tipo admin

* 3 Usuário admin pode cadastrar/alterar/deletar novas categorias de curso;
  * 3.1 Usuário admin pode cadastrar/alterar/deletar novos cursos;
  * 3.2 Usuário admin pode suspender conta de usuário aluno;
  * 3.3 Tem acesso a listagem dos alunos;
  * 3.4 Faz a rotina de “fechar” um curso, emitindo certificados para quem terminou mais de 90% da carga horária;
  
* 4 Usuário aluno pode se cadastrar no sistema
  * 4.1 Usuário aluno pode alterar seu próprio perfil (atualizar endereço, celular, foto do perfil);
  * 4.2 Usuário aluno pode se inscrever nos cursos disponíveis no sistema;

* 5 Cursos devem estar vinculados a somente uma categoria de cursos;
  * 5.1 Categorias de cursos podem conter vários cursos vinculados a ela;
  * 5.2 Curso deve ter (id, nome_do_curso, categoria_curso(FK), data_inicio, carga_horária, quantidade_inscritos);

*6 Certificados são emitidos seguindo algum critério de validação do aluno. Exemplo:
 * - Aluno terminou de responder um questionário e acertou > 70% E/OU
 * - Quando o aluno termina mais de 90% da carga horária do curso.
    * 6.1 Para essa versão do sistema quem lança a carga horária do aluno é algum perfil admin do sistema

* 7 Sistema de emissão e controle dos certificados implementado utilizando Blockchain (desafio!)

* 8 O sistema deve ser publicado na AWS (deploy da aplicação em uma instância EC2). Seguindo os passos vistos em aula.

## 🛠️ Construído com:

* [VS Code](https://code.visualstudio.com) - IDE de desenvolvimento
