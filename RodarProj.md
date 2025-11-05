# 🚀 Como Executar Localmente e Como Utilizar o sistema 🖥️

```bash
### Como Rodar o projeto?

- Baixe os arquivos necessesarios para rodar o sistema

### Abra o primeiro terminal

- De o comando cd desktop_interface
- Logo em seguida de .\venv\Scripts\Activate.ps1 para rodar a bibliotica virtual e não precisar baixar as extenções no computador
- Use o cd .. para voltar a pasta helpdesk_project

### Abra outro Terminal

- De o comando cd desktop_backend\HelpdeskApiFilter para acessar a pasta do backend
- Rode o comando cd restore para restaurar o backend
- Logo em seguida de o comando $env:GEMINI_API_KEY="SUA_CHAVE_AQUI" inserindo a chave api criada comunicar com o gemini
- Rode o comando cd run para rodar a api


### Volte para o 1 terminal e rode o codigo

- python -m desktop_interface.login ele ira abrir a tela de login do sistema
- Coloque suas credenciais e pronto, o sistema esta rodando, tente criar um chamado ou deletar/adicionar um usuario para testar o sistema
