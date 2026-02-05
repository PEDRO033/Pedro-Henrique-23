#O cenário: Um sistema de análise de temperaturas.
# O programa deve pedir para o usuário digitar 5 temperaturas.
# Armazene essas temperaturas em uma lista chamada leituras.
# Depois de coletar, percorra essa lista e:
# Se a temperatura for maior que 30, exiba: "Alerta: Calor excessivo!".
# Se for menor que 15, exiba: "Alerta: Frio intenso!".
# Caso contrário, exiba: "Temperatura amena".
# No final, mostre a lista completa para o usuário.
# Dica de código:
# Para adicionar itens a uma lista, use: lista.append(valor).

#leitura = [] # Criamos uma lista vazia antes de começar

# 1. Coleta os dados
# for i in range(5):
#   temp = float(input(f'Digite a {i+1} temperatura: '))
#   leitura.append(temp) # Adiciona o valor na lista
# print('----- Leitutra de temperatura -----')

# 2. Analisa os dados guardados na lista
# for it in leitura:
#   if it > 30:
#     sensação = 'Alerta: Calor excessivo!'
#   elif it < 15:
#     sensação = 'Alerta: Frio intenso!'
#   else:
#     sensação = 'Temperatura amena'
#   print(f' A temperatura {it}°C esta: {sensação}')
# print(f'\n a lista completa das leituras{leitura}')
