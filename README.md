# CÓDIGO FEITO PARA ESTUDOS DE THREADS EM LINGUAGEM PERL


# [!] ATENÇÃO [!]

...

Ao usar este script, você concorda que esta ciente de que ao realizar um ataque de negação de serviço (DoS) é crime, e que qualquer ataque realizado a um servidor, IP, site, computador ou qualquer outro dispositivo eletrônico ligado ou não a internet sem conscientização do dono resultará em pena de prisão e/ou multa perante as leis do Estado em que ataca e/ou esta atacando, e que você (usuário final) é totalmente responsável pelo uso deste script.

Eu não me responsabilizo pelo mal uso deste script.
...

# Descrição

--------------

Este script realiza um ataque de negação de serviço (DoS) baseado na potência do computador. O interessante dele é que ele faz um loop de criação de variaveis para criação de threads que retornam uma sub rotina.

# COMO EXECUTAR O SCRITP

--------------

Basta você caminhar até o diretório aonde se encontra o script e roda-lo com o comando "~$ perl MultiStresser.pl"


# DEPENDÊNCIAS 

--------------

Você precisará dos seguintes módulos instalados em seu computador:

* threads;
* threads::shared;
* IO::Socket::INET;
* utf8;

--------------
PS: Script disponível apenas para sistemas operacionais Linux para incentivar o uso de Sistemas Operacionais de Códigos Aberto. :D