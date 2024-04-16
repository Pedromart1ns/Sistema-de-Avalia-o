# Sistema-de-Avalia-o

---

# Sistema de Avaliação de Alunos

Este programa em C permite a avaliação de 10 alunos com base em suas notas e atribui um conceito correspondente a cada aluno.

## Como usar o programa

1. Compile o código-fonte usando um compilador C, como o gcc:

```
gcc -o avaliacao_alunos avaliacao_alunos.c
```

2. Execute o programa compilado:

```
./avaliacao_alunos
```

3. Siga as instruções para inserir as três notas de cada aluno quando solicitado.

4. O programa calculará a média das notas e atribuirá um conceito correspondente a cada aluno.

## Exemplo de Uso

```
Digite a primeira nota do 1° aluno:
8.5
Digite a segunda nota do 1° aluno:
7.8
Digite a terceira nota do 1° aluno:
6.9
O 1° aluno obteve o conceito B
...
```

## Como funciona

1. O programa utiliza um laço de repetição `for` para iterar sobre cada um dos 10 alunos.
2. Para cada aluno, solicita-se que o usuário insira as três notas.
3. Calcula-se a média das notas do aluno.
4. Com base na média, o programa atribui um conceito ao aluno:
   - A: média maior ou igual a 9
   - B: média maior ou igual a 7 e menor que 9
   - C: média maior ou igual a 6 e menor que 7
   - D: média maior ou igual a 4 e menor que 6
   - E: média menor que 4
5. O programa repete esse processo para os 10 alunos.

## Observações

- O programa presume que as notas inseridas são números reais.
- A função `setlocale` é utilizada para configurar a localidade para "Portuguese", permitindo a exibição correta de caracteres especiais em português.

--- 
