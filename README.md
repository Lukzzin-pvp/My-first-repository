# 📊 Projeto: Tabelas em HTML

Este é um projeto simples desenvolvido para praticar e demonstrar a criação, estruturação e estilização de tabelas utilizando **HTML5** e **CSS3**. O objetivo é aplicar as melhores práticas de semântica web para tornar os dados tabulares organizados e acessíveis.

---

## 🚀 Tecnologias Utilizadas

*   **HTML5:** Estruturação semântica dos dados.
*   **CSS3:** Estilização básica (bordas, espaçamentos, cores alternadas e efeito *hover*).

---

## 🏗️ Estrutura do Código HTML

O arquivo `index.html` utiliza as tags semânticas recomendadas pela W3C para a construção de tabelas:

*   `<table>`: Container principal da tabela.
*   `<caption>`: Título ou descrição da tabela (ótimo para acessibilidade).
*   `<thead>`: Agrupa o conteúdo do cabeçalho.
*   `<tbody>`: Agrupa o corpo/conteúdo principal dos dados.
*   `<tfoot>`: Agrupa o rodapé da tabela (geralmente usado para totais ou resumos).
*   `<tr>`: Define as linhas (*table rows*).
*   `<th>`: Define as células de cabeçalho (*table headers*).
*   `<td>`: Define as células de dados comuns (*table data*).

### Atributos Especiais Utilizados:
*   `colspan`: Usado para fazer uma célula ocupar o espaço de várias colunas.
*   `rowspan`: Usado para fazer uma célula ocupar o espaço de várias linhas.

---

## 🎨 Funcionalidades de Estilização (CSS)

Para deixar a tabela visualmente agradável e fácil de ler, foram aplicadas as seguintes regras CSS:
1.  **`border-collapse: collapse;`**: Remove o espaço duplo entre as bordas das células.
2.  **`nth-child(even)`**: Cria o efeito "zebra" (linhas alternadas com cores diferentes) para facilitar a leitura visual.
3.  **`:hover`**: Destaca a linha em que o usuário passa o mouse por cima.
4.  **`padding`**: Garante um espaçamento interno confortável para o texto não encostar nas bordas.

---

## 💻 Como Visualizar o Projeto

1. Faça o clone ou baixe este repositório.
2. Navegue até a pasta do projeto.
3. Abra o arquivo `index.html` diretamente no seu navegador de preferência (Chrome, Firefox, Edge, etc.) ou utilize a extensão **Live Server** no VS Code.

---

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

---
Feito com ❤️ por [Seu Nome/Seu GitHub]
