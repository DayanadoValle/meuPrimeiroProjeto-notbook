# 🚀 Guia de Comandos Git - Passo a Passo

Repositório criado para documentar os primeiros passos no Git e GitHub em 2026.

---

### 🛠️ 1. Configuração de Identidade
Configura quem é você no Git:
* `git config --global user.name "SeuNome"`
* `git config --global user.email "SeuEmail"`

### 📁 2. Criando o Repositório Local
Comandos para criar a pasta e preparar o Git:
* `"mkdir nome-do-projeto   # Cria a pasta
cd nome-do-projeo"`     # Entra na pasta
git init             # Transforma em repositório

### 🔗 3. Conectando ao GitHub
Vincula a pasta do seu computador ao site do GitHub:

```bash
git remote add origin github.com
git remote -v

###⬆️ 4. Enviando Alterações (Fluxo Diário)
Preparar os arquivos:

```bash
git add .
Use o código com cautela.

Gravar a versão (Commit):
bash
git commit -m "Sua mensagem aqui"
Use o código com cautela.

Combin para a†:
bash
git push origin main
Use o código com cautela.

🔍 5. Comandos de Verificação
Para monitorar o estado do seu projeto:
Status dos arquivos: git status
Histórico de versões: git log --oneline
Verificar ramificação: git branch
