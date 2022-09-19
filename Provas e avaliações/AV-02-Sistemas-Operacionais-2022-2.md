1) Ao utilizar o comando ls -l no Linux, obtém-se uma lista detalhada, mostrando a seguinte informação sobre as permissões do arquivo teste.txt: rwx rw- r--

Quais as permissões aplicadas ao dono deste arquivo?

**Gabarito: Leitura, gravação e execução.**

---

2) No Linux, as permissões são aplicadas em arquivos e diretórios. Isto é extremamente eficaz e engenhoso porque mesmo os dispositivos no Linux são representados como se fossem arquivos (dentro do diretório /dev).

Assim, é possível, por exemplo, restringir o acesso dos usuários num determinado dispositivo, alterando suas permissões ou grupo pertencente.

No Linux, as permissões são aplicadas em níveis, em relação...

**Gabarito: ... ao dono do arquivo, ao grupo do arquivo e a outros demais usuários do sistema.**

---

3) Segundo Machado e Maia (2007), um sistema de arquivos possui diferentes mecanismos de proteção. Além da senha de acesso e grupo de usuários, pode-se implementar a lista de controle de acesso (Access Control List – ACL), em que é associada a cada arquivo com as permissões de cada usuário.

Agora avalie as seguintes asserções e a relação proposta entre elas:

I. A segurança do sistema operacional pode ser reforçada com o uso da lista de controle de acesso.

PORQUE

II. Quando um usuário tentar acessar um arquivo, o sistema operacional verificará a sua permissão para autorizar ou não a operação.

A respeito dessas asserções, assinale a opção correta.

**Gabarito: As asserções I e II são proposições verdadeiras, e a II é uma justificativa da I.**

---

4) Existem questões de confiabilidade que devem manter a integridade dos arquivos, como consistência do sistema de arquivos e cópias de segurança (backups). A consistência do sistema de arquivos permite que os arquivos sejam salvos antes de finalizar a sua tarefa. Assim, caso um usuário esteja modificando um arquivo e a luz acabe, por exemplo, a parte trabalhada até o momento é salva em disco. 

As cópias de segurança (backups) garantem que:

**Gabarito: os dados sejam copiados e armazenados em diferentes lugares e dispositivos.**

---

5) Segundo Machado e Maia (2007), o sistema operacional precisa controlar quais as áreas ou blocos no disco estão livres quando um arquivo é criado. A seguir serão apresentados os principais métodos de implementação de arquivos utilizados nos sistemas operacionais.

Fonte: MACHADO, Francis B.; MAIA, Luiz P. Arquitetura de sistemas operacionais. 5. ed. Rio de Janeiro: LTC, 2013.

De acordo com as informações apresentadas na tabela a seguir, faça a associação dos métodos de implementação de arquivos contidas na coluna A com suas respectivas vantagens e desvantagens contidas na coluna B.

Coluna A:
I. Alocação por lista Encadeada usando uma tabela na memória

II. Alocação por lista encadeada.

III. Alocação Contígua.

Coluna B:
1. Não há desperdício de espaço com a fragmentação, além de precisar somente do primeiro endereço do disco para acessar todo o arquivo. Porém, o acesso aleatório é lento, além de gastar espaço de memória para armazenar os ponteiros.

2. Método é simples e possui um bom desempenho. Porém, gera a fragmentação do disco.

3. O acesso aleatório se torna mais fácil pela tabela estar carregada na memória. Porém, a tabela deve estar na memória o tempo todo para funcionar.

**Gabarito: I-3, II-1, III-2.**