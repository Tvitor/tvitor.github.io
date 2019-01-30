---
layout: post
title:  "As etapas do desenvolvimento de software"
date:   2018-07-02 10:18:00
categories: Desenvolvimento_de_software
---
Quem nunca viu essa situação? Uma solução que uma empresa inteira  utiliza, está causando problemas para os usuários. E os problemas só apareceram depois que esse software foi entregue. E pior, o software foi diretamente implementado, sem nenhuma análise prévia ou criação de documentação. 

E esse cenário? um software confuso que não possui documentação, confunde todos que estão usando, até mesmo quem o criou. Vive mudando as regras de negócio e nunca melhora o desempenho.
As falhas e defeitos devem ser descobertas antes do produto ser entregue. 

As etapas que envolvem o desenvolvimento de software têm justamente essa intenção. Essas etapas, ou fases, tem por objetivo garantir uma qualidade no software. Qualidade que atenda os desejos que motivaram a criação desse produto e que evitem a entrega com problemas. 

A intenção desse post é justamente falar dessas etapas, pois acredito que é um assunto que merece ser valorizado e o conhecimento compartilhado, afim de contribuir com a comunidade de TI através dos recursos das boas práticas. 
Entender os processos de desenvolvimento de software é um passo inicial e fundamental para o amadurecimento do conhecimento relacionado a capacidade de produzir e manter um software de qualidade. Além disso, a definição padronizada de trabalho fomenta nas organizações um crescimento e um amadurecimento na forma de execução dos projetos, permitindo, inclusive, a repetição do que foi positivo.

Os Processos e as boas práticas na construção de um software é determinante para a qualidade final do produto. Esse produto, é envolvido por atividades sistematizadas, divididas em fases ou etapas. Para qualificar o entendimento, é necessário utilizar a análise de requisitos de algumas dessas etapas, garantindo a qualidade e reduzindo riscos. A descrição correta dos requisitos permitirá uma modelagem ou desenho do software, possibilitando então a implementação e posteriormente o teste.

É importante ressaltar, que esses processos só terão resultado, se respeitarem a necessidade do cliente e dos usuários, tendo qualidade, reduzindo custos e prazos. São fases ou etapas do processo de desenvolvimento do software e suas fases específicas:


![tabelaEtapasComuns](https://raw.githubusercontent.com/Tvitor/Tvitor.github.io/master/assets/images/imagePosts/Tabela%201%202018-07-02%2010-48.PNG)

**Especificação**

O início da especificação de requisitos, onde é demostrado o que foi solicitado, tem o usuário como peça chave. 

Primeiro, suas declarações em linguagem natural e também em diagramas, apresenta como deseja que o sistema funcione.

![Diagrama](https://raw.githubusercontent.com/Tvitor/Tvitor.github.io/master/assets/images/imagePosts/dados%202018-07-02.PNG)

 Em seguida, é estabelecido detalhadamente as funções e restrições. Documentado, chamado de especificação funcional. Pode ser representado como um contrato entre comprador do sistema e o desenvolvedor do software. Ao final, é feito uma descrição abstrata desse projeto sendo uma base para sua implementação, acrescentando mais detalhes aos requisitos do sistema.
Em um segundo momento, começa a análise de requisitos, onde basicamente envolve o reconhecimento do problema e sua modelagem. Nessa análise de requisitos, definir os conceitos do projeto, do produto, e as suas características funcionais e não funcionais é determinante.

Destaco aqui os requisitos funcionais (as ações que deverá existir no programa) e não funcionais (características triviais)

![requisitos](https://raw.githubusercontent.com/Tvitor/Tvitor.github.io/master/assets/images/imagePosts/levantamento%20de%20requisitos%202018-07-02.PNG)

A modelagem é outro momento que merece destaque, aqui compreendemos os fluxos da informação, do controle dos aspectos funcionais e do comportamento do sistema.

![dados](https://raw.githubusercontent.com/Tvitor/Tvitor.github.io/master/assets/images/imagePosts/dados%202018-07-02.PNG)

Ao final da análise de requisitos, encerramos com uma documentação de especificação de requisitos de software. Esse documento pode conter um manual prévio do usuário, afim de criar uma revisão dos requisitos pelo usuário ainda no estágio inicial. Isso sem dúvidas vai diminuir as chances de ocorrer um problema no futuro.

A especificação do software define funções e restrições de sistema através da engenharia de requisitos. É produzido uma série de documentos de requisitos.
São eles: Estudo de viabilidade, Levantamento e análise de requisitos, especificação de requisitos, validação de requisitos. Todos eles são feitos simultaneamente.
Futuramente em outros posts, estarei falando a respeitos dos padrões de desenvolvimento de software(PDS) e os diferentes modelos de ciclo de vida do software

**Projeto**

Desenvolver o desenho ou a arquitetura através das suas propriedades estruturais (organizando a iteração dos módulos, objetos filtros etc.) e não funcionais, que seria a descrição do projeto de arquitetura, suas capacidades, confiabilidade, segurança, etc.

**Codificação**

Agora sim, o momento da codificação. Nessa etapa utilizamos a linguagem de programação, e é necessário também a documentação dessa etapa. Conhecer as diferentes linguagens e os recursos relacionados a elas podem ser determinante no aspecto de desempenho e tempo de entrega do software.



**Fase de Testes**

Quem garante que depois de tudo isso, o software estará 100% como o usuário gostaria? Por isso, é fundamental uma etapa precoce do uso do software, através de procedimentos de testes tendo sua última etapa uma revisão da especificação do projeto e da codificação. Dois nomes conhecidos aparecem nessa fase: O black box e White box

No black box foca nos requisitos funcionais através da opinião do usuário. Concentra-se nas funções que o software deve possuir. O testador utiliza as seguintes técnicas: 

Caso de uso (ao selecionar o caso de uso a ser testado, é identificado os fluxos e observado o diagrama de atividade, em seguida, é executado as ações do ator para verificar se as respostas são esperadas), particionamento de equivalência(separar as entradas do sistema em categorias e observar os dados se serão válidos ou inválidos, onde deveria ser rejeitado) testes baseados em grafo(testa o relacionamento entre objetos ), teste de todos os pares, teste de tabela de decisão, tabelas de estado de transição e análise do valor limite. 
No White box, as partes internas como seus componentes são examinados detalhadamente. Aqui o código é observado.

**Manutenção**

A manutenção permite a correção ou alteração após a entrega do sistema. É importante no ciclo de vida do software ter ações preventivas e atividades corretivas nas falhas descobertas no código, no projeto ou nas especificações. Além disso, podem acrescentar novas funções. Todo software precisa ter mudanças continuas para não se tornar inútil com a evolução dos sistemas. Existem quatro formas de manutenção:

![tabelaManutencao](https://raw.githubusercontent.com/Tvitor/Tvitor.github.io/master/assets/images/imagePosts/Tabela%202%202018-07-02%2010-48.PNG)

**Documentação:** 

Uma documentação completa, sendo preenchida em todas as fases do processo, garante uma manutenção mais eficiente. Pois facilita o trabalho do suporte técnico permitindo um atendimento eficaz.  Ter uma documentação de uso comum e outra documentação técnica, permite ao usuário uma documentação de fácil compreensão, através de apostilas ou manuais. E aos técnicos e desenvolvedores, ter uma documentação específica, facilita o ganho de tempo para alterações ao observar fluxogramas, o código fonte, os processos e as regras de negócio.

Na modelagem Ágil, enfatiza-se que somente existirá a necessidade da documentação se a regra do negócio assim exigir. Nesse caso, a energia e o tempo dos participantes do projeto estará voltada para uma documentação eficiente e econômica, Diminuindo a carga de trabalho ao máximo que puder. O benefício de ter a documentação tem que ser maior do que o custo de cria-la e mantê-la. 

Futuramente, quero me aprofundar mais nesse tema de análise e desenvolvimento de sistemas, postando alguns diagramas e apresentando o desenvolvimento de programas em diversas linguagens e a utilização de diversas metodologias e recursos. Mas não poderia fazer isso sem antes falar de um assunto base para qualquer desenvolvimento, que é o seu planejamento.


