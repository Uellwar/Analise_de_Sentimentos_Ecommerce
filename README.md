Introdução do Projeto:

Durante minhas férias, decidi me aventurar em um novo projeto de ciência de dados: a construção de um modelo de classificação de sentimentos em comentários de reviews de e-commerce. Utilizei dados reais fornecidos pela Olist para treinar os modelos. Para resolver o problema de classificação prévia dos sentimentos nos comentários, escolhi usar a pontuação de avaliação de compra real. Assim, os comentários com notas 1 e 2 são considerados sentimentos negativos, com nota 3 é considerado neutro e os sentimentos positivos foram atribuídos aos comentários com notas 4 e 5.

Para desenvolver este projeto, segui algumas etapas importantes: Primeiro, carreguei as bibliotecas, modelos e dados necessários. Em seguida, foi realizada uma limpeza e tratamento dos dados para que eles estivessem prontos para o treinamento do modelo. Depois, apliquei a vectorização e normalização aos dados e reduzi a dimensionalidade deles, para que os modelos pudessem processá-los de forma mais eficiente. Utilizei validação cruzada para selecionar os melhores modelos e, em seguida, realizei o ajuste dos parâmetros dos modelos selecionados usando random search. Depois, avaliei os melhores modelos e os comparei com um modelo em ensemble. Por fim, escrevi um relatório detalhando os principais pontos do trabalho realizado e sugerindo melhorias futuras.


---

Conclusão do Projeto:

Após analisarmos os comentários de reviews de e-commerce com nosso projeto de classificação de sentimentos, pudemos constatar que o modelo VotingClassifier foi robusto e preciso para a solução do problema. Além disso, os resultados obtidos pelo modelo GradientBoostingClassifier foram promissores, oferecendo uma alternativa viável quando o tempo de processamento é uma questão crucial.

Embora os resultados obtidos neste projeto sejam promissores, é importante lembrar que eles foram obtidos a partir de um conjunto específico de dados e parâmetros. Portanto, é recomendado realizar testes adicionais para avaliar a generalização dos modelos em outros contextos e garantir sua eficiência. Além disso, é importante lembrar que outros modelos ou técnicas poderiam ser úteis no problema em questão. Como profissionais da área de ciência de dados, é fundamental ser críticos e buscar sempre a melhor solução para cada problema, de forma a garantir resultados precisos e confiáveis. Isso nos permite trabalhar de forma eficiente e proporcionar soluções valiosas para nossos clientes.

O link do projeto no Kaggle (onde foi desenvolvido e possui histórico de versões):
https://www.kaggle.com/code/uelitonviana/analise-sentimentos-olist

![Compração dos Modelos Finais](https://cdn.discordapp.com/attachments/1068910706314989590/1068910882693861396/nFull_metricas_teste.png)


