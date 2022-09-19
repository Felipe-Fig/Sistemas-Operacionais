1) As memórias de um computador podem variar em sua tecnologia, capacidade de armazenamento, velocidade, custo, e são interligadas de modo estruturado, compondo um subsistema de memória. Este subsistema também chamado de hierarquia de memória é mostrado na figura a seguir. Os diversos tipos de memórias são mostrados em ordem decrescente de acordo com a velocidade, sendo os registradores as memórias que apresentam maiores velocidades porém com menor capacidade e as memórias secundárias as que são mais lentas e com maior capacidade.

Fonte: FÁVERO, Eliane M. B. Organização e arquitetura de computadores. Pato Branco: Universidade Tecnológica Federal do Paraná, 2011.

![fig1adg04so](https://github.com/Felipe-Fig/Sistemas-Operacionais/blob/6effde960ac7b60f6c014f2539089fbe9cb5f803/Provas%20e%20avalia%C3%A7%C3%B5es/fig1%20adg04%20so.png)

Sobre o subsistema de memórias de um computador, analise as sentenças a seguir.

I. Os registradores são locais da memória que armazenam os dados que serão processados.

II. Memória cache é um tipo de memória não volátil.

III. A memória principal é também chamada de memória RAM (Random Access Memory).

IV. Memória secundária ou memória ROM (Ready Only Memory) é um tipo de memória volátil.

Agora, assinale a alternativa que apresenta a resposta CORRETA.

**Gabarito: Apenas as afirmativas I e III estão corretas.**

---

2) Quando se fala em gere^ncia de memo´ria é comum associar conceitos que estão diretamente relacionados aos espac¸os reservados em memo´ria principal para alocar processos residentes e que em um determinado momento precisam ceder esse enderec¸o ou posic¸a~o de memo´ria a outros processos na~o residentes.

Com relação à gerência de memória, complete as lacunas da sentença a seguir.

A técnica de _________foi desenvolvida com o intuito de solucionar um problema comum em _________, que é a falta de espaço na memória principal. Então, ela propõe que, ao invés de um processo residente em _________, esse seja enviado por tempo determinado para a memória secundária, para dar espaço suficiente para que um processo não residente seja alocado e, com isso, após a sua execução, o espaço volta a ser liberado para que aquele processo residente retorne ao endereço de origem.

Assinale a alternativa que completa as lacunas corretamente.

**Gabarito: swapping / multiprogramação / memória principal.**

---

3) A alocação contigua simples (outro termo usado para monoprogramação sem troca de processos ou paginação) foi utilizada nos primeiros sistemas operacionais e ainda está presente em alguns sistemas monoprogramáveis. O usuário tem o controle sobre toda a memória, podendo acessar qualquer posição dela e, até mesmo, a área do sistema operacional.

Neste método, a utilização de recursos computacionais não é eficiente, pois:

**Gabarito: somente um usuário tem acesso aos recursos.**

---

4) Em sistemas de compartilhamento de tempo (ou time-sharing) quando ha´ algum tempo ocioso entre um processo e outro, executa-se um outro processo de forma que se possa alternar entre va´rios processos, transmitindo ao usua´rio a impressa~o de que os processos esta~o sendo executados simultaneamente. No entanto, eles compartilham o tempo de execuc¸a~o.

Fonte: TANENBAUM, A. S. Sistemas Operacionais Modernos. 2.ed. São Paulo: Pearson, 2003.

Com relação aos sistemas de compartilhamento, complete as lacunas da sentença a seguir.

Nestes sistemas de compartilhamento de tempo ou computadores pessoais com memória RAM insuficiente para conter todos os processos ativos do sistema, é necessário que eles permaneçam em _________ e sejam trazidos dinamicamente para a memória para serem executados somente quando necessário. Neste caso, podem ser utilizados dois métodos para o gerenciamento de memória: troca de processos (também conhecido como _________) e  _________.

Assinale a alternativa que completa as lacunas corretamente.

**Gabarito: disco / swapping / memória principal.**

---