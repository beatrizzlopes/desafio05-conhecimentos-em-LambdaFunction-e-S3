# desafio05-conhecimentos-em-LambdaFunction-e-S3

# Introdução

Este repositório possui: desafio consolidar seus conhecimentos em tarefas automatizadas com Lambda Function e S3, minhas anotações e insights adquiridos durante as aulas e o desafio do bootcamp Santander Code Girls com a DIO, focado em computação em nuvem com AWS.

# Explicação do desafio

Repositório organizado contendo anotações e insights adquiridos durante a prática.

# Material presente no repositório

README.md: Explicação de qual é o desafio, anotações e insights adquiridos durante as aulas e o desafio.

anotações extras: Contém anotações.

# Anotações

###### Amazon S3

O Amazon S3 (Simple Storage Service) é um serviço de armazenamento de objetos na nuvem da AWS. Ele permite guardar arquivos de qualquer tipo (imagens, vídeos, documentos, backups, logs) de forma segura, escalável e durável.

Características:

- Serviço de armazenamento de objetos.

- Pode armazenar arquivos como imagens, vídeos, logs, documentos, etc.

- Suporta eventos (ex.: upload de arquivo, exclusão) que podem disparar ações automaticamente.


###### AWS Lambda

O AWS Lambda é um serviço de computação serverless da Amazon. Ele permite que você execute código sem precisar gerenciar servidores. Ou seja, você só precisa escrever a função e o Lambda cuida do resto: provisionamento, escalabilidade e execução.

Características: 

- Serviço de computação serverless: você roda código sem gerenciar servidores.

- Executa funções em resposta a eventos.

- Pode ser usado para processar dados, enviar notificações, integrar sistemas, etc.

###### Como funciona a automação S3 + Lambda

1. Um evento acontece no S3, como:

Um novo arquivo é enviado.

Um arquivo é deletado.

2. Esse evento dispara uma função Lambda, que pode:

Redimensionar imagens automaticamente

Converter arquivos de formato (ex.: PNG para JPG)

Processar logs e enviar dados para banco

Notificar usuários via SNS ou e-mail







# Insights

# Autora

Beatriz Lopes

# Referência

https://web.dio.me/track/santander-code-girls-2025
