docs/user-stories.md
# 📄 User Stories

## 🟦 US01 - Login do usuário

### ÉPICO: Autenticação de usuário

### User Story
Como usuário da loja  
Quero realizar login com meu usuário e senha  
Para acessar minha conta e realizar compras  

### Critérios de Aceite

#### Cenário: Login válido
Dado que o usuário está na tela de login  
Quando informa usuário e senha válidos  
Então deve acessar o sistema  

#### Cenário: Senha inválida
Dado que o usuário está na tela de login  
Quando informa senha inválida  
Então deve exibir mensagem de erro  

---

## 🟦 US02 - Adicionar produto ao carrinho

### ÉPICO: Carrinho de compras

### User Story
Como usuário autenticado  
Quero adicionar produtos ao carrinho  
Para realizar compras posteriormente  

### Critérios de Aceite

#### Cenário: Adicionar produto
Dado que o usuário está na lista de produtos  
Quando clica em adicionar ao carrinho  
Então o produto deve ser adicionado  
      
#### Cenário: Produto no carrinho
Dado que o usuário adicionou um produto  
Quando acessa o carrinho  
Então o produto deve ser exibido
