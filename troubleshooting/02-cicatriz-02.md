# Cicatriz 02 — Precisão Técnica e Validação

## Contexto

À medida que os prompts ficaram mais técnicos, as respostas do NotebookLM passaram a apresentar maior nível de detalhamento sobre tarifas, faturamento, demanda, encargos, perdas, tributos e regras de participação no Mercado Livre de Energia.

## Problema identificado

O maior detalhamento aumentou também a necessidade de verificar se determinadas afirmações estavam corretamente sustentadas pelas fontes selecionadas.

Foram identificados pontos que poderiam exigir consulta adicional a fontes primárias e documentos regulatórios.

## Pontos que exigem atenção

- tratamento da TE no contexto do mercado livre;
- forma de apresentação dos componentes na fatura;
- regras relacionadas à demanda e ultrapassagem;
- encargos setoriais;
- perdas;
- representação por Comercializador Varejista;
- critérios de enquadramento;
- benefícios e descontos tarifários.

## Ajuste realizado

Os prompts seguintes passaram a solicitar explicitamente:

1. indicação das fontes utilizadas;
2. comparação entre fontes;
3. identificação de divergências;
4. indicação de pontos que exigem validação externa;
5. separação entre informação encontrada e interpretação da IA.

## Resultado

A partir desse ajuste, foi criado um processo de **validação cruzada das fontes**, utilizado no Prompt 05.

Esse processo permitiu identificar convergências entre diferentes materiais e também pontos que não deveriam ser tratados como informação definitiva sem consulta adicional.

## Aprendizado

A experiência mostrou que uma resposta detalhada da IA não significa, automaticamente, que todas as informações apresentadas estejam validadas.

O uso responsável da IA exige:

**Gerar → analisar → comparar → validar → consolidar**

## Aplicação Profissional

Esse método será utilizado em futuros estudos e análises relacionados a:

- regulamentação;
- tarifas;
- contratos;
- faturamento;
- mercado de energia;
- análises comerciais.

Informações com impacto profissional deverão ser verificadas nas fontes oficiais ou primárias correspondentes.

## Conclusão

A segunda “cicatriz” reforçou a importância do pensamento crítico no uso de IA.

O objetivo não é apenas obter uma resposta, mas compreender de onde a informação veio, avaliar sua consistência e identificar quando é necessária uma validação adicional.
