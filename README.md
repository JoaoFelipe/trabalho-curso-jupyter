# Trabalho do curso Ciência de Dados com Reprodutibilidade usando Jupyter

O objetivo deste trabalho é avaliar o aproveitamento do [curso](https://raw.githubusercontent.com/opgabriel/curso-jupyter).

## Especificação

Neste trabalho, o pandas deve ser usado em um notebook Jupyter para juntar pontuações de 4 exercícios e salvar um CSV com as médias. Além disso, o notebook deve incluir a visualização de boxplots das notas e médias e deve incluir uma mágica ou widget para consultar a média de uma pessoa a partir de suas iniciais. Tudo isso deve ser feito seguindo recomendações de boas práticas.

## Instruções

1. Faça um clone deste repositório e crie um notebook Jupyter para a realização do trabalho.

   Isso pode ser feito tanto localmente, quanto em um [Binder](https://mybinder.org/v2/gh/JoaoFelipe/trabalho-curso-jupyter/HEAD).
   
   Se usar o Binder, não se esqueça de baixar o seu notebook para o envio do trabalho.

2. Utilize o `pandas` para carregar o arquivo de inscricoes e os 4 arquivos de pontuação de exercícios que estão no diretório [dados](dados), junte-os, calcule a média de cada pessoa e salve um arquivo CSV com o resultado.

   É necessário realizar limpezas nos dados para remover duplicatas (considere apenas a resposta mais antiga) e para padronizar o campo "Iniciais".

3. Exiba boxplots para as notas de cada exercício e para as médias.

   Preferencialmente todas devem estar no mesmo gráfico, com intervalo de 0 a 100. Além disso, o boxplot não deve incluir médias de pessoas que não fizeram nenhum dos exercícios.

4. Crie uma mágica ou widget para consultar a média de alguma pessoa usando suas iniciais.

   Inclua pelo menos uma célula com o uso da mágica ou widget.

5. Siga as recomendações de boas práticas aplicáveis ao trabalho.

   Não é necessário enviar para um Repositório de Acesso Aberto.
   
Todos os arquivos do trabalho devem ser enviados para avaliação, incluindo o notebook com a solução, o CSV resultando e quaisquer outros arquivos que forem pertinentes.

## Avaliação

   Os últimos 4 itens da Seção anterior serão avaliados e será atribuida uma nota de 0 a 100 para o resultado. Aqueles que ficarem com mais do que 60 serão aprovados.

