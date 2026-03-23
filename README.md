# atividade-programacao- Ricardo Cardozo
Explorar como diferentes prompts podem gerar explicações, exemplos e soluções de programação, ajudando o estudante a compreender melhor conceitos e práticas da área.


# Atividade – Prompt Mestre em Programação de Computadores
 
## Tema: Estruturas de Repetição
 
### Prompt Mestre Inicial
"Escreva um programa em Python que calcule a raiz quadra."
 
### Variação 1
"Escreva o programa em Python e explique passo a passo como funciona."

**import math
Importa a biblioteca matemática do Python, que já possui funções prontas, como a de raiz quadrada.
input("Digite um número: ")
Mostra uma mensagem na tela e espera o usuário digitar um valor.
float(...)
Converte o valor digitado (que vem como texto) para número decimal (float), permitindo cálculos.
math.sqrt(numero)
Calcula a raiz quadrada do número informado.
print(...)
Exibe o resultado na tela.
 
### Variação 2
"Otimize o programa em Python usando compreensão de listas."

**entrada.split()
Divide a string digitada em uma lista de números (ex: "4 9 16" → ["4", "9", "16"]).
for n in entrada.split()
Percorre cada valor digitado.
float(n)
Converte cada item para número.
math.sqrt(...)
Calcula a raiz quadrada de cada número.
[ ... for n in ... ]
Aqui está a compreensão de lista, que cria uma nova lista já com os resultados.
 
### Variação 3
"Explique o programa em linguagem simples, como se fosse para um iniciante."
**Ele pega vários números que você digita e calcula a raiz quadrada de cada um deles de uma vez só.

🔎 Linha por linha:

import math
Aqui a gente “puxa” uma caixinha de ferramentas pronta do Python. Dentro dela tem a função que calcula raiz quadrada.

entrada = input("Digite números separados por espaço: ")
O programa pede pra você digitar números.
Exemplo:

4 9 16 25

Tudo isso entra como texto (não como número ainda).

entrada.split()
Essa parte pega o texto e separa em pedacinhos.
Exemplo:

"4 9 16 25" → ["4", "9", "16", "25"]

[math.sqrt(float(n)) for n in entrada.split()]
Essa é a parte mais importante (e pode parecer complicada no começo, mas calma):

Pensa assim:

“Para cada número que eu digitei…”
“Transforma ele em número de verdade (float)”
“Calcula a raiz quadrada”
“Guarda o resultado numa lista”

Ou seja, ele faz tudo isso de uma vez só.

👉 Resultado:

[2.0, 3.0, 4.0, 5.0]

print("Raízes quadradas:", raizes)
Mostra o resultado final na tela.

🧠 Resumindo:

O programa:

Recebe vários números
Separa eles
Calcula a raiz de cada um
Mostra tudo organizado em uma lista

### Reflexão

A cada comando é observado que tem um "enxurgamento" de códigos e jeito de programar. Com isso o prompt fica mais rápido e com poucos códigos.
