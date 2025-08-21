Desafio de projeto Microsoft Azure - DIO

Resumo: SLA e Zonas de Disponibilidade no Azure
O SLA (Service Level Agreement) é o acordo de nível de serviço que define a disponibilidade mínima garantida de um serviço de nuvem. Ele é geralmente expresso em percentuais, como 99%, 99,9% ou 99,99% — conhecidos como “quantidade de noves”. Quanto mais “noves”, menos tempo de inatividade o serviço terá.
Exemplo rápido:
99% → até ~7h de indisponibilidade por mês. <br>
99,9% → até ~43min de indisponibilidade por mês. <br>
99,99% → até ~4min de indisponibilidade por mês. <br>

As zonas de disponibilidade (Availability Zones) são regiões físicas separadas dentro de um mesmo datacenter que permitem redundância. Ao distribuir recursos entre essas zonas, é possível minimizar falhas e aumentar a confiabilidade, o que influencia diretamente o SLA, já que serviços distribuídos têm menos risco de ficar indisponíveis.

Em resumo:
SLA indica o quanto você pode confiar que o serviço estará disponível, e usar zonas de disponibilidade ajuda a atingir ou melhorar esse SLA.
