# Projeto-BI---Venda-de-Albuns
Dashboard desenvolvido no Power BI para analisar os fatores de sucesso e a concentração de mercado dos álbuns musicais mais vendidos de todos os tempos. O objetivo é transformar dados brutos em insights estratégicos sobre a indústria fonográfica, explorando tendências temporais e a dominância de gêneros e artistas.

Link para o Projeto: https://colaboragov-my.sharepoint.com/:u:/g/personal/luisa_silva_povosindigenas_gov_br/IQAReA81M4EMRrksNocVPde6AVSagKQq1ZHB8NGrFj7q5Z8?e=r3oERt

#Principais Insights Extraídos
Concentração de Mercado (Regra de Pareto): Identifiquei que aproximadamente 29% dos artistas (11 de 38 na base geral) são responsáveis por 50% das vendas totais, evidenciando um mercado dominado por "Superstars".

Análise por Gênero: No gênero Rock, a concentração é ainda maior, onde apenas 5 artistas detêm metade do volume de vendas do gênero.

Evolução Temporal: Análise das "Eras de Ouro" da música, identificando quais décadas produziram os maiores volumes de vendas acumuladas.

Recursos Técnicos Utilizados
DAX Avançado:

Criação de medidas de inteligência (Total de Vendas, Média, Desvio Padrão).

Cálculo dinâmico de Ranking e % Acumulado para o Gráfico de Pareto.

Modelagem de Dados: Tratamento de dados CSV e organização de hierarquias (Década > Álbum).

Visualização de Dados:

Gráfico de Pareto (Colunas + Linha com eixo secundário).

Matriz com Formatação Condicional (Heatmap) para destacar os Top 3 álbuns por década.

Segmentadores de dados (Slicers) para filtragem dinâmica por Gênero, País e Ano.

Estrutura do Repositório
Relatorio_Vendas_Musica.pbix: Arquivo original do Power BI.

best_selling_albums.csv: Base de dados utilizada.

/screenshots: Imagens do dashboard em funcionamento.

Dicas para brilhar na entrevista:
O "Porquê" do Desvio Padrão: Se te perguntarem por que você calculou o desvio padrão, diga: "Eu queria entender a consistência das vendas dentro de cada gênero. Um desvio alto indica que o sucesso é disparado para poucos álbuns, enquanto um baixo indica um mercado mais equilibrado."

A Medida de Texto Dinâmica (Dica Final): Para fechar o visual, crie esta medida e coloque em um Cartão:
