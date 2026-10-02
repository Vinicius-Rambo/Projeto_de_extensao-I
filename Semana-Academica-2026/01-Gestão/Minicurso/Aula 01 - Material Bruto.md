# Estação 01: O Diagnóstico

## **Tópico 01: O que é a LGPD?**

A **Lei Geral de Proteção de Dados Pessoais (LGPD)**, instituída pela **Lei nº 13.709/2018**, é a legislação brasileira que estabelece regras para o tratamento de dados pessoais realizado por empresas, órgãos públicos e outras organizações. Ela determina como esses dados podem ser coletados, utilizados, armazenados, compartilhados e protegidos.

A criação da LGPD está relacionada ao crescimento do uso de informações pessoais no ambiente digital. Atualmente, empresas e serviços coletam uma grande quantidade de informações sobre seus usuários, muitas vezes para oferecer serviços, realizar compras, personalizar anúncios, criar cadastros ou analisar comportamentos.

A lei busca estabelecer limites para esse tratamento e garantir maior controle ao cidadão sobre suas próprias informações.

**Dado pessoal:** É qualquer informação relacionada a uma pessoa identificada ou identificável. Não se limita apenas a informações como nome ou CPF. Um dado também pode ser considerado pessoal quando, combinado com outras informações, permite identificar alguém.

Exemplos:

- Nome completo;  
- CPF e RG;  
- Número de telefone;  
- Endereço;  
- E-mail;  
- Data de nascimento;  
- Endereço IP, em determinadas situações;  
- Dados de localização;  
- Informações relacionadas a uma conta ou cadastro.

**Dado pessoal sensível:** São dados pessoais que possuem uma proteção diferenciada devido ao potencial de causar discriminação ou outros prejuízos ao indivíduo caso sejam utilizados de maneira inadequada.

Exemplos:

- Origem racial ou étnica;  
- Religião;  
- Opinião política;  
- Filiação a sindicato ou organização de caráter religioso, filosófico ou político;  
- Dados referentes à saúde;  
- Dados referentes à vida sexual;  
- Dados genéticos;  
- Dados biométricos, quando vinculados a uma pessoa.

---

### **Qual é o objetivo da LGPD?**

A LGPD possui como objetivo principal proteger os direitos fundamentais de liberdade, privacidade e o livre desenvolvimento da personalidade.

Entre seus principais objetivos estão:

**Privacidade:** Garantir que as informações pessoais dos cidadãos sejam tratadas de maneira adequada, evitando que sejam utilizadas de forma abusiva ou sem justificativa.

**Transparência:** Garantir que o titular dos dados tenha informações claras sobre como seus dados são tratados, incluindo informações sobre coleta, utilização e compartilhamento.

**Segurança:** Determinar que empresas e organizações adotem medidas técnicas e administrativas para proteger os dados contra acessos não autorizados, perdas, alterações, vazamentos e outras situações que possam comprometer sua segurança.

**Controle sobre os próprios dados:** A LGPD estabelece uma série de direitos para os titulares, permitindo que eles tenham maior participação e controle sobre o tratamento de suas informações pessoais.

---

### **Princípios importantes da LGPD**

Além de estabelecer direitos e obrigações, a LGPD apresenta princípios que devem orientar o tratamento de dados pessoais.

**Finalidade:** Os dados devem ser tratados para propósitos legítimos, específicos e informados ao titular.

**Adequação:** O tratamento deve ser compatível com as finalidades informadas ao titular.

**Necessidade:** Devem ser utilizados apenas os dados necessários para atingir a finalidade pretendida, evitando a coleta excessiva de informações.

**Transparência:** O titular deve receber informações claras e acessíveis sobre o tratamento de seus dados.

**Segurança:** Devem ser utilizadas medidas para proteger os dados contra acessos não autorizados e situações acidentais ou ilícitas.

Esses princípios são importantes porque mostram que proteger dados não significa apenas impedir hackers de acessarem sistemas. A própria organização deve analisar quais informações realmente precisa coletar, por que precisa delas e como irá protegê-las.

---

### **Artigos da LGPD em destaque para a aula:**

**Informação sobre compartilhamento (Art. 18, VII):** O titular possui o direito de saber com quais entidades públicas e privadas seus dados pessoais foram compartilhados, observadas as condições previstas na legislação. Esse direito é importante porque uma pessoa pode fornecer seus dados para uma empresa e não ter conhecimento de que essas informações também podem ser utilizadas ou compartilhadas com outras organizações.  *Destacar*

