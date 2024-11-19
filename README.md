## Atividade 1

### Comandos básicos do Git

1. **`cmdkey /delete:LegacyGeneric:target=git:https://github.com`**

Exclui todas as credenciais armazenadas anteriormente no computador.

2. **`git config --global user.name "<nome>"`**

Configura seu nome de usuário para todos os repositórios Git no seu computador.

3. **`git config --global user.email "<e-mail>"`**

Configura seu e-mail para todos os repositórios Git no seu computador.

4. **`git init`**

Cria um novo repositório Git no seu projeto.

5. **`git clone <url>`**

Copia um repositório que está online para o seu computador.

6. **`git add <arquivo>`**

Adiciona um arquivo para que seja salvo no próximo "commit" (salvamento). **`git add .`** adiciona todos os arquivos e pastas no diretório atual.

7. **`git commit -m "<mensagem>"`**

Salva suas mudanças com uma descrição do que foi alterado.

8. **`git status`**

Mostra quais arquivos foram modificados e o que está pronto para ser salvo.

9. **`git push`**

Envia suas mudanças para o repositório online. **`git push -u origin main`** envia suas alterações na "branch" (bifurcação) "main" para o repositório remoto e configura o Git para lembrar onde enviar suas mudanças no futuro.

10. **`git pull`**

Baixa e aplica as mudanças do repositório online para o seu computador.

11. **`git branch <nome>`**

Cria uma nova "branch" para você trabalhar em algo novo. Por exemplo, **`git branch -M main`** renomeia a branch atual para "main".

12. **`git remote add origin <url>`**

Conecta o seu repositório local a um repositório remoto online.

13. **`git log`**

Mostra um histórico de todas as mudanças que foram salvas.

## Atividade 4
1. Para inicializar o Git em um novo repositório: `git init`
2. Para adicionar as alterações realizadas no repositório: `git add`
3. Para gravar as alterações: `git commit`
4. Para enviar as alterações para a nuvem/repositório online: `git push`
5. Se o repositório em meu computador estiver desatualizado, como faço para atualizá-lo? Lembrando que estarei atualizando com base no repositório salvo no GitHub: `git pull`