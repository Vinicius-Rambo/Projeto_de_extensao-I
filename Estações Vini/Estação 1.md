## Estação 1: O Diagnóstico

**Tópico 1: O que é a LGPD?**

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

**Qual é o objetivo da LGPD?**

A LGPD possui como objetivo principal proteger os direitos fundamentais de liberdade, privacidade e o livre desenvolvimento da personalidade.

Entre seus principais objetivos estão:

**Privacidade:** Garantir que as informações pessoais dos cidadãos sejam tratadas de maneira adequada, evitando que sejam utilizadas de forma abusiva ou sem justificativa.

**Transparência:** Garantir que o titular dos dados tenha informações claras sobre como seus dados são tratados, incluindo informações sobre coleta, utilização e compartilhamento.

**Segurança:** Determinar que empresas e organizações adotem medidas técnicas e administrativas para proteger os dados contra acessos não autorizados, perdas, alterações, vazamentos e outras situações que possam comprometer sua segurança.

**Controle sobre os próprios dados:** A LGPD estabelece uma série de direitos para os titulares, permitindo que eles tenham maior participação e controle sobre o tratamento de suas informações pessoais.

---

**Princípios importantes da LGPD**

Além de estabelecer direitos e obrigações, a LGPD apresenta princípios que devem orientar o tratamento de dados pessoais.

**Finalidade:** Os dados devem ser tratados para propósitos legítimos, específicos e informados ao titular.

**Adequação:** O tratamento deve ser compatível com as finalidades informadas ao titular.

**Necessidade:** Devem ser utilizados apenas os dados necessários para atingir a finalidade pretendida, evitando a coleta excessiva de informações.

**Transparência:** O titular deve receber informações claras e acessíveis sobre o tratamento de seus dados.

**Segurança:** Devem ser utilizadas medidas para proteger os dados contra acessos não autorizados e situações acidentais ou ilícitas.

Esses princípios são importantes porque mostram que proteger dados não significa apenas impedir hackers de acessarem sistemas. A própria organização deve analisar quais informações realmente precisa coletar, por que precisa delas e como irá protegê-las.

---

**Artigos da LGPD em destaque para a aula:**

**Informação sobre compartilhamento (Art. 18, VII):** O titular possui o direito de saber com quais entidades públicas e privadas seus dados pessoais foram compartilhados, observadas as condições previstas na legislação. Esse direito é importante porque uma pessoa pode fornecer seus dados para uma empresa e não ter conhecimento de que essas informações também podem ser utilizadas ou compartilhadas com outras organizações.  *Destacar*

**Reparação de danos (Art. 42):** Estabelece regras de responsabilidade relacionadas aos danos causados em razão do tratamento de dados pessoais. Quando uma violação da legislação causar dano patrimonial ou moral, individual ou coletivo, podem existir responsabilidades e obrigação de reparação conforme as circunstâncias previstas na lei.

**Dever de segurança (Art. 46):** Os agentes de tratamento devem adotar medidas de segurança, técnicas e administrativas capazes de proteger os dados pessoais contra acessos não autorizados e situações acidentais ou ilícitas, como destruição, perda, alteração, comunicação ou difusão indevida.

**Comunicação de incidentes (Art. 48):** Quando ocorrer um incidente de segurança que possa acarretar risco ou dano relevante aos titulares, o controlador deve comunicar a ocorrência à Autoridade Nacional de Proteção de Dados (ANPD) e aos titulares afetados, nos termos da legislação. *Destacar*


---
## Prática Rápida: A Realidade dos Vazamentos

**Pergunta para a turma:** Será que as empresas estão realmente nos alertando sobre vazamentos de dados? E será que nós sabemos quando nossos próprios dados são expostos?

Para responder a essas perguntas, será utilizada uma ferramenta real de segurança da informação: o **Have I Been Pwned?**

### O que é o Have I Been Pwned?

**Have I Been Pwned?** (abreviado como HIBP) é um serviço criado para permitir que pessoas verifiquem se seus endereços de e-mail apareceram em vazamentos de dados conhecidos.

A plataforma foi criada em **2013 por Troy Hunt**, especialista em segurança da informação, após uma série de grandes incidentes envolvendo vazamentos de dados. O objetivo do projeto é facilitar o acesso a uma informação importante: saber se uma conta ou endereço de e-mail foi encontrado em alguma base de dados exposta.

O site reúne informações provenientes de diversos vazamentos conhecidos. Quando um usuário realiza uma pesquisa, a plataforma pode apresentar quais vazamentos estão associados ao endereço consultado e quais categorias de informações foram comprometidas.

O serviço não foi criado para permitir que uma pessoa descubra a senha de outra. Pelo contrário, o projeto procura disponibilizar informações suficientes para que o próprio usuário possa avaliar sua exposição e tomar medidas de segurança.

---

**Como funciona o Have I Been Pwned?**

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

**O que significa “Have I Been Pwned”?**

A expressão **“Have I Been Pwned?”** pode ser traduzida aproximadamente como **“Eu fui comprometido?”**.

O termo _pwned_ surgiu como uma variação da palavra inglesa _owned_, utilizada na cultura da internet e dos jogos para indicar que alguém foi derrotado ou dominado. No contexto da segurança da informação, a expressão passou a ser utilizada para representar situações em que uma conta, sistema ou conjunto de dados foi comprometido.

O nome do site transforma uma questão técnica em uma pergunta simples que qualquer usuário consegue entender:

**“Meus dados já foram expostos em algum vazamento?”**

---

**Por que essa ferramenta é importante?**

Uma das principais dificuldades relacionadas à segurança de dados é que o usuário muitas vezes não sabe que suas informações foram expostas.

Uma empresa pode sofrer um ataque, ter uma base de dados roubada e o usuário continuar utilizando a mesma senha e o mesmo endereço de e-mail em outros serviços sem saber que existe um risco.

Por isso, ferramentas como o Have I Been Pwned ajudam a aumentar a conscientização sobre segurança digital. A consulta pode servir como um alerta para que o usuário altere senhas, ative autenticação em dois fatores e verifique outras contas que utilizem as mesmas credenciais.

A ferramenta também ajuda a demonstrar um problema importante: **um vazamento de dados não termina necessariamente quando a empresa corrige a vulnerabilidade.** As informações que foram copiadas podem continuar circulando ou sendo utilizadas posteriormente.

---

## Atividade: Verificando a exposição dos seus dados

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

## Relacionando o HIBP com a LGPD

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

### Reflexão final da estação

Ao final da atividade, espera-se que os alunos compreendam que seus dados pessoais possuem valor e podem ser utilizados por diferentes serviços e organizações.

Um simples endereço de e-mail pode estar associado a redes sociais, lojas virtuais, serviços de streaming, aplicativos, bancos, plataformas de estudo e diversos outros sistemas.

Quando essas informações são expostas, elas podem ser utilizadas em tentativas de golpes, phishing, criação de contas falsas, engenharia social e outros tipos de fraude.

Por isso, conhecer a LGPD não significa apenas conhecer uma lei. Significa entender **quais são os direitos relacionados aos nossos dados, quais responsabilidades as organizações possuem e quais atitudes podemos tomar para reduzir os riscos no ambiente digital.**

O **Have I Been Pwned?** será utilizado nesta estação justamente para transformar esse conceito em uma experiência prática: primeiro o aluno aprende que seus dados devem ser protegidos; depois verifica se alguma de suas informações já apareceu em um vazamento conhecido.