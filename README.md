# Caixa Eletrônico - Banco XYZ

Bem-vindo ao Caixa Eletrônico do Banco XYZ!

## Introdução

Este projeto consiste em melhorias e ajustes para um caixa eletrônico. Certifique-se de entender cada modificação antes de implementá-las.

## Modificações e Ajustes

1. **Saudação Personalizada**
    - Ao acessar o sistema, pergunte o nome do usuário e exiba a mensagem "Olá {Nome}, é um prazer ter você por aqui!"

2. **Menu Principal**
    - Na função "inicio", utilize a estrutura de escolha/caso (switch/case) para validar a opção escolhida pelo usuário.

3. **Restrição de Saque**
    - Ao realizar um saque, o valor restante não pode ser negativo. Caso o usuário tente sacar mais do que tem em saldo, exiba a mensagem "Operação não autorizada."

4. **Validação de Valor de Saque**
    - O valor a ser sacado não pode ser igual ou menor que zero. Em caso de tentativa inválida, exiba a mensagem "Operação não autorizada."

5. **Opção Extrato**
    - Adicione a opção para ver o extrato, incluindo algumas transações fictícias.

6. **Opção Transferência**
    - Adicione a opção para fazer uma transferência. Solicite o número da conta e o valor da transferência. Caso o usuário tente transferir mais do que tem em saldo, exiba "Operação não autorizada."

7. **Validação de Valor de Transferência**
    - O valor a ser transferido não pode ser igual ou menor que zero. Em caso de tentativa inválida, exiba a mensagem "Operação não autorizada."

8. **Ordem do Menu Principal**
    - No menu principal, altere a ordem das opções para: Saldo, Extrato, Saque, Depósito, Transferência e Sair.

9. **Atualização da Função "Erro"**
    - Atualize a função "erro" para incluir as novas opções do menu.

10. **Validação de Depósito**
    - Caso o usuário informe um valor igual ou menor que zero para depósito, exiba a mensagem "Operação não autorizada."

11. **Senha de Acesso**
    - Sempre que o usuário acessar o saldo, sacar, visualizar o extrato ou transferir dinheiro, solicite uma senha (Senha padrão: 3589). Valide a senha com uma condicional. Caso incorreta, chame a função novamente.

12. **Mensagem de Despedida**
    - Ao sair do sistema, exiba a mensagem agradecendo por utilizar os serviços do banco: "{Nome}, foi um prazer ter você por aqui!"

## Observações

Certifique-se de testar todas as funcionalidades. Experimente e divirta-se!

**Equipe de Desenvolvimento - Banco XYZ**
