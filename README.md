
Este repositório foi criado com o objetivo de atender ao desafio do bootcamp DIO Linux do Zero. Aqui, você encontrará uma seleção de comandos básicos para trabalhar com o Git, uma ferramenta de versionamento, e o GitHub, um repositório para hospedar seus projetos.

Aqui está um passo a passo dos comandos básicos do Git:

Configuração do Git:

1. Para começar, você precisa configurar o Git no seu computador com o seu nome de usuário e endereço de email:

```bash
git config --global user.name "Seu nome"
git config --global user.email "seu-email@example.com"
```

2. Criando um novo repositório:

Para criar um novo repositório, basta criar uma nova pasta e, em seguida, executar o comando git init dentro dela:

```bash 
mkdir novo-repositorio
cd novo-repositorio
git init
```

3. Adicionando arquivos ao repositório:

Para adicionar arquivos ao repositório, você pode usar o comando git add:

```bash 
git add arquivo.txt (adiciona um arquivo específico)
git add . (adiciona todos os arquivos na pasta atual)
```

4. Fazendo um commit:

Após adicionar arquivos ao repositório, você precisa fazer um commit para registrá-los no histórico do Git:

```bash 
git commit -m "Mensagem de commit"
```

5. Verificando o status do repositório:

Você pode verificar o status atual do repositório usando o comando git status:

```bash 
git status
```

6. Visualizando o histórico de commits:

Para visualizar o histórico de commits do repositório, você pode usar o comando git log:
```bash 
git log
```

7. Ramificação e mesclagem:

Você pode criar uma nova ramificação usando o comando git branch e mudar para ela usando git checkout:

```bash 
git branch nova-ramificacao
git checkout nova-ramificacao
```

8. Para mesclar as alterações em uma ramificação de volta à ramificação principal (ou outra ramificação), você pode usar o comando git merge:

```bash
git checkout ramificacao-de-volta
git merge nova-ramificacao
```

10. Trabalhando com repositórios remotos:

Você pode clonar um repositório remoto usando o comando git clone:

```bash
git clone https://github.com/usuario/repositorio.git
```

11. Para enviar alterações para um repositório remoto, você pode usar o comando git push:

```bash 
git push origin ramificacao
```

12. Para obter as alterações mais recentes de um repositório remoto, você pode usar o comando git pull:

```bash 
git pull origin ramificacao
```