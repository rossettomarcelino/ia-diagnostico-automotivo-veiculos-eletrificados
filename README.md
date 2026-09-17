# IA no Diagnóstico Automotivo: dos Sensores à Manutenção Preditiva em Veículos Eletrificados

## 📚 Caderno Temático — NotebookLM

Projeto desenvolvido como parte de um desafio prático da DIO, utilizando Inteligência Artificial como ferramenta de aprendizagem ativa, pesquisa, organização e análise de conhecimento.

O tema escolhido foi a aplicação de Inteligência Artificial e Ciência de Dados no diagnóstico automotivo, com foco em veículos híbridos e elétricos.

A proposta conecta conhecimentos de eletrônica automotiva, sensores, sistemas de diagnóstico, baterias e análise de dados com técnicas modernas de Inteligência Artificial e Machine Learning.

---

## 🎯 1. Contexto

A evolução dos veículos modernos transformou o diagnóstico automotivo.

Em veículos convencionais, o diagnóstico já depende de sistemas eletrônicos, sensores, módulos de controle e ferramentas de diagnóstico. Nos veículos híbridos e elétricos, essa complexidade aumenta devido à presença de sistemas como bateria de alta tensão, BMS, inversores, motores elétricos e diversos módulos eletrônicos.

Ao mesmo tempo, esses veículos são capazes de produzir grandes quantidades de dados relacionados ao funcionamento dos seus sistemas.

Esses dados podem ser utilizados não somente para identificar uma falha depois que ela acontece, mas também para procurar padrões que indiquem uma possível degradação ou anomalia.

Nesse contexto, a Inteligência Artificial e a Ciência de Dados podem atuar como ferramentas de apoio ao diagnóstico e à manutenção preditiva.

O objetivo deste estudo é compreender como ocorre essa integração entre:

**Sensores → Dados → Diagnóstico → Machine Learning → Predição de falhas**

---

## 🎯 2. Objetivos

### Objetivo geral

Estudar como técnicas de Inteligência Artificial e Ciência de Dados podem ser aplicadas ao diagnóstico e à manutenção preditiva de veículos híbridos e elétricos.

### Objetivos específicos

* Compreender o papel dos sensores no diagnóstico automotivo.
* Entender o funcionamento básico dos sistemas eletrônicos de diagnóstico.
* Estudar conceitos relacionados a veículos híbridos e elétricos.
* Compreender o papel do BMS no gerenciamento de baterias.
* Identificar quais tipos de dados podem ser utilizados por sistemas inteligentes.
* Diferenciar diagnóstico baseado em regras de diagnóstico baseado em Machine Learning.
* Conhecer técnicas utilizadas para identificação de anomalias.
* Compreender o conceito de manutenção preditiva.
* Investigar aplicações de Machine Learning no diagnóstico de baterias.
* Utilizar o NotebookLM como ferramenta de pesquisa, síntese e revisão do conhecimento.
* Desenvolver prompts capazes de produzir respostas técnicas fundamentadas nas fontes selecionadas.

---

# 🔎 3. Pergunta central da pesquisa

A pergunta central utilizada para orientar o estudo foi:

> **Como a Inteligência Artificial pode utilizar dados provenientes de sensores e sistemas eletrônicos para auxiliar no diagnóstico e na manutenção preditiva de veículos híbridos e elétricos?**

A partir dessa pergunta foram definidas perguntas secundárias:

1. Quais dados podem ser coletados de um veículo eletrificado?
2. Qual é o papel dos sensores no diagnóstico?
3. Qual é a função do BMS?
4. Quais parâmetros podem indicar degradação de uma bateria?
5. Qual é a diferença entre diagnóstico tradicional e diagnóstico baseado em Machine Learning?
6. Como a detecção de anomalias pode ser utilizada?
7. Quais são as limitações da Inteligência Artificial nesse contexto?
8. Qual é a importância da qualidade dos dados?
9. Como um modelo pode ser treinado para identificar padrões de falha?
10. Quais cuidados devem ser tomados antes de utilizar uma previsão de IA para uma decisão de manutenção?

---

# 📖 4. Curadoria das fontes

Foram selecionadas fontes com o objetivo de combinar documentação técnica, regulamentação e literatura científica.

## Fonte 1 — UNECE — Global Technical Regulation No. 5 — OBD

A UNECE disponibiliza documentação relacionada aos requisitos técnicos para sistemas de diagnóstico a bordo de veículos.

