# Projeto Dayanadovalle
📝 Guia Rápido de Comandos Git
1. Configuração Inicial (Apenas uma vez)
Configure sua identidade para que o GitHub saiba quem fez as alterações:
bash
git config --global user.name "Seu Nome"
git config --global user.email "seu.email@exemplo.com"
Use o código com cautela.

2. Iniciando um Projeto Local
Crie uma pasta e transforme-a em um repositório Git:
bash
mkdir nome-do-projeto    # Cria a pasta
cd nome-do-projeto       # Entra na pasta
git init                 # Inicia o Git
Use o código com cautela.

3. Conectando com o GitHub
Após criar o repositório no site do GitHub , conecte a pasta do seu PC com a nuvem:
bash
git remote add origin github.com
Use o código com cautela.

4. O Ciclo de Trabalho (O que você fará no dia a dia)
Sempre que criar ou alterar arquivos, siga estes 3 passos:
Preparar os arquivos:
bash
git add .
Use o código com cautela.

Salvar a versão (Commit):
bash
git commit -m "Explique o que você fez aqui"
Use o código com cautela.

Enviar para o GitHub:
bash
git push origin main
Use o código com cautela.

5. Comandos de Verificação
Para saber o que está acontecendo:
git status: Mostra quais arquivos foram alterados.
git remote -v: Mostra a qual repositório do GitHub você está conectado.
git log: Mostra o histórico de commits (salvamentos).
