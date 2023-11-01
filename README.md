# Projeto-de-Criptacao-Descriptacao
Neste projeto, foi desenvolvido um programa de criptografia e descriptografia em Python que utiliza a cifra de Vigenère e a cifra de Cézar juntas. Após tentar construir a cifra de Cézar e ver limitações nela, apareceu a opção de trabalhar com a cifra de Vigenère que também havia limitações, sendo assim, as duas foram adicionadas em um mesmo código para trabalharem simultaneamente. O usuário vai inserir uma mensagem e uma chave, a partir da chave o código vai criptografar a mensagem passando pela cifra de Cézar e pela cifra de Vignère.

# Funcionalidades do Programa
Criptografia: Permite ao usuário inserir uma mensagem e uma chave para criptografar a mensagem. A mensagem é convertida em uma série de números com base na tabela de caracteres personalizada e, em seguida, realiza uma operação de soma com a chave para criar a mensagem criptografada.

Descriptografia: Permite ao usuário inserir uma mensagem criptografada e a chave correspondente para descriptografar a mensagem. O processo reverso é aplicado, onde a chave é subtraída da mensagem criptografada para obter a mensagem original.

Saída do Programa: O programa permite ao usuário sair a qualquer momento.

# Cifras de criptografia e descriptografia
### Cifra de Vigenère
A cifra de Vigenère é um método de criptografia polialfabética que utiliza uma chave para cifrar mensagens. Em vez de substituir cada letra individualmente, como na cifra de César, a cifra de Vigenère aplica diferentes deslocamentos ao longo da mensagem, dependendo da chave. Isso torna a criptografia mais segura e difícil de ser quebrada.

### Cifra de Cézar
A cifra de César é um tipo simples de cifra de substituições em que cada letra em um texto é derivada de outra letra que está localizada um número fixo de posições à frente no alfabeto. A chave vai resultar em um número inteiro que determina o deslocamento no alfabeto. Por exemplo, se a chave for 3, isso significa que cada letra será deslocada 3 posições.

# Limitações
Esse código apresenta as seguintes limitações:

Palavras com acento não são descriptadas em sua grafia exata;
Na cifra de Vigenère e na criptação com as duas cifras, caso o usuário insira aspas simples ('') ou hashtag (#) o código não irá funcionar.

# Colaboradores
Andrew Alaniz; Caio Miazzi; Christiany Belini; Kely Murta; Letícia Costa.

