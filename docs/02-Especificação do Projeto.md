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
|RF-001   | A homepage da aplicação deverá apresentar uma lista de itens de vestuário disponíveis, com suas respectivas imagens e descrições.                                          | ALTA       | 
|RF-002   | Na homepage, logada ou não, deverá existir filtros de busca que permitirão ao usuário filtrar os anúncios por categorias como tipo de vestuário, tamanho, cor, entre outros. | ALTA       |
|RF-003   | Usuários não registrados deverão ser capazes de visualizar os itens, mas para anunciar em anúncios a criação de uma conta ou login será requerido.                    | ALTA       |
|RF-004   | Ao criar um anúncio, o usuário deverá fornecer informações do anúncio como valor, título, descrição, localidade, foto, tamanho, tipo de vestuário, condição (novo/usado), entre outros.         | ALTA       |
|RF-005   | Cada anúncio deve mostrar claramente o nome do vendedor e dados de contato, além dos dados essenciais sobre aquele anúncio, de acordo com os informados na RF-004.                                                          | ALTA       |
|RF-006   | O usuário logado deverá ter um painel pessoal onde poderá visualizar seus anúncios ativos.                                  | MÉDIA      |
|RF-007   | O usuário logado deverá ter um painel pessoal onde poderá criar anúncios.                                  | MÉDIA      |
|RF-008   | O usuário logado deverá ter um painel pessoal onde poderá gerenciar seus dados de perfil.                                  | MÉDIA      |
|RF-009   | No painel pessoal, o usuário deve ter a opção de marcar um item como vendido, o que irá mover o anúncio da lista principal para uma lista específica de vendidos.          | ALTA       |
|RF-010   | Ao visualizar um anúncio, o sistema apresentará sugestões de peças para o usuário advindas de anúncios pagos por empresas, baseando-se em categorias semelhantes.          | BAIXA      |
|RF-011   | Os anúncios permitirão que usuários interajam por meio de comentários para que tirem dúvidas ou apenas expressem opiniões sobre as peças.                                  | BAIXA      |

### Requisitos não Funcionais

|ID        | Descrição do Requisito                                                                                                                                                    | Prioridade |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
|RNF-001   | O sistema deve ser responsivo para rodar em variados dispositivos.                                                                                                        | ALTA       | 
|RNF-002   | Garantir a privacidade e segurança dos dados dos usuários.                                                                                                                | ALTA       |
|RNF-003   | Deve processar requisições do usuário em no máximo 2s.                                                                                                                    | BAIXA      |
|RNF-004   | Fornecer uma interface amigável e intuitiva.                                                                                                                              | MÉDIA      |
|RNF-005   | Facilitar a integração com futuras atualizações.                                                                                                                          | BAIXA      |
|RNF-006   | O sistema deverá fornecer feedbacks de ações para o usuário, como confirmações ou erros durante a interação.                                                              | MÉDIA      |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                                                                                                                                                                      |
|--|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre.                                                                                                                                         |
|02| Deverá ser desenvolvido um módulo de backend e frontend.                                                                                                                                       |
|03| Não será possível realizar transações financeiras na plataforma.                                                                                                                               |

## Diagrama de Casos de Uso

![Diagrama de Uso - Outra Chance](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e2-proj-int-t11-pmv-ads-2023-2-e2-proj-int-t11-grupo3/assets/75391453/638a32ba-53c4-40b6-b166-3d0b62e94a96)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
