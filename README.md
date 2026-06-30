
# SISTEMA DE CARRINHO DE COMPRAS ELETRÔNICO


Este projeto consiste em uma aplicação interativa que simula um carrinho de 
compras para uma loja virtual. O script em JavaScript é responsável por 
gerenciar a adição de produtos selecionados, calcular os subtotais com 
base na quantidade informada, atualizar o valor total geral da compra em 
tempo real e permitir a limpeza completa do carrinho.

------------------------------------------------------------------------
1. FUNCIONALIDADES PRINCIPAIS
------------------------------------------------------------------------
* Adição de Itens: Recupera o produto selecionado e a quantidade inserida 
  pelo usuário, processando os dados para inseri-los no carrinho.
* Cálculo Automático: Extrai o valor unitário do texto do elemento e 
  calcula o subtotal (quantidade × valor unitário).
* Manipulação Dinâmica do DOM: Injeta dinamicamente novos elementos HTML 
  na lista de produtos do carrinho, mantendo o histórico de itens visível.
* Atualização de Totais: Acumula o valor de cada subtotal na variável de 
  controle geral e atualiza o display de preço para o usuário.
* Redefinição de Estado: Reseta o campo de quantidade após cada inserção 
  e oferece uma função dedicada para limpar todo o histórico e zerar os valores.

------------------------------------------------------------------------
2. ESTRUTURA DO CÓDIGO JAVASCRIPT
------------------------------------------------------------------------
* `totalGeral` (Variável Global): Armazena o valor numérico acumulado de 
  todos os itens presentes no carrinho.
* `adicionar()`: Função disparada ao incluir um item. Realiza o parsing 
  da string do produto (separando nome e preço por delimitadores), calcula 
  o subtotal, atualiza a interface e limpa o campo de entrada.
* `limpar()`: Função que redefine o estado inicial da aplicação, limpando 
  a lista visual de produtos e resetando o totalizador para R$ 0,00.

------------------------------------------------------------------------
3. TECNOLOGIAS UTILIZADAS
------------------------------------------------------------------------
* 🟡 JavaScript (ES6+) - Lógica de negócios, manipulação do DOM e strings.
* 🌐 HTML5 - Estruturação dos formulários, seleção de itens e seções do carrinho.
* 🎨 CSS3 - Classes de estilização para o layout e realce de textos (como .texto-azul).

------------------------------------------------------------------------
4. REFERÊNCIA DO PROJETO
------------------------------------------------------------------------
Este projeto foi desenvolvido com base no seguinte treinamento:
* Instituição: Alura
* Curso: Lógica de programação: Praticando com desafios

========================================================================
Criado para fins educacionais e consolidação de manipulação de strings e DOM.
========================================================================
