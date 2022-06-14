#HTML
- HyperText Markup Language

- Hiper Texto são links que podemos colocar nos nossos textos
- Marcação
  - Tags
    - Cada TAG é uma INSTRUÇÃO
    - Atributos (Servem para dar mais informação a uma tag)
Linguagem
  - Maneira de escrever

# CSS

# Declaração
- Seletor: É a forma que declaramos determinado item do HTML 
- Propriedade: Se trata do que estamos alterando nessa Declaração
- Valor: Se trata do aspecto que o elemento será apresentado no navegador.

#Conceito
- Cascata: o CSS trabalha no modo cascata, ou seja, sempre irá considerar a ÚLTIMA declaração.
- Especificidade: Serve para definir PRIORIDADES na alteração que a declaração está fazendo.
- Box Model: Tudo são caixas, cada parte do código é uma caixa.

# Explicação JAVASCRIPT (JS)
Serão oito conceitos
- 1. Variáveis
  - let estaChovendo = true
    - A variável LET (letchange = deixe mudar) pode ter seu tipo alterado a qualquer momento.
  - const meuNome = "Gabriel"
    - Já a variável CONST (constante) não é possível alterar, ela é CONSTANTE durante o código todo.

- 2. Tipos de Dados
  - String = Textos / Cadeia de caracteres
    - ""
    - ''
  - Number = Números
    - 12 - Integer (+ -) - Números inteiros
    - 3.2 - Float (+ -) - Números flutuantes
  - Boolean
    - true ou false
  - undefined = algum dado INDEFINIDO, que não existe.

- 3. Operadores
  - Atribuição (sinal de igual =)
    - Serve para atribuir valor 
    - forma de leitura:
      - let n1 = 12 (let n1 RECEBE 12) - Estamos atribuindo VALOR a variável
  
  - Aritméticos (Multiplicação * ; divisão / ; soma + ; subtração -)
    -  Serve para cálculos matemáticos simples
  
  - Concatenação de String (+)
    - Serve para JUNTAR duas strings
  
  - Comparação (Maior > ; Menor < ; igual ==)
    - A comparação transforma a expressão em true ou false
    - Ex: 1 > 2 // false
    - Ex: 1 < 2 // true
    - Ex: 3 == 3 // true

- 4. Condicional (if/else)
  const idade = 17
  const maiorDeDezoito = idade >= 18

  if(maiorDeDezoito) {
    alert("Pode tirar carteira de motorista")
  }
  else {
    alert("Não pode tirar")
  }

  - Em resumo, se tiver 18 ou mais voltará o valor do IF, caso contrário voltará o valor do ELSE.

- 5. Estrutura de Dados
  - Array - Vetor - Lista // Array são listas
  - Array ----            0    1    2  3
  const temperaturas = [23.3, 32.2, 1, 5]

  Object
  const pessoa = {
    nome: "Gabriel",
    idade: 22,
    filhos: ["K", "E", "J", "L", "G"]
  }

- 6. Função
  - 1. Criação
  function nomeDaFuncao() {
    console.log('código da função. ')
  }

  - 2. Execução
  nomeDaFuncao

  - Parâmetros da função
  function soma(a, b) {
    console.log(a + b)
  }
  soma(34, 45)
  soma(90, 54)

  - Retorno da função
  function soma(a, b) {
    return a + b
  }

  const multiplica = soma(2, 2) * 4
  console.log(multiplica)

  console.log(soma(2, 2))

- 7. Extensões da linguagem (ex.: Math, Date ...)

  - Math.random() - Traz um valor randomico entre 0 e 1
  - Math.floor(1.2) - Arredonda pra baixo
  - Math.ceil(1.2) - Arredonda para cima
  - Math.PI - Traz o valor de PI

- 8. DOM - Document Object Model - Modelagem do nosso documento em objeto

  - Window
  - window.alert("alerta")
  - document
  - document.write("texto")
  - manipular elementos
  - document.documentElement.style.background = "black"