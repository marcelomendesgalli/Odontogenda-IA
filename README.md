# Odontogenda-IA
Odontogenda: Análise de Demanda por Horário em Consultas Odontológicas
Descrição Geral

Este projeto tem como objetivo desenvolver uma aplicação que possibilite a análise de demanda por horários de consulta, com foco na otimização da alocação de recursos e agendamento. Diferente da proposta inicial, que focava na análise de faixa etária dos pacientes, esta etapa do projeto se concentra na identificação dos horários com maior demanda. Essa nova abordagem permite uma análise mais direta dos picos de uso, contribuindo para melhorias no gerenciamento de horários e na experiência dos pacientes.

Objetivos Específicos

1. Diferença Entre a Etapa Atual e a Primeira Entrega

Na primeira entrega, a proposta era realizar uma análise com base na faixa etária dos pacientes e analisar qual delas possuei a maior tendência de cancelamento. Essa abordagem foi revista para atender melhor à demanda da aplicação e aos interesses dos usuários. Agora, o foco está nos horários mais procurados durante a semana, o que permite identificar diretamente os horários de pico e adaptar a gestão da clínica conforme essas demandas.

2. Frameworks, Bibliotecas e Ferramentas Utilizadas

SQLite3: Utilizado como banco de dados embutido para armazenar informações das consultas (paciente, especialidade, dia da semana, horário e data).

Pandas: Biblioteca utilizada para manipulação e análise de dados, permitindo operações como agrupamentos e contagem, essenciais para identificar os horários de maior demanda.

Matplotlib: Utilizada para visualização gráfica dos dados, o que ajuda a entender os horários de pico de maneira visual.

3. Funcionamento dos Recursos/Ferramentas na Aplicação

SQLite3: Armazena todos os dados das consultas, permitindo consultas e filtragens rápidas diretamente no banco de dados. Pandas: Realiza a leitura do banco de dados SQLite para um DataFrame, facilitando as operações de análise. Com o Pandas, agrupamos e ordenamos os dados por horário para identificar períodos de maior uso. Matplotlib: Exibe graficamente os dados dos horários de pico, melhorando a visualização e permitindo insights visuais sobre a demanda.

4. Uso de Machine Learning / IA

Nesta etapa do projeto, a coleta e estruturação de dados preparam o terreno para futuras aplicações de Machine Learning. Com o histórico de horários e demanda, é possível:

Aplicar modelos de previsão de demanda para identificar horários futuros de maior procura.

Utilizar algoritmos de aprendizado supervisionado para prever o volume de consultas com base no histórico, auxiliando na tomada de decisões para alocação de recursos.

Estrutura do Projeto

Banco de Dados (consultas.db): Contém a tabela consultas, que armazena os dados das consultas. Scripts: Scripts em Python que configuram o banco de dados, inserem dados fictícios, realizam consultas para análise e exibem gráficos de horários de pico. Gráficos: Visualização dos horários mais demandados, gerados com Matplotlib.

Integrantes

Erick Lopes Silva - RM 553927

Gabriel Sá Bragança - RM 554064
