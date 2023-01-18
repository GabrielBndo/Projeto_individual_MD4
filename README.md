# Projeto_individual_MD4
Modelagem de banco de dados


![image](https://user-images.githubusercontent.com/101153501/213169688-74843bfe-3705-46b4-8d11-0979d5bff29d.png)

⇨ Existem outras entidades além dessas três?
Sim, Projetos, professores e monitores

⇨ Quais são os principais campos e tipos?
Os principais campos são as ID e CPF, e os principais tipos são INT e VARCHAR

⇨ Como essas entidades estão relacionadas?

# Alunos e Projetos:

![image](https://user-images.githubusercontent.com/101153501/213169732-b9d1b76d-4f4c-4f7d-a0b4-10a17e5d2828.png)

estão relacionadas diretamente ligadas as outras, podendo repetir a cada módulo, pois cada aluno ter aum projeto individual e em grupo em cada módulo.


# Professores e Monitores:

![image](https://user-images.githubusercontent.com/101153501/213169777-cb4244e9-8fb9-4df9-af64-5a08f00d5778.png)

PROJETOS possui 1:N com ALUNOS;

ALUNOS possui 1:N com CURSOS;

CURSOS possui 1:N com TURMAS;

PROFESSOR possui 1:N CURSOS;

MONITORES possui 1:N com TURMAS;

