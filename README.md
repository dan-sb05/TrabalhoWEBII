# Trabalho WEB II

## Clonar o projeto

```bash
git clone https://github.com/ph-santos0/TrabalhoWEBII.git
```

Entrar na pasta:

```bash
cd TrabalhoWEBII
```

---

## Configurar o banco de dados

1. Abra o MySQL.
2. Abra o arquivo SQL disponibilizado pela equipe.
4. Execute o script no banco criado.

---

## Executar o sistema

Acesse:

```text
http://localhost:8080
```

---

# Fluxo de Desenvolvimento

## Antes de começar qualquer tarefa

Atualize sua cópia local:

```bash
git checkout main
git pull origin main
```

---

## Criar sua branch

Substitua pelo seu nome:

```bash
git checkout -b seu_nome
```

Exemplos:

```bash
git checkout -b julya
```

```bash
git checkout -b daniel
```

---

## Programar normalmente

Faça suas alterações no projeto.

---

## Depois de programar voce vai Salvar alterações:

Verificar alterações:

```bash
git status
```

Adicionar arquivos:

```bash
git add .
```

Criar commit:

```bash
git commit -m "Descrição da alteração"
```

Exemplo:

```bash
git commit -m "Implementado CRUD de clientes"
```

---

## Enviar para o GitHub

```bash
git push origin seu_nome
```

Exemplo:

```bash
git push origin daniel
```

---

# Receber atualizações da equipe

Antes de iniciar uma nova tarefa:

```bash
git checkout main
git pull origin main
```

Depois volte para sua branch:

```bash
git checkout seu_nome
```

---

# Comandos Úteis

Ver branch atual:

```bash
git branch
```

Ver todas as branches:

```bash
git branch -a
```

Ver alterações:

```bash
git status
```

Ver histórico:

```bash
git log --oneline
```
