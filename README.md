# Atividade-da-disciplina-ASOO-projeto
Cenário: Uma empresa de médio porte possui um setor de TI responsável por atender solicitações internas de suporte técnico. Atualmente todas as requisições são recebidas por e-mail ou telefone, o que gera dificuldades no controle dos chamados, atrasos e falhas na priorização. A empresa deseja adotar um sistema integrado, no qual os colaboradores possam registrar suas solicitações e a IA possa sugerir soluções automáticas ou encaminhar ao técnico adequado com base no histórico de chamados e complexidade do problema.


## Equipe

* PO: Ana Clara Leão Ferreira
* ScrumMaster: Igor Sene Idalgo
* Devs: Mauricio R. Verdussen, Pedro Henrique T. de Carvalho, Henry M. Damasceno Santos, Vinícius Gobis Novo.

## Requisitos funcionais:
* Cadastro de usuário: Usufruidores podem cadastrar no sistema;
*  Autenticação de login com diferentes níveis de acesso;
*  Abertura de chamados: Usuários podem registrar requisições de suporte;
* Classificação inteligente: A IA analisa os chamados e, com base no histórico de chamados anteriores, sugere soluções às requisições antes de encaminhar ao suporte técnico adequado.

## Requisitos não funcionais:
* Banco de dados em sql server;
* Segurança;
* Modularidade.

## Backlog
Sprint 1: Infraestrutura e Base do Sistema
* Configuração do ambiente de desenvolvimento
* Configuração do banco de dados SQL Server
* Definição da arquitetura do sistema (modularidade)
* Implementação inicial da segurança (criptografia de senhas, autenticação básica)

Sprint 2: Cadastro e Autenticação
* Desenvolvimento do cadastro de usuários
* Implementação da autenticação com diferentes níveis de acesso
* Validação e testes iniciais

Sprint 3: Abertura de Chamados
* Criar a funcionalidade para abertura de chamados
* Interface para exibição dos chamados abertos
* Testes de integração com banco de dados

Sprint 4: Classificação Inteligente (IA)
* Treinamento inicial da IA com base no histórico de chamados (dados fictícios se necessário)
* Implementação da sugestão automática de soluções
* Testes e ajustes no modelo

Sprint 5: Refinamento e Segurança
* Melhorias na segurança do sistema
* Ajustes na modularidade e refatoração do código
* Testes finais e documentação

## Modelagem De Requisitos

### Casos de Uso

O diagrama de caso abaixo representa o fluxo de ações realizadas por um funcionário e uma inteligência artificial (IA) em um sistema de suporte técnico.

[![Image](https://github.com/user-attachments/assets/c5de1ded-f814-4892-8a5e-85e6c33f53a1)](https://github.com/IgorIdalgo/Atividade-da-disciplina-ASOO-projeto/issues/2#issue-2947327498)


O funcionário faz login no sistema e, assim que validado, abre o chamado. A IA recebe o chamado e realiza a triagem para validar sua procedência.

Após a validação, a IA determina a urgência do chamado em três níveis: urgência alta, média urgência e baixa urgência.

Em seguida, a IA atribui o chamado a um setor e analisa se o problema pode ser resolvido por ela mesma. Se conseguir, a solução é encaminhada ao usuário; caso contrário, um técnico da área é acionado.

Por fim, o chamado é encerrado.

### Classe
Diagrama de Classe.

![Image](https://github.com/user-attachments/assets/9800321e-7027-4b52-8c19-f4d7e421e55b)

Diagrama de classe, de um sistema de suporte onde a IA auxilia o técnico na triagem de níveis de importância dos chamados, e sugere soluções praticas e mais rápidas. O sistema também possui um histórico para armazenar os chamados já resolvidos.
### Sequência
Diagrama de sequência.
![Image](https://github.com/IgorIdalgo/Atividade-da-disciplina-ASOO-projeto/blob/main/diagrama%20de%20sequencia.png)


### Implantação
![Image](https://github.com/IgorIdalgo/Atividade-da-disciplina-ASOO-projeto/blob/main/Diagram%20de%20Implanta%C3%A7%C3%A3o)
