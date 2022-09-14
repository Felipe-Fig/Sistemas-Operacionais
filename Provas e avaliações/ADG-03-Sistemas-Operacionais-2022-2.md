1) Um arquivo é definido como um conjunto de dados armazenados em um dispositivo físico não volátil, com um nome ou outra referência que permita sua localização posterior. A forma mais simples de organização de arquivos é através de uma seqüência não-estruturada de bytes, onde o sistema de arquivos não impõe nenhuma estrutura lógica para os dados. É um conjunto de registros definidos pelo sistema de arquivos e podem ser armazenados em diferentes dispositivos físicos. A parte do sistema responsável pela gerência é denominada sistema de arquivo que é a parte mais visível do sistema operacional.

Sobre o sistema de arquivos, é correto afirmar que:

**Gabarito: A principal vantagem do sistema sem estrutura lógica para os dados é a flexibilidade para criar as estruturas de dados.**

---

2) Cada arquivo é caracterizado por um conjunto de atributos, que podem variar de acordo com o sistema de arquivos utilizado. Os atributos mais usuais são: nome, tipo, tamanho, proprietários e permissões de acesso. Nem sempre os atributos oferecidos por um sistema de arquivos são suficientes para exprimir todas as informações a respeito de um arquivo, nesse caso, a solução encontrada pelos usuários é usar o nome do arquivo para exprimir a informação desejada.

Assinale a alternativa correta:

**Gabarito: O formato de arquivo é definido pelo núcleo do sistema operacional, reconhecendo os formatos de arquivos binários executáveis e bibliotecas.**

---

3) No acesso sequencial de arquivos, os dados são lidos e/ou escritos em sequência, do início ao final do arquivo. Para cada arquivo aberto por uma aplicação é definido um ponteiro de acesso, que inicialmente aponta para a primeira posição do arquivo. A cada leitura ou escrita, esse ponteiro é incrementado e passa a indicar a posição da próxima leitura ou escrita. Quando esse ponteiro atinge o final do arquivo, as leituras não são mais permitidas, mas as escritas ainda o são, permitindo acrescentar dados ao final do mesmo. A chegada do ponteiro ao final do arquivo é normalmente sinalizada ao processo através de um flag de fim de arquivo.

Outra forma de acessar arquivos é de forma direta. Analise as afirmações a seguir:

I) No método de acesso direto indica-se a posição no arquivo onde cada leitura ou escrita deve ocorrer, sem a necessidade de um ponteiro.

II) No acesso direto deve-se conhecer previamente a posição de um determinado dado no arquivo.

III) A vantagem do acesso direto é acessar rapidamente as posições do arquivo correspondentes ao registros desejados em uma operação.

É correto o que se afirma em:

**Gabarito: I, II e III apenas.**

---

4) Complete as lacunas a seguir:

A estrutura de ____________ é como o sistema organiza logicamente os diversos arquivos contidos em um ____________. O diretório é uma estrutura de dados que contém entradas associadas aos ____________ em que cada entrada armazena informações com localização física, nome, organização e demais atributos.

Assinale a alternativa que preenche corretamente as lacunas:

**Gabarito: diretórios / disco / arquivos.**