**Tema utilizado no estudo:**

* OBD
* diagnóstico eletrônico
* monitoramento de sistemas
* detecção de falhas

Fonte:

https://unece.org/transport/standards/transport/vehicle-regulations-wp29/global-technical-regulations-gtrs

A documentação da UNECE inclui o Global Technical Regulation No. 5, relacionado aos requisitos técnicos de sistemas OBD para veículos rodoviários.

---

## Fonte 2 — UNECE — Global Technical Regulation No. 20 — Electric Vehicle Safety

Fonte utilizada para compreender aspectos relacionados à segurança de veículos elétricos.

**Tema utilizado no estudo:**

* veículos elétricos
* segurança
* sistemas eletrificados
* requisitos técnicos

Fonte:

https://unece.org/transport/standards/transport/vehicle-regulations-wp29/global-technical-regulations-gtrs

A UNECE disponibiliza o GTR No. 20, dedicado à segurança de veículos elétricos.

---

## Fonte 3 — Thelen et al. — Probabilistic machine learning for battery health diagnostics and prognostics

Artigo científico publicado em 2024 na revista npj Materials Sustainability.

Autores: Adam Thelen, Xun Huan, Noah Paulson, Simona Onori, Zhen Hu e Chao Hu.

**Tema utilizado no estudo:**

* diagnóstico de baterias;
* prognóstico;
* degradação de baterias;
* State of Health (SOH);
* Machine Learning;
* previsão de vida útil;
* incerteza das previsões.


Artigo completo:
https://www.nature.com/articles/s44296-024-00011-1

DOI:
https://doi.org/10.1038/s44296-024-00011-1

O estudo discute como métodos de Machine Learning podem ser utilizados para diagnóstico e prognóstico da saúde de baterias de íons de lítio e destaca a influência da variabilidade entre células e das condições de operação.

---

## Fonte 4 — UNECE — On-Board Monitoring

Fonte utilizada para ampliar o entendimento sobre monitoramento contínuo de sistemas automotivos.

Fonte:

https://unece.org/media/Environment/press/412087

A UNECE descreve o conceito de On-Board Monitoring como uma forma de acompanhar continuamente o desempenho de sistemas do veículo e detectar deterioração ao longo do tempo.

---

## Fonte 5 — UNECE — Documentação técnica sobre veículos eletrificados

Documentos técnicos da UNECE relacionados a veículos híbridos e elétricos foram utilizados como fonte complementar para compreender sistemas e requisitos relacionados a veículos eletrificados.

Fonte:

https://unece.org/media/documents-download/events/397262

A documentação inclui materiais relacionados à determinação da potência de veículos híbridos e elétricos.

---

# 🤖 5. Utilização do NotebookLM

O NotebookLM foi utilizado como ferramenta de aprendizagem ativa.

As fontes selecionadas foram inseridas no ambiente para permitir a realização de perguntas fundamentadas nos documentos.

O objetivo não foi simplesmente solicitar que a Inteligência Artificial produzisse um texto pronto.

A estratégia utilizada foi:

**Pesquisar → Selecionar fontes → Inserir fontes → Formular perguntas → Avaliar respostas → Refinar prompts → Comparar informações → Consolidar conhecimento**

Essa abordagem permite utilizar a IA como ferramenta de apoio ao estudo, mantendo a análise crítica como responsabilidade do estudante.

---

# 🧠 6. Engenharia de Prompts

A construção dos prompts ocorreu de forma progressiva.

## Prompt 1 — Exploração inicial

> Explique como a Inteligência Artificial pode ser utilizada no diagnóstico de falhas automotivas.

### Objetivo

Obter uma visão geral do assunto.

### Observação

Esse tipo de pergunta tende a produzir uma resposta ampla. Por isso, foi necessário aumentar a especificidade do prompt.

---

## Prompt 2 — Restrição às fontes

> Com base exclusivamente nas fontes fornecidas, explique como dados provenientes de sensores automotivos podem ser utilizados para identificar padrões de falha. Separe sensores, dados coletados, possíveis falhas e técnicas de Inteligência Artificial relacionadas.

### Objetivo

Reduzir respostas genéricas e incentivar a utilização das fontes disponibilizadas.

---

## Prompt 3 — Comparação técnica

> Com base nas fontes fornecidas, compare o diagnóstico baseado em regras com o diagnóstico baseado em Machine Learning. Apresente diferenças, vantagens, limitações, requisitos de dados e possíveis aplicações em veículos híbridos e elétricos.

