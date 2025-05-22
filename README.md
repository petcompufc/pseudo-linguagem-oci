# Pseudo-linguagem para a Olimpíada Cearense de Informática

- Nesse documento está especificada o os detalhes referentes à pseudo-linguagem para as questões que possuem algoritmos na prova
- Estamos nos baseando na linguagem **Python** por ser uma ferramenta mais conhecida dentre os estudantes de computação
- Aqui está um *cheat sheet* que apresenta os pontos mais importantes com base na linguagem Python

| Ação | Python | Pseudo-linguagem |
| - | - | - |
| Atribuição | `a = 5` | `a = 5` |
| Igual | `a == 5` | `a == 5` |
| Menor que | `a < 5` | `a < 5` |
| Maior que | `a > 5` | `a > 5` |
| Menor que ou igual | `a <= 5` | `a <= 5` |
| Maior que ou igual | `a >= 5` | `a >= 5` |
| Conjunção | `a and b` | `a E b` |
| Disjunção | `a or b` | `a OU b` |
| Negação | `not a` | `NÃO a` |
| Estrutura condicional | <pre>if a == 5:<br>  .<br>  .<br>  .</pre> | <pre>se a == 5:<br>  .<br>  .<br>  .</pre>
| Laço while | <pre>while a == 5:<br>  .<br>  .<br>  .</pre> | <pre>enquanto a == 5:<br>  .<br>  .<br>  .</pre>
| Laço for (em lista) | <pre>for e in lista:<br>  .<br>  .<br>  .</pre> | <pre>para cada e em lista<br>  .<br>  .<br>  .</pre>
| Laço for (estilo C) | <pre>for i in range(0,5):<br>  .<br>  .<br>  .</pre> | <pre>para i de 0 até 4:<br>  .<br>  .<br>  .</pre>**ATENÇÃO**: o "range" da pseudo-linguagem inclui o último elemento |
| Laço for (estilo C com passo diferente de 1) | <pre>for i in range(0,5,2):<br>  .<br>  .<br>  .</pre> | <pre>para i de 0 até 4 passo 2:<br>  .<br>  .<br>  .</pre>**ATENÇÃO**: o "range" da pseudo-linguagem inclui o último elemento |
| Declaração de função | <pre>def nomeFuncao(a, b):<br>  c = a + b</pre> | <pre>func nomeFuncao(a, b):<br>  c = a + b</pre> |
| Chamada de função | <pre>nomeFuncao(a, b)</pre> | <pre>nomeFuncao(a, b)</pre> |
| Entrada de dados | <pre>a = input('Insira valor de a')</pre> | <pre>a = leia("Insira valor de a")</pre> |
| Saída de dados | <pre>print(a)</pre> | <pre>escreva(a)</pre> |

- Esse documento pode ser alterado caso haja necessidade
