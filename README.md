LocaCar 

Ana Clara Pinheiro Campos, Gustavo Henrique de Moura Luz, João Pedro Lindenberg Pimenta, João Vitor Jangola Mendes, Leandro Augusto Santos Araujo, Maria Clara Freitas Soares, Natália Kiefer Ferreira. 

1Instituto de Informática e Ciências Exatas – Pontifícia Universidade Católica de Minas Gerais (PUC MINAS) 
Belo Horizonte – MG – Brasil 

acpcampos@sga.pucminas.br, 

ghmluz@sga.pucminas.br, 

joao.lindenberg@sga.pucminas.br, 

joao.jangola@sga.pucminas.br, 

leandro.araujo@sga.pucminas.br, 

natalia.ferreira.784420@sga.pucminas.br, 

maria.soares.1490964@sga.pucminas.br, 

Resumo. O sistema LocaCar representa uma solução inovadora para os desafios enfrentados pelas locadoras de veículos, visando otimizar processos e aprimorar a experiência do cliente. Ao abordar questões como a gestão manual de reservas, falta de comunicação eficiente e processos despadronizados, o LocaCar oferece uma plataforma integrada que simplifica operações e eleva os padrões de serviço. Sua implementação promete aumentar a eficiência operacional, reduzir custos e oferecer uma experiência mais satisfatória para clientes e locadoras. Embora tenhamos desafios como a curva de aprendizado, o potencial de transformação do LocaCar é indiscutível, moldando o futuro da indústria de locação de veículos. 

 

1. Introdução 

O mercado de locação de veículos experimentou um alto crescimento nos últimos anos, impulsionado pelas transformações paradigmáticas na mobilidade urbana do Brasil. Para reforçar o bom momento das locadoras brasileiras, a ABL (Associação Brasileira das Locadoras de Automóveis) (1), registrou 69,3 milhões de usuários em 2022, número superior em 38,3% e 55,4% em relação a 2021 e 2020, respectivamente. Este fenômeno pode ser atribuído a diversos fatores, incluindo o elevado custo de aquisição de um veículo e o surgimento de alternativas de mobilidade urbana, como os aplicativos de motoristas, que tornaram a posse de um carro obsoleta para muitos. No entanto, ainda há momentos em que o acesso a um veículo se faz necessário. 

 

       Figura 1: Gráfico demonstrando o crescimento da locação diária de  

automóveis no Brasil de 2020 a 2023. (2) 

 

 

No setor de locação de veículos, uma série de desafios complexos e interligados impactam diretamente a eficiência operacional e a experiência do cliente. Entre os problemas enfrentados, destacam-se: 

 Controle de Frotas: A falta de um sistema integrado e eficiente para o controle de frotas dificulta a gestão dos veículos disponíveis, levando a inconsistências nos registros de manutenção, localização e disponibilidade dos automóveis. 

 Gestão Manual de Reservas: O processo de reservas realizado de forma manual, seja por telefone ou pessoalmente, resulta em erros de inserção de dados, conflitos de agendamento e retrabalho para resolver duplicidades, afetando a eficiência operacional da locadora. 

 Comunicação Ineficiente: A falta de uma comunicação eficiente entre os funcionários e os clientes pode causar atrasos na confirmação das reservas, indisponibilidade de veículos e desentendimentos, comprometendo a qualidade do serviço prestado. 

 Dificuldade de Acesso às Informações: A ausência de um sistema integrado dificulta o acesso às informações relevantes sobre as reservas, histórico de locações e preferências dos clientes, prejudicando a capacidade da empresa de oferecer um serviço personalizado e de qualidade. 

Processos de Retirada e Devolução Despadronizados: A falta de um processo padronizado para a retirada e devolução dos veículos pode resultar em atrasos, erros na documentação e insatisfação por parte dos clientes, afetando negativamente a experiência geral. 

 	Esses desafios evidenciam a necessidade premente de uma solução abrangente e integrada, que não apenas simplifique os processos operacionais, mas também eleve a qualidade do serviço oferecido pela locadora, garantindo uma experiência satisfatória para os clientes. É aqui que entra o LocaCar. Esta solução visa não apenas simplificar o processo de locação para as empresas, mas também elevar a qualidade e eficiência dos serviços oferecidos, aumentando, por conseguinte, a satisfação do consumidor final. 