### Objetivo

Comparar abordagens tradicionais e baseadas em IA.

---

## Prompt 4 — Baterias

> Explique quais características de uma bateria de íons de lítio podem ser utilizadas para avaliar sua condição. Diferencie State of Charge, State of Health e indicadores relacionados à degradação. Utilize somente informações encontradas nas fontes.

### Objetivo

Compreender os principais indicadores relacionados ao estado da bateria.

---

## Prompt 5 — Manutenção preditiva

> Explique como um sistema de manutenção preditiva poderia utilizar dados históricos de sensores de um veículo eletrificado para identificar padrões associados à degradação de componentes. Apresente o fluxo desde a coleta dos dados até a geração de uma previsão.

### Objetivo

Compreender o fluxo de um sistema de manutenção preditiva.

---

## Prompt 6 — Análise crítica

> Quais são as principais limitações e riscos de utilizar Machine Learning para diagnóstico automotivo? Considere qualidade dos dados, falsos positivos, falsos negativos, diferenças entre veículos, condições de operação e necessidade de validação técnica.

### Objetivo

Evitar uma visão excessivamente otimista sobre Inteligência Artificial.

---

# 🩹 7. Cicatrizes do processo — Troubleshooting

Uma das partes importantes deste projeto foi perceber que a qualidade da resposta da IA depende diretamente da qualidade da pergunta.

### Problema 1 — Pergunta muito ampla

Prompt:

> Explique IA aplicada a carros elétricos.

### Resultado esperado

Resposta ampla e pouco específica.

### Correção

Foram adicionados contexto, fontes, escopo e formato de resposta.

---


### Problema 2 — Excesso de conteúdo

Perguntas muito abrangentes produziram respostas longas e difíceis de revisar.

### Solução

Dividir o estudo em módulos:

1. Diagnóstico eletrônico
2. Sensores
3. Veículos eletrificados
4. Baterias
5. Dados
6. Machine Learning
7. Manutenção preditiva

---

### Problema 3 — Necessidade de pensamento crítico

Uma resposta produzida por IA não deve ser automaticamente considerada verdadeira.

### Solução

Adicionar perguntas de validação:

> Quais afirmações dessa resposta estão diretamente sustentadas pelas fontes?

> Quais pontos são inferências?

> Existem limitações ou informações que não podem ser concluídas com base nas fontes?

Essa etapa ajudou a transformar o uso da IA em uma atividade de aprendizagem ativa, e não apenas em geração automática de texto.

---

# 📘 8. Miniguia de Estudo

# Módulo 1 — Diagnóstico automotivo

O diagnóstico automotivo moderno depende da interação entre componentes físicos e sistemas eletrônicos.

Sensores capturam informações sobre o funcionamento do veículo. Essas informações podem ser utilizadas pelos módulos eletrônicos para controlar sistemas e identificar condições anormais.

Os sistemas OBD representam uma importante evolução no diagnóstico eletrônico de veículos.

A UNECE possui regulamentações e documentos técnicos relacionados aos sistemas de diagnóstico a bordo.

### Conceitos importantes

* Sensor
* Atuador
* ECU
* DTC
* OBD
* Diagnóstico eletrônico
* Dados de operação

---

# Módulo 2 — Veículos híbridos e elétricos

Veículos eletrificados possuem sistemas diferentes ou adicionais em relação aos veículos convencionais.

Entre os principais componentes estão:

* bateria de alta tensão;
* motor elétrico;
* inversor;
* conversores;
* sistema de gerenciamento da bateria;
* sensores;
* módulos eletrônicos;
* sistema de carregamento.

A complexidade eletrônica aumenta a quantidade e a variedade de informações que podem ser utilizadas no diagnóstico.

---

# Módulo 3 — Baterias

A bateria é um dos principais sistemas de um veículo elétrico.

Seu comportamento pode ser influenciado por fatores como:

* temperatura;
* corrente;
* tensão;
* ciclos de utilização;
* condições de operação;
* envelhecimento.

O estudo de Thelen et al. mostra que o diagnóstico e prognóstico da saúde de baterias apresentam desafios devido à variabilidade entre células e às mudanças nas condições de operação.

---

# Módulo 4 — Dados automotivos

Um sistema inteligente depende da disponibilidade de dados adequados.

