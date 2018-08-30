# Falso-Alarme-Incêndios
Previsor que permite detetar se uma alerta de incêndio é um falso alarme com base na hora, data, local entre outras variáveis.
De momento encontra-se com 85% de accuracy, embora seja possível melhorar este valor com outros algoritmos ou adicionar/retirar variáveis.

# Descrição do Dataset
Variáveis:
- Ano: Desde 1895 até 2015
- Códigos da proteção civil: Permite relacionar ocorrências com outras variáveis. Não utilizadas aqui.
- Zona Nut / Distrito / Concelho / Freguesia / Local : Orientação geográfica
- Datas importantes como do primeiro alerta, primeria intervenção e extinção.
- Áreas ardidas : Dados sobre a tipologia do terreno ardido.
- Tipo de incêndio : Permite saber algumas especificações sobre a origem do incêndio.
- Entre outras.
São 38 no total.


# Imports Necessários:

  - numpy
  - pandas
  - sklearn
  - matplotlib
  - seaborn
  - time
  
  # Nota de Agradecimento:
  Agradeço ao projecto central de dados por este fantástico dataset.
  # Links Importantes:
  - DataSet utilizado:http://centraldedados.pt/incendios/ 
    https://github.com/centraldedados/incendios