O LocaCar representa um avanço significativo no setor, proporcionando uma plataforma intuitiva e abrangente que atende às necessidades das locadoras de veículos e dos usuários finais. Ao integrar tecnologias inovadoras de desenvolvimento WEB e modelagem de processos, o LocaCar otimiza cada etapa do processo de locação, desde a reserva até a devolução do veículo, garantindo uma experiência fluida e sem complicações. 

Além disso, o LocaCar não apenas simplifica a gestão operacional das locadoras, mas também oferece recursos avançados de personalização e acompanhamento em tempo real, permitindo uma interação mais próxima com os clientes e uma resposta ágil às suas necessidades. 

 	Em resumo, o LocaCar representa não apenas uma solução tecnológica para o setor de locação de veículos, mas sim uma transformação fundamental na forma como as pessoas acessam e utilizam os serviços de mobilidade. Com sua abordagem inovadora e foco na qualidade e eficiência, o LocaCar está moldando o futuro da locação de veículos e proporcionando uma experiência excepcional para todos os envolvidos. 

1.1. Objetivos geral e específicos 

Objetivo Geral: 

Elaborar e implementar um sistema de gestão integrada para otimizar os processos de uma locadora de veículos, visando melhorar a eficiência operacional e a satisfação do cliente. 

Objetivos Específicos: 

1 - Modelar os processos operacionais da locadora de veículos, identificando pontos de melhoria e oportunidades de automação. 

2 - Desenvolver e implementar um software personalizado que atenda às necessidades específicas da locadora, incluindo funcionalidades de reservas, gestão de frota e atendimento ao cliente. 

1.2. Justificativas 

A locadora de veículos enfrenta desafios significativos em sua operação diária, desde a gestão da frota até o atendimento ao cliente. Este projeto se justifica pela necessidade de modernizar e otimizar esses processos, garantindo uma experiência mais eficiente e satisfatória tanto para a empresa quanto para os clientes. A implementação de um sistema de gestão integrada trará benefícios tangíveis, como redução de custos operacionais, aumento da produtividade da equipe e melhoria na qualidade dos serviços oferecidos. 

2. Participantes do processo de negócio 

Clientes: São os principais usuários do sistema de locação de veículos, realizando reservas, retiradas e devoluções de automóveis. 

Funcionários: Incluem atendentes, agentes de locação, mecânicos e outros profissionais envolvidos na operação da locadora. Eles desempenham papéis cruciais na prestação de serviços de alta qualidade e no atendimento às necessidades dos clientes. 

Gerentes e Supervisores: Responsáveis pela supervisão e coordenação das atividades da locadora, garantindo o cumprimento de metas e a eficiência operacional. 

3. Modelagem do processo de negócio 

3.1. Análise da situação atual (AS-IS) 

1. Processo de Reserva de Veículo: 

Descrição da Situação Atual (AS-IS): 

No contexto do projeto de otimização dos processos de uma locadora de veículos, identificamos que a gestão manual das reservas de veículos é um ponto crítico. Atualmente, as reservas são realizadas de forma manual, com os clientes entrando em contato por telefone ou pessoalmente para solicitar um veículo. Isso gera a necessidade de inserção manual das informações em planilhas ou sistemas desatualizados, aumentando o risco de erros e inconsistências nos dados. Além disso, devido à falta de integração entre os diferentes canais de reserva e à ausência de um sistema centralizado, ocorrem frequentemente conflitos de agendamento e duplicidade de reservas. Isso resulta em retrabalho para resolver as discrepâncias e insatisfação por parte dos clientes. A comunicação entre os funcionários responsáveis pelas reservas e os clientes também é ineficiente, levando a atrasos na confirmação das reservas, falta de disponibilidade de veículos e desentendimentos. A falta de um sistema integrado dificulta ainda mais o acesso às informações relevantes sobre as reservas, como disponibilidade de veículos, histórico de locações e preferências dos clientes, prejudicando a capacidade da empresa de fornecer um serviço personalizado e de qualidade. 

  

