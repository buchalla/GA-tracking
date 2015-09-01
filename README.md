# GA-tracking
Adicione os atributos:
 * ga-category
 * ga-label (*opcional*)
 * ga-action (*opcional*)
 
E o evento desejado:
 * ga-trigger
  
Exemplos:
  - Clique no botão de cadastro
    <pre>
    ```<button ga-category="Formulario - Cadastro" ga-label="Botão Enviar" ga-trigger="click"> Enviar </button>```
    </pre>
  - Foco em um input de email
    <pre>
    ```<input type="email" ga-category="Formulario - Cadastro" ga-label="Input Email" ga-trigger="focus" placeholder="Digite seu email" />```
    </pre>

O script gerará os eventos de acordo com o atributo "ga-trigger"
