# Pagina com a estrutura do Twiter 
- Criada para enteder melhor os conceitos de FlexBox

### Dicas:
1. Colocar `display: flex` na div mais externa.
2. Usar `flex-direction` para direcionar os elementos na tela.
3. Forçar o boby a ocupar a `altura total do documento`.
  ```
    html, body, #app {
    height: 100%;
    margin: 0;
    }
  ```
4. `align-itens` e `justify-content`
5. Redimencionar componetes: espremido ou aumentado. 
  5.1 `flex-grow`: 1 => permite que os componentes se adaptem em tamnho de acordo com o flex-direction.
  5.2 `flex-shrink`: 1 => permite que os elementos se expremam em tamanho de acordo com o flex-direction.
  5.3 `flex`: 1 => combinação do grow com o shrink

6. Quebra de linhas `flex-wrap: wrap`
  - `align-content`: para alinhar elementos que estão em mais de uma linha
7. Ordenação `order: 1` pra cada elemento definir um numero para qual ordem se sequência quer que o elemento apareça

