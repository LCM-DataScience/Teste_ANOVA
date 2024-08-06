Como a análise de variância pode ajudar a entender melhor as diferenças entre setores comerciais?

Diferente do Teste T de Student, ANOVA adota como premissa que as variâncias sejam homogêneas e sejam comparados três ou mais grupos independentes, para determinar se há diferenças significativas entre eles. Ele assume que os dados seguem uma distribuição normal e que as variâncias entre os grupos são iguais (homocedasticidade) e é baseado na análise da variância, daí o nome ANOVA (Analysis Of Variance).

Se o resultado deste teste indica uma diferença significativa entre os grupos, pode-se concluir que pelo menos um dos grupos difere dos demais. No entanto, o teste ANOVA por si só não identifica quais grupos são diferentes, sendo necessário realizar testes 'post hoc' para essa finalidade.

Neste exemplo, usando a biblioteca Yahoo Finance, foi criada uma análise utilizando dados de Dividend Yield (DY) de diferentes setores do IBOV. A análise ANOVA foi utilizada para verificar se as médias de DY diferem significativamente entre os setores.

Após a confirmação de homocedasticidade com o teste de Levene, a ANOVA revelou diferenças significativas entre alguns setores. Posteriormente, o teste post hoc Tukey HSD identificou quais setores apresentaram as maiores diferenças.

Achei interessante notar, comparando outros exemplos de fontes de dados, como os "NaN's" influenciam negativamente os resultados. Aqui destaca-se a importância de um bom tratamento inicial dos dados que serão usados.
