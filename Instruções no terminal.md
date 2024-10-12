
# ⚙️ Configurando e Utilizando o GitHub no Terminal
Testando
Este guia rápido ensinará como configurar o GitHub no seu terminal e realizar um fluxo básico de trabalho com os comandos principais do Git. 

## 1. Instalação do Git

Antes de começar, certifique-se de ter o Git instalado na sua máquina. Para verificar, use o comando:

```bash
git --version
```

Se o Git não estiver instalado, siga as instruções no site oficial para instalar: [Instalação do Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

## 2. Configurando suas credenciais Git

Depois de instalar o Git, configure suas informações de usuário para que seus commits sejam associados ao seu nome e e-mail.

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

Você pode verificar suas configurações com:

```bash
git config --list
```

## 3. Conectando ao GitHub

Você precisa de uma autenticação para se conectar ao GitHub. A maneira mais recomendada é usando uma chave SSH. Aqui está como configurar:

1. Gere uma chave SSH (pressione "Enter" para os prompts padrão):
   ```bash
   ssh-keygen -t ed25519 -C "seuemail@example.com"
   ```

2. Adicione sua chave SSH ao ssh-agent:
   ```bash
   eval "$(ssh-agent -s)"
   ssh-add ~/.ssh/id_ed25519
   ```

3. Adicione a chave SSH ao seu GitHub:
   - Copie a chave pública:
     ```bash
     cat ~/.ssh/id_ed25519.pub
     ```
   - Vá até o GitHub, em **Settings > SSH and GPG keys**, clique em **New SSH key**, cole a chave e salve.

## 4. Clonando um Repositório

Agora que você está conectado ao GitHub, pode clonar um repositório existente para trabalhar localmente. Para clonar, use o comando:

```bash
git clone git@github.com:usuario/repo.git
```

Substitua `usuario` e `repo` pelo nome do seu repositório. Isso criará uma cópia local do projeto no seu diretório.

## 5. Criando um Novo Repositório

Para iniciar um novo repositório localmente e enviá-lo para o GitHub, siga estes passos:

1. Crie um novo diretório e navegue até ele:
   ```bash
   mkdir meu-projeto
   cd meu-projeto
   ```

2. Inicialize o Git no diretório:
   ```bash
   git init
   ```

3. Adicione um arquivo README:
   ```bash
   echo "# Meu Projeto" >> README.md
   ```

4. Adicione o arquivo ao controle de versão:
   ```bash
   git add README.md
   ```

5. Faça o primeiro commit:
   ```bash
   git commit -m "Primeiro commit"
   ```

6. No GitHub, crie um novo repositório vazio. Depois, conecte-o ao repositório local:
   ```bash
   git remote add origin git@github.com:usuario/meu-projeto.git
   ```

7. Envie o código local para o GitHub:
   ```bash
   git push -u origin main
   ```

## 6. Fluxo de Trabalho Comum

### 6.1. Atualizando seu Repositório Local

Sempre antes de começar a trabalhar, é uma boa prática atualizar seu repositório local com as últimas mudanças do GitHub:

```bash
git pull origin main
```

### 6.2. Fazendo Alterações e Commitando

1. Edite seus arquivos e adicione-os ao controle de versão:
   ```bash
   git add arquivo_modificado.txt
   ```

2. Faça um commit das suas mudanças com uma mensagem descritiva:
   ```bash
   git commit -m "Descrição das alterações feitas"
   ```

### 6.3. Enviando Alterações para o GitHub

Depois de commitá-las, envie as alterações para o GitHub:

```bash
git push origin main
```

### 6.4. Trabalhando com Branches

1. Crie uma nova branch para trabalhar em uma funcionalidade:
   ```bash
   git checkout -b nova-funcionalidade
   ```

2. Após finalizar as alterações, adicione, commit e faça push para o GitHub:
   ```bash
   git add .
   git commit -m "Implementação da nova funcionalidade"
   git push origin nova-funcionalidade
   ```

3. No GitHub, abra um **Pull Request** para mesclar sua branch `nova-funcionalidade` com a `main`.

### 6.5. Mesclando uma Branch

Após revisarem seu Pull Request e tudo estiver correto, faça o merge:

1. Troque para a branch `main`:
   ```bash
   git checkout main
   ```

2. Mescle as alterações da branch:
   ```bash
   git merge nova-funcionalidade
   ```

3. Envie as alterações atualizadas para o GitHub:
   ```bash
   git push origin main
   ```

## 7. Resolvendo Conflitos

Se houver conflitos ao mesclar alterações de branches diferentes, o Git indicará os arquivos conflitantes. Você pode resolver manualmente os conflitos e depois:

1. Adicionar os arquivos resolvidos:
   ```bash
   git add arquivo_com_conflito.txt
   ```

2. Continuar o processo de merge:
   ```bash
   git commit
   ```

3. Enviar o merge resolvido para o GitHub:
   ```bash
   git push origin main
   ```

## 🎉 Parabéns!

Agora você está pronto para trabalhar com Git e GitHub no terminal! Pratique esse fluxo para dominar o controle de versão e a colaboração em seus projetos.
