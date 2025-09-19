# Sistema Inteligente na Saude

`CURSO: Sistemas de Informação`

`DISCIPLINA: Projeto - Design de Centrado no Usuário`

`SEMESTRE: 3º`

Um Sistema de Integração de Dados na área da saúde consiste em um portal seguro e centralizado, que reúne todas as informações médicas relevantes de um paciente, como histórico de doenças, alergias, consultas já realizadas, consultas agendadas, além de registros de exames e procedimentos. Esse sistema possibilita que médicos e pacientes tenham acesso rápido e organizado aos dados, permitindo marcações de exames de forma prática, melhorando a comunicação entre clínicas, hospitais e laboratórios, e reduzindo a fragmentação de informações médicas.

Com credenciais autorizadas, o médico consegue acessar de maneira segura os dados completos do paciente, independentemente do plano de saúde utilizado. Isso proporciona uma triagem mais rápida, diagnósticos mais precisos e um acompanhamento contínuo e eficiente da evolução clínica. Além disso, o sistema evita retrabalho, duplicidade de exames e falhas por falta de informações, garantindo maior agilidade no atendimento e fortalecendo a qualidade do cuidado em saúde.

## Integrantes

* Rafael Alves Faria
* Nome completo do aluno 2



## Orientador

* Maria Ines Lage de Paula

# Planejamento

| Etapa         | Atividades |
|  :----:   | ----------- |
| ETAPA 1         |[Introdução](docs/introducao.md) <br> [Estado da Arte](docs/estado.md) <br> [Referências](docs/referencias.md) |
1. INTRODUÇÃO

A integração de dados na área da saúde é um recurso essencial para modernizar o atendimento médico e garantir maior eficiência nos processos clínicos. A proposta de um portal seguro e centralizado permite reunir informações completas dos pacientes, como histórico de doenças, alergias, consultas já realizadas, consultas futuras e registros de exames. Com isso, tanto pacientes quanto médicos podem acessar dados de forma prática e organizada, facilitando agendamentos, acompanhamentos e o compartilhamento de informações entre diferentes instituições de saúde.

Esse sistema promove uma triagem mais rápida e eficaz, já que o médico autorizado, por meio de credenciais de acesso, pode visualizar o quadro clínico completo do paciente, independentemente do plano de saúde utilizado. Dessa forma, o profissional dispõe de subsídios mais precisos para interpretar o estado de saúde do indivíduo, agilizando diagnósticos e reduzindo falhas por falta de informação. Além de melhorar a qualidade do atendimento, a integração de dados contribui para a continuidade do cuidado, a redução de custos e o fortalecimento da relação entre pacientes e profissionais da saúde.

1.1. Problema

A ausência de um sistema de integração de dados na área da saúde gera um grande problema na qualidade do atendimento médico e na gestão das informações dos pacientes. Atualmente, os dados ficam dispersos em diferentes clínicas, hospitais e laboratórios, muitas vezes sem comunicação entre si, o que dificulta o acesso rápido ao histórico clínico. Isso pode resultar em falhas no diagnóstico, repetição de exames já realizados, atrasos em consultas e dificuldades na marcação de procedimentos, além de comprometer a eficiência no acompanhamento do paciente.

Sem um portal seguro e centralizado, médicos enfrentam limitações para obter informações essenciais, como histórico de doenças, alergias e registros de atendimentos, o que atrapalha uma triagem rápida e precisa. A falta de integração também prejudica a continuidade do cuidado, já que cada profissional acessa apenas fragmentos do histórico, aumentando o risco de erros e dificultando a interpretação completa do estado de saúde do paciente. Dessa forma, a inexistência desse sistema compromete a agilidade, a segurança e a eficácia do atendimento médico.

1.2. Objetivos do trabalho

Os principais objetivos de um Sistema de integração de dados na área da saúde estão voltados para centralizar e organizar as informações médicas dos pacientes em um portal seguro e de fácil acesso. Esse recurso busca reunir dados completos, como histórico de doenças, alergias, consultas realizadas, consultas futuras e exames, permitindo maior agilidade na marcação de procedimentos e no acompanhamento clínico. Além disso, o sistema visa reduzir a fragmentação das informações, evitando retrabalho e falhas ocasionadas pela falta de dados atualizados.

Outro objetivo fundamental é fornecer ao médico, por meio de credenciais autorizadas, acesso rápido e confiável ao histórico do paciente, independente do plano de saúde utilizado. Isso possibilita uma triagem mais eficiente, diagnósticos mais precisos e interpretações rápidas sobre o estado clínico, favorecendo a continuidade do cuidado e a qualidade do atendimento. Dessa forma, o sistema não apenas moderniza os processos de saúde, como também fortalece a segurança, a eficiência e a integração entre profissionais, pacientes e instituições de saúde.

