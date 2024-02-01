# Projeto Data Expert
Seja bem vindo ao meu projeto de análise de dados e inteligência de negócios, a famosa “Business Intelligence”. 
Este projeto foi pensado e desenvolvido durante a formação “Data Expert”, oferecida pelo maior ecossistemas dos dados, a corporação Experiun.

Nessa experiência prática, busquei aprimorar as minhas habilidades nas principais ferramentas para análise de dados, além de conhecimentos em Business, pensamento analítico e as soft-skills (habilidades interpessoais). 

Nele será possível compreender como funciona de ponta a ponta a execução de uma análise de negócios, para a tomada de decisões. Além da criação de um deshboard que realmente é utilizado e ajuda nas empresas.

Posto isto, o meu “Know-How” (conhecimento técnico de ferramenta, conhecimento de conceitos e experiência prática) foram aperfeiçoados durante essa jornada.

![photo-1608222351212-18fe0ec7b13b](https://github.com/mariacdev/Projeto-Data-Expert/assets/134116444/adb2484d-c268-4bda-8007-902531fd463c)

O mundo empresarial vive em constante evolução. Os empresários já estão cientes sobre a importância de analisar seus dados para obter sucesso em seus negócios. O case resolvido ao decorrer da formação foi do setor comercial do segmento de moda, a requisição veio através do Diretor Comercial, da Pinski Modas.

**Que trouxe os seguintes desafios:** acompanhamento de metas da equipe de vendas e performance de produtos. 
Alguns detalhes do cenário em que vivem hoje trazidos nesse primeiro contato foi de que hoje eles têm diversos relatórios espalhados em Excel, o que dificulta a análise e muitas vezes vem com erros ou demora muito para serem entregues. 

Gostaríamos de levar eles para um nível mais avançado e com dados em tempo real pra agilizar e melhorar nossas análises. 

### 1. Briefing
O Diretor Comercial da Pinski Modas entrou em contato relatando dificuldades em conseguir ter mais previsibilidade dos resultados do time comercial e medir a performance de vendas dos produtos.

Durante o Data Expert tiveos como grande Missão construir uma Solução que ajude o Diretor Comercial a se antecipar aos resultados do seu time, contribuindo para que a equipe alcance a meta e além disso gere insights de como melhorar os resultados da Pinski Modas em todas as regiões.

#### 1.1. Briefing Geral:
- Empresa do segmento de Moda
- B2B (Vende somente para Empresa)
- Funcionários: 35 pessoas
- Área de atenção do Projeto: Comercial
- Quem entrou em contato: Diretor Comercial

#### 1.2. Relato do Cliente: 
Hoje temos diversos relatórios espalhados em Excel, o que dificulta a análise e muitas vezes vem com erros ou demora muito para serem entregues. Gostaríamos de levar eles para um nível mais avançado e com dados em tempo real para agilizar e melhorar nossas análises. 

### 2. Workflow do projeto:
O Workflow utilizado no projeto foi baseado na Metodologia ESI (Entendimento, Solução e Implantação) 

![Metodologia ESI](https://github.com/mariacdev/Projeto-Data-Expert/assets/134116444/5e823a39-3b5e-4c90-8a6d-1893efe1b89d) 


### 2.1. Entendimento: 

#### 2.1.1. Entendimento do negócio:
Aqui, o foco é compreender profundamente o negócio do cliente. Isso envolve pesquisas, entrevistas e análises de documentos. 
O objetivo é identificar os desafios e necessidades do cliente, criando uma base sólida para as etapas subsequentes.

- Análise de informações gerais
- Reunião de Diagnóstico
- Análise de Documentos do Cliente

#### 2.1.2. Entendimento dos Requisitos:
O primeiro passo para você planejar uma solução de BI, após entender o negócio, é identificar as dores e necessidades atuais dos usuários (tomadores de decisão). Sua solução tem como objetivo resolver essas dores.
O mais importante aqui é identificar as dores que o cliente possui, para que você possa resolver esses problemas através da sua solução.

- Identificação dos Desafios e Desejos
- Definição dos Requisitos Funcionais

Entendendo o negócio e as dores/necessidades do projeto, é preciso agora definir os requisitos funcionais da solução, ou seja, o que de fato ela precisa responder para que funcione corretamente.

- Faça perguntas que ajudem o cliente a explicar quais eventos ele deseja acompanhar e como ele quer analisar:
  
O que aconteceu? (What)

Como aconteceu? (How)

Onde aconteceu? (Where)

Quando aconteceu? (When)

Quem fez? (Who)
    
#### 2.1.3. Entendimento dos Dados

Chegou a hora de entender os dados e definir os requisitos técnicos e os não funcionais para que seja possível implementar os requisitos funcionais descritos anteriormente. O grande objetivo é mapear as fontes de dados e definir como a solução deve ser comportar em relação à governança, segurança, disponibilidade, manutenção, etc.

#### 2.1.4. Mapa de Requisitos BUS MATRIX

- Importante para documentar e comunicar a arquitetura do negócio, o que nos permite também definir o modelo de dados do Data Warehouse

![busmatrix](https://github.com/mariacdev/Projeto-Data-Expert/assets/134116444/14bc0478-1cdd-4432-919c-324074c01d73) 

Após o entendimento dos dados, uma ferramenta valiosa que pode ser utilizada para otimizar o processo de mapeamento de requisitos é a Bus Matrix. A Bus Matrix é uma matriz que relaciona os processos de negócios com os dados, ajudando a identificar as interações e dependências entre eles, o que nos permite também definir o modelo de dados do Data Warehouse. Com ela temos clareza absoluta sobre quais tabelas Fato e quais tabelas Dimensão precisaremos tem em um nosso DW, e como elas se cruzam.

A Bus Matrix é frequentemente referida na literatura como uma ferramenta para mapear requisitos funcionais. No entanto, é importante notar que, embora a matriz se concentre nos requisitos funcionais, ter uma compreensão clara dos dados disponíveis é crucial para sua eficácia. Sem essa compreensão, a matriz pode se tornar intangível e menos útil.

- ***Fatos (Processos de Negócios):** Nas linhas, liste os principais indicadores ou eventos do negócio que você identificou nas conversas iniciais.*
- ***Dimensões (Atributos):** Nas colunas, coloque as informações descritivas ou categorias relacionadas aos fatos.*
- ***Marque as Conexões:** Para cada combinação de fato e dimensão, marque se eles estão relacionados. Use símbolos ou cores para isso.*

*Pense na Bus Matrix como um mapa visual que mostra como os indicadores (fatos) se relacionam com as informações descritivas (dimensões). Ela ajuda a ver onde pode haver falhas ou sobreposições no seu projeto. Usar essa matriz torna o processo de planejamento mais claro e organizado.*

*A Bus Matrix está dentro da nossa Matriz Semântica, que é o documento que acompanha todo o desenvolvimento do projeto - do início até a entrega.*

#### 2.1.5. Canvas 

O Canvas do Mapa de Requisitos é uma ferramenta visual inspirada no Business Model Canvas. Ele proporciona uma visão consolidada dos principais pontos de um projeto em um único documento, garantindo que todos os aspectos cruciais sejam contemplados desde o início. Com ele, você pode visualizar:

- Canvas - Ferramenta visual inspirada no Business Model Canvas
- Proporciona clareza ao projeto, consolidando os principais pontos em um único documento
- Assegura que todos os aspectos cruciais do projeto sejam contemplados desde o começo

![Mapa de Requisitos preenchido](https://github.com/mariacdev/Projeto-Data-Expert/assets/134116444/44e6aceb-8b90-4c8e-9fce-2551d4384afe)

- Objetivos do Projeto: O que se espera alcançar.
- Fontes de Dados: De onde os dados serão extraídos.
- Meta: O alvo ou padrão a ser alcançado.
- Indicadores e Métricas: Medidas quantitativas para avaliar o progresso.
- Análises: Exames detalhados dos dados.
- Stakeholders: Partes interessadas no projeto.
- Informações de Usabilidade: Detalhes sobre como o projeto será usado.

### 3. Solução
Com base no entendimento adquirido, esta fase é dedicada ao desenvolvimento da solução. Aqui, vamos definir a arquitetura de BI, escolher as ferramentas e tecnologias adequadas para realizar os processos de ETL, cálculo e criação dos Dashboards. 


![pilares do power bi](https://github.com/mariacdev/Projeto-Data-Expert/assets/134116444/9cfcb3d4-4b0d-4c52-8630-ebf562e9acae)


#### 3.1. Premissas de negócio
A base de dados  foi disponibilizada pela equipe da formação, mas trazendo para nosso cenário foi programado um job junto a equipe de TI, onde todos os dias é feito o processo de extração do servidor do cliente para o meu ambiente, enviando as tabelas e colunas que preciso para fazer as transformações.

 **Base de dados:** PinskDatabase

Os atributos do conjunto de dados são: 

**Tabela Vendas**
| Atributos  | Descrição |
| --- | --- |
| nfe | Nota fiscal |
| data | Data da venda | 
| vendedor_id | Identificação do Vendedor |
| cliente_id  | Identificação do Cliente  |
| produto_id  | Identificação do Produto  |
| valor_desconto | Desconto da Venda      |
| item_quantidade | Quantidade Vendida    |
| valor_unitario  | Valor Unitário dos Produtos |

**Tabela Metas**
| Atributos  | Descrição |
| --- | --- |
| categoria_id | Identificação da Categoria |
| data | Data dos dias Úteis do Ano |
| vendedor_id | Identificação do Vendedor |
| valor | Valor das Metas |

**Tabela Vendedor** 
| Atributos  | Descrição |
| --- | --- |
| id | Identificação do Vendedor |
| descricao | Nome do Vendedor |
| supervisor_id | Identificação do Superfisor | 
| supervisor_descricao | Nome do Supervisor |
| gerente_id | Identificação do Gerente |
| descricao_gerente | Nome do Gerente | 

**Tabela Produto**
| Atributos  | Descrição |
| --- | --- |
| id | Identificação do Produto |
| descricao | Nome do Produto |
| tamanho | Numeração do Produto |
| custoUnitario | Valor Unitário do Produto |
| categoria_id | Identificação da Categoria |
| categoria_descricao | Nome da Categoria |

**Tabela Cliente** 
| Atributos  | Descrição |
| --- | --- |
| id | Identificação do Cliente |
| descricao | Nome do Cliente |
| cidade_id | Identificação da Cidade | 
| cidade | Nome da Cidade |
| estado | Nome do Estado | 
| uf | Cigla do Estado |
| regiao | Identificação da Região |


O processo de extração e transformação, finaliza  após a limpeza no SQL Sever com as seguintes tabelas  e colunas:

**Confira o código das consultas no GitHub:**

MODELAGEM
Uma tabela a ser adicionada nesse primeiro momento é a dCalendario.

**Tabela Calendário**  
| Atributos  | Descrição |
| --- | --- |
| data | Dias do Anos |
| ano | Anos 2021 a 2023 |
| NomeMes | Nome do Mês |
| MesAbre | Mês Abreviado |
| MesAno | Mês e Ano | 
| MesNum | Mês por Número |
| AnoMesINT | Mês Inteiro | 
| InicioMes | Início do Mês |
| Trimestre | Trimestres do Ano |
| TrimestreAbreviado | Trimestres Abreviado| 
| Bimestre | Bimestres do Ano |
| Semestre | Semestres do Ano |
| Semana | Semanas do Mês |
| DiaSemana | Dia da Semana |
| NomeDia | Nome do Dia | 
| Passado | Passsado | 
| AnoAtual | Ano Atual | 
| MesAtual | Mês Atual | 

#### 3.1.2. Planejamento da solução

#### 3.1.3. Produto final

- Entregar Insights para a área comercial
- Dashboard para visualização dos dados

#### 3.1.4. Ferramentas

- SQL Server (Extração e Transformação)
- Excel (Planilhas)
- Power BI (Modelagem, Calculos e Modelagem)

### 4. Análise Comercial 
Dashboard para acompanhar as principais KIP's da área de comercial.


Acesse o Dashboard: 

#### 4.1. Os Principais Indicadores Visualizados:








  















