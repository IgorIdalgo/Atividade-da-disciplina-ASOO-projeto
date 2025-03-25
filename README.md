# Atividade-da-disciplina-ASOO-projeto
Cenário: Uma empresa de médio porte possui um setor de TI responsável por atender solicitações internas de suporte técnico. Atualmente todas as requisições são recebidas por e-mail ou telefone, o que gera dificuldades no controle dos chamados, atrasos e falhas na priorização. A empresa deseja adotar um sistema integrado, no qual os colaboradores possam registrar suas solicitações e a IA possa sugerir soluções automáticas ou encaminhar ao técnico adequado com base no histórico de chamados e complexidade do problema.


## Equipe

* PO:
* ScrumMaster:
* Devs:


## Backlog

### Requisitos funcionais:
* Gerenciamento de chamados;
* Autenticação de usuário;
* Modulagem de IA.

### Requisitos não funcionais:
* Proteção dos dados sensíveis seguindo a LGPD

## Modelagem De Requisitos

### Casos de Uso

O diagrama de caso abaixo representa o fluxo de ações realizadas por um funcionário e uma inteligência artificial (IA) em um sistema de suporte técnico.

[![Image](https://github.com/user-attachments/assets/c5de1ded-f814-4892-8a5e-85e6c33f53a1)](https://github.com/IgorIdalgo/Atividade-da-disciplina-ASOO-projeto/issues/2#issue-2947327498)

O funcionário faz login no sistema e, assim que validado, abre o chamado. A IA recebe o chamado e realiza a triagem para validar sua procedência.

Após a validação, a IA determina a urgência do chamado em três níveis: urgência alta, média urgência e baixa urgência.

Em seguida, a IA atribui o chamado a um setor e analisa se o problema pode ser resolvido por ela mesma. Se conseguir, a solução é encaminhada ao usuário; caso contrário, um técnico da área é acionado.

Por fim, o chamado é encerrado.

### Classe

### Sequência

### Implantação