**Reparação de danos (Art. 42):** Estabelece regras de responsabilidade relacionadas aos danos causados em razão do tratamento de dados pessoais. Quando uma violação da legislação causar dano patrimonial ou moral, individual ou coletivo, podem existir responsabilidades e obrigação de reparação conforme as circunstâncias previstas na lei.

**Dever de segurança (Art. 46):** Os agentes de tratamento devem adotar medidas de segurança, técnicas e administrativas capazes de proteger os dados pessoais contra acessos não autorizados e situações acidentais ou ilícitas, como destruição, perda, alteração, comunicação ou difusão indevida.

**Comunicação de incidentes (Art. 48):** Quando ocorrer um incidente de segurança que possa acarretar risco ou dano relevante aos titulares, o controlador deve comunicar a ocorrência à Autoridade Nacional de Proteção de Dados (ANPD) e aos titulares afetados, nos termos da legislação. *Destacar*

---

## **Tópico 02: O que é o Have I Been Pwned?**

**Pergunta para a turma:** Será que as empresas estão realmente nos alertando sobre vazamentos de dados? E será que nós sabemos quando nossos próprios dados são expostos?

Para responder a essas perguntas, será utilizada uma ferramenta real de segurança da informação: o **Have I Been Pwned?**

**Have I Been Pwned?** (abreviado como HIBP) é um serviço criado para permitir que pessoas verifiquem se seus endereços de e-mail apareceram em vazamentos de dados conhecidos.

A plataforma foi criada em **2013 por Troy Hunt**, especialista em segurança da informação, após uma série de grandes incidentes envolvendo vazamentos de dados. O objetivo do projeto é facilitar o acesso a uma informação importante: saber se uma conta ou endereço de e-mail foi encontrado em alguma base de dados exposta.

O site reúne informações provenientes de diversos vazamentos conhecidos. Quando um usuário realiza uma pesquisa, a plataforma pode apresentar quais vazamentos estão associados ao endereço consultado e quais categorias de informações foram comprometidas.

O serviço não foi criado para permitir que uma pessoa descubra a senha de outra. Pelo contrário, o projeto procura disponibilizar informações suficientes para que o próprio usuário possa avaliar sua exposição e tomar medidas de segurança.

---

### **Como funciona o Have I Been Pwned?**

A utilização básica da ferramenta é simples. O usuário informa um endereço de e-mail e o serviço verifica se ele aparece em registros relacionados a vazamentos conhecidos.

Caso o endereço seja encontrado, o site pode apresentar informações como:

- Nome do vazamento;  
- Empresa ou serviço afetado;  
- Data aproximada do incidente;  
- Quantidade de contas envolvidas;  
- Categorias de dados que podem ter sido expostas.

Entre as categorias que podem aparecer estão informações como endereços de e-mail, nomes, nomes de usuário, números de telefone, endereços e outras informações, dependendo do vazamento.

É importante entender que o fato de um e-mail aparecer no Have I Been Pwned não significa necessariamente que a senha atual daquela conta esteja disponível ou que a conta esteja sendo invadida naquele momento. Significa que aquele endereço foi identificado em uma base relacionada a um vazamento conhecido.

---

### **O que significa “Have I Been Pwned”?**

A expressão **“Have I Been Pwned?”** pode ser traduzida aproximadamente como **“Eu fui comprometido?”**.

O termo *pwned* surgiu como uma variação da palavra inglesa *owned*, utilizada na cultura da internet e dos jogos para indicar que alguém foi derrotado ou dominado. No contexto da segurança da informação, a expressão passou a ser utilizada para representar situações em que uma conta, sistema ou conjunto de dados foi comprometido.

O nome do site transforma uma questão técnica em uma pergunta simples que qualquer usuário consegue entender:

**“Meus dados já foram expostos em algum vazamento?”**

---

### **Por que essa ferramenta é importante?**

Uma das principais dificuldades relacionadas à segurança de dados é que o usuário muitas vezes não sabe que suas informações foram expostas.

Uma empresa pode sofrer um ataque, ter uma base de dados roubada e o usuário continuar utilizando a mesma senha e o mesmo endereço de e-mail em outros serviços sem saber que existe um risco.

Por isso, ferramentas como o Have I Been Pwned ajudam a aumentar a conscientização sobre segurança digital. A consulta pode servir como um alerta para que o usuário altere senhas, ative autenticação em dois fatores e verifique outras contas que utilizem as mesmas credenciais.

A ferramenta também ajuda a demonstrar um problema importante: **um vazamento de dados não termina necessariamente quando a empresa corrige a vulnerabilidade.** As informações que foram copiadas podem continuar circulando ou sendo utilizadas posteriormente.