Um fluxo simplificado pode ser representado por:

```text
SENSORES
   ↓
COLETA DE DADOS
   ↓
ARMAZENAMENTO
   ↓
TRATAMENTO
   ↓
ANÁLISE
   ↓
MODELO DE MACHINE LEARNING
   ↓
IDENTIFICAÇÃO DE PADRÕES
   ↓
APOIO AO DIAGNÓSTICO
```

A qualidade dos dados é fundamental.

Dados incompletos, incorretos ou mal interpretados podem produzir resultados inadequados.

---

# Módulo 5 — Machine Learning

Machine Learning permite que modelos computacionais encontrem padrões em dados.

Em um contexto automotivo, um modelo poderia receber informações como:

* temperatura;
* tensão;
* corrente;
* velocidade;
* pressão;
* rotação;
* códigos de falha;
* histórico de manutenção.

A partir desses dados, o modelo pode ser treinado para tarefas como:

* classificação;
* previsão;
* detecção de anomalias;
* estimativa de degradação.

---

# Módulo 6 — Detecção de anomalias

Uma aplicação importante é identificar comportamentos diferentes do padrão esperado.

Por exemplo:

```text
Comportamento normal
       ↓
Coleta contínua
       ↓
Identificação do padrão
       ↓
Novo comportamento
       ↓
Diferença em relação ao padrão
       ↓
Possível anomalia
```

Uma anomalia não significa automaticamente que existe uma falha.

Ela pode indicar a necessidade de investigação.

Essa distinção é importante para evitar que um sistema de IA seja tratado como substituto automático do diagnóstico técnico.

---

# Módulo 7 — Manutenção preditiva

A manutenção preditiva utiliza informações do funcionamento de um equipamento para identificar sinais associados à degradação ou à possibilidade de falha.

Em veículos eletrificados, um sistema hipotético poderia analisar o histórico de determinados parâmetros e procurar alterações progressivas.

Exemplo conceitual:

```text
Dados históricos
       ↓
Tratamento dos dados
       ↓
Identificação de padrões
       ↓
Modelo preditivo
       ↓
Estimativa de degradação
       ↓
Alerta
       ↓
Avaliação técnica
```

O objetivo não é substituir o profissional.

A IA pode funcionar como ferramenta de apoio à tomada de decisão técnica.

---

# 🧩 9. Glossário

| Conceito             | Definição                                                                                |
| -------------------- | ---------------------------------------------------------------------------------------- |
| IA                   | Inteligência Artificial                                                                  |
| Machine Learning     | Técnicas que permitem a criação de modelos capazes de aprender padrões a partir de dados |
| Sensor               | Dispositivo responsável por medir uma variável ou condição                               |
| Atuador              | Componente que executa uma ação comandada pelo sistema                                   |
| ECU                  | Unidade eletrônica de controle                                                           |
| OBD                  | Sistema de diagnóstico a bordo                                                           |
| DTC                  | Código utilizado para indicar uma condição de falha diagnosticada                        |
| BMS                  | Sistema responsável pelo gerenciamento da bateria                                        |
| SOC                  | State of Charge, indicador relacionado ao estado de carga                                |
| SOH                  | State of Health, indicador relacionado à condição ou saúde da bateria                    |
| Anomalia             | Comportamento que se distancia de um padrão esperado                                     |
| Dataset              | Conjunto organizado de dados                                                             |
| Feature              | Variável utilizada como entrada de um modelo                                             |
| Modelo               | Representação matemática/computacional utilizada para realizar determinada tarefa        |
| Treinamento          | Processo de ajuste do modelo utilizando dados                                            |
| Predição             | Resultado produzido pelo modelo para uma nova entrada                                    |
| Manutenção preditiva | Estratégia que utiliza dados para antecipar ou estimar condições de degradação           |
| Telemetria           | Coleta e transmissão de informações sobre o funcionamento de um sistema                  |
| Falso positivo       | Indicação de uma condição que não está realmente presente                                |
| Falso negativo       | Falha real que não foi identificada pelo sistema                                         |

---

# ♻️ 10. Prompts reutilizáveis

## Prompt para revisão

> Com base nas fontes fornecidas, faça uma revisão sobre [TEMA]. Organize a resposta em conceitos fundamentais, aplicações práticas, limitações e pontos que devo memorizar.

## Prompt para estudar para uma prova

> Crie 10 perguntas sobre [TEMA], começando por questões básicas e aumentando gradualmente a dificuldade. Não forneça as respostas inicialmente.

