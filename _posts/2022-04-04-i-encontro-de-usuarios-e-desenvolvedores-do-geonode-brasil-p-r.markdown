---
layout: post
title:  "I Encontro de Usuários e Desenvolvedores do GeoNode Brasil: Perguntas e Respostas"
date:   2022-04-04 16:03:10 -0300
excerpt: Neste post estão disponíveis todas as perguntas e respectivas respostas disponibilizadas pelos palestrantes durante o evento. 
categories: eventos
---

## Dia 17/03/2022
**Pergunta para Rafael Lopes Silva IBGE** “Dentro da estrutura apresentada, se a instituição aderir ao catálogo de metadados e de geoserviços da INDE, automaticamente os dados estariam disponíveis no portal de dados abertos?" - Alexandre Amorim / ANA

**Resposta:** As entidades ao aderir a INDE, devem catalogar seus conjuntos de dados geoespaciais de acordo com as normas e padrões pré-definidos. A questão da integração com o Portal Brasileiro de Dados Abertos está relacionada com o Visualizador da INDE. Logo, se a instituição possuir apenas metadados publicados, esses dados não estarão disponíveis no portal brasileiro de dados abertos. Com certeza, em determinado momento, isso será possível. A definição de utilizar a estratégia de integrar inicialmente ao visualizador da INDE está relacionada com a garantia dos padrões WMS/WFS estarem coerentes com os padrões de dados abertos. Mas respondendo sua pergunta, a integração direta dos catálogos de metadados e de geoserviços com o Portal brasileiro de dados abertos ainda não estão implementadas, apenas com o visualizador da INDE.

---

**Pergunta para Rafael Lopes Silva IBGE.**  “Existe alguma perspectiva de unificação da INDE com a INDA” Carlos Motta / CPRM

**Resposta:** Não vejo problema na existência das duas infraestruturas nacionais, pois a INDA é bem mais ampla que a INDE. A INDE deverá sempre fazer parte da INDA. O mais importante é que a integração entre INDE e INDA seja efetivamente implementada e reflita de forma completa e consistente os dados publicados. E quando falo isso, faço referência aos dados classificados na INDE como dados abertos. Mas a sua pergunta pode também refletir estratégias importantes, pois unificar as infraestruturas pode trazer benefícios para a INDE, que mesmo que esteja com 14 anos de sua instituição oficial em 2008, ainda tem seu potencial e benefícios desconhecidos no país. Mas concordo que unificar pode ser uma possibilidade, apesar de acreditar que a integração, de forma funcional, já seria um excelente objetivo alcançado.

---

**Pergunta para Rogério Borba IBGE.** “Olá Rogério! Existe uma base de código pública destas soluções?” Fagner Bitencourtt de Oliveira.

**Resposta:** (Pendente)

---

**Pergunta para Rogério Borba IBGE.** “o DBDG tem alguma previsão de homologação de OGC API para uso na INDE?” Carlos Motta / CPRM

**Resposta:** É um trabalho que precisa ser realizado a nível de CONCAR que é a entidade coordenadora e homologadora da INDE no Brasil. Precisaremos da CONCAR para homologar esses novos padrões.  A CONCAR encontra-se, no momento, em um processo de reativação. Ela deverá definir os prazos para homologação das OGC API.

---

**Pergunta para Rogério Borba IBGE.** “Propor via DBDG um grupo interinstitucional para aplicar o perfil MGB 1 e 2 no geonode, para permitir compatibilidade com o que está atualmente na INDE” Carlos Motta / CPRM

**Resposta:** Será proposto

---

**Pergunta para Rogério Borba IBGE** “....para alimentar as plataformas com dados, vocês irão disponibilizar os acessos ou iremos encaminhar para vocês.” Rodrigo Mora / UniLasalle

**Resposta:** As instituições que fazem parte do DBDG da INDE, que são Nó, publicam seus dados e metadados, conforme normas e padrões  e compartilham seus catálogos de endereços com o gestor do DBDG para que sejam disseminados e acessíveis no site e nas plataformas da INDE.

---

**Pergunta para Rogério Borba IBGE.** ”Existe base de código internacional que já é pesquisada e utilizada por instituições no Brasil”. Álvaro Gomes Sobral Barcellos / CPRM

**Resposta:** Não sei se entendi a pergunta, mas existe o perfil de Metadados Geoespaciais do Brasil (Perfil MGB) que é um subconjunto da ISO 19115 que é uma norma internacional. Se a pergunta for em relação à software livre, por exemplo, no IBGE o código fonte de postgres/postgis é baixado e compilado para gerar uma versão do SGBD.

---

**Pergunta para Rogério Borba IBGE.** “E como fica a situação do dado público sendo posto em nuvem sem uma estruturação e preocupação quanto a ontologia e semântica e sem metadados e sem governança é uma bola de neve…” Priscila da Costa Taveira

**Resposta:** Realmente o assunto é muito importante e deveria ser tratado nos comitês da CONCAR. É preciso definir mecanismos como, vocabulários, thesaurus, categorização, rótulos, ontologias,  modelos conceituais entre outros, primeiro para que as informações possam ser publicadas com algumas características e significados comuns, segundo para que possam ser encontradas e relacionadas considerando algum nível de interoperabilidade semântica e esquemática. 

---

**Pergunta para Hesley Py ANP.** “​A comunidade GeonodeBR pode ser uma mola propulsora pra que mais instituições públicas possam integrar suas bases cartográficas à INDE?” Daniel Chaves Webber / Embrapa

