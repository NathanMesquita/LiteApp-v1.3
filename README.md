# 📇 LiteApp v1.3

**LiteApp** é um aplicativo simples, leve e eficiente para gerenciar contatos pessoais.  
Desenvolvido em **C# com Windows Forms**, ele é ideal para quem está aprendendo a programar interfaces gráficas e persistência de dados com JSON.

> 🚀 A versão **1.3** traz a nova funcionalidade de **edição de contatos**, completando o ciclo básico de CRUD (Create, Read, Update, Delete).

---

## 🆕 Novidades da versão 1.3

- ✅ Novo botão "**Atualizar**" para editar contatos
- ✅ Campos de nome e telefone são preenchidos ao selecionar um item da lista
- ✅ Contatos são atualizados diretamente no arquivo `contatos.json`
- ✅ Interface ainda mais prática e amigável

---

## 🧩 Funcionalidades principais

| Funcionalidade       | Status |
|----------------------|--------|
| Adicionar contato    | ✅     |
| Excluir contato      | ✅     |
| **Editar contato**   | ✅     |
| Salvar dados em JSON | ✅     |
| Interface WinForms   | ✅     |

---

## 🖼️ Interface (v1.3)

A interface agora possui:

- Campo `Nome`
- Campo `Telefone`
- Botões:
  - `Adicionar`
  - `Atualizar`
  - `Excluir`
  - `Limpar`
- Lista de contatos cadastrados

> Ao selecionar um contato na lista, os campos são preenchidos automaticamente. Basta editar e clicar em **Atualizar**.

---

## 💾 Estrutura da solução

LiteAppSolution/
├── LiteApp.Domain/ # Define a classe Contato.cs
├── LiteApp.Data/ # ContatoRepository.cs com JSON
├── LiteApp.UI/ # Interface Windows Forms (Form1.cs)
└── contatos.json # Dados persistentes dos contatos

---

## 🛠️ Tecnologias utilizadas

- 💻 C# com .NET Framework
- 🎨 Windows Forms
- 📦 Newtonsoft.Json (para leitura e escrita JSON)

---

## ▶️ Como usar

1. Abra a solução `LiteAppSolution.sln` no Visual Studio
2. Compile com `Ctrl + Shift + B`
3. Execute o projeto `LiteApp.UI`
4. Adicione, exclua ou edite contatos à vontade
5. Feche e reabra para verificar que os dados permanecem

---

## 📁 Sobre o arquivo `contatos.json`

- Gerado automaticamente no mesmo diretório do `.exe`
- Armazena todos os contatos cadastrados
- Atualizado automaticamente a cada modificação

---

## 📌 Próximos passos (v1.4)

- [ ] Campo de busca por nome
- [ ] Máscara de entrada para telefone
- [ ] Exportação para `.csv`
- [ ] Organização alfabética da lista
- [ ] Modo escuro (dark mode)

---

## 👨‍💻 Autor

Desenvolvido por [NathanMesquita]  

Projeto criado para fins educacionais e aprendizado com C# e Windows Forms.