1.3. Justificativa

A implementação de um Sistema de integração de dados na área da saúde está relacionada à necessidade de superar a fragmentação das informações médicas, que atualmente se encontram dispersas em diferentes instituições e sistemas. Essa falta de centralização compromete a qualidade do atendimento, gera retrabalho, atrasos em diagnósticos e dificulta o acompanhamento contínuo dos pacientes. Com um portal seguro e integrado, é possível reunir dados completos, como histórico de doenças, alergias, consultas e exames, garantindo maior praticidade no acesso e na gestão das informações.

Além disso, o sistema justifica-se por oferecer aos médicos credenciados acesso rápido e confiável às informações essenciais, independentemente do plano de saúde. Isso favorece triagens mais eficientes, diagnósticos precisos e uma interpretação ágil do estado clínico do paciente. Ao reduzir erros, duplicidade de exames e falhas de comunicação entre profissionais de saúde, a solução contribui diretamente para a melhoria da qualidade do atendimento, promovendo eficiência, segurança e maior humanização nos cuidados médico

1.4. Público alvo

O público-alvo da aplicação do siatema de integraçao de dados na saúde é amplo e abrange pacientes, profissionais de saúde e gestores hospitalares. 
Para os pacientes, esse sistema facilita a marcação de exames, o acompanhamento médico personalizado, atualização de dados e a adesão a tratamentos. 
Já os profissionais, como médicos e enfermeiros, se beneficiam com suporte em diagnósticos e triagem mais ágil, reduzindo a sobrecarga de trabalho. 
Gestores e instituições de saúde também encontram vantagens na otimização de recursos e na melhoria da qualidade do atendimento. Assim, o sistema de integraçao de dados apoia diferentes perfis dentro do ecossistema da saúde, promovendo eficiência e cuidado centrado no paciente.

2. ESTADO DA ARTE

1.	Quais pesquisas estão sendo desenvolvidas sobre esse tema?

