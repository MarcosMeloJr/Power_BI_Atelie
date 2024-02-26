# Projeto de Análise de Dados - Análise Ateliê de Costura
<div style="display: flex; justify-content: space-between;"> <br>
<img width="1000" alt="netflix" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/atelie-de-costura.jpg">
  
# Sobre o Projeto:
- O objetivo primário de um ateliê é produzir itens costurados, como roupas sob medida e acessórios personalizados. Com o recorrente fluxo de pedidos a proprietária do ateliê de costura Cetim Encantado me contactou para realizar uma análise dos dados adquiridos, visando obter uma visão geral do último trimestre.
  Assim, este projeto analisou o histórico de vendas do ateliê de costura no período de um trimestre, com o objetivo de avaliar o desempenho do empreendimento e identificar insights valiosos.

  
- Ressalto que, tendo em em vista a publicação do projeto, dados sensíveis não foram utilizados, foram utilizados apenas os primeiros nomes dos clientes para que não haja identificação e foram alterados os nomes de lojas compradoras. Além disso, houve a permissão da utilização dos presentes dados trimestrais pela proprietária do empreendimento.
 Todas essas ações indicam uma preocupação em garantir a privacidade e proteção dos dados pessoais, conforme exigido pela LGPD.
<br />

# Etapas do Projeto (DataOps)
- Perguntas de negócio;
- Mapeamento dos dados;
- Prototipação;
- ETL (Extração, Transformação e Carregamento);
- Descobertas e insights;
- Sugestões de decisão.

<br />

# Perguntas de Negócio
Para fornecer um quadro geral dos insights a partir dos dados fornecidos, decidimos junto com a proprietária, que deveríamos responder as seguintes perguntas:
 
- Como ficou a situação financeira da empresa nesse último trimestre?
- Qual o ticket médio dos produtos oferecidos?
- Quais os produtos mais populares?
- Quais clientes mais contribuíram para a empresa?

Após determinar quais perguntas eram importantes, recebemos os dados necessários para as análises. A partir deles conseguiríamos responder as questões previamente levantadas com a finalidade de obtermos insights valiosos que ajudariam a empresa a tomar decisões mais assertivas.


<br />

# Mapeamento dos Dados
- Os dados do trimestre se encontram em planilhas do Excel separadas por mês (Julho, Agosto e Setembro)
 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Bases%20Excel%20.png">

 
<br />
 


# Prototipação
Com as perguntas de negócio estabelecidas e após uma rápida análise dos dados disponíveis, foi feito o protótipo inicial pela ferramenta Paint. Nela decidimos como poderia ser o design e como as informações ficariam dispostas. Posteriormente fizemos o protótipo definitivo pela ferramenta Figma utilizando as cores base da empresa e a logo que nos foi fornecida.
#### Protótipo 1
 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Prot%C3%B3tipo%20Ateli%C3%AA.png">

#### Protótipo 2
  <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Prot%C3%B3tipo%202%20Ateli%C3%AA%20(1).png">

# ETL (Extração, Transformação e Carregamento)
### Preparação dos dados
- Após o recebimento das planilhas realizamos o tratamento e a formatação dos dados. Nessa fase foi corrigido erros que afetariam a precisão da análise, como nomes duplicados, produtos com nomes diferentes, valores nulos, entre outros. Além disso foram criadas mais duas tabelas dimensões tornando mais fácil a manipulação dos dados. 
Terminada essa etapa, exportamos a base de dados para a ferramenta de visualização Power BI onde começaríamos a construção dos insights, no entanto, era necessário realizar a modelagem adequada dos dados, por isso construímos os relacionamentos corretos entre as tabelas fato – dimensão.
 <img width="1000" alt="Imagem dados" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Modelagem.png">
 
 
<br />
  
<br />
 
 
  
# Dashboard Interativo
Com os dados devidamente tratados, começamos a criação de visuais com dados estatísticos pertinentes que serviriam de base para respondermos as perguntas propostas no início. Foram necessárias criar algumas medidas utilizando fórmulas DAX, além de adcionarmos um Tooltip em um dos gráficoss para trazer informações extras a respeito do cliente.

- [Clique aqui para visualizar o dashboard de maneira interativa](https://app.powerbi.com/view?r=eyJrIjoiMmM5NjBhMjUtMzkyMy00ZmVjLWI1ZWEtNDZhZWNhZmQ0NWFkIiwidCI6ImI2ZTUxYmY3LTlmNjItNDM0Ny1hYTk1LTlhYzljMjI2OTFlOCJ9)

<br />
 
![DASHBOARD](https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Dashboard%20Completo.png)





<br />
<br />


# Descobertas e Insights
<img width="1000" src="https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/Insights.png">

Terminada a construção visual e realizada acurada análise do material notou-se as seguintes percepções:
- A margem de lucro líquido representou 59% do faturamento da empresa. Uma margem de lucro líquido de 59% é relativamente alta e indica que a empresa está gerando um lucro significativo em relação ao seu faturamento. Isso pode ser considerado um sinal positivo de saúde financeira da empresa.
- O ticket médio foi de R$ 6,11. Um ticket médio baixo pode indicar que os produtos ou serviços da empresa são relativamente acessíveis ou que a empresa pode atender a um grande volume de clientes.
- O produto mais vendido foi a Xuxa representando 84% das vendas realizadas no trimestre.
- Foi identificado o Top 3 Clientes que mais contribuíram para a receita ao longo dos três meses.

 
 <br />
 
 
 
 # Recomendações ao tomador de decisão
Em seguida foram apresentadas algumas alternativas, baseadas nas análises realizadas, que pudessem melhorar as vendas no próximo trimestre:
- Melhor administração do estoque, uma vez que é conhecido os produtos mais populares. Dessa forma agilizaria o tempo de entrega e aumentaria a satisfação dos clientes.
- Possibilidade de ajuste na estratégia de marketing para aumentar a venda dos produtos menos populares;
- Utilizar estratégias de fidelização para os clientes que mais contribuíram (Top 3 Clientes) permanecerem adquirindo produtos.   Ex: Programa de pontos: Eles receberiam pontos a cada compra e trocariam por descontos, produtos gratuitos ou brindes exclusivos.   2) Acesso antecipado a lançamentos de produtos novos. 
- Implementação de um sistema de brindes ou amostras grátis para surpreender e agradar os clientes aumentando assim a preferência pela marca. Altamente recomendado para clientes esporádicos, visando fidelizá-los.


<br />

# BÔNUS - Dica de Ferramenta - Tooltip
- As dicas de ferramentas no Power BI permitem análises dentro de outras análises, conforme mostrado no vídeo abaixo.
 



https://github.com/MarcosMeloJr/Projeto-Atelie/blob/main/ToolTip%20Ateli%C3%AA.mp4
