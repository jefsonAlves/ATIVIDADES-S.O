# Atividade 2
## Memoria RAM

> A memória RAM é um tipo de tecnologia que permite o acesso aos arquivos armazenados no computador. Diferentemente da memória do HD, a RAM não armazena conteúdos permanentemente. É responsável, no entanto, pela leitura dos conteúdos quando requeridos. Ou seja, de forma não-sequencial, por isso, a nomenclatura em inglês de Random Access Memory (Memória de Acesso Aleatório). 
Quanto maior a memória RAM, maior sua capacidade de trabalho. Mas a capacidade da é medida em área. Quanto maior mais rapidamente se faz o trabalho. Já a capacidade da memória RAM, mede-se pelo fluxo de bits suportados nas operações.
Ou seja, para se acessar uma grande quantidade de memória no HD de uma só vez, como muitos programas atuais exigem, é necessário uma grande quantidade de memória RAM. São estes, portanto, os megabites ou gigabites que aparecem nas configurações.
A memória RAM é um chip semelhante a um micro-processador, composto por milhões de transistores e capacitores. O capacitor é uma peça capaz de armazenar elétrons. Quando ele está carregado, o sistema faz uma leitura com base no famoso código binário de “zeros e uns”. Cada leitura dessa em zero ou um significa um bit de informação. Essa leitura é feita de forma muito rápida, são muitas em poucos milésimos de segundos. É assim que a memória RAM processa todas as ações executadas pelo usuário.

## Memória ROM

> O termo ROM, a rigor, serve para diferenciar uma memória que só pode ser lida, e nunca escrita, de uma que tem caráter randômico: permite que dados sejam escritos, lidos e apagados sem problemas. ROM é uma sigla no inglês para “memória somente de leitura”. Portanto, surgiu como forma de diferenciar da RAM, que por sua vez, refere-se à “memória de acesso randômico”.
Mas para que um computador precisava de uma memória que não poderia ser apagada ou escrita? Na verdade, eles ainda precisam. Um bom exemplo de memória ROM é a BIOS do seu computador.
A BIOS é um chip que carrega as configurações mais básicas do sistema antes de inicializar o sistema operacional propriamente dito. Ela verifica se a data e hora estão certas, se a ventoinha do processador está operando, se os diversos periféricos e controladores estão recebendo tensão, bem como se as memórias RAM estão prontas para trabalhar para, enfim, "chamar" o HD que acordará o sistema operacional. 
Retirado: TechTudo

## SWAP

>Usada pelos sistemas operacionais para aumentar quantidade de memória real do computador a fim de rodar os programas e o próprio sistema sem travamentos.
Essa memória virtual que vai auxiliar a memória RAM fica armazenada no seu HD e tem diferenças de sistema para sistema, porém cumpre a mesma função.
A memória SWAP tem uma ligação quase familiar com a memória RAM, uma ajuda a outra, para ser mais claro, a memória SWAP costuma entrar em ação quando a memória RAM não consegue "dar conta do recado".
Retirado: Diolinux

## Paginação de Memória

> No contexto dos sistemas operacionais,  paginação da memória do computador é um processo de virtualização da memória que consiste na subdivisão da memória física em pequenas partições (frames), para permitir-lhe uma utilização mais eficiente. As frames da memória física correspondem a páginas de memória virtual. A alocação de memória é requisitada por páginas, a menor unidade deste método. Cada página é mapeada numa frame de memória através de um processo que chama paginação. 
A paginação é implementada normalmente por unidades dedicadas de hardware integradas nos processadores. No caso dos processadores da família Intel x86, esta funcionalidade está atribuída à MMU. A paginação é obtida através de consulta a tabelas que relacionam os endereços lineares das páginas de memória com os endereços físicos das frames de memória respectivas.
Neste sistema, cada processo no computador tem a sua própria tabela de páginas, em que a cada endereço virtual corresponde o endereço físico em que a informação está efectivamente armazenada. Visto que a informação está dividida em pequenas unidades, o seu armazenamento não tem de ser necessariamente sequencial, o que elimina a fragmentação externa da memória.

Retirado: https://pt.wikipedia.org/wiki/Mem%C3%B3ria_paginada 
