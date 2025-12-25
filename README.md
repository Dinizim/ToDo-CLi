
````markdown
# 📝 Todo CLI (Python)

Uma **CLI simples de gerenciamento de tarefas**, escrita em **Python**, voltada para uso no **Linux**.

Este projeto foi criado com o objetivo de praticar:
- Python
- Manipulação de arquivos
- Criação de ferramentas de linha de comando (CLI)
- Uso de argumentos via terminal

---

## 🚀 Funcionalidades

- ➕ Adicionar tarefas
- 📋 Listar tarefas pendentes
- ✅ Marcar tarefas como concluídas
- ❌ Deletar tarefas
- 📊 Gerar relatório de tarefas

As tarefas são persistidas em arquivos de texto:
- `todo.txt` → tarefas pendentes
- `done.txt` → tarefas concluídas

---

## 🛠️ Requisitos

- Linux
- Python 3.x

Verifique se o Python está instalado:

```bash
python3 --version
````

---

## 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/todo-cli.git
cd todo-cli
```

Dê permissão de execução aos arquivos:

```bash
chmod +x todo.py
chmod +x todo.sh
```

---

## ▶️ Como usar

### ➕ Adicionar uma tarefa

```bash
./todo.sh add "Estudar Python"
```

### 📋 Listar tarefas pendentes

```bash
./todo.sh ls
```

### ✅ Marcar uma tarefa como concluída

```bash
./todo.sh done 1
```

### ❌ Deletar uma tarefa

```bash
./todo.sh del 1
```

### 📊 Gerar relatório

```bash
./todo.sh report
```

### ❓ Exibir ajuda

```bash
./todo.sh help
```

---

## 📂 Estrutura do projeto

```text
todo-cli/
├── todo.py      # Código principal da CLI
├── todo.sh      # Script de execução no Linux
├── README.md    # Documentação do projeto
└── .gitignore   # Arquivos ignorados pelo Git
```

---

## 🎯 Objetivo do projeto

Este projeto foi desenvolvido para fins educacionais, com foco em:

* Desenvolvimento de CLIs
* Boas práticas iniciais com Python
* Uso do terminal Linux
* Manipulação de arquivos sem banco de dados

---

## 📄 Licença

Este projeto é de uso livre para estudo e aprendizado.
