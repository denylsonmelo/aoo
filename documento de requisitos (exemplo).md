# Descrição Inicial do Sistema

O sistema deverá apoiar na fiscalização e gerenciamento de frequência dos professores,com o objetivo geral do sistema é auxiliando e automatizando o máximo possível das funções exercidas pelos coordenador de disciplinas e assistentes de alunos, focando nas potencialidades e requisitos requeridos pelo usuário,fornecendo assim uma informação clara e pontual para o mesmo.

## Atribuições:
- O sistema deverá inserir, alterar, apagar e consultar a presença ou falta dos professores, permutações fixas ou temporárias, atrasos, e em que turma e horário que ele estará dando aula em certo dia,guardando essas informações em um histórico de fácil acesso ao usuário com a permissão adequada;
- Deverá dar suporte aos calendários letivos referentes três modalidades de ensino: Técnico, médio e superior, atendendo todas as demandas;
- O sistema irá contar com um sistema de pesquisa simples quem, deve informar as aulas, horários e professores pesquisados no certo dia;
- Identificação de cumprimento de carga horária;
- Opções de Justificativa de falta;
- Relatório Diário com observações opcionais;
- No caso de reposições, anteposições, devera passará por um processo de pendência, até que seja confirmado. Além disso, no caso de falta e reposição de um professor, a reposição deve ser vinculada a falta, para que a falta seja cancelada.Contará reserva de aulas disponíveis;
- Aba exclusiva para gerencia de equipamentos,informando o controle de inventário, ou seja, controlar recursos como, reservas de auditório, Data Show, caixa amplificadora, e outros itens que em primeiro estado deve ser avaliado como "pendente" para depois ser confirmado pelo usuário competente. O controle de inventário contará com um sistema de pesquisa próprio e com notificações para reserva de equipamento;
- Opções de prioridade na reserva de laboratórios e auditório; 
- Filtros e cadastro de usuários.
- Agenda de compromissos diários.
- gerencia de salas.

## Atores do Sistema
- Assistente de Alunos
- Coordenador de Disciplina
- Diretor de Ensino
- Coordenador de Curso
- Professor
- Monitor de Laboratório

## Requisitos Funcionais 

Obs.: A prioridade serão definidas como:
- Essencial: O requisito deve fazer parte do sistema. Ele não pode ser negociado sua retirada.
- Importante: O requisito deve fazer parte do sistema, mas sua retirada pode acontecer em casos de fim do tempo de entrega.
- Desejável: Requisitos de baixo impacto na produtividade do sistema. São dispensáveis. (Cereja do bolo)

CRUDS que vem das entidades identificadas

#### RF001 – Cadastrar Sala
    Atores envolvidos: Assistente de Alunos
    Descrição: Permite a inserção de uma sala.
    Prioridade: Essencial
#### RF002 – Listar Salas
    Atores envolvidos: Assistente de Alunos, Professor,
    Descrição: Permite a exibição das salas cadastradas.
    Prioridade: Essencial
#### RF003 – Alterar Sala
    Atores envolvidos: Assistente de Alunos
    Descrição: Permite a alteração de uma sala.
    Prioridade: Essencial
#### RF004 – Excluir Sala
    Atores envolvidos: Assistente de Alunos
    Descrição: Permite a exclusão de uma sala.
    Prioridade: Essencial
#### RF005 - Emprestar Equipamento
    Atores envolvidos: Assistente de Alunos
    Descrição: Permite o empréstimo de um equipamento pelo solicitante.
    Prioridade: Desejável
#### RF006 - Solicitar reserva de Equipamento
    Atores envolvidos: Solicitante - Professor(prioridade) e alunos.
    Descrição: Permite a solicitação de reserva de um equipamento.
    Prioridade: Desejável
#### RF007 - Autorizar Uso de Sala
    Atores envolvidos: Assistente de Alunos, Monitor de Laboratórios, Coordenador de Cursos
    Descrição: Permite a utilização de uma sala pelo solicitante.
    Prioridade: Essencial
#### RF008 - Solicitar reserva de Sala(Discutível)
    Atores envolvidos: Solicitante
    Descrição: Permite a solicitação de reserva de uma sala.
    Prioridade: Essencial
#### RF009 - Cadastrar usuário
    Atores envolvidos: Coordenador de Disciplina
    Descrição: Permite o cadastro de um usuário.
    Prioridade: Essencial
#### RF012 - Atribuir presença ao ator professor.
    Atores envolvidos: Coordenador de Disciplinas
    Descrição: Permite que seja efetuada a presença do professor.
    Prioridade: Essencial
#### RF013 - Atribuir falta ao ator professor.
    Atores envolvidos: Coordenador de Disciplinas
    Descrição: Permite que seja efetuada a falta do professor.
    Prioridade: Essencial
#### RF014 - Efetuar uma permutas fixa
    Atores envolvidos: Coordenador de Disciplinas,Professor,Direção de Ensino
    Descrição: Permite que uma permutas fixa de horários.
    Prioridade: Essencial
