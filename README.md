# 📌 HelpDesk Inteligente

## 👤 Dev do Projeto

| Nome do Aluno        | RA       | Turma   |
|-----------------------|----------|---------|
| Vinícius Gobis Novo   | G967BG0  | DS4P48  |

## Status do Projeto 📊

## 📌 Status do Projeto

| Projeto          | Status        |
|------------------|---------------|
| Sistema HelpDesk | 🟡 Em andamento |

---

# Requisitos Levantados 📝

[Requsitos](./Requisitos.md)

---

# Casos de Uso

[Imagem do diagrama de Caso de Uso](./Sistema%20Helpdesk%20integrado%20a%20IA.png)
O diagrama acima representa os *principais fluxos do sistema HelpDesk Inteligente* e os diferentes papéis de usuários.  

- *Colaborador:* pode autenticar-se, abrir chamados, acompanhar o andamento, receber notificações e fechar chamados quando resolvidos.  
- *Técnico:* tem acesso às funcionalidades de gestão dos chamados, podendo visualizar, classificar, atualizar, atribuir a si mesmo ou a outros técnicos, além de registrar soluções e encerrar chamados.  
- *Administrador:* possui permissões avançadas para gerenciar usuários, definir níveis de acesso e gerar relatórios do sistema.  

Também estão representadas funcionalidades de *notificações* (e-mail, sistema e atribuição), *pesquisa de chamados* (por filtros e exportação) e a integração de *IA* para sugerir soluções e apoiar a triagem.  

Esse diagrama fornece uma visão geral clara de como os diferentes atores interagem com o sistema, ajudando a entender os requisitos funcionais do projeto.

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

[Backlog](./Backlog.md)

---

## 📅 Cronograma de Evolucão do Projeto

[Imagem do Cronograma](./Cronograma%20do%20Projeto.png)
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
[Tecnologias](./Tecnologias.md)

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
git clone https://github.com/meu-repositorio.git
cd helpdesk-inteligente

# restaure pacotes e crie o banco
dotnet restore
dotnet ef database update

# rode o projeto
dotnet run
