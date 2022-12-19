Link para download do Git: https://git-scm.com/downloads

O Git Bash é um terminal extendido para otimizar o uso do Git.

# Comandos do Git bash

cd "local" - navega para o local

git status - mostra a situação dos arquivos (Se a branch main ta atualizada com o que ta no github, se algum arquivo não adicionado ou comitado, etc)

git add . / git add -A - Adiciona todos os arquivos ainda não adicionados para serem considerados no controle de versão local

git commit - Da um commit nos arquivos adicionados (Prepara todas as alterações para serem exportadas com o push)
 -m "Mensagem" - Adicione isso para escrever uma mensagem no commit criado (mensagens são importantes para se ter alterações bem documentadas)

git push origin main - Envia todos os commit para a nuvem (para o espaço do seu perfil relacionado ao projeto). "origin main" quer dizer que o commit será enviado para o bransh principal.