Potencialidades e Oportunidades de Melhoria: 

 Implementação de um sistema de reservas online para permitir que os clientes façam reservas de forma autônoma e simplificada. 

Integração do sistema de reservas com o sistema de gestão da locadora para garantir a disponibilidade em tempo real dos veículos. 

Oferecimento de opções de veículos similares automaticamente pelo sistema em caso de indisponibilidade do modelo desejado. 

 

 

 

2. Processo de Retirada do Veículo: 

 Descrição da Situação Atual (AS-IS): 

Ao analisarmos a otimização dos processos, percebemos que a retirada do veículo se destaca como um momento crucial. Atualmente, quando o cliente chega à filial no horário agendado, ele precisa informar ao atendente sobre sua intenção de retirar o veículo. O atendente, então, verifica manualmente os documentos do cliente e a disponibilidade do veículo no caderno de anotações. Após a confirmação, o cliente é solicitado a assinar os termos de consentimento e contrato de locação. Por fim, um funcionário conduz o cliente até o veículo e entrega as chaves. 

  

Potencialidades e Oportunidades de Melhoria: 

 Implementação de um sistema de check-in digital para agilizar o processo de retirada. 

Realizar a verificação dos documentos e assinatura de contrato digitalmente, proporcionando maior mobilidade e eficiência. 

Introdução de um sistema de inspeção digital do veículo antes da retirada para documentar possíveis danos e evitar disputas no momento da devolução. 

 

3. Processo de Devolução do Veículo: 

 Descrição da Situação Atual (AS-IS): 

Este processo também se destaca no contexto de locação como uma etapa fundamental e que necessita de determinados cuidados. Atualmente, quando o cliente retorna o veículo na filial, ele entrega as chaves a um funcionário. Esse funcionário, então, verifica manualmente o estado do veículo, procurando por danos visíveis e verificando o nível de combustível. Se o veículo estiver em boas condições, o cliente é encaminhado ao guichê de pagamento. Caso contrário, o funcionário registra os danos e encaminha o cliente ao setor de análise para calcular os custos de reparo. 

Potencialidades e Oportunidades de Melhoria: 

Implementação de um sistema de check-out digital para registrar o estado do veículo de forma mais precisa e eficiente. 

 

4. Gestão da Frota de Veículos: 

 Descrição da Situação Atual (AS-IS): 

O gerenciamento e controle da frota de veículos representam um processo complexo, com múltiplas variáveis e subprocessos. As etapas essenciais são o acompanhamento do estado de conservação, histórico de manutenções (preditivas, corretivas e preventivas), revisões, limpeza e higienização, vida útil de peças e componentes como os pneus, controle de quilometragem e nível de combustível. Atualmente, essas atividades são realizadas manualmente em planilhas digitais e cadernos de anotação, sem integração com outros sistemas, sujeitas a erros e que demandam um volume considerável de retrabalho. 

 Potencialidades e Oportunidades de Melhoria: 

 Implementação de lembretes automatizados para as datas das próximas manutenções e troca de óleo. 

Estabelecimento de um sistema de controle em tempo real do estoque de veículos, permitindo um planejamento mais eficiente de limpeza, higienização e manutenção. 

 

3.2.  Modelagem dos processos aprimorados (TO-BE)  

 

1. Processo de Reserva de Veículo: 

Descrição do Processo de Aprimoramento (TO-BE): 

