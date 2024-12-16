# Lab 9 -  Modelação de Classes e Composição

## Aplicações Java 

:dart: Desenvolva os seguintes programas com recurso ao IDE `IntelliJ IDEA`.

:warning: Crie os diferentes exercícios em projetos separadas.

:warning: Não se esqueça de guardar o seu trabalho!  

## Exercícios :pen:

Pretende-se gerir uma conta de e-email. Cada e-mail contém o endereço de quem o enviou (remetente), a data de envio, o assunto e o texto do corpo do e-mail.

1. Crie a classe `Date` que representa uma data (dia, mes e ano);

2. Crie uma classe `Mail` que represente um e-mail;

3. Crie uma classe `MailBox` que permita guardar todos os e-mails na conta (enviados e recebidos). 

    Esta classe possui como atributos: 
    - o endereço de e-mail da conta;
    - uma lista de e-mails recebidos (caixa de entrada);
    - uma lista de e-mails enviados (caixa de saída);    
    - uma lista de e-mails considerados *spam* (caixa de spam).  
    
    Implemente as seguintes operações (dê nomes apropriados e decida os parâmetros e retornos necessários):

    - Enviar um email (o endereço do remetente é o da caixa);
    - Receber um email;
    
    - Determinar o número total de e-mails enviados; 
    - Determinar o número total de e-mails recebidos;  
    - Determinar o número total de e-mails *spam*;  

    - Imprimir o "estado" da conta de email, no formato:

        ```console
        MailBox[address=?, inboxCount=?, sendCount=?, spamCount=?]
        ```

    - Devolver os emails diferentes caixas (deve retornar cópias das coleções);

    - Criar uma lista de e-mails recebidos que têm por origem um dado endereço de remetente.

    - Criar uma lista de e-mails recebidos que no assunto contêm uma determinada palavra(s) - ignore a capitulação das letras.

    - Criar uma lista dos emails recebidos no dia de hoje.

    - Eliminar todos os e-mails recebidos antes de uma determinada data (de todas as caixas);
    
    - Dada uma lista de palavras, marcar como *spam* todos os e-mails que no seu assunto contenham uma qualquer destas palavras.

        - Utilize *varargs* para passar a lista de palavras: <https://www.geeksforgeeks.org/variable-arguments-varargs-in-java/>
    
4. Crie um programa de teste (não necessita criar nenhum menu ou interação com o utilizador).
     

---
paula.miranda@estsetubal.ips.pt e bruno.silva@estsetubal.ips.pt

