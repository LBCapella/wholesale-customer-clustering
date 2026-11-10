# IA & Machine Learning: Atividade de Laboratório (Clustering com DBSCAN)

## Contexto da Aula

Este notebook foi desenvolvido como parte das aulas práticas de Inteligência Artificial e Machine Learning. O material aborda conceitos fundamentais de **aprendizado não supervisionado**, explorando o algoritmo de *clustering* baseado em densidade **DBSCAN** para segmentar clientes de um distribuidor atacadista e identificar clientes atípicos, usando o dataset *Wholesale Customers*.

## Atividade Desenvolvida (LAB)

A atividade proposta sob a diretriz **"IA ML Cluster - IA não supervisionada"** consistiu em um mini projeto prático, com dados escolhidos no Kaggle (diferentes para cada equipe), para experimentar e explorar um modelo de *clustering*.

### Detalhes do Projeto:

- **Equipe:** Atividade realizada em dupla - Luan Bonasorte Capella e Matheus Heimrath Barbosa.
- **Dataset Escolhido:** *Wholesale Customers Data Set* (obtido no [Kaggle](https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set), originalmente do UCI Machine Learning Repository), com os gastos anuais de 440 clientes por categoria de produto.
- **Técnica Abordada:** Implementação do **DBSCAN** para encontrar segmentos de clientes sem definir o número de grupos e separar os clientes atípicos como ruído.
- **Objetivo:** Realizar a análise exploratória, tratar a assimetria dos gastos (transformação logarítmica), padronizar os dados, escolher os parâmetros `eps` e `min_samples` com o gráfico de distância k e uma busca em grade, avaliar os grupos com métricas internas (Silhouette e Davies-Bouldin), visualizar os resultados com PCA, interpretar o perfil de compra de cada grupo, analisar os clientes atípicos, comparar os grupos com o canal do cliente (Horeca × Varejo) e estudar a sensibilidade do modelo aos parâmetros.
