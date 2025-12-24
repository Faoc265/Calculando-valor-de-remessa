# Calculando-valor-de-remessa
Script Python que calcula o valor de exportações de papel. O programa recebe o peso da carga, o preço por tonelada e o tipo de cliente. Através de estruturas condicionais (if/elif), aplica descontos de 5% para clientes fidelizados ou 10% para premium. O resultado é o valor total líquido, formatado com duas casas decimais.

Exemplos de Teste:
A tabela abaixo demonstra o comportamento esperado do programa para diferentes cenários de entrada:

Peso (ton),Preço/Ton ($),Tipo de Cliente,Valor Final (Saída)
10.0,500.0,Novo cliente,**$5000.00**
8.0,600.0,Cliente fidelizado,$4560.00
12.0,400.0,Cliente premium,$4320.00
