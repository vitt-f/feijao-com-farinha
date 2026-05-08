## Casos de Uso:

### Caso de uso 1: Gerenciar cadastro

#### Atores:

- User.
  
#### Fluxo principal:

- O user seleciona a opção “Criar conta”.
  
- O sistema leva o user até a tela de registro contendo um formulário.
  
- O user preenche os campos do formulário (informando nome de usuário e criando uma senha).
  
- O sistema consulta o banco de dados para verificar a disponibilidade das informações fornecidas.
  
- O banco de dados retorna uma confirmação positiva.
  
- O sistema realiza o cadastro, salvando os dados do novo user.
  
- O sistema encaminha o user para o menu principal do jogo.

### Caso de Uso 2: Fazer log-in.

#### Atores: 

- User

#### Fluxo principal:

- O user seleciona a opção "Login".

- O sistema leva o user até a tela de preenchimento de senha e nome de usuário.

- User preenche os campos da tela.

- O sistema consulta o banco de dados para a confirmação dos dados inseridos.

- O banco de dados retorna uma confirmação positiva.

- O sistema encaminha o user para o menu principal do jogo.


### Caso de Uso 3: Editar personagem

#### Atores: 

- Jogador

#### Fluxo principal: 

- O jogador acessa a página saves

- o jogador escolhe um personagem

- O jogador aperta no botão "editar" e edita o personagem selecionado

### Caso de Uso 4: Excluir save/personagem

#### Atores: 

- Jogador

#### Fluxo principal: 

- O jogador acessa o menu principal do jogo 

- O jogador clica em "Saves"

- O jogador escolhe um save e clica em "Excluir save"

- O sistema faz requisição ao banco de dados para excluir os dados do save

- O banco de dados exclui os dados do save e retorna uma mensagem de sucesso

### Caso de Uso 5: Criar save/personagem

#### Atores: 

- Jogador

#### Fluxo principal: 

- O jogador acessa o menu principal do jogo

- O jogador acessa a página "Carregar saves"

- A página exibe uma lista com todos os saves

- O jogador clica num botão "Criar save" ou "Criar Personagem" e cria o save/personagem correspondente ao botão

### Caso de Uso 6: Jogar

#### Atores: 

- Jogador

#### Fluxo principal: 
- Após criar um novo save/personagem ou carregar um save/personagem já existente, o jogador inicia o jogo

- O jogador pode interagir dentro do jogo com comandos

### Caso de Uso 7: Coletar item

#### Atores: 

- Jogador

#### Fluxo principal:

- O jogador está numa cena de diálogo 

- Um botão escrito "Pegar item" é exibido na tela

- Uma descrição do item aparece ao lado

- O jogador aperta em "Pegar item"

- O item é adicionado ao inventário do jogador

### Caso de Uso 8: Comprar item

#### Atores: 

- Jogador

#### Fluxo principal: 

- O jogador está numa cena de loja

- Um menu lateral é exibido com os itens compráveis

- O jogador seleciona um item

- O jogador aperta no botão "Comprar"

- O sistema verifica se o usuário tem moedas suficientes

- As moedas do jogador são subtraídas pelo valor do item

- O item é adicionado ao inventário do jogador

### Caso de Uso 9: Abrir inventário

#### Atores: 

- Jogador

#### Fluxo principal: 

- O jogador está numa cena de combate 

- O jogador aperta num botão escrito "Inventário"

<!-- incompleto -->

### Caso de Uso 9: Usar item

#### Atores: 

- Jogador

#### Fluxo principal: 

- O inventário do jogador está aberto

- O jogador clica no item que deseja usar

- O item altera os atributos do jogador 

### Caso de Uso 6: Gerenciar inimigos

#### Atores: 

- Adm

#### Fluxo principal: 

- O adm acessa o menu principal do jogo

- O adm acessa a página "Inimigos"

- A página exibe uma lista com todos os inimigos

- O adm pode criar, editar, e excluir inimigos
 
### Caso de Uso 7: Gerenciar NPCs

#### Atores: 

- Adm

#### Fluxo principal: 

- O adm acessa o menu principal do jogo

- O adm acessa a página "NPCs"

- A página exibe uma lista com todos os NPCs

- O adm pode criar, editar, e excluir NPCs

### Caso de Uso 8: Excluir jogadores

#### Atores: 

- Adm

#### Fluxo principal: 

- O adm acessa o menu principal do jogo

- O adm acessa a página "jogadores"

- A página exibe uma lista com todos os jogadores

- O adm clica num botão "Excluir jogador" e exclui o jogador correspondente ao botão

