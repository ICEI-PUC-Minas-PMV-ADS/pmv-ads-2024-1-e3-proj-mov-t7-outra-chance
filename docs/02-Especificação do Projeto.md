# Especificações do Projeto

O projeto Outra Chance é uma ferramenta útil para ajudar os usuários a vender e/ou comprar itens de vestuários usados, facilitando o contato entre os interessados.  

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas nas Figuras que se seguem. 

![Persona1 1](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t11-pmv-ads-2023-2-e2-proj-int-t11-grupo3/assets/126190493/2fb42323-abbf-431a-8063-b9164d401294)

![Persona2](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t11-pmv-ads-2023-2-e2-proj-int-t11-grupo3/assets/126190493/c5b9ec42-87fe-438a-8826-231d7b466c51)

![Persona3](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t11-pmv-ads-2023-2-e2-proj-int-t11-grupo3/assets/126190493/32a4b002-00e3-454c-9529-4b8dc388177a)

![Persona4](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t11-pmv-ads-2023-2-e2-proj-int-t11-grupo3/assets/126190493/2bd66e30-7559-47e4-8a3a-e88e77db135e)

![Persona5](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t11-pmv-ads-2023-2-e2-proj-int-t11-grupo3/assets/126190493/a83adb01-219e-4239-8c6a-e3022ee4e1ba)

## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários:

|EU COMO... `PERSONA`|QUERO/DESEJO ... `O QUE`                                                                    |PARA ... `POR QUE`                                                                                          |
|--------------------|--------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
|Lilian Elizei       | uma fonte de renda extra                                                                   | para ajudar nas despesas de casa                                                                           |
|Lilian Elizei       | revender roupas                                                                            | conseguir uma renda extra                                                                                  |
|Joana Marques       | revender roupas sem tomar tanto tempo                                                      | para ajudar famílias carentes                                                                              | 
|Ana Pereira         | renovar seu guarda-roupa de forma fácil e ecconômica                                       | melhorar a autoestima                                                                                      |
|Ana Pereira         | vender roupas sem usa                                                                      | desapegar de itens que não combinam mais                                                                   |
|Carla Montenegro    | aumentar o faturamento do seu brechó                                                       | adquirir novas peças para renovação do estoque                                                             |
|Carla Montenegro    | encontrar uma plataforma de venda on line de vestuário usuado                              | encontrar maneiras mais eficazes para vender suas peças                                                    |
|Lucas Oliveira      | encontrar roupas que reflitam suas personalidade, mantendo um estilo de compra sustentável | encontrar roupas que encaixem no seu orçamento, mas mantendo uma boa qualidade                             |

   
## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID       | Descrição do Requisito                                                                                                                                                     | Prioridade |
|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
|RF-001   |A tela inicial do aplicativo deve apresentar uma lista de itens de vestuário disponíveis, com suas respectivas imagens, descrições e funcionalidade de scroll infinito para melhor navegação. | ALTA       | 
|RF-002   | Na homepage, logada ou não, devem existir filtros de busca que permitam ao usuário filtrar os anúncios por categorias como tipo de vestuário, tamanho, cor, entre outros, com uma interface adaptada para telas sensíveis ao toque. | ALTA       |
|RF-003   |Usuários não registrados deverão ser capazes de visualizar os itens, mas a criação de uma conta ou login será necessária para anunciar itens. A autenticação deve ser otimizada para dispositivos móveis, com opções de login social.	| ALTA       |
|RF-004   |Ao criar um anúncio, o usuário poderá utilizar a câmera do dispositivo para tirar fotos do item e adicionar diretamente no anúncio, além de fornecer outras informações como valor, título, descrição, localidade, tamanho, tipo de vestuário, condição (novo/usado), entre outros.	 | ALTA       |
|RF-005   |Cada anúncio deve mostrar claramente o nome do vendedor, dados de contato e informações essenciais sobre o anúncio, com um design adaptado para telas menores.	 | ALTA       |
|RF-006   | O usuário logado deverá ter um painel pessoal onde poderá visualizar seus anúncios ativos, adaptado para navegação em smartphones.	| MÉDIA      |
|RF-007   | O usuário logado deverá ter um painel pessoal onde poderá criar anúncios, com interface otimizada para dispositivos móveis. | MÉDIA      |
|RF-008   |O usuário logado deverá ter um painel pessoal onde poderá gerenciar seus dados de perfil, com interface responsiva e intuitiva para dispositivos móveis. | MÉDIA      |
|RF-009   | No painel pessoal, o usuário deve ter a opção de marcar um item como vendido, o que irá mover o anúncio da lista principal para uma lista específica de vendidos, com feedback visual claro no aplicativo móvel.	| ALTA       |
|RF-010   | O aplicativo deve incluir uma tela de abertura (splash screen) com o logo e o nome do aplicativo, proporcionando uma experiência de marca agradável e profissional. | BAIXA      |
|RF-011   |O aplicativo deve utilizar o GPS do dispositivo para filtrar anúncios com base na localização do usuário, oferecendo opções mais relevantes e personalizadas | BAIXA      |

