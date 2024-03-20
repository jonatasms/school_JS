# school_JS






Exercício de fixação

1. Crie uma aplicação para efetuar o cálculo do índice de massa corporal.
Considere os seguintes critérios:
    1 Ao executar o script a aplicação deve solicitar a entrada do nome da pessoa.
    2 Na sequência a aplicação deve solicitar que seja informada a altura da pessoa em
    centímetros.
    3 Na sequência a aplicação deve solicitar que seja informado o peso da pessoa.
    4 Após as estradas de dados, atente-se a conversão das informações para dados do tipo
    float.
    5 Converta a altura recebida em centímetros para metros. (basta dividir a altura por
    100).
    6 Internamente a aplicação deve executar o cálculo do índice de massa corporal através
    da expressão: M = peso (quilos) ÷ altura²
    7 Após identificar o índice de massa corporal o sistema deverá classificar em faixas
    descritivas utilizando os critérios abaixo:
        a) Se M estiver abaixo de 16 : Baixo peso muito grave
        b) Se M estiver entre 16 e 16,99: Baixo peso grave
        c) Se M estiver entre 17 e 18,49: Baixo peso
        d) Se M estiver entre 18,50 e 24,99: Peso normal
        e) Se M estiver entre 25 e 29,99: Sobrepeso
        f) Se M estiver entre 30 e 34,99: Obesidade grau I
        g) Se M estiver entre 35 e 39,99: Obesidade grau II
        h) Se M for maior que 40: Obesidade grau III
    8 Ao término o sistema deve fornecer a seguinte saída para o usuário:
“<Nome> possui índice de massa corporal igual a <m>, sendo classificado como:
<classificacao>.”
*As informações em vermelho são variáveis e devem ser substituídas pelos seus respectivos
valores calculadas dentro da aplicação.

Exercício de fixação
1) Crie uma aplicação capaz de identificar a faixa etária com base na idade informada pelo
usuário. Considere os seguintes critérios:
Se a idade informada for maior ou igual a 0 e menor que 15, exibir a mensagem “Criança”.
Se a idade informada for maior ou igual a 15 e menor que 30, exibir a mensagem “Jovem”.
Se a idade informada for maior ou igual a 30 e menor que 60, exibir a mensagem “Adulto”.
Se a idade informada for maior ou igual a 60, exibir a mensagem “Idoso”.
Fique à vontade para utilizar qualquer uma das funções aprendidas para exibição de dados
para o usuário.



Exercício de fixação
1) Crie um campo <input type="text"> e aplique os seguintes controles com base nos
eventos abaixo:
    • No evento de foco modifique o background do input para amarelo.
    • Quando o campo perder o foco, recupere o seu respectivo valor e:
        - Caso o conteúdo contido no campo tenha menos de 3 caracteres o mesmo
        deve ter seu background alterado para vermelho.
        - Caso o conteúdo contido no campo tenha 3 caracteres ou mais o background
        deve ser alterado para verde.




Exercício fixação 1

1) Crie uma aplicação web contendo um campo para entrada de texto (input text) e dois
botões (buttons), sendo um botão com a descrição "Adicionar" e outro com a descrição
"Ordenar".

Após criar os elementos de interação com o usuário acima, crie um Array de nome objetos contendo os seguintes valores:

var objetos = Array('Cadeira', 'Impressora', 'Garfo')

Os próximos passos são:
A) Ao clicar no botão "Adicionar" disparar função que irá:
    • Recuperar o valor contido no campo de texto.
    • Verificar se o valor está vazio ou preenchido.
        o Se vazio, exibir alert com a mensagem "Informe um valor válido".
        o Se preenchido:
            ▪ Verificar se o valor informado já existe dentro do Array objetos.
            ▪ Se existir, exibir alert com a mensagem "Objeto já foi adicionado".
            ▪ Se não existir:
                • Incluir o valor preenchido no campo dentro do Array.
                • Efetuar um console.log do Array para debug (checar se está
                funcionado).
                • Limpar o valor contido no campo de entrada de texto.
B) Ao clicar no botão "Ordenar" disparar função que irá:
    • Ordenar de forma alfabética os valores do Array de objetos.
    • Efetuar um console.log do Array para debug (checar se está funcionado)




Exercício fixação  2
2. Crie uma aplicação para efetuar cálculo aritméticos de soma e subtração.
Considere os seguintes critérios:
    2.1 Ao executar o script a aplicação deve solicitar a entrada de um número, seguido de
        uma operação de soma ou subtração e posteriormente seguido de um segundo
        número.
    2.2 A operação deve ser inserida pelo usuário de forma textual, ou seja, quando o sistema
    solicita a operação o usuário deve informar o texto ‘soma’ ou ‘subtração’ (sem as
    aspas).
    2.3 Na sequência o sistema deve enviar os parâmetros para uma função efetuar o devido
    cálculo. Exemplo: calculo(num1, num2, operacao).
    2.4 A função deve executar o cálculo com base na operação informada pelo usuário e na
    sequência deve retornar o valor encontrado.
    2.5 Ao término o sistema deve fornecer a seguinte saída para o usuário:
“O resultado é: <resultado>.”
*A informação em vermelho é uma variável e deve ser substituída pelo seu respectivo valor
calculada dentro da aplicação.

