Digital Innovation One
Código criado para utilização junto a plataforma da Digital Innovation One



Desafio GCP Dataproc
O desafio faz parte do curso na plataforma da Digital Innovation One:

Criando um ecossitema Hadoop totalmente gerenciado com Google Cloud Platform

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento irá efetuar a contagem das palavras de um livro e informar quantas vezes cada palavra aparece no mesmo.

Etapas do Desafio
Criar um bucket no Cloud Storage
Atualizar o arquivo contador.py com o nome do Bucket criado nas linhas que contém {SEU_BUCKET}.
Fazer o upload dos arquivos contador.py e livro.txt para o bucket criado (instruções abaixo)
https://cloud.google.com/storage/docs/uploading-objects
Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando gs://{SEU_BUCKET}/contador.py
O Job irá gerar uma pasta no bucket chamada resultado. Dentro dessa pasta o arquivo part-00000 irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.
