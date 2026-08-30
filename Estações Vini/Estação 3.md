## Estação 3: Fechando as Portas

**Tópico 1: O que é soberania digital?**

A terceira estação apresenta o conceito de **soberania digital** como a capacidade de uma pessoa compreender, controlar e proteger seus próprios dados, contas, dispositivos e permissões no ambiente digital.

No cotidiano, utilizamos dezenas de serviços diferentes e, muitas vezes, concedemos permissões sem analisar exatamente o que está sendo autorizado. Aplicativos podem ter acesso a informações da nossa conta, arquivos podem ser compartilhados com outras pessoas e contas podem permanecer sem mecanismos adicionais de proteção.

Por isso, segurança digital não significa apenas utilizar uma senha forte.

Ter soberania digital significa saber:

- Quais dados estão armazenados sobre nós;
- Quem pode acessar esses dados;
- Quais aplicativos possuem acesso às nossas contas;
- Quais arquivos estão compartilhados;
- Quais permissões foram concedidas;
- Quais dispositivos estão conectados às nossas contas;
- Quais mecanismos existem para impedir acessos não autorizados.

A ideia central desta estação é mostrar que **uma conta pode estar tecnicamente protegida por uma boa senha e ainda assim possuir diversas portas abertas**.

---

## Tópico 2: Segurança não é apenas uma senha forte

Uma senha forte é uma das primeiras barreiras contra acessos não autorizados, mas ela não é suficiente para garantir a segurança de uma conta.

Imagine, por exemplo, que uma pessoa possua uma senha extremamente complexa, mas tenha concedido acesso à sua conta para diversos aplicativos que não utiliza mais.

Nesse caso, o problema não está necessariamente na senha. O problema está nas **permissões concedidas**.

O mesmo acontece com arquivos armazenados em serviços de nuvem. Um documento pode possuir informações pessoais importantes e, mesmo que a conta esteja protegida, o arquivo pode estar configurado para ser acessado por qualquer pessoa que possua o link.

Por isso, nesta estação serão apresentadas diferentes formas de "fechar as portas" de uma conta:

**Senha:** primeira barreira contra acessos indevidos.

**Permissões:** determinam quais aplicativos e serviços podem acessar informações da conta.

**Compartilhamento:** determina quem pode acessar arquivos e informações armazenados na nuvem.

**Autenticação em dois fatores:** adiciona uma segunda etapa de verificação para dificultar o acesso mesmo quando a senha é descoberta.

**Auditoria:** processo de verificar regularmente as configurações e identificar acessos ou permissões desnecessárias.

---

# Prática 1: Auditoria do Google Drive

A primeira atividade consiste em realizar uma pequena auditoria nos arquivos armazenados no **Google Drive**.

O objetivo é descobrir quantos arquivos estão compartilhados e verificar se as permissões concedidas ainda fazem sentido.

Um arquivo pode possuir diferentes níveis de acesso, dependendo da configuração utilizada. Por exemplo, uma pessoa pode possuir permissão apenas para visualizar um documento, enquanto outra pode receber autorização para editar ou compartilhar aquele arquivo.

Durante a atividade, os alunos deverão utilizar o filtro de pesquisa:

**`is:shared`**

Esse comando permite localizar arquivos que foram compartilhados com outras pessoas.

Após realizar a busca, os alunos deverão analisar alguns arquivos e observar:

- Com quem o arquivo está compartilhado;
- Se a pessoa possui permissão para visualizar ou editar;
- Se o compartilhamento ainda é necessário;
- Se existem arquivos antigos que continuam compartilhados;
- Se informações pessoais ou acadêmicas estão disponíveis para outras pessoas.

A atividade deverá demonstrar que um arquivo antigo pode continuar acessível mesmo depois de ter deixado de ser utilizado.

---

## Tópico 3: O que é um Dork?

Durante a auditoria, também será apresentado o conceito de **Dork**, principalmente no contexto de mecanismos de busca.

Um **Google Dork**, também chamado de **Search Dork**, é uma consulta de pesquisa construída utilizando operadores específicos para encontrar informações de maneira mais precisa em mecanismos de busca.