Pesquisas atuais sobre sistemas de integração de dados em saúde concentram-se fortemente em capacidade de diferentes sistemas, como softwares ou organizações, que trabalharem juntos, trocando informações e dados de maneira eficaz, segura e automática e padronização (especialmente FHIR/HL7) para permitir a troca segura e semântica de prontuários eletrônicos entre hospitais, clínicas e laboratórios; trabalhos recentes propõem ferramentas e pipelines para mapear e converter dados clínicos para o modelo FHIR. 
(https://medinform.jmir.org/2024/1/e58445?utm_source=chatgpt.com)

Outra linha ativa investiga privacidade e segurança, abordagens criptográficas, protocolos de autenticação robustos, conformidade com LGPD/GDPR/HIPAA e soluções híbridas:
Por exemplo, blockchain para registro de auditoria sem expor dados sensíveis, para viabilizar portais seguros onde médicos credenciados acessem informações completas sem violar leis ou privacidade. 
(https://pmc.ncbi.nlm.nih.gov/articles/PMC12138216/?utm_source=chatgpt.com)

2.	Quem está pesquisando e onde?

Daiane Evangelista Santos da Silva & Jano Moreira de Souza (UFRJ), empresas ProntLife e Lemobs. 
Tese de doutorado em “Interoperabilidade e Modelagem de Dados Clínicos no Brasil: Aplicação dos Padrões OpenEHR e HL7 FHIR”. Eles estudam implementação prática desses padrões para dados clínicos, em casos reais, analisando desafios e benefícios.
(https://cos.ufrj.br/index.php/en/publicacoes-pesquisa/details/20/3223?utm_source=chatgpt.com)
Equipe da Universidade de São Paulo (USP) – Exemplos:

Verena Hokino Yamaguti, Newton Shydeo Brandão Miyoshi, Milena Gomes Delfini, Rui Pedro Charters Lopes Rijo, e Domingos Alves fizeram estudo “Estudo e Projeto de um Servidor de Terminologia HL7 FHIR” voltado a interoperabilidade e uso de terminologias padrão (CID-10, CIF) para saúde mental. 
(https://repositorio.usp.br/item/002955479?utm_source=chatgpt.com)

Repositório da Produção USP:
Felipe Carvalho Pellison, Rui Pedro Rijo, dentre outros, atuam em integração semântica de sistemas de saúde no estado de São Paulo, com foco em tuberculose, usando Web Semântica para interoperabilidade.
(https://medinform.jmir.org/2020/7/e17176/?utm_source=chatgpt.com)

3.	O que as atuais pesquisas científicas concluíram sobre o tema? 

As pesquisas científicas atuais convergem para que a adoção de padrões de interoperabilidade (especialmente HL7 FHIR) seja a base mais promissora para integrar prontuários e permitir portais seguros com dados completos de pacientes — vários estudos e revisões sistemáticas mostram que FHIR facilita troca semântica de informações e suporte a aplicações clínicas reais. 
(https://pmc.ncbi.nlm.nih.gov/articles/PMC9346559/?utm_source=chatgpt.com)

Ao mesmo tempo, a literatura destaca que segurança, privacidade e governança de dados permanecem como desafios centrais: técnicas criptográficas, gestão de consentimento dinâmico e mecanismos de auditoria (algumas propostas usam blockchain apenas para metadados/consentimentos) aparecem como soluções potenciais, mas com limitações práticas e necessidade de testes em larga escala. Implementações bem-sucedidas exigem também alinhamento regulatório (LGPD/HIPAA/GDPR), maturidade das instituições e investimento em infraestrutura. 
(https://link.springer.com/article/10.1007/s10389-022-01795-z?utm_source=chatgpt.com)

Estudos sobre impacto clínico indicam benefícios esperados — redução de exames duplicados, triagem mais rápida, continuidade do cuidado e melhor suporte à decisão clínica — porém ressaltam que ganhos reais dependem de qualidade dos dados, adoção por profissionais e integração com fluxos de trabalho (barreiras técnicas, culturais e econômicas continuam a atrasar resultados em larga escala). 


4.	Quais as divergências dos pesquisadores sobre o assunto? 

As pesquisas sobre sistemas de integração de dados em saúde apresentam algumas divergências importantes entre os especialistas. Um dos principais pontos de debate está na escolha dos padrões tecnológicos: enquanto parte dos pesquisadores defende o uso do HL7 FHIR como caminho consolidado para a interoperabilidade, outros apontam limitações práticas, como custos de implementação, necessidade de infraestrutura robusta e dificuldades na adaptação de sistemas legados. Há também divergências sobre a melhor forma de estruturar os dados — alguns grupos priorizam modelos clínicos padronizados (openEHR, SNOMED CT), enquanto outros defendem soluções mais flexíveis e adaptáveis às realidades locais.

Outro campo de divergência envolve a segurança e privacidade dos dados. Há pesquisadores que defendem o uso de tecnologias descentralizadas, como blockchain, para garantir rastreabilidade e confiabilidade no acesso aos registros, enquanto outros consideram essa solução pouco viável devido ao alto custo computacional e às dificuldades de escalabilidade. Além disso, existem opiniões distintas sobre o grau de centralização dos dados: alguns defendem portais unificados nacionais, enquanto outros acreditam que modelos distribuídos, interligados por padrões de interoperabilidade, oferecem mais segurança e flexibilidade. Por fim, há divergências quanto à velocidade de adoção dessas soluções — parte dos pesquisadores acredita que os benefícios clínicos são imediatos e justificam investimentos rápidos, enquanto outros ressaltam barreiras culturais, regulatórias e econômicas que ainda precisam ser superadas para que esses sistemas tragam impacto efetivo no cuidado em saúde.

5.	Quais aspectos carecem de maior abordagem?

Alguns aspectos do tema de integração de dados na saúde ainda carecem de maior aprofundamento por parte das pesquisas e das práticas em desenvolvimento. Um deles é a padronização completa dos dados clínicos, já que muitos sistemas utilizam formatos diferentes, dificultando a comunicação entre plataformas. Também falta maior avanço em estratégias de governança e auditoria de acesso, garantindo que médicos com credenciais autorizadas tenham uso facilitado das informações, sem comprometer a privacidade e a segurança dos pacientes.

Outro ponto que exige maior abordagem é a adoção prática no cotidiano dos serviços de saúde, considerando barreiras culturais, econômicas e de treinamento de profissionais. Além disso, a usabilidade dos portais seguros, tanto para médicos quanto para pacientes, precisa ser aprimorada para garantir acesso rápido e intuitivo às informações. Questões relacionadas à interoperabilidade entre sistemas públicos e privados, bem como a integração independente de planos de saúde, também carecem de estudos mais consistentes para tornar realidade um fluxo único de dados clínicos, que realmente favoreça diagnósticos mais rápidos, triagens eficientes e continuidade do cuidado em saúde.

| ETAPA 2         |[Especificação de Requisitos de Software](docs/especificacao.md) |
| ETAPA 3         |[Design de Interação](docs/design.md) |
| ETAPA 4        |[Testes de Software](docs/testes.md) |
| ETAPA 5         | [Apresentação](docs/apresentacao.md) |


# Código

<li><a href="src/codigo.md"> Código Fonte</a></li>

# Apresentação

<li><a href="docs/apresentacao.md"> Apresentação da solução</a></li>
