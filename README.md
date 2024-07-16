<h1>Chatbot Recomendação</h1>
<p><i>Trabalho realizado durante a pós-graduação de Data Science, na disciplina de Machine Learning.</i></p>
<p>O objetivo deste projeto foi criar um chatbot para ajudar os clientes de uma empresa de e-commerce fictícia a encontrar os produtos, com o intuito de recomendar o produto que resolveria o problema, sem a influencia das pesquisas/compras realizadas anteriormente.</p>

<h2>Dados</h2>
<p>Dataset utilizado foi obtido a partir do Kaggle, em que contém os produtos vendidos pela Amazon Brasil em 2023.</p>

<h2>Metodologia</h2>
<ul>
  <li>LLM - Gemini 1.5 Flash</li>
  <li>Lang Chain</li>
  <li>RAG</li>  
</ul>
<h2>Métricas de Avaliação</h2>
<p>O modelo poderá ser avaliado quanto a sua eficácia, seguindo os seguinte itens:</p>
<ul>
  <li> Usuário acessou um dos links enviados pelo chatbot</li>
  <li>Compra realizada através do links disponibilizado</li>
  <li>Reviews positivas/negativas feitas pelo usário autor da busca que realizou a compra</li>
</ul>
<h3>Observações:</h3>
<p>Foi utilizada apenas uma amostra de 10% do dataset, devido estar utilizando a plataforma do Google Colab, não foi possível processar o dataset inteiro para o treinamento.</p>
