1) Uma forma particular de acesso direto ao conteúdo de um arquivo é o mapeamento em memória por meio de mecanismos de memória virtual. Nesse tipo de acesso, um arquivo é associado a um vetor de bytes (ou de registros) de mesmo tamanho na memória principal, de forma que cada posição do vetor corresponda à sua posição equivalente no arquivo. As escritas no vetor são transferidas para o arquivo por um procedimento similar. Caso o arquivo seja muito grande, pode-se mapear em memória apenas partes dele.

Sobre acessos aos arquivos, assinale a alternativa correta:

**Gabarito: Quando uma posição específica do vetor ainda não acessada é lida, é gerada uma falta de página. O mecanismo de paginação da memória virtual intercepta o acesso à memória, lê o conteúdo correspondente no arquivo e o deposita no vetor.**

---

2) Quando um arquivo é aberto e usado por um único processo, o funcionamento das operações de leitura e escrita é inequívoco: quando um dado é escrito no arquivo, este está prontamente disponível para leitura se o processo desejar lê-lo novamente. No entanto, arquivos podem ser abertos por vários processos simultaneamente, e os dados escritos por um processo podem não estar prontamente disponíveis aos demais processos que leem aquele arquivo.

Isso ocorre porque os discos rígidos...

**Gabarito: ...são normalmente lentos, o que leva os sistemas operacionais a usar buffers intermediários para acumular os dados a escrever e assim otimizar o acesso aos discos.**

---

3) Um programa de suporte independente para sistemas de arquivos englobando um sistema de gestão empresarial abaixo do padrão oferece um serviço básico simples, a um custo inicial relativamente baixo. A realidade é que essa abordagem de baixa qualidade, com um conjunto incompleto de serviços, não protege a empresa de riscos e de custos ocultos, incluindo a evolução e o aumento da vida útil de um software de missão crítica. Esse nível de suporte inferior coloca as organizações em risco em vários níveis.

Avalie as afirmações a seguir quanto aos níveis de risco:

I) Risco Operacional de Inatividade, afetando a credibilidade empresarial.

II) Risco de Compliance por uso indevido de arquivos, que pode levar a multas e despesas legais.

III) Risco de Segurança ao sistema de usuário, que se torna ainda mais ameaçador e prejudicial.

É correto o que se afirma em:

**Gabarito: I, II e III apenas.**

---

4) As chamadas aos sistemas que gerenciam as operações com diretórios variam de sistema para sistema. As principais operações de manipulação de diretórios são: create, delete, opendir, closedire rename.

De acordo com as informações apresentadas na tabela a seguir, faça a associação das operações de manipulação de diretórios contidas na coluna A com suas respectivas descrições na coluna B.

COLUNA A
I. Create

II. Delete

III. Opendir

IV. Closedir

V. Rename

COLUNA B
1. Apaga um diretório.

2. Após a leitura de um diretório, ele é fechado liberando espaço em disco.

3. Permite a troca de nome de um diretório.

4. Lê um diretório.

5. Cria um diretório.

Assinale a alternativa que apresenta a associação CORRETA.

**Gabarito: I-5, II-1, III-4, IV-2, V-3.**