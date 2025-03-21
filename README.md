# Odontogenda-IA: Análise de Demanda por Horário em Consultas Odontológicas

## Descrição Geral

Este projeto desenvolve uma aplicação para análise de demanda por horários de consulta odontológica, focando na otimização da alocação de recursos e agendamento. O sistema agora inclui um componente de recomendação inteligente de horários, aprimorando a gestão de agendamentos e a experiência dos pacientes.

## Objetivos Específicos

- Identificar os horários de maior demanda para consultas odontológicas.
- Analisar padrões de agendamento por dia da semana e especialidade.
- Implementar um sistema de recomendação de horários baseado nos dados históricos.

## Frameworks, Bibliotecas e Ferramentas Utilizadas

- SQLite3: Banco de dados para armazenamento de informações das consultas.
- Pandas: Manipulação e análise de dados.
- Matplotlib: Visualização gráfica dos dados.

## Funcionamento dos Recursos/Ferramentas na Aplicação

1. SQLite3: Armazena dados das consultas, permitindo consultas rápidas.
2. Pandas: Realiza leitura e análise dos dados do banco SQLite.
3. Matplotlib: Exibe graficamente os horários de pico de demanda.
4. Sistema de Recomendação: Sugere horários menos ocupados com base no histórico.

## Uso de Machine Learning / IA

O projeto agora inclui um sistema de recomendação simples, que analisa os padrões históricos de agendamento para sugerir horários menos ocupados. Esta implementação prepara o terreno para futuras aplicações mais avançadas de Machine Learning, como:

- Modelos de previsão de demanda para identificar futuros horários de maior procura.
- Algoritmos de aprendizado supervisionado para prever o volume de consultas.

## Estrutura do Projeto

- `consultas.db`: Banco de dados SQLite com a tabela de consultas.
- Scripts Python:
- Configuração do banco de dados
- Inserção de dados fictícios
- Análise de demanda por horário
- Visualização gráfica dos horários de pico
- Sistema de recomendação de horários
- Gráficos: Visualizações dos horários mais demandados.

## Nova Funcionalidade: Sistema de Recomendação de Horários

O sistema de recomendação implementado oferece sugestões de horários menos ocupados com base no dia da semana e na especialidade desejada. Funcionalidades:

- Filtra consultas por dia da semana e especialidade.
- Analisa a frequência de agendamentos em cada horário.
- Recomenda os três horários menos ocupados, promovendo uma distribuição mais equilibrada das consultas.

Este recurso auxilia na otimização do agendamento, reduzindo a concentração em horários de pico e melhorando a eficiência operacional da clínica.

## Próximos Passos

- Integração com interface de usuário para fácil visualização das recomendações.
- Implementação de modelos preditivos mais avançados.
- Análise de fatores adicionais que influenciam a demanda por horários.
