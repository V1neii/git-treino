# git-treino

## 📦 Inicialização e Configuração do Repositório
``git init``
Inicia um novo repositório Git local.

``git remote add origin https``
Adiciona o repositório remoto com o nome origin (o https deve ser a URL do repositório remoto).

## 📁 Gerenciamento de Arquivos
``git add``
Adiciona todos os arquivos (ou arquivos específicos) ao staging area para serem commitados.

``git commit -m ""``
Cria um commit com a mensagem entre aspas. Ex: git commit -m "mensagem".

``git status``
Mostra o estado atual dos arquivos (modificados, staged, não rastreados, etc.).

``git reset --soft HEAD~1``
Desfaz o último commit, mas mantém as mudanças no staging area.

## 🌱 Branches
``git branch``
Lista todas as branches locais.

``git branch -M ""``
Renomeia a branch atual para o nome especificado. Ex: git branch -M main.

``git branch -D "nome_da_branch"``
Deleta forçadamente a branch local especificada.

``git checkout "nome_da_branch"``
Troca para a branch especificada.

``git checkout -b "nome_da_branch"``
Cria e já troca para uma nova branch.

## 🔀 Integração e Sincronização
``git merge``
Junta a branch atual com outra (é necessário especificar a outra branch depois do comando, ex: git merge develop).

``git pull origin "nome_da_branch"``
Busca e integra alterações da branch remota especificada.

``git push -u origin "nome_da_branch"``
Envia a branch atual para o repositório remoto. (⚠️ https parece estar fora do lugar — aqui deveria ser o nome da branch.)

``git push origin "nome_da`_branch"``
Envia a branch especificada para o repositório remoto.

## 📥 Clonagem e Fork
``git clone https``
Clona um repositório remoto para o seu computador local (⚠️ https deve ser a URL completa do repositório).

``git fork``
Esse não é um comando Git. Fork é uma ação feita via GitHub (ou outro serviço similar) para criar uma cópia de um repositório.

## :pencil: Recomendação de canais de Python e programação no geral:
- Programador Lhama: https://www.youtube.com/@ProgramadorLhama/videos
- Téo Me Why: https://www.youtube.com/@teomewhy
- Rafaella Ballerini: https://www.youtube.com/@rafaellaballerini
- Eduardo Mendes: https://www.youtube.com/@Dunossauro
- Augusto Galego: https://www.youtube.com/@GutoGalego
