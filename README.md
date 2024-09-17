# Comandos básicos do Git

1. **`git config --global user.name "<nome>"`**

Configura seu nome de usuário para todos os repositórios Git no seu computador.

2. **`git config --global user.email "<email>"`**

Configura seu e-mail para todos os repositórios Git no seu computador.

3. **`git init`**

Cria um novo repositório Git no seu projeto.

4. **`git clone <url>`**

Copia um repositório que está online para o seu computador.

5. **`git add <arquivo>`**

Adiciona arquivos para que eles sejam salvos no próximo "commit" (salvamento). **`git add .`** adiciona todos os arquivos e pastas no diretório atual.

6. **`git commit -m "<mensagem>"`**

Salva suas mudanças com uma descrição do que foi alterado.

7. **`git status`**

Mostra quais arquivos foram modificados e o que está pronto para ser salvo.

8. **`git push`**

Envia suas mudanças para o repositório online. **`git push -u origin main`** envia suas alterações na "branch" "main" para o repositório remoto e configura o Git para lembrar onde enviar suas mudanças no futuro.

9. **`git pull`**

Baixa e aplica as mudanças do repositório online para o seu computador.

10. **`git branch <nome>`**

Cria uma nova "branch" para você trabalhar em algo novo. Por exemplo, **`git branch -M main`** renomeia a branch atual para "main".

11. **`git remote add origin <url>`**

Conecta o seu repositório local a um repositório remoto online.

12. **`git log`**

Mostra um histórico de todas as mudanças que foram salvas.