---

#### **Atividade: Verificando a exposição dos seus dados**

Cada aluno deverá acessar o site do **Have I Been Pwned?** e realizar uma consulta utilizando seu próprio endereço de e-mail.

Após realizar a pesquisa, deverá observar:

1. Se o endereço de e-mail aparece em algum vazamento;  
2. Quantos vazamentos foram identificados;  
3. Quais empresas ou serviços estão relacionados;  
4. Em que período os vazamentos ocorreram;  
5. Quais categorias de dados podem ter sido expostas;  
6. Se os vazamentos envolvem informações que poderiam representar algum risco.

Os alunos não precisam apresentar seus resultados pessoais para a turma. O objetivo é utilizar a experiência individual para compreender o problema de forma prática.

**Importante:** durante a atividade, os alunos não devem informar suas senhas no site ou compartilhar senhas com colegas, professores ou qualquer outra pessoa.

---

### **Relacionando o HIBP com a LGPD**

Após a atividade, os resultados serão utilizados para discutir a relação entre vazamentos de dados e a LGPD.

A turma deverá refletir sobre algumas questões:

- Se uma empresa coleta nossos dados, qual é a responsabilidade dela sobre essas informações?  
- O que acontece quando esses dados são expostos em um vazamento?  
- O usuário é informado quando ocorre um incidente?  
- Quais dados estavam armazenados pela empresa?  
- Esses dados eram realmente necessários?  
- Com quem essas informações poderiam ter sido compartilhadas?  
- Quais consequências um vazamento pode trazer para uma pessoa?  
- O que o usuário pode fazer depois de descobrir que seus dados foram expostos?

A atividade permite relacionar diretamente a experiência dos alunos com os artigos apresentados anteriormente. O **Art. 18** pode ser relacionado ao direito de obter informações sobre o tratamento e compartilhamento dos dados; o **Art. 46**, à responsabilidade de adotar medidas de segurança; o **Art. 48**, à comunicação de determinados incidentes; e o **Art. 42**, às regras de responsabilidade e reparação de danos.

Dessa forma, a atividade deixa de apresentar a LGPD apenas como uma legislação teórica e demonstra como seus princípios e obrigações estão relacionados a situações que podem afetar qualquer pessoa que utilize serviços digitais.

#### **Reflexão final da estação**

Ao final da atividade, espera-se que os alunos compreendam que seus dados pessoais possuem valor e podem ser utilizados por diferentes serviços e organizações.

Um simples endereço de e-mail pode estar associado a redes sociais, lojas virtuais, serviços de streaming, aplicativos, bancos, plataformas de estudo e diversos outros sistemas.

Quando essas informações são expostas, elas podem ser utilizadas em tentativas de golpes, phishing, criação de contas falsas, engenharia social e outros tipos de fraude.

Por isso, conhecer a LGPD não significa apenas conhecer uma lei. Significa entender **quais são os direitos relacionados aos nossos dados, quais responsabilidades as organizações possuem e quais atitudes podemos tomar para reduzir os riscos no ambiente digital.**

O **Have I Been Pwned?** será utilizado nesta estação justamente para transformar esse conceito em uma experiência prática: primeiro o aluno aprende que seus dados devem ser protegidos; depois verifica se alguma de suas informações já apareceu em um vazamento conhecido.

---

# Estação 02: Fechando as Portas

## **Tópico 01: O que é soberania digital?**

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

## **Tópico 2: Segurança não é apenas uma senha forte**

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

#### **Prática 1: Auditoria do Google Drive**

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

## **Tópico 3: O que é um Dork?**

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

### **Dorks e segurança da informação**

Os Dorks possuem usos legítimos e também podem ser utilizados de maneira indevida.

Na área de segurança, eles podem ser utilizados por profissionais durante **auditorias e testes de exposição**, buscando descobrir se uma organização possui informações públicas que deveriam estar protegidas.

Por exemplo, uma empresa pode utilizar consultas para verificar se existem documentos, páginas ou informações internas que foram publicados acidentalmente.

Por outro lado, uma pessoa mal-intencionada pode utilizar as mesmas técnicas para procurar informações expostas e tentar utilizá-las em ataques.

Por isso, o objetivo desta estação não é ensinar os alunos a procurar informações privadas de terceiros, mas demonstrar um princípio importante:

> **Se uma informação está disponível publicamente na internet, pode ser encontrada e utilizada por outras pessoas.**

A melhor defesa contra esse tipo de exposição é evitar que informações que deveriam ser privadas sejam publicadas ou compartilhadas de maneira incorreta.

