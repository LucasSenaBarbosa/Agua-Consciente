# ÁguaConsciente

Aplicação web educacional para estimar parte do consumo de água de uma casa e ajudar seus moradores a identificar oportunidades de economia. A calculadora compara o consumo estimado por pessoa com uma referência nacional e deixa explícito que não contabiliza todos os usos de água.

## Funcionalidades

- Estimativa diária e mensal do consumo informado para a casa.
- Estimativa de consumo diário por pessoa, calculada com o número de moradores.
- Comparação por pessoa com a referência de 151 L por dia, atribuída ao SNIS.
- Classificação por pessoa: consciente até 150 L/dia, moderado até 250 L/dia e elevado acima de 250 L/dia.
- Distribuição do consumo estimado por atividade e recomendações personalizadas.
- Estimativa de custo mensal e opção de copiar o resultado.

## Usos considerados

A calculadora estima seis categorias: banho, torneira aberta, descarga, máquina de lavar roupa, lavagem de carro com mangueira e rega de jardim ou quintal.

O resultado é parcial. Cozinha, água para beber, limpeza da casa e outros usos não são contabilizados; por isso, o consumo real pode ser maior do que o estimado. Os valores informados para as atividades devem representar a rotina total da casa, não a rotina de apenas um morador.

## Como as estimativas são calculadas

- Consumo diário da casa: soma dos seis usos considerados.
- Consumo diário por pessoa: consumo diário da casa dividido pelo número de moradores informado.
- Consumo mensal: consumo diário da casa multiplicado por 30.
- Custo mensal: consumo mensal convertido para metros cúbicos e multiplicado pela tarifa estimada de R$ 5,00/m³.
- Roupas: cada carga semanal é convertida em uma média diária.
- Carro: cada lavagem mensal é convertida em uma média diária.

A tarifa é apenas uma estimativa e pode diferir da cobrança da concessionária. A referência de 151 L/dia por pessoa é apresentada como média nacional do SNIS; ela serve para comparação, não como medição do consumo completo da residência.

## Tecnologias

- HTML5
- CSS3
- JavaScript, sem dependências externas

## Como executar

Abra `index.html` em um navegador. Não é necessário instalar dependências nem iniciar um servidor.

## Equipe

- Gustavo Cardoso
- Gustavo Wacker
- João Caldas