**Resposta:** Certamente. Quanto mais pessoas/comunidades tivermos trabalhando em softwares que utilizam/promovem os padrões adotados na INDE maior será a possibilidade de, em qualquer momento, os dados estarem disponíveis na infraestrutura. Além disso, o Geonode promove um processo muito mais integrado e facilitado para a publicação dos dados, metadados e serviços. O que falta ou faltava para sua ampla utilização no apoio às instituições interessadas em participar da INDE ou criarem as suas próprias IDEs era ou é, justamente, uma comunidade brasileira.

---

**Pergunta para Silvana UFPR.** “como voluntários podem ajudar no FRONT-END?” Rodrigo Mora

**Resposta:** Pendente

---

**Pergunta para Silvana UFPR:** “a implementação do geonode é feito do jeito clássico, ou como Geonode Project?” Carlos Mota / CPRM

**Resposta:** Pendente

---

**Pergunta para Davi Embrapa.** “Gostaria de saber, por gentileza, quais tecnologias são utilizadas na composição dessas aplicações SIG Web da Embrapa. Obrigado!” PAULO JHONNY SCHELEDER DA COSTA ROSA

**Resposta:** Basicamente estamos usando ReactJS + Leaflet no FrontEnd, e NodeJS + NestJS para as APIs no BackEnd. Também estamos utilizando um framework chamado EasyMaps (desenvolvido internamente pela Embrapa) que fornece os principais componentes de UX ligando ReactJS + MaterialUI + Leaflet.

---

**Pergunta para a Silvana (UFPR):** "Tem experiência com o uso do Thesaurus para a padronização de vocabulários e semântica dentro do geonode?" Amorim/ANA

**Resposta:** Pendente

---

**Pergunta a todos:** “Vocês acreditam que a documentação do geonode que contempla a parte de instalação tem informações suficientemente precisas?” Fagner Bitencourtt de Oliveira​

**Resposta:** Rafael Lopes - Pelo que percebi a partir dos comentários dos palestrantes que já se envolveram nessa atividade de instalação do geonode, a documentação possui falhas e imprecisões. Como é uma aplicação que já está sendo utilizada por algumas organizações, acredito que esta nova comunidade geonode poderia já incluir uma tarefa para o grupo: “A elaboração de uma documentação fundamental para a instalação do geonode nas organizações”. Esse documento pode facilitar a disseminação e o uso do geonode em nível nacional.

---

**Pergunta** “e dentro da própria instituição. Pergunto como tem sido a experiência de vocês para fazer esse convencimento das chefias/coordenações/diretorias e conseguir implementar uma IDE em suas instituições?” karl

**Resposta:** Rafael Lopes - Esse é um assunto delicado, muito trabalhoso e repetitivo. As mudanças organizacionais, a rotatividade das pessoas em cargos gerenciais e a falta de entendimento nos benefícios de uma IDE, torna a conscientização e convencimento  na implementação de uma IDE uma atividade contínua e trabalhosa. Mas não tem outra forma, é uma atividade que deve estar sempre presente no planejamento estratégico. Desde o início do meu envolvimento com as atividades da INDE em 2010 até os dias de hoje, a atividade de conscientização da INDE existe e esteve presente em todo esse período. Enquanto a INDE não se tornar necessária de fato nas organizações, continuará a ser tratada como uma etapa a mais no dia a dia de cada uma delas.	É preciso um processo contínuo de evangelização, mostrando os grandes benefícios internos e externos.

---

**Comentário de Hesley:** Penso que o técnico tem interesse na publicação dos dados e metadados. Ele entende os benefícios e tem interesse na utilização do que foi, por ele, produzido. Contudo, um trabalho de evangelização, como já mencionado, precisa ser feito com os gestores.

---

**Comentário.** “Essa diferenciação de dados entre geoespaciais e dados abertos (cartoriais), gera uma disputa por responsáveis nestas infraestruturas e com isso os caminhos não convergem e de certa forma conflitam.” IDAS pelo Brasil

**Resposta Hesley:** Isso. Por isso, uso e gosto do termo geoespacializável que, em uma tradução livre, seriam todos os dados que conseguimos apresentar identificado em um ponto ou área do território. Tal definição amplia consideravelmente o escopo da INDE. Todo o dado disponível na INDE deve ser aberto e deve poder ser posicionado no território.

---

**Pergunta para o Rogério Borba:** “Acaso a INDE vislumbra a possibilidade de substituir GeoNetwork e GeoServer pelo GeoNode ou não? Seriam soluções excludentes ou complementares no futuro?” Philipe Rodrigo

**Resposta:** Importante citar primeiro que o Geonode é composto por ferramentas para metadados e dados geoespaciais, além de gestão de conteúdo e com algumas funcionalidades de redes sociais. o Geoserver é a ferramenta do geonode para publicação de dados geoespaciais. Para metadados, podemos usar o PyCSW ou mesmo o Geonetwork. Então o Geonode por estar em conformidade com ferramentas e padrões para INDE poderia sim ser utilizado em um futuro no DBDG da INDE.

---

**Comentário** “Acho que construir interfaces mais amigáveis para inserir metadados pode favorecer a inserção dos metadados” raphael campos

**Resposta Hesley:** De acordo. A comunidade do Geonode Br pode auxiliar nesse processo de construção. Além disso, temos tb a possibilidade de criação de plugins que permitam a publicação dos metadados a partir de outros softwares como, por exemplo, já foi feito para o QGis.
