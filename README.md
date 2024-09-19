## Atividade 1

### Comandos básicos do Git

1. **`git config --global user.name "<nome>"`**

Configura seu nome de usuário para todos os repositórios Git no seu computador.

2. **`git config --global user.email "<e-mail>"`**

Configura seu e-mail para todos os repositórios Git no seu computador.

3. **`git init`**

Cria um novo repositório Git no seu projeto.

4. **`git clone <url>`**

Copia um repositório que está online para o seu computador.

5. **`git add <arquivo>`**

Adiciona um arquivo para que seja salvo no próximo "commit" (salvamento). **`git add .`** adiciona todos os arquivos e pastas no diretório atual.

6. **`git commit -m "<mensagem>"`**

Salva suas mudanças com uma descrição do que foi alterado.

7. **`git status`**

Mostra quais arquivos foram modificados e o que está pronto para ser salvo.

8. **`git push`**

Envia suas mudanças para o repositório online. **`git push -u origin main`** envia suas alterações na "branch" (bifurcação) "main" para o repositório remoto e configura o Git para lembrar onde enviar suas mudanças no futuro.

9. **`git pull`**

Baixa e aplica as mudanças do repositório online para o seu computador.

10. **`git branch <nome>`**

Cria uma nova "branch" para você trabalhar em algo novo. Por exemplo, **`git branch -M main`** renomeia a branch atual para "main".

11. **`git remote add origin <url>`**

Conecta o seu repositório local a um repositório remoto online.

12. **`git log`**

Mostra um histórico de todas as mudanças que foram salvas.

## Atividade 4
1. Para inicializar o Git em um novo repositório: `git init`
2. Para adicionar as alterações realizadas no repositório: `git add`
3. Para gravar as alterações: `git commit`
4. Para enviar as alterações para a nuvem/repositório online: `git push`
5. Se o repositório em meu computador estiver desatualizado, como faço para atualizá-lo? Lembrando que estarei atualizando com base no repositório salvo no GitHub: `git pull`