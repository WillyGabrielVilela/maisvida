<h1 align="center">
  MaisVida - Gerenciamento de pacientes para nutricionistas
</h1>

<img src="gifgithub/gifmaisvida.gif"

## Aplicação
Aplicação que consiste em um gerenciamento de pacientes para nutricionistas, podendo cadastrar pacientes cadastrar informações e metricas de saúde indicar planos alimentares.

## Tecnologias e práticas utilizadas
- Python 
- Django 
- SQLite
- Templates(Front-end): HTML, CSS e Javascript
- Arquitetura MVC Model View Controller

## Funcionalidades
- Cadastro dos nutricionistas
- Login dos nutricionistas
- Envio de e-mail para confirmar cadastro
# Dentro da plataforma:
- Cadastro de pacientes com informações:
 Sexo, idade, email e telefone
- Adição de metricas dos pacientes:
peso, altura, percentual de gordura, percentual de musculos, indeces de colesterol e trigliceridios
- Adição de refeições para cada paciente indicando o que comer em cada refeição assim como hora e uma imagem ilustrativa
- Acompanhamento do progresso do paciente por meio de um grafico

## Vantagens das Tecnologias
# Python com Django:
- Facil aprendizado e adoção no projeto
- Django é um framework que facilita bastante a implementação
- Area administrativa completa
- Facilidade em trocar o banco, com apenas algumas alterações é possivel fazer a portabilidade
- Não ter Node_Modules :)
# Banco de dados: SQLite
Facilidade na implementação

## Desvantagens das Tecnologias
- Python por ser de tipagem dinamica pode ocorrer alguns problemas que será dificil identificar
- Django é mais pesado e menos performatico que outros frameworks, como por exemplo Flask
- SQLite, não é tão recomendado para ambientes de produção, bancos como PostgreSQL são mais recomendados por serem mais robustos

## Comandos

python manage.py runserver
