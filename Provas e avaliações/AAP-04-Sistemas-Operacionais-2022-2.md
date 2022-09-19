1) A memória principal é também chamada de memória RAM (Random Access Memory) e faz o armazenamento dos dados inseridos no computador, dados de programas e os próprios programas. Ela permite ao processador ter acesso às memórias secundárias, disponibilizando os dados gravados nestas memórias e processá-los.

Fonte: PETTERSON, D. A.; HENNESSY, J. L. Arquitetura de computadores: uma abordagem quantitativa. Rio de Janeiro: Elsevier, 2014.

Considerando o contexto apresentado, avalie as seguintes asserções e a relação proposta entre elas:

I. A memória principal é do tipo não volátil.

PORQUE

II. Os dados armazenados na memória principal são apagados quando o computador é desligado.

A respeito dessas asserções, assinale a opção correta.

**Gabarito: A asserção I é uma proposição falsa, e a II é uma proposição verdadeira.**

---

2)

A multiprogramação é uma técnica utilizada na maioria dos sistemas operacionais modernos e permite que vários processos executem ao mesmo tempo. Essa técnica apresenta alguns problemas, um dele é a transferência de um código de um local para outro de forma que um programa não escreva na área de outro programa. Esse problema é necessário uma vez que processos executam em diferentes endereços na memória física.

O problema da multiprogramação que realiza essa transferência de um código para outro sem escrever na área de outra programa é a:

**Gabarito: realocação.**

---

3) Segundo Tanenbaum (2003), o gerenciamento de memória pode ser dividido em duas classes: (1) sistemas que durante o processamento levam e trazem a informação da memória para o disco e (2) sistemas que não o fazem.

De acordo com o contexto, complete as lacunas da sentença a seguir.

A _____________carrega todo o programa para a memória principal, o executa por um determinado tempo e depois o mesmo retorna para o disco. A ____________ divide o/a  ____________em partições para a execução das aplicações de forma eficiente.

Assinale a alternativa que completa as lacunas corretamente.

**Gabarito: troca de processos / paginação / memória.**

---

4) A troca de processos (swapping) é uma técnica que traz totalmente cada processo para a memória, o executa por algum tempo e o retorna para o disco.

Fonte: TANENBAUM, A. S. Sistemas Operacionais Modernos. 2.ed. São Paulo: Pearson, 2003.

Considerando o contexto apresentado, analise as afirmativas a seguir e assinale V para verdadeiro e F para falso:

(  ) Swapping faz a verificação de disponibilidade de troca de um processo da memória principal para a memória secundária.

(  ) Através de um algoritmo que é responsável por verificar qual processo residente está estado de espera, um processo pode ceder o seu espaço para que um outro processo utilize aquele recurso.

(  ) Ao se realizar swapping, é possível compartilhar mais recursos ou endereços na memória principal.

(  ) Embora haja melhor aproveitamento da memória principal, a técnica de swapping não consegue otimizar o processamento e maximizar a utilização dos recursos da máquina de modo geral.

Assinale a alternativa que apresenta a sequência CORRETA:

**Gabarito: V – V – V – F.**