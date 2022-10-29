# Prova Presencal Sistemas Operacionais
## Engenharia de Software
---

### **Questão 1**

Associe na tabela o sistema de arquivo à sua respectiva descrição e assinale a alternativa que contém a ordem correta:

|Sistema de Arquivo|Descrição|
|-----|-----|
|I. NTFS|()Suporte a Journaling. Indexação de diretórios ampliada. Muito bom para servidores pois permite até 1024 Pb (Petabytes) para partições e até 16 Tb por arquivos.|
|II. ReiserFS|()Organiza os arquivos em diretórios, como o HPFS. Garante recuperação de dados, identificação e remoção de falhas fatais ao sistema e evita o envio de mensagens de erro ao sistema operacional, técnica conhecida como *hot fixing*|
|III. ext4|()Supor a Journaling. Alocação dinâmica de arquivos. Utiliza a estrutura de dados para armazenamento conhecido como Árvore B+, sendo que os dados são armazenados em unidades chamadas de folhas.|

**Gabarito: III, I, II.**

---

### **Questão 2**

O Sistema operacional é o sistema que faz comunicação entre o hardware e os demais softwares. O Sistema Operacional cria uma plataforma comum a todos os programas utilizados.

Assinale a alternativa que contém os tipos de sistemas operacionais:

**Gabarito: Monotarefa/monoprogramáveis, multitarefa/multiprogramáveis, multiprocessadores, sistemas distribuídos.**

---

### **Questão 3**

O registrador ou registo de uma CPU é a memória dentro da própria CPU que armazena n bits. Os registradores estão no topo da hierarquia de memória, sendo assim, é um tipo de memória mais rápida e financeiramente mais custosa.

Os registros é uma forma de fazer persistir determinada informação durante um período de tempo. Considere as afirmações e assinale a alternativa correta:

I – Os registros podem ser definidos como do tipo lógico ou físico.

II – Os registros lógicos: campos, que contêm atributos como nome, tipo e comprimento.

III – Registros físicos referem-se às ações que serão desempenhadas pelo sistema de arquivos.

Está correto o que se afirma em:

**Gabarito: I, II e III.**

---

### **Questão 4**

Dada a definição "visa estabelecer um critério de acesso e implementar maior segurança ara a realização de ações com os arquivos", assinale a alternativa correspondente ao conceito do atributo apresentado:

**Gabarito: Senha.**

---

### **Questão 5**

Gerenciamento de memória é a tarefa desempenhada pela parte do SO que controla o uso da memória. 

Assinale a alternativa que contém uma das principais responsabilidades da gerência de memória:

**Gabarito: Manter em memória física ou principal, a maior quantidade de processos residentes de forma que seja possível aproveitar ao máximo o compartilhamento de recursos.**

---

### **Questão 6**

O controle remoto das TVs atuais possui microfone e aceita comandos por voz; comunica-se com a tela por Bluetooth, servindo como mouse ou cursor, com sensor de movimentos ou touchpad. As TVs Smart possuem processadores de alto desempenho e sistema operacional como os computadores, com plataforma multitarefas que podem processar mais de uma tela ao mesmo tempo, de forma mais intuitiva e integrada.

Fonte: SANTOS, A. TVs: comparando os sistemas operacionais. Home Theater e Casa Digital, 2015. Disponível em: . Acesso em: 23 abr. 2018.

Analisando o texto acima e conhecendo as características dos sistemas operacionais multitarefa, marque a questão correta:

**Gabarito: No caso do texto apresentado, as televisões atuais conseguem realizar várias tarefas ao mesmo tempo, pois o sistema operacional instalado nelas gerencia de forma eficaz as atividades solicitadas pelos usuários, como acessar a internet e ouvir música.**

---

### **Questão 7**

Complete a frase com uma das opções das alternativas a seguir:

Uma _____________________, também chamada de ______, é responsável por manter atualizadas as informações dos arquivos abertos e isto ocorre para todos os processos do sistema, em função de um arquivo ser acessado por vários processos ao mesmo tempo.

**Gabarito: tabela de descritores de arquivos abertos / TDAA.**

---

### **Questão 8**

Devemos conhecer ferramentas importantes do ambiente computacional para facilitar algumas atividades, como a escolha de programas, aplicativos e dispositivos.

Os sistemas operacionais têm, basicamente, algumas funções, entre elas, analise as afirmativas abaixo e selecione a alternativa correta:

