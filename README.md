# 🚀 Guia de Comandos Git - Passo a Passo

Repositório Git e GitHub em 2026.

---

### 🛠️ 1. Configuração de Identidade
* `git config --global user.name "SeuNome"`
* `git config --global user.email "seuEmail"`

### 📁 2. Criando o Repositório Local
```bash
mkdir meu-projeto
cd meu-projeto
git init
```

### 🔗 3. Conectando ao GitHub
```bash
git remote add origin github.com/seuRepositorioRemoto
git remote -v
```

### ⬆️ 4. Fluxo de Trabalho (O Dia a Dia)
1. **Adicionar:** `git add .`
2. **Salvar:** `git commit -m "mensagem"`
3. **Enviar:** `git push origin main`

### 🔍 5. Comandos de Verificação
* `git status`
* `git log --oneline`
* `git branch`