Após a análise da situação atual do modelo de reservas e dos problemas apresentados nos processos manuais, que podem gerar diversos erros no processo e experiência do cliente, torna-se visível a necessidade da implementação de uma aplicação web para a reserva de veículos, de modo que seja acessível e prático ao cliente. Na plataforma que será desenvolvida, o usuário poderá verificar a disponibilidade do veículo desejado, após essa verificação, poderá reservá-lo de maneira online, preenchendo seus dados e recebendo a confirmação instantânea e seu código de reserva, isso melhorará a comunicação entre a locadora e os clientes, reduzindo atrasos e desentendimentos. Caso o veículo desejado não esteja disponível, o site ofertará automaticamente veículos semelhantes ao desejado, com base nas características no automóvel, dessa forma, a frustração do cliente será reduzida e haverá aumento na taxa de conversão de reserva. 

Essas modificações serão feitas com a implementação de um banco de dados, onde será possível gerenciar e atualizar automaticamente as informações dos veículos com base em reservas confirmadas e devoluções programadas, isso garantirá a organização e eficácia da locação dos veículos, garantindo uma visão precisa dos dados e evitando reservas sobrepostas. 

 

2. Processo de Retirada do Veículo: 

Descrição do Processo de Aprimoramento (TO-BE): 

Com o intuito de otimizar o processo de retirada, haverá a implementação de um sistema de check-in online. Os clientes serão convidados a preencher um formulário em nosso site, onde fornecerão o código de reserva e seus detalhes pessoais, além de enviar seus documentos. Em retorno, receberão um arquivo PDF. Esse PDF será apresentado ao atendente no local, agilizando a liberação do veículo e eliminando a necessidade de preenchimento manual de informações. Além disso, será realizada uma inspeção prévia do veículo para registrar e rastrear qualquer dano existente, visando evitar conflitos durante a devolução. 

  

 

3. Processo de Devolução do Veículo: 

Descrição do Processo de Aprimoramento (TO-BE): 

Com a necessidade de otimizar o processo de devolução, analisando o modelo atual em funcionamento (AS-IS), ficou exposto a necessidade de implantar um processo para aprimorar o serviço de devolução (TO-BE), visando melhorar a qualidade dos serviços prestados, agilidade no processo, ganho de tempo para o cliente e para a empresa, economia operacional. 

O sistema irá verificar com base nas fotos inseridas na retirada se o veículo possui algum dano causado pelo cliente, caso haja o sistema já analisará os danos e será gerado o link de pagamento do valor da franquia do veículo, somente após o pagamento o sistema validará a devolução do veículo. 

Sendo assim o modelo TO-BE apresenta todas as formas para a devolução ser feita 100% online, o cliente apresentará um PDF gerado na locadora com a devolução do veículo autorizada, dispensando o atendente preencher qualquer formulário. 

 

 

 

4. Gestão da Frota de Veículos: 

 Descrição do Processo de Aprimoramento (TO-BE): 

Visando aprimorar o gerenciamento das frotas, com o intuito de economizar tempo, reduzir erros e facilitar a visualização, o funcionário encarregado do controle dos veículos poderá acessar uma um sistema de controle. Nele, será capaz de incluir e excluir veículos, bem como modificar os dados dos veículos já cadastrados. 

 
 

4. Projeto da arquitetura de dados da solução proposta 

4.1. Diagrama de Entidades e Relacionamentos (DER) 

Segue abaixo a modelagem do diagrama entidade-relacionamento (DER) associado ao processo de negócio que contempla as entidades e atributos associados as atividades. 

 

 

4.2. Impactos da implementação em um banco de dados NoSQL 

A adoção de um banco de dados NoSQL como parte da solução para a LocaCar traria uma série de possibilidades e impactos significativos, incluindo vantagens e desafios que precisam ser considerados cuidadosamente. 

Automatização de Processos: A implementação de um banco de dados NoSQL permitiria a automação de processos, resultando em uma eficiência operacional aprimorada para a locadora. Isso eliminaria tarefas manuais e agilizaria a execução de atividades repetitivas, como preenchimento manual de formulários e armazenamento de informações, reduzindo consideravelmente a possibilidade de erros nesses processos. 

