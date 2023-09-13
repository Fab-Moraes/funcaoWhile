# funcaoWhile
1. **`opcao = -1`**: Inicializa a variável **`opcao`** com o valor -1, que é usado como valor inicial para entrar no loop.
2. **`while opcao != 0:`**: Inicia um loop que continuará até que a variável **`opcao`** seja igual a 0. Enquanto a opção não for 0, o programa continuará a solicitar ao usuário uma escolha de operação.
3. **`opcao = int(input("[1] Sacar \n[2] Extrato \n[0] sair \n: "))`**: Solicita ao usuário que insira um número inteiro que corresponde a uma das opções: 1 para sacar, 2 para exibir o extrato e 0 para sair. O valor inserido pelo usuário é convertido para um número inteiro e atribuído à variável **`opcao`**.
4. **`if opcao == 1:`**: Verifica se a opção escolhida pelo usuário é 1 (sacar). Se for o caso, o programa exibe "Sacando..." na tela.
5. **`elif opcao == 2:`**: Verifica se a opção escolhida pelo usuário é 2 (exibir extrato). Se for o caso, o programa exibe "Exibindo Extrato..." na tela.
6. **`else:`**: Este bloco não está presente no código, mas você mencionou que "também posso acrescentar o else". Se você adicioná-lo, pode lidar com casos em que o usuário insira uma opção inválida, exibindo uma mensagem apropriada.
7. **`print("Obrigado por usar nosso sistema bancário, até logo!")`**: Quando o usuário escolhe a opção 0 (sair), o loop **`while`** termina e essa mensagem é exibida, agradecendo ao usuário por usar o sistema bancário e encerrando o programa.