Em vez de realizar uma pesquisa comum, o usuário combina operadores para restringir os resultados.

Por exemplo:

**`site:exemplo.com`**

indica ao mecanismo de busca que os resultados devem pertencer ao domínio especificado.

Outro exemplo é:

**`filetype:pdf`**

que permite procurar arquivos PDF indexados pelo mecanismo de busca.

Também existem operadores como:

**`intitle:`** — procura determinada palavra ou expressão no título das páginas.

**`inurl:`** — procura determinada palavra ou expressão dentro da URL.

**`site:`** — limita a pesquisa a determinado site ou domínio.

**`filetype:`** — procura arquivos de determinado formato.

O conceito de Dork ficou bastante conhecido na área de segurança da informação porque esses operadores podem ser utilizados para localizar informações que foram publicadas ou indexadas na internet sem a devida atenção.

Por exemplo, uma organização pode publicar acidentalmente um documento contendo informações que não deveriam estar disponíveis publicamente. Se esse documento for indexado por um mecanismo de busca, determinadas consultas podem facilitar sua localização.

Isso não significa que o mecanismo de busca "invadiu" o sistema. A informação pode simplesmente ter sido publicada de forma acessível e posteriormente indexada.

---

## Dorks e segurança da informação

Os Dorks possuem usos legítimos e também podem ser utilizados de maneira indevida.

Na área de segurança, eles podem ser utilizados por profissionais durante **auditorias e testes de exposição**, buscando descobrir se uma organização possui informações públicas que deveriam estar protegidas.

Por exemplo, uma empresa pode utilizar consultas para verificar se existem documentos, páginas ou informações internas que foram publicados acidentalmente.

Por outro lado, uma pessoa mal-intencionada pode utilizar as mesmas técnicas para procurar informações expostas e tentar utilizá-las em ataques.

Por isso, o objetivo desta estação não é ensinar os alunos a procurar informações privadas de terceiros, mas demonstrar um princípio importante:

> **Se uma informação está disponível publicamente na internet, pode ser encontrada e utilizada por outras pessoas.**

A melhor defesa contra esse tipo de exposição é evitar que informações que deveriam ser privadas sejam publicadas ou compartilhadas de maneira incorreta.

---

## Prática 2: Investigando a exposição de arquivos

Após compreender o conceito de Dork, os alunos poderão observar exemplos controlados de como informações públicas podem ser localizadas por mecanismos de busca.

A atividade deverá utilizar **arquivos e páginas preparados especificamente para a aula**, evitando a busca por informações pessoais de terceiros.

O objetivo será demonstrar a diferença entre:

**Arquivo privado:** somente pessoas autorizadas possuem acesso.

**Arquivo compartilhado:** pessoas específicas possuem acesso de acordo com as permissões configuradas.

**Arquivo público:** qualquer pessoa que tenha acesso ao endereço ou que consiga encontrá-lo poderá visualizar o conteúdo, dependendo da configuração.

A partir disso, será discutida uma pergunta:

**"Eu realmente sei quem pode acessar aquilo que publico na internet?"**

---

# Prática 3: Auditoria das permissões de aplicativos

Outra forma de deixar uma "porta aberta" é conceder acesso a aplicativos e serviços de terceiros.

Muitos sites permitem que o usuário faça login utilizando uma conta Google. Durante esse processo, pode ser solicitada autorização para acessar determinadas informações.

Com o passar do tempo, é comum que uma pessoa acumule permissões de aplicativos que já não utiliza.

Durante a atividade, os alunos deverão acessar as configurações de segurança da própria Conta Google e analisar os aplicativos e serviços de terceiros que possuem algum tipo de acesso.

Eles deverão observar:

- Quais aplicativos possuem acesso;
- Quais informações foram autorizadas;
- Quando o acesso foi concedido, quando essa informação estiver disponível;
- Se o aplicativo ainda é utilizado;
- Se a permissão continua sendo necessária.

Caso exista algum aplicativo desconhecido ou que não seja mais utilizado, o aluno poderá revisar a autorização e, quando apropriado, removê-la.