Escalabilidade Horizontal: Uma característica fundamental dos bancos de dados NoSql é a escalabilidade horizontal, o que significa que podem lidar com um grande volume de dados distribuindo o armazenamento e processamentos em diversos servidores. Esse é um ponto positivo para a LocaCar, pois, com a possibilidade de disponibilidade de veículos e clientes crescer rapidamente, o banco de dados permitiria que o sistema escalasse rapidamente para atender as demandas crescentes sem comprometer o desempenho  

Alta Disponibilidade: Muitos sistemas NoSql são construídos para ter alta disponibilidade e tolerância a falhas, garantindo que os dados continuem acessíveis mesmo em caso de falha na rede ou no hardware. Para a LocaCar, a disponibilidade contínua do sistema é essencial, pois em caso de problemas na rede, os clientes poderão continuar utilizando de nosso sistema de reserva, devolução e retirada sem interrupções. 

Curva de Aprendizagem: Um dos desafios a serem considerados na transição do processo manual para a implementação de uma nova tecnologia é a curva de aprendizado. Essa mudança implica que a equipe de alguns setores seja treinada e capacitada para o novo sistema, exigindo tempo e investimento em recursos para garantir que estejam adaptados e aptos a desempenhar suas funções. Além disso, será necessário contratar novos funcionários na área de tecnologia e realocar aqueles que ocupavam cargos em processos manuais que serão substituídos. 

4.3. Modelo relacional 

Segue abaixo o mapeamento do diagrama entidade-relacionamento (DER) para o modelo relacional de banco de dados seguindo as regras de normalização. 

 

 

5. Relatórios analíticos 

 

Relatório de taxa de ocupação dos veículos 

 

Com o objetivo de suprir as necessidades informacionais dos funcionários, desenvolvemos um relatório que visa mensurar a média da taxa de ocupação mensal de todos os veículos da frota por mês. 

 

 

Quantidade de reservas por modelo no mês 

Para poder auxiliar os colaboradores da organização desenvolvemos um relatório que quantifica o número de reservas por modelo de um determinado mês, sendo assim possível observar quais os modelos mais procurados pelos clientes, para poder ajustar o valor da diária e fazer o balanceamento da frota. 

 

Média da quilometragem rodada por locação 

Para facilitar a visualização de métricas importantes referentes a utilização dos veículos da frota pelos clientes, desenvolvemos este relatório que calcula a média mensal de quilometragem por locação, para entender aspectos de desvalorização do veículo, revisões e manutenção. 

 

 

 

Média anual de retiradas por veículo 

Um relatório importante que pode auxiliar o entendimento sobre o andamento do negócio é saber a quantidade de retiradas por veículo e entender melhor a necessidade do cliente final realizando possíveis ajustes conforme necessário. 

 

 

 5.1. Associação de comandos SQL com relatórios analíticos 

Nome do Relatório Analítico 

Comando SQL-DML (SELECT) 

Taxa de ocupação de veículos mensal 

SELECT 

  CONCAT(MONTH(r.data_retirada), '/', YEAR(r.data_retirada)) AS mes_referencia, 

  FORMAT((SUM(v.disponivel) / COUNT(r.veiculo_placa)) * 100, 2, '0') AS taxa_ocupacao 

FROM reserva r 

JOIN veiculo v ON r.veiculo_placa = v.veiculo_placa 

WHERE YEAR(r.data_retirada) = YEAR(CURRENT_DATE) 

  AND MONTH(r.data_retirada) = MONTH(CURRENT_DATE) 

GROUP BY CONCAT(MONTH(r.data_retirada), '/', YEAR(r.data_retirada)) 

ORDER BY mes_referencia; 

 

 

Quantidade de reservas por modelo no mês 

 

 

SELECT modelo, COUNT(*) AS reservas_mensal FROM reserva JOIN veiculo ON placa = veiculo_id WHERE YEAR(data_reserva) = YEAR(CURRENT_DATE) AND MONTH(data_reserva) = MONTH(CURRENT_DATE) GROUP BY veiculo_modelo ORDER BY reservas_mensal DESC; 

 

