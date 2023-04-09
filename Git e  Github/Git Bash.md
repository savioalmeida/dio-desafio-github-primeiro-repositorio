# Comando básicos para poder utilizar o terminal do Git bash.

* **Ctrl + L :** Serve para limpar o ambiente do terminal.

* **ls:** Serve para listar arquivou diretórios.

* **pwd:** Serve para mostrar o caminho completo do diretório

* **cd:** Serve para mudar de diretórios.

* **ssh-add:** Esse comando possibilita adicionar uma chave SSH.

* **eval $ (ssh - agent  -s):** Com ele você pode inicializar as chaves SSH.

* **cat:** Possibilita visualiza o conteúdo das chaves SSH. 

* **git init [nome do repositório]:** Com ele você consegue inicializar o git dentro do diretório, podendo criar ou iniciar um novo repositório git.

* **git config --global:** Serve apara setar uma configuração no git bash.

* **git config --liste:** Vai listar todas as configurações do git.

* **git config --global --unset + "propriedade que você deseja mudar":**  Com ela é possível resetar a configuração estabelecida para aquela propriedade.
  Exemplos(s):

  ```
  git config --global --unset user.name
  git config --global --unset user.email
  ```

* **git config --global --replace-all + "propriedade que você ira alterar":** Com ela é possível atribuir/configurar um valor a propriedade que escolher.
  Exemplo(s):

  ```
  git config --global --replace-all user.name "Your New Name"
  
  git config --global --replace-all user.email "Your new email"
  ```

* **git config --global --remove-section user:** é usado quando o usuário adiciona mais propriedades que não tinham necessidade.
* **git remove:** Esse comando lista as conexões remotas que você tem com outros repositórios.