A ideia principal é mostrar que **autorizações antigas também representam uma superfície de risco**.

---

# Prática 4: Autenticação em dois fatores

A próxima etapa apresenta a **Autenticação em Dois Fatores (2FA)**.

A autenticação tradicional normalmente depende de algo que o usuário sabe, como uma senha.

Com o 2FA, uma segunda forma de comprovação é adicionada ao processo de login.

Essa segunda etapa pode utilizar, dependendo do serviço:

- Aplicativo autenticador;
- Código temporário;
- Chave de segurança;
- Notificação de confirmação;
- Outros mecanismos de autenticação.

Uma das formas mais utilizadas é o aplicativo autenticador. Ele gera códigos temporários que mudam periodicamente e são utilizados junto com a senha.

Isso cria uma barreira adicional.

Se alguém descobrir a senha de uma conta protegida por 2FA, ainda poderá precisar da segunda forma de autenticação para conseguir concluir o acesso.

Durante a atividade, os alunos poderão ativar a autenticação em dois fatores em serviços compatíveis que utilizem, como exemplo, **WhatsApp e Instagram**, seguindo as configurações oficiais de segurança de cada plataforma.

O objetivo não é apenas ativar o recurso, mas compreender o motivo pelo qual ele é importante.

---

# Prática 5: Dinâmica de invasão controlada

Para finalizar a estação, será realizada uma **simulação controlada de tentativa de acesso**.

A atividade será realizada exclusivamente em um ambiente preparado para a aula, utilizando contas de teste ou um sistema criado especificamente para a demonstração.

Primeiramente, será apresentado um cenário em que um usuário possui apenas uma senha como mecanismo de proteção.

A partir desse cenário, será demonstrado como a descoberta ou comprometimento da senha pode permitir uma tentativa de acesso.

Em seguida, o mesmo cenário será apresentado utilizando autenticação em dois fatores.

A diferença será utilizada para demonstrar que, mesmo quando uma senha é comprometida, a existência de uma segunda etapa de autenticação pode impedir ou dificultar significativamente o acesso.

A atividade deverá reforçar uma ideia importante:

**Segurança não significa tornar um sistema impossível de atacar. Significa criar camadas suficientes para dificultar, detectar e impedir acessos indevidos.**

---

# Conectando as práticas

As atividades desta estação apresentam diferentes formas de controlar a exposição digital.

Na auditoria do **Google Drive**, o aluno verifica quem pode acessar seus arquivos.

Na utilização de **Dorks**, aprende como informações publicadas na internet podem ser localizadas por mecanismos de busca.

Na auditoria de **aplicativos de terceiros**, verifica quais serviços possuem acesso às suas contas.

Com o **2FA**, adiciona uma camada adicional de proteção à autenticação.

Na **simulação de invasão**, observa na prática a diferença entre uma conta protegida apenas por senha e uma conta protegida por múltiplas camadas.

Todas essas atividades possuem o mesmo objetivo: fazer o aluno perceber que a segurança de uma conta não depende de uma única configuração.

---

## Reflexão final da estação

Ao final da estação, os alunos deverão compreender que a proteção dos dados depende também das escolhas realizadas pelo próprio usuário.

Uma pessoa pode possuir uma senha forte e, ainda assim:

- Manter arquivos pessoais públicos;
- Compartilhar documentos com pessoas que não deveriam mais ter acesso;
- Possuir aplicativos antigos conectados à sua conta;
- Não utilizar autenticação em dois fatores;
- Publicar informações pessoais sem perceber que elas podem ser encontradas por mecanismos de busca.

A ideia de **"fechar as portas"** representa justamente esse processo de revisar e reduzir os pontos de exposição.

A soberania digital começa quando o usuário deixa de simplesmente utilizar os serviços digitais e passa a compreender **quais informações está entregando, quem pode acessá-las e quais mecanismos possui para controlar esse acesso**.

A pergunta final da estação será:

> **"Quantas portas da sua vida digital estão abertas neste momento, e você sabe quem possui a chave?"**