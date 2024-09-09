## **## README.md: Aplicação de Busca de Personagens Monster High**

### **Descrição**

Esta aplicação web simples permite que os usuários pesquisem por personagens de Monster High. Ao digitar o nome de um personagem no campo de pesquisa, a aplicação retorna uma lista de resultados relevantes, exibindo o nome do personagem, uma breve descrição e links para mais informações.

### **Funcionalidades**

* **Pesquisa por nome:** Permite buscar personagens digitando parte do nome.
* **Resultados dinâmicos:** A lista de resultados é atualizada em tempo real conforme o usuário digita.
* **Links para mais informações:** Cada resultado inclui um link para uma página externa com mais detalhes sobre o personagem.

### **Estrutura do Projeto**

* **index.html:** Arquivo principal que contém a estrutura HTML da página.
* **Style.css:** Arquivo CSS responsável pelo estilo visual da página.
* **dados.js:** Arquivo JavaScript que contém um array de objetos com informações sobre os personagens (nome, descrição, links, etc.).
* **Function.js:** Arquivo JavaScript que contém a lógica da função de pesquisa.

### **Como funciona:**

1. **Interface do usuário:** O usuário interage com a página digitando o nome do personagem no campo de pesquisa e clicando no botão "Pesquisar".
2. **Evento de pesquisa:** Ao clicar no botão, a função `pesquisar()` é chamada.
3. **Busca:** A função `pesquisar()` percorre o array de dados, comparando o termo de pesquisa com o nome, descrição e tags de cada personagem.
4. **Resultados:** Se houver correspondência, a função cria elementos HTML para exibir os resultados da pesquisa.
5. **Atualização da página:** Os resultados são inseridos na seção destinada a exibir os resultados, substituindo o conteúdo anterior.

### **Tecnologias utilizadas:**

* **HTML:** Estrutura básica da página.
* **CSS:** Estilização da página.
* **JavaScript:** Lógica da aplicação, incluindo a função de pesquisa.

### **Como rodar a aplicação:**

1. **Clone o repositório:**
   ```bash
   git clone https://seu-repositorio.git
   ```
2. **Abra o arquivo index.html:** Abra o arquivo `index.html` em um navegador web.

### **Observações:**

* **Dados:** Os dados dos personagens estão armazenados no arquivo `dados.js`. Você pode adicionar ou modificar esses dados conforme necessário.
* **Personalização:** O estilo visual da aplicação pode ser personalizado editando o arquivo `Style.css`.
* **Melhorias:** A aplicação pode ser aprimorada com novas funcionalidades, como:
    * Pesquisa por tags
    * Ordenação dos resultados
    * Filtros adicionais
    * Integração com APIs externas

### **Contribuições:**

Contribuições são bem-vindas! Se você encontrar algum bug ou tiver alguma sugestão de melhoria, por favor, abra um issue ou faça um pull request.

**Observação:** Substitua "https://seu-repositorio.git" pelo URL do seu repositório no GitHub.

**Este README.md fornece uma visão geral da aplicação e pode ser adaptado para incluir informações mais específicas sobre seu projeto.**

**Recursos adicionais que você pode considerar adicionar:**

* **Diagrama de fluxo:** Um diagrama que mostra o fluxo de execução da aplicação.
* **Capturas de tela:** Imagens da interface da aplicação.
* **Instruções de instalação:** Se a aplicação exigir alguma instalação específica.
* **Licença:** Indique a licença sob a qual o código está sendo distribuído.

Com este README.md, você terá um documento claro e conciso que explica o funcionamento da sua aplicação e facilita a colaboração com outros desenvolvedores.
