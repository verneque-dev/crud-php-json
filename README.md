# 📋 CRUD em PHP com JSON

Projeto de um **gerenciador de tarefas** desenvolvido em PHP, utilizando arquivos JSON como forma de persistência de dados (sem uso de banco de dados relacional).

---

## 🔗 Projeto Online

Você pode testar o projeto funcionando aqui:  
👉 [https://gerenciadortarefas.wuaze.com/](https://gerenciadortarefas.wuaze.com/)

---

## 🛠 Tecnologias Utilizadas

- PHP  
- JSON (para armazenamento dos dados)  
- HTML5  
- CSS3  
- JavaScript (interações no front)

---

## ✨ Funcionalidades

- [x] Criar tarefa  
- [x] Listar tarefas  
- [x] Editar tarefa  
- [x] Excluir tarefa  
- [x] Persistência via `tarefas.json`  

---

## 📂 Estrutura do Projeto

crud-php-json/  
├── index.php # Página principal com as opções relacionadas às tarefas  
├── tarefas.json # Arquivo onde as tarefas são salvas  
├── style.css # Estilo global (se existir)  
├── img/ # Imagens utilizadas no projeto  
│  
├── create/  
│ ├── criarTarefa.php # Formulário de criação  
│ ├── create.php # Lógica de criação  
│ └── style.css # Estilos da página de criação  
│  
├── read/  
│ ├── read.php # Exibição das tarefas  
│ └── style.css # Estilos da página de leitura  
│  
├── update/  
│ ├── updateTarefa.php # Formulário de edição  
│ ├── update.php # Lógica de atualização  
│ └── style.css # Estilos da página de edição  
│  
├── delete/  
│ ├── deleteTarefa.php # Confirmação de exclusão  
│ ├── delete.php # Lógica de exclusão  
│ └── style.css # Estilos da página de exclusão  

---

## 🧪 Como Rodar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/crud_php_json.git
```

2. Copie os arquivos para a pasta `htdocs` do seu servidor local (XAMPP, WAMP, Laragon etc.)

3. No navegador, acesse:

```url
http://localhost/crud_php_json
```

4. Pronto! O sistema estará funcionando.

---

## 📦 Sobre o Armazenamento com JSON

Em vez de usar banco de dados, esse projeto salva todas as tarefas no arquivo `tarefas.json`, que é lido e escrito diretamente pelo PHP com funções como:

- `file_get_contents()`  
- `json_decode()`  
- `json_encode()`  
- `file_put_contents()`

Essa abordagem facilita o uso em ambientes mais simples e didáticos.

---

## 🧠 Aprendizados

Esse projeto foi desenvolvido como prática para:

- Entender o funcionamento de requisições e respostas com PHP  
- Manipular arquivos JSON com PHP  
- Trabalhar com arrays e objetos em PHP  
- Organizar um CRUD completo usando uma estrutura simples e clara

---

## 📫 Contato

Feito por **Vitor Henrique Verneque Silva**  
✉️ verneque.dev@gmail.com