---

#### **Prática 2: Investigando a exposição de arquivos**

Após compreender o conceito de Dork, os alunos poderão observar exemplos controlados de como informações públicas podem ser localizadas por mecanismos de busca.

A atividade deverá utilizar **arquivos e páginas preparados especificamente para a aula**, evitando a busca por informações pessoais de terceiros.

O objetivo será demonstrar a diferença entre:

**Arquivo privado:** somente pessoas autorizadas possuem acesso.

**Arquivo compartilhado:** pessoas específicas possuem acesso de acordo com as permissões configuradas.

**Arquivo público:** qualquer pessoa que tenha acesso ao endereço ou que consiga encontrá-lo poderá visualizar o conteúdo, dependendo da configuração.

A partir disso, será discutida uma pergunta:

**"Eu realmente sei quem pode acessar aquilo que publico na internet?"**

---

#### **Prática 3: Auditoria das permissões de aplicativos**

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

#### **Prática 4: Autenticação em dois fatores**

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

#### **Prática 5: Dinâmica de invasão controlada**

Para finalizar a estação, será realizada uma **simulação controlada de tentativa de acesso**.

A atividade será realizada exclusivamente em um ambiente preparado para a aula, utilizando contas de teste ou um sistema criado especificamente para a demonstração.

Primeiramente, será apresentado um cenário em que um usuário possui apenas uma senha como mecanismo de proteção.

A partir desse cenário, será demonstrado como a descoberta ou comprometimento da senha pode permitir uma tentativa de acesso.

Em seguida, o mesmo cenário será apresentado utilizando autenticação em dois fatores.

A diferença será utilizada para demonstrar que, mesmo quando uma senha é comprometida, a existência de uma segunda etapa de autenticação pode impedir ou dificultar significativamente o acesso.

A atividade deverá reforçar uma ideia importante:

**Segurança não significa tornar um sistema impossível de atacar. Significa criar camadas suficientes para dificultar, detectar e impedir acessos indevidos.**

---

### **Conectando as práticas**

As atividades desta estação apresentam diferentes formas de controlar a exposição digital.

Na auditoria do **Google Drive**, o aluno verifica quem pode acessar seus arquivos.

Na utilização de **Dorks**, aprende como informações publicadas na internet podem ser localizadas por mecanismos de busca.

Na auditoria de **aplicativos de terceiros**, verifica quais serviços possuem acesso às suas contas.

Com o **2FA**, adiciona uma camada adicional de proteção à autenticação.

Na **simulação de invasão**, observa-se na prática a diferença entre uma conta protegida apenas por senha e uma conta protegida por múltiplas camadas.

Todas essas atividades possuem o mesmo objetivo: fazer o aluno perceber que a segurança de uma conta não depende de uma única configuração.

---

#### **Reflexão final da estação**

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

---

# FONTES

## Estação 01

- [Lei Geral de Proteção de Dados — Planalto](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)

- [Direitos dos Titulares –- ANPD](https://www.gov.br/anpd/pt-br/assuntos/titular-de-dados-1/direito-dos-titulares)  
    
- [Titular de Dados — ANPD](https://www.gov.br/anpd/pt-br/assuntos/titular-de-dados-1)  
    
- [Perguntas Frequentes —- ANPD](https://www.gov.br/anpd/pt-br/acesso-a-informacao/perguntas-frequentes/perguntas-frequentes)  
    
- [Comunicação de Incidente de Segurança — ANPD](https://www.gov.br/anpd/pt-br/canais_atendimento/agente-de-tratamento/comunicado-de-incidente-de-seguranca-cis)

## Estação 02

- [Cartilha de Segurança para Internet — CGI.br](https://www.cgi.br/publicacao/cartilha-de-seguranca-para-internet)  
    
- [Fascículos de Segurança — CERT.br](https://cartilha.cert.br/fasciculos)  
    
- [Autenticação e proteção de contas — CERT.br](https://www.cgi.br/noticia/releases/cert-br-explica-como-usar-a-autenticacao-e-proteger-o-acesso-as-suas-contas)  
    
- [Novos fascículos sobre golpes e fraudes —](https://www.cgi.br/noticia/releases/cert-br-lanca-novos-fasciculos-da-cartilha-de-seguranca-para-internet-com-foco-na-prevencao-de-golpes-e-fraudes-online) [CERT.br](http://CERT.br)  
    
- [Seus arquivos do google drive — Diolinux](https://diolinux.com.br/tutoriais/arquivos-google-drive-expostos.html)

