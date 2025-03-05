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