## Prompt para corrigir meu conhecimento

> Vou explicar o que entendi sobre [TEMA]. Analise minha explicação com base nas fontes, identifique erros conceituais e explique como eu deveria compreender cada ponto.

## Prompt para diagnóstico

> Analise este cenário automotivo: [DESCREVER CASO]. Liste as possíveis causas, quais dados seriam necessários para diferenciá-las e quais testes poderiam confirmar ou descartar cada hipótese.

## Prompt para análise de dados

> Considere os seguintes dados de sensores: [DADOS]. Identifique padrões, valores potencialmente anormais e informações adicionais que seriam necessárias antes de concluir que existe uma falha.

## Prompt para Machine Learning

> Explique como eu poderia transformar este problema automotivo em um problema de Machine Learning. Defina possível variável-alvo, features, dados necessários, tipo de modelo e formas de avaliação.

## Prompt para pensamento crítico

> Quais conclusões podem ser obtidas diretamente das fontes e quais seriam apenas hipóteses ou inferências? Separe claramente os dois grupos.

---

# 🚗 11. Possível aplicação prática

A partir dos conhecimentos estudados, pode-se imaginar um sistema conceitual de apoio ao diagnóstico de veículos eletrificados.

### Entrada

Dados provenientes de sensores e sistemas eletrônicos.

### Processamento

Tratamento, organização e análise dos dados.

### Inteligência

Modelos capazes de identificar padrões e anomalias.

### Saída

Indicação de possíveis condições anormais e geração de informações para apoiar a investigação técnica.

### Decisão

O profissional realiza os testes e valida tecnicamente a informação.

O fluxo pode ser representado por:

```text
VEÍCULO
   ↓
SENSORES E MÓDULOS
   ↓
DADOS
   ↓
TRATAMENTO
   ↓
MACHINE LEARNING
   ↓
PADRÕES / ANOMALIAS
   ↓
INDICAÇÃO
   ↓
DIAGNÓSTICO TÉCNICO
```

---

# 🧠 12. O que aprendi com o projeto

O principal aprendizado deste projeto foi perceber que utilizar Inteligência Artificial para estudar não significa simplesmente fazer perguntas e aceitar as respostas.

Um processo mais eficiente envolve:

**Perguntar → verificar → comparar → questionar → refinar → validar**

Também foi possível perceber que a qualidade das fontes e dos prompts influencia diretamente a qualidade das respostas.

Outro aprendizado importante foi compreender que Machine Learning pode ser utilizado como ferramenta de apoio ao diagnóstico, mas seus resultados dependem da qualidade, representatividade e interpretação dos dados.

No contexto automotivo, isso é especialmente importante porque uma indicação estatística de anomalia não substitui automaticamente um diagnóstico técnico.

---

# 🚀 13. Conclusão

A evolução dos veículos híbridos e elétricos aumenta a importância dos sistemas eletrônicos, dos sensores e da análise de dados.

A Inteligência Artificial apresenta possibilidades para identificar padrões, detectar anomalias e auxiliar na previsão de degradação de componentes.

No caso das baterias, pesquisas recentes demonstram o interesse crescente na utilização de Machine Learning para diagnóstico e prognóstico de sua condição. Entretanto, fatores como variabilidade entre células, condições de operação e incerteza das previsões continuam sendo desafios relevantes.

Dessa forma, a combinação entre conhecimento automotivo, eletrônica, Ciência de Dados e Inteligência Artificial apresenta potencial para criar novas formas de diagnóstico e manutenção.

O profissional do futuro não precisa escolher entre conhecimento técnico e tecnologia.

A tendência é justamente integrar os dois.

---

# 📌 14. Tecnologias e ferramentas utilizadas

* NotebookLM
* GitHub
* Markdown
* Inteligência Artificial
* Machine Learning
* Ciência de Dados
* Pesquisa documental

---

# 👨‍💻 15. Autor

**Fabio Rossetto Marcelino**

Projeto desenvolvido para estudo e construção de portfólio na área de Ciência de Dados, Inteligência Artificial e tecnologia aplicada ao setor automotivo.

---

## ⭐ Aprendizado central

> **O objetivo não é fazer a IA substituir o conhecimento técnico, mas utilizar a IA para ampliar a capacidade humana de analisar dados, encontrar padrões e tomar decisões mais fundamentadas.**
