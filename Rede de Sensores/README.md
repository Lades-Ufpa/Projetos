# Aplicações de Monitoramento Ambientais e Aquáticas através de Redes de Sensores sem Fio – Um estudo de caso na região do Salgado.

Projeto do Programa Institucional de Bolsas de Iniciação Científica (PIBIC) financiado pelo Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq) tem como proposta uma Avaliação de Desempenho em Cenários de Elevada e Baixa Taxa de Transferência para Redes de Sensores Sem Fio o trabalho também tem um objetivo fazer um estudo de caso no nordeste Paraense.

### Integrantes 

Hygor Jardim da Silva (Bolsita)

Dr. Tássio Costa de Carvalho (Orientador)

### Realização 


[Universidade Federal do Pará campus Universitário de Castanhal](http://www.campuscastanhal.ufpa.br/)

[Faculdade de Computação](http://facompcastanhal.ufpa.br/)

[Laboratório de Desenvolvimento de Sistemas](http://facompcastanhal.ufpa.br/lades/)

## Introdução:

Avanços recentes na fabricação de circuitos integrados tornam possível a integração de tecnologia de micro-sensores, computação de baixa potência e comunicação sem fio em um sistema compacto. As redes formadas por esses dispositivos, denominadas Rede de Sensores Sem Fio (RSSFs), criam oportunidades para diversas aplicações, tais como: monitoramento ambiental, monitoramento de tráfego e rodovias, agricultura de precisão, monitoramento de processos industriais, segurança pública e de ambientes em geral, transporte e controle militar [Kazem Sohraby e Daniel M, 2007].

Uma rede de sensores é uma infraestrutura composta de detecção (de medição), computação e elementos de comunicação que oferece ao administrador a capacidade de instrumentar, observar e reagir a eventos e fenômenos em um ambiente especificado. RSSFs geralmente incluem nós sensores, capazes de coletar dados e transmiti-los a outros nós da rede. Um grande número de nós sensores podem ser implantados aleatoriamente dentro ou perto da área de monitoramento, essas redes podem ser formuladas através de auto-organização dos nós [BRÖRING, 2011]. 

As atividades de sensoriamento estão relacionadas com a percepção do ambiente e a coleta de dados. De acordo com o tipo das aplicações e os tipos de sensores envolvidos, esta fase inclui a determinação de distância do alvo, ruídos do ambiente, tipo do dado coletado, volume de informação envolvida e frequência de amostragem. As RSSFs podem ter demandas de dados diferentes dependendo das dimensões, funcionalidades e quantidade dos nodos sensores. Por exemplo, as aplicações de monitoração de tráfego podem utilizar sensores de imagem e acústicos, embutidos no mesmo nodo sensor, e dependendo da quantidade de vezes que as informações são coletadas isso resultaria em uma rede com altas taxas de transferências. Por outro lado, em uma aplicação ambiental onde os sensores coletem dados a respeito da temperatura, pressão atmosférica, quantidade de luz e umidade relativa, com uma taxa de amostragem baixa (quantidade de vezes que a coleta é realizada), resultaria em uma rede com baixa taxas de transferências [Antônio A.F. Loureiro, 2010]. 

Algumas potenciais aplicações de rede sem fios, que possuem pequenas exigências de vazão e são frequentemente medidas em alguns bits por segundo, e incluem controles e monitoramentos; automação residencial e alguns eletrônicos de consumo; detecção de segurança e militar; rastreamento de ativos e gerenciamento de cadeia de energia/abastecimento; agricultura inteligente; e monitorização de saúde. Essas aplicações requerem um menor consumo de energia e uma menor complexidade de ligação sem fio. Um menor consumo energético é um problema crítico neste tipo de redes em desenvolvimento na subcamada MAC, da camada de enlace em RSSF [REF1, 2, 3]. O padrão IEEE 802.11 é um dos muitos padrões para a implantação de redes de sensores sem fio.

O IEEE 802.11 emprega um mecanismo portador de acesso múltiplo com que evita colisões (CSMA-CA) e suporta redes em estrela single-hop e redes peer-to-peer multi-hop. Em ambas as topologias de rede, o primeiro passo para iniciar está a definir o dispositivo coordenador da rede sem fio do sensor (RSSF) a fim controlar e manter recursos da rede. Este procedimento define o potencial gargalo da rede, além de definir o maior consumidor de energia de toda a rede.

Desta forma, este trabalho de pesquisa elabora um estudo do desempenho de diferentes protocolos existentes para o padrão IEEE 802.11 realizado para avaliar as redes de sensores sem fio ad hoc de taxa de dados baixas propostas por meio de vários conjuntos de simulação, incluindo o impacto das cargas de tráfego e tamanhos de carga de dados.

## Justificativa 

O avanço no uso de RSSF e a justificativa para se apoiar nessa tecnologia atualmente se explica pela evolução dos microprocessadores, micro sistemas eletromecânicos, materiais de sensoriamento modernos e a comunicação sem fio, o uso de tais, têm habilitado o estímulo à agregação destes em um só sensor, conhecidos como sensores “inteligentes”, e seus empregos se dão nas mais diversas áreas como processos químicos, físicos, biológicos e assim por diante, liberando o homem de ambientes insalubres e danosos. O uso de um chip com vários sensores, sensores “inteligentes”, para comunicação sem fio é comum e a sua propensão é para a fabricação em larga escala depreciando assim seu custo, investindo ainda mais no desenvolvimento tecnológico destes artefatos [Sadraque S. Viana, 2013].

Nodos sensores são dispositivos autônomos equipados com capacidades de sensoriamento, processamento e comunicação. Quando estes nodos são dispostos em um modo ad hoc formam as redes de sensores sem fio, redes ad hoc são redes sem fio que dispensam o uso de um ponto de acesso comum aos dispositivos conectados a ela, de modo que todos os dispositivos da rede funcionam como se fossem um roteador, encaminhando comunitariamente informações que vêm de dispositivos vizinhos. Os nodos coletam dados via sensores, processam localmente ou coordenadamente entre vizinhos podendo enviar a informação para o usuário ou, em geral para um coletor de dados (data sink).

Conectar esses sensores utilizando outra tecnologia que não seja rede sem fio, como por exemplo, através de meios guiados, como par trançado, cabo coaxial ou fibra óptica, é uma tarefa que pode não ser viável devido ao tipo de aplicação da rede, por exemplo, monitoramento numa floresta ou oceano, ou devido à quantidade de sensores que devem ser interconectados, esta necessidade faz com que a estrutura e a logística de transporte e armazenamento prevejam o uso de vários metros de cabos que por sua vez apresentam um volume e peso consideráveis na aplicação das pesquisas, realizadas quase sempre em áreas de difícil acesso [Antônio A.F. Loureiro, 2010]. 

Na maioria das aplicações, a capacidade de processamento dos dispositivos é baixa para favorecer a autonomia de funcionamento. Porém, o uso de dezenas (e até centenas) destes dispositivos integrados em rede oferece possibilidades tecnológicas realmente novas. O poder das redes reside na habilidade de agregar um grande número de pequenos sensores que se organizam e se configuram independentemente. Os custos na instalação deste tipo de sistema tendem a ser minimizados uma vez que estruturas como conduítes, cabos e fios não são necessários, permitindo que uma dada área possa ser facilmente monitorada por centenas de sensores que automaticamente formam uma rede de interconexão e informam os dados sendo aquisitados [Marcel Salvioni da Silva e Fabiano Fruett, 2013].

Observando o cenário paraense, o desmatamento na região é uma questão preocupante, posto que em março de 2010 do desmatamento ocorrido em toda Amazônia Legal, 45% se deu no Pará, dentre os quais o município de Rondon do Pará ocupa o 8º lugar e Tomé-Açu o 9º lugar no ranking de municípios que mais desmataram, de acordo com relatórios divulgados pelo Imazon, [Maria José, 2011], a região paraense possui uma extensa área costeira, nas suas regiões portuárias e áreas adjacentes dos grandes centros urbanos, os riscos de acidentes por óleos ou derivados, produtos químicos, entre outros, podem representar uma eminente ameaça ao meio ambiente [Luci Cajueiro, 2009].

Analisando os dados, a utilização de rede de sensores para monitoramento ambiental pode ser justificada devido suas características de auto-organização e dispensar de estruturas cabeadas para sua implantação, o estudo desta tecnologia por parte do projeto se torna imprescindível podendo abrir margem a estudo posteriores para auxiliar a implantação de uma rede real dentro da região paraense.


## Objetivos

O objetivo do projeto é desenvolver uma avaliação de desempenho em cenários de elevada e baixa taxa de transferência para redes de sensores sem fio como visto em [Muhamad S. e Hamed S, 2013], fazendo uma proposta de estudo de caso para região nordeste paraense, tendo como premissa a elaboração cenários de simulação levando em conta as características da região em estudo, como a variabilidade climática, as altas taxas de umidade no ar que podem interferir na transmissão de dados, como pode ser visto em [Kohta Ohshima e Hiroshi Hara 2012], também inclui-se a essas características, das longas áreas desde cultivo à agropecuária ou até as mesmo pequenas de agricultura familiar, que para se ter um controle sobre a rede que irá monitorá-las terão que visar uma maior eficiência energética, atrasos menores e emprego de protocolos que otimizem a rede [Mohamed e Ahmad, 2016]; a partir dessas simulações serão extraídos dados para averiguar a viabilidade da utilização de rede de sensores sem fio para região, além do estudo de caso, espera-se também realizar uma análise de desempenho para esse tipo de rede, alguns parâmetros de rede principais, tais como a porcentagem de perda de pacotes, taxa de transferência, atraso fim-a-fim, jitter e o consumo de energia serão analisados, baseados no estudo desenvolvido em [Oliveira, 2015], [Faieza Hanum, 2009] e [Álisson de Oliveira Alves e Felipe Denis, 2016].

### Objetivos Específicos

* Aprender as abstrações do ambiente de simulação;
* Estudar cenários ambientais;
* Estudar cenários aquáticos e suas peculiaridades;
* Estudar cenários da região nordeste paraense;
* Estudar cenários de elevada e baixa transferência de dados;
* Realizar experimentos comparativos;

## Materiais e Métodos

Para atingir os objetivos deste projeto, utilizou-se simulação de eventos discretos. A simulação é uma técnica baseada no desenvolvimento de modelos, isto é, abstrações da realidade, que capturam aspectos essenciais do objeto em estudo. Em geral, os modelos são especificados através de linguagens de programação de propósito geral com bibliotecas para geração de números aleatórios que serão utilizadas para o escalonamento de eventos, ou linguagens específicas. Para nosso estudo utilizou-se um simulador de eventos discretos, o Network Simulator 3 (ns-3), que é amplamente utilizado pela comunidade internacional de pesquisa em redes de computadores.

Além disso utilizou-se como fonte de informação a biblioteca digital IEEE Explorer (Institute of Electrical and Electronic Engineers) para buscar trabalhos relacionados com a temática de pesquisa, com finalidade fundamentar teoricamente e tecnicamente o projeto. Também foi usado o software GitKraken para o gerenciamento de versões dos códigos das simulações que são salvas dentro de um repositório público no Github, com intuito de facilitar o acompanhamento do orientador nas tarefas e também deixar público os artefatos gerados nesse projeto para contribuir com a comunidade acadêmica em geral. 

## Acidentes e Desastres Ambientais no Pará

<img src="Imagens/linha-do-tempo-desastres-no-para.png" alt="Linha do tempo" align="center"/>

### Megaoperação fecha 13 serrarias e apreende R$ 6 milhões em madeira ilegal, 2009.

A operação Caapora foi comandada pelo ministro do [Meio Ambiente](http://www.mma.gov.br/informma/item/5382-megaoperacao-fecha-13-serrarias-e-apreende-r-6-milhoes-em-madeira-ilegal), Carlos Minc, e envolveu 140 homens e 30 viaturas. Treze serrarias instaladas no local arrasaram 80 mil dos 250 mil hectares que compõem a área indígena, aterraram o rio e mantiveram trabalhadores em situação semelhante ao trabalho escravo, cerca de 200 fornos de carvão foram destruídos e foi apreendida madeira suficiente para encher 400 caminhões, avaliada em R$ 6 milhões. Até agora sete serrarias foram embargadas e seis tratores, dois caminhões, vários motores de serras, além de armas e munições foram apreendidos. Posteriormente, as demais foram fechadas.

### A Defesa Civil concluiu o levantamento do desastre ocorrido em Abaetetuba, 2014.

Segundo [G1 PA](http://g1.globo.com/pa/para/noticia/2014/01/defesa-civil-divulga-relatorio-do-desastre-ocorrido-em-abaetetuba.html), a Defesa Civil concluiu o levantamento do desastre ocorrido em Abaetetuba no dia 4 de janeiro, quando dezenas de casas, no bairro São João, em Abaetetuba, foram destruídas após uma erosão provocada pela cheia do rio Maratauíra, um buraco se abriu e atravessou a rua, ''engolindo'' as casas ao redor. De acordo com o relatório, ao todo, 213 pessoas foram afetadas diretamente pelo desabamento das casas. A área do desastre atingiu cerca de mil metros quadrados.

### Barcarena decreta situação de emergência após tragédia ambiental, 2015.

A Prefeitura de Barcarena decretou [situação de emergência](http://g1.globo.com/pa/para/noticia/2015/10/barcarena-decreta-situacao-de-emergencia-apos-tragedia-ambiental.html) no município, localizado no nordeste do Pará, devido à tragédia ambiental causada pelo naufrágio de um navio que transportava 5 mil bois no dia 6 de outubro. O óleo da embarcação e corpos dos animais mortos se espalharam por praias do município, após o rompimento da barreira de contenção montada para conter os resíduos do acidente. [Segundo a Defesa Civil](http://g1.globo.com/pa/para/noticia/2015/11/barraqueiros-de-praia-afetada-por-naufragio-no-pa-pedem-providencias.html), a praia de Beja foi a mais atingida pelo óleo que vazou do interior da embarcação por conta das correntes marinhas que convergem em direção ao local, prejudicando barraqueiros e pescadores.

### Pará já registrou 38 mil focos de queimadas este ano, 20 mil deles só em setembro, 2017.

Em 2017, o Pará já registrou [38 mil focos de queimadas](https://g1.globo.com/pa/para/noticia/para-ja-registrou-38-mil-focos-de-queimadas-este-ano-20-mil-deles-so-em-setembro.ghtml), só no mês de setembro, foram 20 mil. Isso tudo pode ser consequência de dois anos seguidos de secas muito severas na floresta amazônica, diz um estudo da Nasa, a Agência Espacial Americana. Os focos se espalham agora por áreas protegidas. Em Parauapebas, sudeste do Pará, o Parque Nacional do Campos Ferruginosos ficou em chamas por mais de duas semanas, as queimadas já destruíram uma região do tamanho de cinco mil campos de futebol. De acordo com os [dados divulgados](https://g1.globo.com/pa/para/noticia/registros-de-focos-de-queimadas-no-interior-do-para-chega-a-mais-de-400.ghtml) pela Semas os municípios no interior do estado que mais tiveram focos de queimadas são: Altamira (124 focos), São Feliz do Xingu (114 focos) e Itaituba (48 focos).

###  Operação apura crimes ambientais no Aterro Sanitário de Marituba, no Pará, 2017.

A Polícia Civil do Pará e o Ministério Público do Estado realizaram a [Operação Gramacho](https://g1.globo.com/pa/para/noticia/policia-civil-e-ministerio-publico-fazem-operacao-para-combater-crimes-ambientais-no-para.ghtml), de combate a crimes ambientais no Aterro Sanitário de Marituba, na região metropolitana de Belém. As investigações são quanto a danos ambientais que têm causado prejuizos à população de Marituba desde o início do funcionamento do aterro, em 2016. No mês de março de 2017, a Divisão Especializada em Meio Ambiente (Dema) da Polícia Civil instaurou inquérito para apurar os crimes ambientais. Durante as investigações, a Polícia Civil apurou que, no mês de janeiro de 2017, por não ter mais lagoas para armazenamento de chorume, a empresa despejou o líquido bruto no solo sem impermeabilização.

###  Vazamento de rejeitos da Hydro Alunorte causa danos socioambientais em Barcarena, 2018.

Segundo [Amazônia Real](http://amazoniareal.com.br/vazamento-de-rejeitos-da-hydro-alunorte-causa-danos-socioambientais-em-barcarena-no-para/) Treze comunidades ribeirinhas, viram seus quintais e poços artesianos serem tomados por uma lama vermelha, rejeitos químicos. Segundo o pesquisador do IEC (Instituto Evandro Chagas), as amostras analisadas tinham níveis de chumbo, sódio, nitrato e alumínio, sendo que este último está 25% acima do permitido para a saúde humana. A lama vermelha vista nas comunidades  São João, Burajuba, Sítio Conceição, Cupuaçu Boa Vista, São Lourenço Gibiriê, todas de remanescentes quilombolas, é de bauxita e outros produtos químicos. De acordo com o site da BBC Brasil, após negar irregularidades com o duto, a Hydro admitiu, em nota, a existência do canal encontrado por pesquisadores do Instituto Evandro Chagas (IEC). 

###  Prefeito decreta situação de emergência em função da cheia do rio e do número de desalojados, 2018.

A informação oficial é que o nível do Rio atingiu 10.90 metros, elevando para 300 o número de famílias em estado de risco. No [decreto](http://maraba.pa.gov.br/prefeito-decreta-situacao-de-emergencia-em-funcao-da-cheia-do-rio-e-do-numero-de-desalojados/) o prefeito Considera que os Rios Tocantins e Itacaiúnas devido ao elevado índice pluviométrico das chuvas nesta época, vem enchendo além do normal. O parecer da Coordenadoria Municipal de Defesa Civil, relata que a ocorrência deste desastre é favorável à declaração de Situação de Emergência, este decreto coloca em estado de emergência todas as secretarias do governo voltadas para área de estrutura, saúde e social, agilizando ainda o processo de ação das mesmas.

###  Suspeita de vazamento em mineradora no Pará faz moradores temerem sofrer a mesma tragédia de Mariana, 2018.

A comunidade ficou assustada com um [possível vazamento de rejeitos](https://g1.globo.com/pa/para/noticia/suspeita-de-vazamento-em-mineradora-no-para-faz-moradores-temerem-sofrer-a-mesma-tragedia-de-mariana.ghtml) de uma mineradora. Fotos feitas no município mostram uma alteração na cor da água do rio, que invadiu as casas próximas à empresa. Testemunhas dizem que a lama teria vindo da minerdora Hydro Alunorte, que processa bauxita a dois quilômetros da comunidade.O Ministério Público do Pará abriu dois inqueritos pra apurar as denúncias. Peritos do Instituto Evandro Chagas coletaram amostras de água. 

###  Paragominas: Barragem rompe na madrugada e deixa mortos e desaparecidos, 2018.

Segundo o [Correio de Carajás](https://correiodecarajas.com.br/paragominas-barragem-rompe-na-madrugada-e-deixa-mortos-e-desaparecidos/), a Prefeitura Municipal de Paragominas confirmou em nota divulgada agora pouco a morte de duas crianças em decorrência da tragédia que pegou os moradores do município de surpresa durante a madrugada. Há relatos de que uma barragem tenha se rompido em decorrência das fortes chuvas, causando o transbordamento do Rio Uraim e alagamentos em toda a cidade. No posicionamento, a administração informou que já decretou estado de calamidade pública em toda a extensão do munícipio de Paragominas, em virtude de desastres.






## Referências 

> **Oliveira, F., D. (2015)** *“FTE-LEACH: Um Protocolo Energeticamente Eficiente e Tolerante a Falhas Aplicado às Redes Industriais de Sensores sem Fio”*, Tese (Doutorado), Universidade Federal do Rio Grande do Norte. Centro de Tecnologia –Programa de Pós-Graduação em Engenharia Elétrica e de Computação. Page 144;

> **Oliveira, F., D., Semente, R., S., Melo, T., A., e Salazar, A., O. (2014)** *“QoS Analysis of Routing Protocols in Wireless Sensor Networks in the Monitoring of Wind Farms.”* Instrumentation and Measurement Technology Conference (I2MTC) Proceedings of the IEEE: pages 1059-1064.

> **Álisson de Oliveira Alves, Felipe Denis Mendonça de Oliveira, (2016)** *“Análise de Desempenho dos Protocolos de Roteamento de Redes de Sensores sem fio em Smart Grids”*;

> **Kazem Sohraby, Daniel Minoli, Taieb Znati, (2007)** - *“Wireless Sensor Networks”*;

> **BRÖRING (2011)**, *“New generation sensor web enablement. Sensors”*;

> **Kohta Ohshima, Hiroshi Hara , Yoichi Hagiwara, Matsuaki Terada (2012)** *“Field Investigation of the Radio Transmission Performance and Distance in a Environmental Wireless Sensor Network”*, The International Conference on Information Network 2012, Pages: 132 - 137, DOI: 10.1109/ICOIN.2012.6164364;

> **Fabrício Braga S. de Carvalho, Brauliro G. Leal, (2012)**, *"Aplicações Ambientais de Redes de Sensores Sem Fio."* Revista de Tecnologia da Informação e Comunicação, Vol. 2, No. 1, Outubro 2012;

> **Ertugrul Basar, Ibrahim Altunbas (2017)**, *“Space-Time Channel Modulation”* IEEE Transactions On Vehicular Technology, VOL. 66, NO. 8, Agosto 2017;

> **Yogesh Nijsure, Mohammed F. A. Ahmed , Georges Kaddoum , Ghyslain Gagnon, Francois Gagnon, (2016)**, *“WSN-UAV Monitoring System with Collaborative Beamforming and ADS-B based Multilateration.”* 2016 IEEE 83rd Vehicular Technology Conference (VTC Spring) Pages: 1 - 5, DOI: 10.1109/VTCSpring.2016.7504535;

> **Sadraque S. Viana, (2013)**, *“HydroNode: Uma rede de sensores aquáticos de baixo custo e consumo”*;

> **Muhamad S. Iqbal and Hamed S. Al-Raweshidy, (2013)**, *“Performance Evaluation of IEEE 802.15.4 Standard for Low Data Rate Ad Hoc Wireless Sensor Networks”*, ICCAIS 2013: Main Track;

> **Mohamed Rawidean Mohd Kassim & Ahmad Nizar Haru, (2016)**, *“Applications of WSN in Agricultural Environment Monitoring Systems”*, IEEE ICTC 2016;

> **Faieza Hanum Yahaya, Yusnani Mohd Yussoff, Ruhani Ab. Rahman and Nur Hafizah Abidin, (2009)**, *“Performance Analysis of Wireless Sensor Network”*, 5th International Colloquium on Signal Processing & Its Applications (CSPA);

> **Antônio A.F. Loureiro, José Marcos S. Nogueira, Linnyer Beatrys Ruiz, Raquel Aparecida de Freitas Mini, Eduardo Freire Nakamura, Carlos Maurício Seródio Figueiredo, (2010)**, *“Redes de Sensores Sem Fio”*, XXI Simpósio Brasileiro de Redes de Computadores;

> **Fabrício Braga S. de Carvalho, Brauliro G. Leal, José Valentim dos S. Filho, Orlando R. Baiocchi, Waslon T. A. Lope e Marcelo S. de Alencar, (2012)**, *“Aplicações Ambientais de Redes de Sensores Sem Fio”*, Revista De Tecnologia Da Informac Ão Vol. 2, No. 1, Outubro 2012;

> **Anjana Tiwari, Inderjeet Kaur, (2017)**, *“Performance Evaluation of Energy Efficient For MANET Using AODV Routing Protocol”*, 3rd IEEE International Conference on "Computational Intelligence and Communication Technology" (IEEE-CICT 2017)

> **Ulf Sterner, Ulrika Uppman, (2017)**, *“On the Robustness of OLSR in a Mobile Tactical Scenario in Rural Terrain”*, 2017 International Conference on Military Communications and Information Systems (ICMCIS)

> **Ashutosh Sharma, Rajiv Kumar, (2017)**, *“On the Robustness of OLSR in a Mobile Tactical Scenario in Rural Terrain”*, 2017 International Conference on Military Communications and Information Systems (ICMCIS)

> **IEEE 802.11 Working Group. (2016)**, IEEE Standard for Information Technology–Telecommunications and information exchange between systems–Local and metropolitan area networks–Specific requirements – *“Part 11: Wireless LAN Medium Access Control (MAC) and Physical Layer (PHY) specifications Amendment 1: Fast Initial Link Setup”*. 

> **Kurose, J. F., & Ross, K. W. (2006)**, *“Redes de Computadores e a Internet”*. São Paulo: Person, 28.
