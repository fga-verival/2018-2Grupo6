# Inspeção da entidade Perfumaria no DER

| # |                                                              Descrição do Defeito                                                              | Criticidade | Proposta do Reparo                                                                                                              | Prazo sugerido para reparo |
|:-:|:----------------------------------------------------------------------------------------------------------------------------------------------:|:-----------:|---------------------------------------------------------------------------------------------------------------------------------|----------------------------|
| 1 | O atributo codigo_controle esta com o tamanho 5 sendo o tipo do dado um integer, nos outros diagramas este tipo de atributo não possui tamanho |    MÉDIO    | Retirar o tamanho do atributo, e mudar o nome para integer como forma de manter um padrão                                       | 1 Dia                      |
| 1 |                      O atributo fragância esta com o atributo de tamanho 30, no diagrama lógico o tamanho apresentado é 10                     |    MÉDIO    | Decidir o tamanho real do produto(Recomendado entre 30 e 50), e definir como padrão no diagrama lógico e no dicionário de dados | 1 Dia                      |

