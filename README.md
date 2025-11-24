# Problema.suap
Desenvolvendo melhorias para digitalizar o processo de advertências 
1. Escopo do Projeto
-  Garantir que os pais sejam alertados das ocorrências dos filhos 
-  Cadastro simultâneo de infrações escolares
-  Responsável seja alertado a cada ocorrência
2. Problema
2.1 Instrução do Problema
O problema é:  As falhas que ocorrem de alunos com infrações não serem punidos
descrever o problema: Alunos que excederem o limite de ocorrência não comunica os pais/alunos não cadastrados as ocorrências
O que afeta:A coordenação do curso
Descrever o que afeta,quem afeta: Traz dores de cabeça para a coordenação do curso
O impacto do problema é: Em não manter o controle dessas ações do alunos
Que "prejuízos" causa: Traz prejuízo a moral da coordenação
Uma solução seria: Garantir as punições
Descreva a sua solução: Garantir que as imprudências sejam punidas/informadas

2.2 Problemas a serem resolvidos

Problema:Descumprimento das regras disciplinares 
Descrição:Alunos que não cumprem as medidas que devem ser seguidas 

3. Descrição da Parte Interessada e do Usuário
Parte Interessada: Coordenação,Direção,Pais
Usuários: Alunos,Pais,Coordenador,Professor

4. Visão Geral do Produto
E um sistema que garante a organização dos termos que devem ser seguidas no IFPI 

4.1 Perspectiva do Produto
Ele faz parte do sistema escolar onde ele tem informações dos alunos tem
contato do responsável interagem com os funcionários, mantém o controle de infrações

4.2 Resumo dos Recursos
| Recursos | Descrição |
|---|---|
|Cadastrar infrações de |Realiza o cadastro de infrações de alunos|
|Controla a quantidade de infrações de alunos|Faz a verificação se alunos já excederam o limite de infrações
|Comunica os responsáveis|Garante o contato com o responsável
|Permite que o coordenador registre ocorrências de alunos|Garante que a ocorrência vai ser realmente cadastrada

5. Recursos do Produto(Funcionalidades)
Manter infrações.
Garantir que os alunos que estouraram o limite de infrações sejam penalizados.
Faz a comunicação entre a escola e o responsável.
Coordenação de manter infrações acadêmicas.
Aluno/Responsáveis consultar infrações
6. Casos de Uso


6.1 Diagrama de Casos de Uso
   
![Diagrama](https://raw.githubusercontent.com/Gringol07/Problema.suap/main/Diagrama%20aula.aps.drawio.png)


6.2 Fluxo de Casos de Uso
- O coordenador acessa o sistema e registra uma infração para o aluno.
- O sistema salva a infração e atualiza a quantidade total do aluno.
- O sistema verifica se o aluno atingiu ou ultrapassou o limite de infrações.
Se o limite for ultrapassado, o sistema gera uma penalidade e comunica o responsável.
- Se o responsável estiver cadastrado, ele recebe a notificação caso contrário, o sistema alerta a coordenação para completar o cadastro.
- Responsáveis ou coordenadores podem consultar as infrações registradas no sistema a qualquer momento.
- Aluno é avisado em um intervalo de dias quantas infrações faltam para ele ser penalizado. 
- O sistema mantém o histórico organizado e garante que a coordenação tenha controle sobre as ocorrências.

7. Restrições
O sistema só pode ser acessado por coordenadores, professores, alunos e responsáveis.


O cadastro de infrações só pode ser feito pelo coordenador ou professor.


Notificações só são enviadas se existir responsável cadastrado.


O aluno só pode ser penalizado após ultrapassar o limite definido pela escola.


O sistema deve seguir as regras disciplinares do IFPI.

7.1 Restrições de Design
- O sistema deve funcionar de forma online, acessado pelo navegador.
- O sistema deve possuir interface simples e intuitiva para uso por coordenadores e professores.
- O sistema deve permitir consulta rápida ao histórico de infrações.
- O sistema deve possibilitar futuras expansões, como relatórios e integração com sistemas maiores.
7.2 Restrições de Segurança
- Apenas usuários autenticados podem acessar o sistema.
- Coordenadores e professores têm permissões diferentes dos alunos e responsáveis.
-Dados dos alunos e responsáveis devem ser protegidos e não podem ser acessados por usuários não autorizados.


- Notificações enviadas devem conter apenas informações necessárias para evitar exposição indevida.


- O sistema deve registrar quem fez cada ação

7.3 Restrições de Metodologia (Processos e Ferramentas)

- A equipe deve seguir um padrão de desenvolvimento organizado, utilizando documentação simples e clara para registrar decisões importantes do projeto.


-Deve ser utilizada uma metodologia de trabalho que permita revisões rápidas, garantindo que o sistema esteja sempre alinhado com as necessidades da coordenação do IFPI.


- Todas as funcionalidades devem ser validadas com a coordenação antes de serem finalizadas, evitando retrabalho e garantindo que o sistema realmente resolva o problema.


- As ferramentas escolhidas para o desenvolvimento devem ser de fácil manutenção, permitindo que qualquer membro da equipe consiga entender o código e dar continuidade ao projeto.


- O código deve ser versionado, para evitar perda de informações e facilitar o controle de mudanças.