I. facilitar o acesso a recursos do sistema;

II.organizar o compartilhamento de recursos de forma a garantir a sua proteção.

III. é responsável por verificar os parâmetros da solicitação e enviar a sua respectiva resposta com o estado do processo, no caso, concluído, ou se houve algum erro e precise retornar à pilha de processos

**Gabarito: Apenas as assertivas I e II estão corretas.**

---

### **Questão 9**

Com relação à classificação dos sistemas operacionais multiprogramáveis (vários programas utilizando o mesmo recurso) e à maneira com que as aplicações são gerenciadas, analise as questões a seguir e associe as colunas de acordo com a característica de cada sistema:
|Coluna 1|Coluna 2|
|---|---|
|1. Sistema batch. |( ) Vários programas são executados a partir da divisão de tempo do processador.|
|2. Sistema de tempo real. |( ) Não interagem com do usuário com a aplicação.|
|3. Sistemas de tempo compartilhado (time-sharing).	|( ) O tempo é o principal parâmetro de funcionamento.|
|  |( ) O usuário tem a impressão de que o sistema está totalmente disponível para ele.|
|  |( ) Os prazos são rígidos na execução das tarefas.|

Assinale a alternativa que possui a ordem correta da associação das duas colunas:

**Gabarito: 3, 1, 2, 3, 2.**

---

### **Questão 10**

Analise o parágrafo a seguir e complete as lacunas com as palavras de uma das alternativas a seguir, referentes aos conceitos apresentados:

O ___________ tamanho refere-se à quantidade de dados que um arquivo armazena; já localização fornece o diretório, dispositivo de armazenamento ou pastas em que se encontra o arquivo. Quanto a/à

__________, fica evidente a lógica da organização do sistema de arquivos, de forma a permitir sua localização. ______________ atribui restrições quanto à permissão para manipular o arquivo. O tipo define se é um arquivo executável, por exemplo, ou mesmo um arquivo de texto. __________ refere-se à quantidade de vezes que um arquivo passa por alterações, atualizações e mesmo remoção de informações. Por fim, o quadro traz atividade como um indicador de registros constantes em um arquivo.

**Gabarito: atributo / localização / acessibilidade / volatilidade.**

---

### **Questão 11**

O tipo de partição contém um sistema de arquivos. Assinale a alternativa que contém os tipos de particionamento que podem ser realizados:

**Gabarito: Estático e dinâmico.**

---

### **Questão 12**

É verdadeiro o que se afirma em:

I. A principal vantagem em memórias virtuais é que um software pode fazer referência a processos que estejam fora da memória principal, pois deixaram de ser limitados ao tamanho da memória física para que possam ser selecionados e entrar em execução.

II. A principal vantagem é que em memórias virtuais o acesso ao dado é idêntico ao acesso randômico e não utiliza identificadores de processos ou bit de validade.

III. O bit de validade indica o tempo de execução dos processos que estão na memória virtual.

**Gabarito: Apenas I.**

---

### **Questão 13**

O Driver é utilizado para fazer a comunicação entre um hardware e o sistema operacional utilizado na sua máquina.

Assinale a alternativa que contém os componentes de um driver:

**Gabarito: Número de registradores do controlador; comandos do dispositivo e o fluxo de processos de funcionamento do dispositivo a que se refere.**

---

### **Questão 14**

Uma máquina virtual é um software de ambiente computacional em que um sistema operacional ou programa pode ser instalado e executado. De maneira mais simplificada, podemos dizer que a máquina virtual funciona como um "computador dentro do computador".

Fonte: HAMMERSCHMIDT, R. O que são máquinas virtuais? Disponível em: . Acesso em: 23 abr. 2018.

Considerando os conceitos de máquina virtual, escolha a opção correta:

**Gabarito: Nem todos os usuários de computadores precisam de uma máquina virtual, ela é indicada quando é necessário rodar outro sistema operacional no computador.**

---

### **Questão 15**

Swapping faz a verificação de disponibilidade de troca de um processo da memória principal para a memória secundária. 

Swap in refere-se à:

**Gabarito: operação de saída de um processo da memória principal para ser armazenado em disco ou memória secundária.**

---

### **Questão 16**

Memória virtual é uma técnica que usa a memória secundária como uma cache para armazenamento secundário. 

São técnicas de implementação de memória virtual:

**Gabarito: Paginação, segmentação e segmentação com paginação.**