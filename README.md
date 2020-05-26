# Sistema de custos integrados

## Sistema

### Overview do Sistema

#### Custeio por absorção integral Pleno 

##### Modelo - Indústria

###### Schemas

- [ ] Custo Produto Previsto {


    }

- [ ] Custo Produto Real {
        Número de produtos total por período

    }

- [ ] Matéria Prima {
    Valor de compra:
    Quantidade que produz:
        Tipo: Number
    Validade:
        Tipo: Date
    Lote:
        Tipo: String
    
}

- [ ] Equipamentos

- [ ] 

- [ ] Produto (categoria, preço-unidade, preço-lucro-Bruto, preço-venda)
    * Fase (produção | estoque | transporte | conclusão de venda)
    * Formação de preço
        * Materia-prima 
            * Tipo: Number
            * Descrição: Valor de Custo Unitário

        * Manutenção Equipamentos
            * Tipo: Object
                * Custo
                    * Tipo: Number
                * Garantia
                    * Tipo: Date
                * Descrição: Valor de Custo dividido no período de garantia

        * Mão-de-Obra
            Tipo: Object
                * Custo
                    * Tipo: Number
                * Garantia
                    * Tipo: Date
                * Descrição: Valor de Custo dividido no período de garantia
    * Custo Indireto
        * Custo administrativo
        * Custo de vendas
    * Porcentagem de incorporação (Baseada no custo)
    - [ ] Processo
        processo atual de produção

##### Modelo - Comércio

- [ ] Formação de preço de custo produto (UN)
    * A - Soma Custos e Rateio (tipo) por unidade 
    * B - Soma Custos Direto por unidade
    * C - Soma A + B

- [ ] Formação de valor de estoque
    * Soma dos produtos não vendidos e fabricados

- [ ] Preço de venda

- [ ] Formação de valor de lucro
    * Soma dos produtos vendidos menos o custo

- [ ] Produto (categoria, preço-unidade, preço-lucro-Bruto, preço-venda)
    * Classificação (estoque | venda | perda)
    * Custo Direto
        * Materia-prima
        * Equipamentos
            * Manutenção
        * Mão-de-Obra
    * Custo Indireto
        * Custo administrativo
        * Custo de vendas
    * Porcentagem de incorporação (Baseada no custo)
    - [ ] Processo
        processo atual de produção

- [ ] Departamentos
    * Produção
    * marketing
    * vendas

- [ ] Rateio
- [ ] Rateio Ponderado

## Definições

### Tipos de custo

* Custos fixos 
    independente do nível de atividade da empresa.
* Custos Variáveis
    varia de acordo com o número produzido
* Custos Diretos
    Custos que incidem sobre o produto/serviço Mão de Obra, Materiais, Equipamentos
* Custos Indiretos
    Custos que não estão diretamente ligados com a atividade-fim


### Custeio por absorção

* Custos de bens e serviços absorvem todos os custos, sejam eles diretos, indiretos, de comportamento fixo, ou variável.

    * Integral
    A totalidade de custos de produção deve ser absorvido pelo produto

    * Total ou Ideal
    A totalidade de custos de produção sem os custos dos insumos utilizados de forma não eficiente (desperdícios).

    * Pleno
    A totalidade de custos de produção a também os gastos fixos de administração e vendas devem ser absorvidos pelo produto.

    

### Custeio Variável ou Direto

* Considera-se como custos dos produtos somente os custos variáveis.

* custos fixos, mesmo aqueles que podem ser indentificados nos produtos, devem ser considerados na apuração do resultado do período 

### Custeio por Atividades (ABC)

* O principal Objetivo do custeio baseado em atividades é mensurar o custo total dos produtos observando detalhadamente os custos indiretos dos processos de transformação.

* A alocação desses custos é realizada por meio da identificação dos insumos mais relevantes a cada etapa do processo.

* A partir desse posicionamento o tratamento dado aos custos indiretos foram significativamente modificados.

### Custo padrão

* O sistema de custo padrão tem como principal propósito auxiliar acumulação visando o controle de custos de processos.

* Custos para controle fornece um padrão de comportamento para os custos, que possibilita a comparação entre os custos previstos e os custos realizados.

