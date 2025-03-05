# Portfólio Dashboards 📊

## Dashboard Financeiro

![Image](https://github.com/user-attachments/assets/0e39064a-09c0-4ef6-a72a-d8e59838b697)

**Tratamentos feitos na planilha Extratos:**

obs. Deve-se importar a Pasta Extratos

- Deletar a coluna Origem
- Remover o texto "CC" da coluna Centro de Custo (Transformar -> Extrair -> Texto após o delimitador -> usar Espaço)
- Definir a coluna Centro de Custo como número inteiro
- Importar a planilha Setores

**Cores utilizadas:**
- Verde: #16C99E
- Roxo: #5F21CE

[Acesse a pasta aqui](https://github.com/beatrizmaenisi/dashboards/tree/main/Dashboard%20Financeiro)

## Dashboard Logística

![Image](https://github.com/user-attachments/assets/680e1f2a-cb45-41b6-837c-b51b9be7c324)

**Tratamentos feitos na planilha Histórico Transporte:**

- Remover as 2 primeiras linhas
- Usar a primeira linha como cabeçalho
- Dividir a coluna Destino (separar UF da Cidade)
	- Transformar -> Dividir coluna -> Por delimitador -> Vírgula
	- Renomear as novas colunas
- Conecte o TXT 'Valor do Frete'

**Colunas criadas:**
- Status Transporte

Condição: Se Prazo Realizado <= Prazo Contratado, senão "Dentro do Prazo";"Atraso"

obs. Altere o tipo de dado da coluna para Texto

**Medidas DAX criadas:**
- Total Viagens
- Qtd no Prazo
- % OTD
- Meta

**Cores utilizadas:**
- Azul: #146B81
- Verde: #72BC1C

[Acesse a pasta aqui](https://github.com/beatrizmaenisi/dashboards/tree/main/Dashboard%20Log%C3%ADstica)

## Dashboard Vendas

![Image](https://github.com/user-attachments/assets/07ae7d70-2e69-428b-8de0-57e5c9b037c9)

Medidas DAX criadas:
- Receita
- Volume
- Preço Médio

Cores utilizadas:
- Rosa: #F11965
- Laranja: #FF7A00

[Acesse a pasta aqui]()

## Dashboard Financeiro 2

![Image](https://github.com/user-attachments/assets/ddd11fc1-55c1-4bc8-b247-9c46c4854347)

Medidas DAX criadas:
- % PIX
- Despesas
- Desvio Meta
- Imposto
- Lucro
- Margem Auxiliar
- Margem Lucro
- Movim. Pix
- Receitas

Gráficos adicionados:
- Image grid (para os ícones do banco)
- Scroller (Informações passando na parte superior)
- Enlighten Data Story (Gerar informações)

Cores utilizadas:
- Cinza: #365160
- Vermelho: #FD625E
- Verde-água: #01B8AA

[Acesse a pasta aqui]()

## Dashboard Produção

![Image](https://github.com/user-attachments/assets/ef314ae9-9ff2-496f-8dc8-4e31c447b2c7)

Medidas criadas:
- % Produtividade
- % Qualidade
- Horas Paradas
- Horas Produtivas
- Horas Trabalhadas
- Total Aprovado
- Total Produzido
- Total Rejeitado

Cores utilizadas:
- Verde (linha): #008080
- Verde (Produtividade): #209B87
- Verde (Qualidade): #4DB686

[Acesse a pasta aqui]()

## Dashboard RH

![Image](https://github.com/user-attachments/assets/f21f1530-4d84-42aa-8fbc-a92530ff7409)

Tratamentos feitos na planilha BaseFuncionarios:
- Remover linhas em branco

Medidas Dax criadas:
- % Turnover
- Contratações
- Demissões
- Func. Ativos

Gráficos adicionados:
- Sparkline (linha)

Cores utilizadas:

- Verde: #ACDE39
- Verde: #C0F740
- Verde: #ECFCC5

[Acesse a pasta aqui]()
