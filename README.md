# Analise de dados de manuteção preditiva em compressor de ar

Este conjunto de dados foi preparado com medições feitas no sistema de compressores que alimenta a linha de ar de uma fábrica. O mesmo dataset foi retirado do kaggle.com e está presente no seguinte link abaixo:

https://www.kaggle.com/datasets/afumetto/predictive-maintenance-dataset-air-compressor?select=maintenance.py

**Introdução**
Este repositório apresenta uma análise detalhada de dados relacionados à manutenção de compressores de ar, realizada utilizando a linguagem de programação Python e bibliotecas populares de análise de dados. O conjunto de dados abrange diversas métricas, incluindo potência do motor, rotações por minuto (RPM), pressão de saída, temperatura, entre outras. Porém o conjunto de carece de informações temporais o que seria de muita importância para maiores conclusões.

**Objetivos**
O objetivo principal desta análise é aprofundar meu conhecimento extrair insights valiosos sobre o desempenho dos compressores de ar, identificar padrões e tendências, e, finalmente, construir modelos de classificação para prever possíveis falhas nas máquinas.
Reforço que nesse projeto também tive foco em descrever claramente o passo a passo e as conclusões obtidas para que até mesmo uma pessoas que não tenha domínio do assunto consiga ter o entendimento. 

**Conteúdo do Repositório**

*Exploração de Dados (EDA):*

- Verificação dos tipos de dados.

*Desempenho do Motor:*

- Distribuição da potência do motor.
- Correlação entre RPM e potência do motor.

*Condição da Água de Refrigeração:*

- Variação das temperaturas de entrada e saída da água.
- Relação entre fluxo de água e temperatura.

*Acelerações:*

- Análise das acelerações do solo e da cabeça.

*Componentes Específicos:*

- Avaliação do impacto de componentes como bomba de refrigeração, radiador, válvula de alívio e motor AC no desempenho geral.
- Indentificação de falhas
  
*Modelo de Classificação:*

- Treinamento de modelos de classificação para prever falhas nas colunas 'bearing' e 'wpump'.

*Avaliação do Modelo:*

- Avaliação detalhada do desempenho dos modelos, incluindo métricas de precisão, revocação, F1-score e matriz de confusão.

*Conclusão*

Esta análise proporciona uma compreensão abrangente do desempenho dos compressores de ar, destacando áreas críticas e fornecendo modelos de classificação para identificar possíveis falhas. Este repositório é uma ferramenta valiosa para engenheiros de manutenção e analistas que buscam insights sobre a saúde e eficiência dos compressores de ar em seus ambientes operacionais.


-------------------------------------------------------------------------------------------------------------------
# Informações do DataSet

Colunas identificadas:

* id = indentificação única
* rpm = Rotações por minuto
* motor_power = Potência do motor (W)
* torque = Força 
* outlet_pressure_bar = Pressão de saída (bar)
* air_flow = fluxo de ar (L/Min ou Pés)
* noise_db = ruído
* outlet_temp = Temperatura de saída
* wpump_outlet_press = Pressão de Saida (bomba do sist de refrigeração)
* water_inlet_temp = Temperatura de entrada de água
* water_outlet_temp = Temperatura de saída de água
* wpump_power = Potência da bomba de água do sist. de *refrigeração
* water_flow = Fluxo de água
* oilpump_power = Potência da Bomba de Óleo
* oil_tank_temp =  Temperatura do Tanque de óleo
* gaccx = Aceleração do solo (m/s²)
* gaccy = Aceleração do solo  (m/s²)
* gaccz = Aceleração do solo (m/s²)
* haccx = Aceleração da cabeça (m/s²)
* haccy = Aceleração da cabeça (m/s²)
* haccz = Aceleração da cabeça (m/s²)
* bearings = Rolamentos
* wpump = Bomba de refrigeração
* radiator = Radiador
* exvalve = Valvula de alívio
* acmotor = Motor AC

# Exemplos dos equipamentos:

![R](https://github.com/perigor/AnalisePreditiva-ManutencaoCompressor/assets/133716998/d6c57680-19f8-42f4-8614-cca510be7e9e)
