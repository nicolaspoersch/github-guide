# Documentação: Como Dar o Primeiro Commit no GitHub via Terminal

## 1. Configuração Inicial

Antes de começar, certifique-se de ter o Git instalado em sua máquina. Se não tiver, você pode baixá-lo em [git-scm.com](https://git-scm.com/downloads).

## 2. Crie um Repositório no GitHub

1. **Acesse o GitHub e Faça Login:**
   - Abra o seu navegador e vá para [GitHub](https://github.com/). Faça login na sua conta GitHub.

2. **Crie um Novo Repositório:**
   - Clique no sinal de "+" no canto superior direito da página e selecione "New repository" no menu suspenso.

3. **Preencha as Informações do Novo Repositório:**
   - Preencha o nome do repositório no campo "Repository name".
   - Adicione uma descrição opcional no campo "Description".
   - Escolha se deseja tornar o repositório público ou privado.
   - Selecione a opção "Initialize this repository with a README" se quiser criar um arquivo README no repositório.
   - Clique em "Create repository" para criar o novo repositório.

4. **Obtenha o Link do Repositório:**
   - Na página do repositório, clique no botão verde "Code".
   - Na janela pop-up, clique no ícone de cópia ao lado da URL para copiar o link do repositório.

## 3. No Terminal, Execute os Seguintes Comandos:

```bash
# Inicialize um repositório local
git init

# Adicione todos os arquivos ao stage
git add .

# Faça o primeiro commit
git commit -m "Primeiro commit"

# Crie uma nova branch (opcional)
git branch -M main

# Adicione o repositório remoto
git remote add origin <cole o link do repositório>

# Tente enviar as alterações para o GitHub
git push -u origin main
```

**Nota:** Caso encontre algum erro ao tentar o push você pode tentar forçar o push usando o seguinte comando:

```bash
git push -u --force origin main
```

Lembre-se que este comando tem que ser utilizado com cuidado pois pode substituir tudo e fazer você perder arquivos.

```bash
<!Documentação ainda não-finalizada!>
```