### Requisitos não Funcionais

|ID        | Descrição do Requisito                                                                                                                                                    | Prioridade |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
|RNF-001   | O aplicativo deve ser projetado com um design responsivo, assegurando compatibilidade e otimização de desempenho em uma ampla gama de dispositivos móveis e tamanhos de tela.	 | ALTA       | 
|RNF-002   | Garantir a privacidade e segurança dos dados dos usuários.                                                                                                                | ALTA       |
|RNF-003   | O aplicativo deve processar e responder a requisições do usuário em no máximo 2 segundos, mantendo um desempenho eficiente em dispositivos móveis.	| BAIXA      |
|RNF-004   | Oferecer uma interface de usuário amigável, intuitiva e adaptada para interação via toque, considerando as diretrizes de usabilidade para dispositivos móveis.	| MÉDIA      |
|RNF-005   | O design e arquitetura do aplicativo devem facilitar a integração com futuras atualizações e novas funcionalidades, mantendo a compatibilidade com versões de sistemas operacionais móveis.	| BAIXA      |
|RNF-006   | O sistema deverá fornecer feedbacks claros e imediatos de ações para o usuário, como confirmações, erros e estados de carregamento, de forma apropriada para dispositivos móveis.	| MÉDIA      |
|RNF-007   | Implementar funcionalidades que economizem dados e bateria do dispositivo, otimizando o uso de recursos do aparelho móvel.	| MÉDIA      |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                                                                                                                                                                      |
|--|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre.                                                                                                                                         |
|02| Deverá ser desenvolvido um módulo de backend e um mobile.                                                                                                                                       |
|03| Não será possível realizar transações financeiras na plataforma.                                                                                                                               |

## Diagrama de Casos de Uso

![Diagrama de Uso - Outra Chance](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t11-pmv-ads-2023-2-e2-proj-int-t11-grupo3/assets/75391453/638a32ba-53c4-40b6-b166-3d0b62e94a96)

# Matriz de Rastreabilidade

![Matriz de rastreabilidade requisitos Outra Chance](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e3-proj-mov-t7-outra-chance/assets/126190493/a09fb5bf-954e-40a3-b268-683d33236944)

# Gerenciamento de Projeto

## Gerenciamento de Tempo

O projeto levará 95 dias úteis para ser realizado, considerando o período de 02 de fevereiro a 23 de junho de 2024. Considerando 4h por dia útil trabalhadas, serão 380h no total.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

|Vr. Hora |Qtd. horas|Subtotal    |Qtd. Devs |Vr. Total    | 
|R$ 20,00 |380       |R$ 7.600,00 |4         |R$ 30.400,00 |

![Orçamento](img/02-orcamento.png)
