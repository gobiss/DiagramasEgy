# 📌 HelpDesk Inteligente

## 👤 Dev do Projeto

| Nome do Aluno        | RA       | Turma   |
|-----------------------|----------|---------|
| Vinícius Gobis Novo   | G967BG0  | DS4P48  |

---

# 🎯 Desafio do Projeto

Atualmente, empresas e usuários enfrentam dificuldades na abertura e gestão de chamados de suporte técnico.  
Os problemas de hardware e software muitas vezes não são classificados corretamente, o que causa:

- Atrasos na resolução dos chamados  
- Retrabalho para a equipe de TI  
- Acúmulo de chamados pendentes  
- Insatisfação dos usuários  

O desafio deste projeto é *desenvolver um sistema de chamados inteligente*, que permita:  
- Registrar e acompanhar chamados de forma organizada  
- Garantir níveis de acesso diferenciados para usuários, técnicos e administradores  
- Integrar uma *IA* capaz de sugerir soluções automáticas com base no histórico de chamados, agilizando a triagem e reduzindo tempo de atendimento  

---

# 📋 Backlog do Produto

### Sprint 1: Infraestrutura e Base do Sistema
- Configuração do ambiente de desenvolvimento  
- Configuração do banco de dados SQL Server  
- Definição da arquitetura do sistema (modularidade)  
- Implementação inicial da segurança (criptografia de senhas, autenticação básica)  

### Sprint 2: Cadastro e Autenticação
- Desenvolvimento do cadastro de usuários  
- Implementação da autenticação com diferentes níveis de acesso  
- Validação e testes iniciais  

### Sprint 3: Abertura de Chamados
- Criar a funcionalidade para abertura de chamados  
- Interface para exibição dos chamados abertos  
- Testes de integração com banco de dados  

### Sprint 4: Classificação Inteligente (IA)
- Treinamento inicial da IA com base no histórico de chamados (dados fictícios se necessário)  
- Implementação da sugestão automática de soluções  
- Testes e ajustes no modelo  

### Sprint 5: Refinamento e Segurança
- Melhorias na segurança do sistema  
- Ajustes na modularidade e refatoração do código  
- Testes finais e documentação  

---

## 📅 Cronograma de Evolucão do Projeto

![Cronograma do Projeto](https://github.com/gobiss/DiagramasEgy/blob/86c2b3dc3db08b49ff9e1131b0a5e0f1bbf9961d/Cronograma%20do%20Projeto.png)

---

# 📊 Tabela das Sprints

| Sprint | Período (2025) | Objetivos | Entregas | Documentação |
|--------|----------------|-----------|----------|--------------|
| *Sprint 1 — Infraestrutura e Base* | *10/02 – 23/02* | Configuração do ambiente, banco de dados e segurança inicial | Ambiente dev configurado, SQL Server, arquitetura modular, criptografia de senhas. | 
| *Sprint 2 — Cadastro e Autenticação* | *24/02 – 09/03* | Cadastro de usuários e autenticação com níveis de acesso | CRUD de usuários, login/logout, RBAC, testes iniciais. |
| *Sprint 3 — Abertura de Chamados* | *10/03 – 23/03* | Criar e exibir chamados integrados ao banco | Formulário de abertura, listagem de chamados, integração com DB. | 
| *Sprint 4 — Classificação Inteligente (IA)* | *24/03 – 06/04* | Treino inicial da IA e sugestão de soluções | Modelo de classificação, endpoint de sugestão, métricas iniciais.
| *Sprint 5 — Refinamento e Segurança* | *07/04 – 20/04* | Refino final, segurança e documentação | Melhorias de segurança, ajustes de modularidade, testes finais, docs. | 
| *Entrega Final* | *24/05* | Versão 1.0 entregue | Sistema prototipo pronto + documentação completa. |

---
## 🛠️ Tecnologias Utilizadas
- *Linguagem:* C#  
- *Frameworks:* ASP.NET Core, Entity Framework  
- *Banco de Dados:* SQL Server  
- *Ferramentas de Apoio:* Figma (prototipagem) e Astah (modelagem de diagramas)

---
## 🖥️ Como Utilizar

O *HelpDesk Inteligente* permite:  
- *Usuário:* criar conta, abrir chamados, acompanhar e encerrar chamados.  
- *Técnico:* visualizar, classificar, atualizar e fechar chamados.  
- *Administrador:* gerenciar usuários, permissões e acompanhar métricas.  

---

## 🚀 Como Executar Localmente

```bash
# clone o repositório
git clone https://github.com/seu-repo.git
cd helpdesk-inteligente

# restaure pacotes e crie o banco
dotnet restore
dotnet ef database update

# rode o projeto
dotnet run
