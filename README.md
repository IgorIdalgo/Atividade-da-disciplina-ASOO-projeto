# 📌 Atividade da Disciplina – ASOO Projeto  

## 📝 Descrição do Desafio  
Uma empresa de médio porte possui um setor de TI responsável por atender solicitações internas de suporte técnico. Atualmente todas as requisições são recebidas por e-mail ou telefone, o que gera dificuldades no controle dos chamados, atrasos e falhas na priorização.  
A empresa deseja adotar um **sistema integrado**, no qual os colaboradores possam registrar suas solicitações e a **IA** possa sugerir soluções automáticas ou encaminhar ao técnico adequado com base no histórico de chamados e na complexidade do problema.  

---

## 👨‍💻 Equipe  
- **PO**: Ana Clara Leão Ferreira  
- **Scrum Master**: Igor Sene Idalgo  
- **Devs**: Mauricio R. Verdussen, Pedro Henrique T. de Carvalho, Henry M. Damasceno Santos, Vinícius Gobis Novo  

---

## 📋 Requisitos  

### Funcionais  
- Cadastro de usuário: usufruidores podem se cadastrar no sistema  
- Autenticação de login com diferentes níveis de acesso  
- Abertura de chamados: usuários podem registrar requisições de suporte  
- Classificação inteligente: IA analisa chamados e sugere soluções ou encaminha ao técnico adequado  

### Não Funcionais  
- Banco de dados em **SQL Server**  
- Segurança  
- Modularidade  

---

## 📆 Backlog do Produto  

### Sprint 1 – Infraestrutura e Base do Sistema  
- Configuração do ambiente de desenvolvimento  
- Configuração do banco de dados SQL Server  
- Definição da arquitetura do sistema (modularidade)  
- Implementação inicial da segurança (criptografia de senhas, autenticação básica)  

### Sprint 2 – Cadastro e Autenticação  
- Desenvolvimento do cadastro de usuários  
- Implementação da autenticação com diferentes níveis de acesso  
- Validação e testes iniciais  

### Sprint 3 – Abertura de Chamados  
- Criar a funcionalidade para abertura de chamados  
- Interface para exibição dos chamados abertos  
- Testes de integração com banco de dados  

### Sprint 4 – Classificação Inteligente (IA)  
- Treinamento inicial da IA com base no histórico de chamados (dados fictícios se necessário)  
- Implementação da sugestão automática de soluções  
- Testes e ajustes no modelo  

### Sprint 5 – Refinamento e Segurança  
- Melhorias na segurança do sistema  
- Ajustes na modularidade e refatoração do código  
- Testes finais e documentação  

---

## 📊 Tabela de Sprints  

| Sprint   | Período             | Objetivos                     | Entregas |
|----------|---------------------|-------------------------------|----------|
| Sprint 1 | 03/06 - 09/06/2024  | Infraestrutura e base do sistema | Ambiente, DB, segurança inicial |
| Sprint 2 | 10/06 - 16/06/2024  | Cadastro e autenticação        | Cadastro + login |
| Sprint 3 | 17/06 - 23/06/2024  | Abertura de chamados           | CRUD de chamados |
| Sprint 4 | 24/06 - 30/06/2024  | Classificação inteligente      | IA treinada + sugestões |
| Sprint 5 | 01/07 - 07/07/2024  | Refinamento e testes           | Sistema ajustado + documentação |

---

## 📚 Modelagem de Requisitos  

### 🔹 Casos de Uso  
![Diagrama de Caso de Uso](https://github.com/user-attachments/assets/2fa7933b-9304-485c-93a4-ed86c0ff05a8)  

Fluxo:  
1. Funcionário faz login → abre chamado  
2. IA recebe e valida chamado  
3. IA define prioridade (alta, média, baixa)  
4. IA resolve ou encaminha ao técnico  
5. Chamado encerrado  

---

### 🔹 Diagrama de Classes  
![Diagrama de Classes](https://github.com/user-attachments/assets/7bb3bd64-5d5b-4eea-ab1b-bb5b1da051b5)  

Representa a estrutura do sistema, com suporte da IA para triagem, histórico e priorização dos chamados.  

---

### 🔹 Diagrama de Sequência  
![Diagrama de Sequência](https://github.com/user-attachments/assets/4be00269-b933-4ac1-b8b5-2aa26f15ceb1)  

---

### 🔹 Diagrama de Implantação  
![Diagrama de Implantação](https://github.com/IgorIdalgo/Atividade-da-disciplina-ASOO-projeto/blob/main/Diagrama%20de%20Implantacao%20.jpg)  

Representa a arquitetura do sistema de chamados com IA.  

---

## 🛠️ Tecnologias Utilizadas  
- **SQL Server** – banco de dados  
- **(Definir linguagens/frameworks usados, ex: C#, .NET, Java, Node.js, etc.)**  
- **Ferramentas de versionamento**: Git/GitHub  

---

## ▶️ Como Executar o Projeto  
```bash
# Clonar repositório
git clone https://github.com/IgorIdalgo/Atividade-da-disciplina-ASOO-projeto

# Entrar na pasta do projeto
cd Atividade-da-disciplina-ASOO-projeto

# (Rodar comandos de instalação conforme a tecnologia escolhida)
