# Projeto_individual_MD4
Modelagem de banco de dados


![image](https://user-images.githubusercontent.com/101153501/213162609-e138463c-0555-408d-9de5-5231691a7963.png)

⇨ Existem outras entidades além dessas três?
Sim, Projetos, professores e monitores

⇨ Quais são os principais campos e tipos?
Os principais campos são as ID e CPF, e os principais tipos são INT e VARCHAR

⇨ Como essas entidades estão relacionadas?

# Alunos e Projetos:

![image](https://user-images.githubusercontent.com/101153501/213162727-a485f71a-c7be-4129-bb73-758a53f52819.png)

estão relacionadas diretamente ligadas as outras, podendo repetir a cada módulo, pois cada aluno ter aum projeto individual e em grupo em cada módulo.


# Professores e Monitores:

![image](https://user-images.githubusercontent.com/101153501/213162873-763210e6-b35e-4b51-b431-92a0d4008fac.png)

PROJETOS possui 1:N com ALUNOS;

ALUNOS possui 1:N com CURSOS;

CURSOS possui 1:N com TURMAS;

PROFESSOR possui 1:N CURSOS;

MONITORES possui 1:N com TURMAS;

