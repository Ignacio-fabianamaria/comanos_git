
# 🐙 Versionamento Git/Github



## 💻 Comandos Git
<details>
<summary> 🟢 Desfazendo alterações no repositório local</summary>

Comando| Descrição
-------|----------
rm -rf .git | Desfaz um repositório Git
git restore [nome-doarq] | Desfaz a ultima alteração localmente
git commit --amend -m"" | Altera o nome da mensagem do ultimo commit
git reset --soft [hash do commit] | Desfaz o commit e deixar os dados em staging area
git reset --mixed [hash do commit] | Desfaz o comit e desfaz o staging area
git reset --hard [hash do commit] | Desfaz o commit e reverter o estado para o commit anterior
git reset [nome-do-arq] | Desfaz o arquivo
git restore --staged [nome-do-arq] | Desfaz o arq que estava em staging area

</details>

<details>
<summary> 🟢 Enviando e baixando alterações com o repositório remoto</summary>

Comando| Descrição
-------|----------
git remote origin [URL] | Conectar com repositório Remoto
git push -u origin main | Envia alterações locais para um repositório remoto
git pull | Puxa alterações do repositório remoto para o repositório local

</details>

<details>
<summary> 🟢 Trabalhando com Breaches</summary>

Comando| Descrição
-------|----------
git checkout -b [nome] | Cria uma nova branch e altera para ela
git branch | lista todas as branches
git checkout [nome da breach] | Altera para branch especificada
git branch -v | Lista o ultimo commit de cada breach
git merge [nome-breanch-para-mesclar] | Mesclar  brenches 
git branch -d [nome-da-breach] | Excluir brench
git fetch | Buscar todas as alterações que foram feitas em um repositório 
git diff | Usado para visualizar as diferenças entre diferentes estados do seu repositório Git
git diff --staged | Mostra diferenças entre a área de staging e o último commit
git diff <branch1> <branch2> | compara diferenças entre duas ramificações 

</details>
