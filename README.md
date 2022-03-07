# Data_Mask
### Mascaramento de dados sensíveis

Quando pensamos e LGPD, pensamos logo em como mascarar dados.

Com o script aqui neste git, evidencio uma das MUITAS formas possíveis para anonimizar dados.

Tipos de dados utilizados:
  - Nome
  - CPF
  - Endereço
  - CEP
  - Telefone
  - E-mail
  - Data de Nascimento

Para Nome e Endereço, dados fakes são inseridos no ligar dos dados originais.

Para CPF e Telefone os dados foram embaralhados.

Para CEP, foram mantidos os 5 primeiros dígitos e os 3 últimos substituídos por 0.

Para Data de Nascimento, dia e mês foram substituídos por 01 e o ano mantido.