Média da quilometragem rodada por locação 

 

 

SELECT data_devolucao, placa, veiculo_modelo, km_rodados, FORMAT(AVG(km_rodados), 2, '0') AS km_medio_locacao FROM devolucao JOIN veiculo ON placa = veiculo_id GROUP BY data_devolucao, placa, modelo ORDER BY data_devolucao; 

 

Média anual de retiradas por veículo 

 

 

SELECT 

  veiculo_placa, 

  YEAR(data_retirada) AS ano_retirada, 

  COUNT(*) AS retiradas_anuais 

FROM retirada 

GROUP BY veiculo_placa, ano_retirada 

ORDER BY veiculo_placa, ano_retirada; 

 

 

 

6. Indicadores de desempenho 

Indicador 

Objetivo 

Descrição 

Fórmula de cálculo 

Fontes de dados 

Perspectiva 

Taxa de Ocupação de Veículos 

Aumentar a utilização da frota de veículos 

Percentual de veículos locados em relação ao total da frota disponível 

(Soma dos Veículos Disponíveis / Soma dos Veículos Locados) * 100  

Tabela de reserva e frotas 

Financeira 

Tempo médio de retirada 

Melhorar a eficiência do processo de retirada do veículo 

Tempo médio que o cliente leva para fazer a retirada do veículo após chegar ao local 

(Hora de Chegada – Hora da Retirada) / Número de Reservas 

Sistema de registro de retirada  

Processos internos 

Percentual de Veículos devolvidos no Prazo 

Garantir a pontualidade nas devoluções  

Percentual de veículos devolvidos dentro do prazo acordado 

(Soma dos Veículos Devolvidos no Prazo / Soma dos veículos Devolvidos) * 100 

Tabela de devoluções 

Processos internos 

Taxa de ocorrência de falhas e defeitos 

Manter controle sobre a frequência de falhas e defeitos  

Número de falhas reportadas em relação ao total de veículos 

Número de falhas / Número de veículos 

Tabela de gestão de frotas  

Financeira e Clientes 

Taxa de retenção de clientes 

Aumentar a fidelidade do cliente 

Percentual de clientes que retornam para alugar veículos novamente 

(Clientes Retornados / Clientes Totais) * 100  

Tabela de clientes e histórico de reservas 

Clientes 

 

 

7. Conclusão 

O LocaCar se propõe como uma solução inovadora para o setor de locação de veículos, otimizando processos e elevando a experiência do cliente. Através da implementação das funcionalidades propostas, espera-se alcançar: 

Maior eficiência operacional, com redução de custos e erros; 

Melhoria da experiência do cliente, proporcionando agilidade, praticidade e comodidade; 

Aumento da lucratividade, através da fidelização de clientes e atração de novos. 

Tal resultado só foi possível a partir de estratégias que auxiliaram entender em detalhes os processos de negócios para então realizarmos a modelagem do processo atual e em seguida realizar uma nova modelagem com diversas melhorias, tornando o processo mais ágil e eficiente. Porém, para que seja possível obter resultados sólidos e duradouros são necessários a adesão e o uso correto do sistema por parte dos envolvidos, exigindo investimento em infraestrutura, treinamento e monitoramento constante. 

Com seu potencial transformador, o LocaCar está moldando o futuro da locação de veículos, proporcionando benefícios para todos os participantes do setor. 

 

Link do repositório do projeto na plataforma GitHub - https://github.com/ICEI-PUC-Minas-PMV-SI/LocaCar 

 

 

REFERÊNCIAS 

 

ABLA. Números do mercado Brasileiro de Locadoras de veículos. Disponível em: 

https://www.abla.com.br/noticia/faturamento-anual-do-setor-de-locacao-de-veiculos-cresceu 

Acesso em: [01/03/2024]. (1) 

 

FGV. Aumento nas locações de veículos no Brasil. Disponível em: https://portal.fgv.br/artigos/aumento-locacoes-veiculos-brasil.  

Acesso em: [01/03/2024]. (2) 

 

 

 

 