#### RF015 - Registrar atrasos
    Atores envolvidos: Coordenador de Disciplinas
    Descrição: Permite que seja registrado atrasos.
    Prioridade: Essencial
#### RF016 - Efetuar uma permuta temporária
    Atores envolvidos: Coordenador de Disciplinas,Professor
    Descrição: Permite que uma permuta temporária de horários.
    Prioridade: Essencial
#### RF017 - Editar calendário letivo
    Atores envolvidos: Coordenador de Disciplinas (Discutir)
    Descrição: Permite que seja feito edições no calendário letivo.
    Prioridade: Essencial
#### RF018 – Cadastrar Curso
    Atores envolvidos: Coordenador de Curso(sujeito a alteração)
    Descrição: Permite o cadastro de curso.
    Prioridade: Essencial
#### RF019 – Listar Curso
    Atores envolvidos: Todos Usuários,sem restrições
    Descrição: Permite a exibição dos cursos existentes.
    Prioridade: Essencial
#### RF020 – Alterar Curso
    Atores envolvidos: Coordenador de Curso(sujeito a alteração)
    Descrição: Permite a alteração do curso.
    Prioridade: Essencial
#### RF021 – Excluir Curso
    Atores envolvidos: Coordenador de Curso(sujeito a alteração)
    Descrição: Permite a exclusão do curso.
    Prioridade: Essencial
#### RF022– Cadastrar Turma
    Atores envolvidos: Assistente de Aluno
    Descrição: Permite o cadastro da Turma.
    Prioridade: Essencial
#### RF023 – Listar Turma
    Atores envolvidos: Todos os usuários Cadastrados
    Descrição: Permite a exibição da turma.
    Prioridade: Essencial
#### RF024 – Alterar Turma
    Atores envolvidos: Assistente de Alunos
    Descrição: Permite a alteração da turma.
    Prioridade: Essencial
#### RF025 – Excluir Turma
    Atores envolvidos: Assistente de Aluno
    Descrição: Permite a exclusão.
    Prioridade: Essencial
#### RF026 – Cadastrar Horário
    Atores envolvidos: Assistente de aluno
    Descrição: Permite o cadastro do horário.
    Prioridade: Essencial
#### RF027 – Listar Horário
    Atores envolvidos: Todos os usuários Cadastrados
    Descrição: Permite a exibição do Horário.
    Prioridade: Essencial
#### RF028 – Alterar Horário
    Atores envolvidos: Assistente do Aluno
    Descrição: Permite a alteração do horário.
    Prioridade: Essencial
#### RF029 – Excluir Horário
    Atores envolvidos: Assistente de Aluno
    Descrição: Permite a exclusão do horário.
    Prioridade: Essencial
#### RF030 – Autorizar Permuta Pontual
    Atores envolvidos: Coordenador de Disciplina.
    Descrição: Autoriza permuta de horarios pontuais.
    Prioridade: Essencial
#### RF031 – Autorizar Permuta fixa
    Atores envolvidos: Coordenador de Curso.
    Descrição: Autoriza permuta de horarios permanentes.
    Prioridade: Essencial
#### RF032 – Disponibilizar Horarios
    Atores envolvidos: Coordenador de Disciplina.
    Descrição: Disponibilizar horarios vagos para professores.
    Prioridade: Essencial
#### RF033 – Solicitar Anteposiçao
    Atores envolvidos: Coordenador de Disciplina,Professores.
    Descrição: Solicita anteposiçao de aulas.
    Prioridade: Essencial
#### RF034 – Solicitar Reposiçao
    Atores envolvidos: Coordenador de Disciplina.
    Descrição: Solicita reposiçao de aulas.
    Prioridade: Essencial
#### RF035 - Cadastrar Calendário
    Atores envolvidos: Assistente de Aluno.
    Descrição: Perminte o cadastro do calendário.
    Prioridade: Essencial.
#### RF036 - Mostrar Calendário
    Atores envolvidos: Assistente de Aluno.
    Descrição: Perminte a exibição do calendário.
    Prioridade: Essencial.
#### RF037 - Alterar Calendário
    Atores envolvidos: Assistente de Aluno.
    Descrição: Perminte a alteração do calendário.
    Prioridade: Essencial.
#### RF037 - Excluir Calendário
    Atores envolvidos: Assistente de Aluno.
    Descrição: Perminte a exclusão do calendário.
    Prioridade: Essencial.
## Requisitos Não-Funcionais
#### RNF001 – Impressão em preto-e-branco
    Descrição: As impressoras, em sua maioria, do Instituto Federal do Piauí Campus Parnaíba imprimem em escalas de tons de cinza (preto-e-branco). Assim, os relatórios do sistema,ao serem impressos, devem ser gerados em cores de escala de tons de cinza.e escala de tons de cinza.