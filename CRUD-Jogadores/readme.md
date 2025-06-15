# CRUD-Jogadores

This is a simple and functional **CRUD (Create, Read, Update, Delete)** project to manage players of a soccer team. Developed for the Algorithms discipline in 2024, it features a friendly user interface, CSS styling, and basic validations to prevent common user errors.

Although it seems simple, this was the project that required the most time and dedication to be completed by the end of 2024.

---

## 🚀 Features

* **Player Registration:** Insert new players with number, name, date of birth, position, height, and weight.
* **Search by Number:** Search for existing players using their number (primary key).
* **Data Change:** Edit the information of already registered players.
* **Player Deletion:** Remove players from the list. * **Input Validation:** Basic controls to ensure valid data entry.
* **Table View:** All registered players are displayed in a dynamic table.
* **Data Persistence (Local):**
* **Download:** Save table data to a CSV file (`Players.csv`) for backup.
* **Upload:** Load data from a CSV file to populate the table.
* **Responsive Interface:** The layout adapts to different screen sizes (desktops, tablets and cell phones).

---

## 🛠️ Technologies Used

* **HTML5:** Page structure.
* **CSS3:** Styling and responsiveness.
* **JavaScript (Vanilla JS):** DOM manipulation logic, CRUD control and validations.

---

## 📂 Project Structure

```
CRUD-Jogadores/
├── src
│ ├── class
│ │ └── class.js # Definition of the Player class
│ ├── javascript
│ │ └── script.js # Main CRUD logic, data manipulation and DOM
│ └── styles
│ └── style.css # Page styling
└── index.html # Home page
```

---

## ▶️ How to Use

1. **Clone the repository:**
```bash
git clone https://github.com/alexandrebpetri/CRUD-Jogadores.git
cd CRUD-Jogadores
```

2. **Open `index.html`:**
Simply open the `index.html` file in your preferred web browser (Chrome, Firefox, Edge, etc.). You can do this by double-clicking the file or dragging it into the browser window.

---

## 💡 How it Works

1. **Initial Loading:** When opening the page, a list of predefined players is loaded and displayed in the table.
2. **Search for Player:**
* Enter the **"Player Number"** in the field and click **"Search"**.
* If the player is found, his data will appear in the form, and the **"Change"** and **"Delete"** buttons will be displayed. * If not found, the warning will indicate that you can **"Insert"** a new player.
3. **Insert Player:**
* After searching for a non-existent number, click **"Insert"**.
* Fill in the new player's data and click **"Save"**.
4. **Change Player:**
* Find the player you want to change.
* Click **"Change"**.
* Modify the desired fields and click **"Save"**.
5. **Delete Player:**
* Find the player you want to delete.
* Click **"Delete"**.
* Confirm the deletion by clicking **"Save"**.
6. **Save/Load Data:**
* Use **"Save Data"** to download a CSV file with the current players.
* Use **"Fetch Saved Data"** to load players from a CSV file into the application.

---

## 🌐 Access Online

You can test the application directly through GitHub Pages:
[https://alexandrebpetri.github.io/CRUD-Jogadores/](https://alexandrebpetri.github.io/CRUD-Jogadores/)

---

## ✨ Credits

* **Developed by:** Alexandre B. Petri
* **Discipline:** Algorithms (2024)

---

## 🤝 Contributions

Suggestions and improvements are always welcome! Feel free to open an **issue** or send a **pull request**.

---

# (🌍 PT-br) CRUD-Jogadores

Este é um projeto **CRUD (Create, Read, Update, Delete)** simples e funcional para gerenciar jogadores de um time de futebol. Desenvolvido para a disciplina de Algoritmos em 2024, ele apresenta uma interface de usuário amigável, estilização CSS e validações básicas para prevenir erros comuns do usuário.

Embora pareça simples, este foi o projeto que mais demandou tempo e dedicação para ser concluído até o final de 2024.

---

## 🚀 Funcionalidades

* **Cadastro de Jogadores:** Insira novos jogadores com número, nome, data de nascimento, posição, altura e peso.
* **Busca por Número:** Procure jogadores existentes usando seu número (chave primária).
* **Alteração de Dados:** Edite as informações de jogadores já cadastrados.
* **Exclusão de Jogadores:** Remova jogadores da lista.
* **Validação de Entrada:** Controles básicos para garantir a inserção de dados válidos.
* **Visualização em Tabela:** Todos os jogadores cadastrados são exibidos em uma tabela dinâmica.
* **Persistência de Dados (Local):**
    * **Download:** Salve os dados da tabela em um arquivo CSV (`Jogadores.csv`) para backup.
    * **Upload:** Carregue dados de um arquivo CSV para popular a tabela.
* **Interface Responsiva:** O layout se adapta a diferentes tamanhos de tela (desktops, tablets e celulares).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura da página.
* **CSS3:** Estilização e responsividade.
* **JavaScript (Vanilla JS):** Lógica de manipulação do DOM, controle do CRUD e validações.

---

## 📂 Estrutura do Projeto

```
CRUD-Jogadores/
├── src
│   ├── class
│   │   └── class.js # Definição da classe Jogador
│   ├── javascript
│   │   └── script.js # Lógica principal do CRUD, manipulação de dados e DOM
│   └── styles
│      └── style.css # Estilização da página
└── index.html # Página inicial
```

---

## ▶️ Como Usar

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/alexandrebpetri/CRUD-Jogadores.git
    cd CRUD-Jogadores
    ```

2.  **Abra o `index.html`:**
    Basta abrir o arquivo `index.html` em seu navegador web preferido (Chrome, Firefox, Edge, etc.). Você pode fazer isso clicando duas vezes no arquivo ou arrastando-o para a janela do navegador.

---

## 💡 Como Funciona

1.  **Carregamento Inicial:** Ao abrir a página, uma lista de jogadores predefinidos é carregada e exibida na tabela.
2.  **Procurar Jogador:**
    * Digite o **"Número do jogador"** no campo e clique em **"Procure"**.
    * Se o jogador for encontrado, seus dados aparecerão no formulário, e os botões **"Alterar"** e **"Excluir"** serão exibidos.
    * Se não for encontrado, o aviso indicará que você pode **"Inserir"** um novo jogador.
3.  **Inserir Jogador:**
    * Após procurar um número não existente, clique em **"Inserir"**.
    * Preencha os dados do novo jogador e clique em **"Salvar"**.
4.  **Alterar Jogador:**
    * Procure o jogador que deseja alterar.
    * Clique em **"Alterar"**.
    * Modifique os campos desejados e clique em **"Salvar"**.
5.  **Excluir Jogador:**
    * Procure o jogador que deseja excluir.
    * Clique em **"Excluir"**.
    * Confirme a exclusão clicando em **"Salvar"**.
6.  **Salvar/Carregar Dados:**
    * Use **"Salvar dados"** para baixar um arquivo CSV com os jogadores atuais.
    * Use **"Buscar dados salvos"** para carregar jogadores de um arquivo CSV para a aplicação.

---

## 🌐 Acesse Online

Você pode testar a aplicação diretamente pelo GitHub Pages:
[https://alexandrebpetri.github.io/CRUD-Jogadores/](https://alexandrebpetri.github.io/CRUD-Jogadores/)

---

## ✨ Créditos

* **Desenvolvido por:** Alexandre B. Petri
* **Disciplina:** Algoritmos (2024)

---

## 🤝 Contribuições

Sugestões e melhorias são sempre bem-vindas! Sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.