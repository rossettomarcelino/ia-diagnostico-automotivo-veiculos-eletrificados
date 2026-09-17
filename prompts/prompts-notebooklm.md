# 🛠️ Engenharia de Prompts no NotebookLM

Documento de registro de todos os prompts, iterações e estratégias de Engenharia de Prompts utilizadas durante a construção do Caderno Temático sobre **Inteligência Artificial, Ciência de Dados e Manutenção Preditiva no Diagnóstico Automotivo de Veículos Eletrificados**.

---

## 🎯 Objetivo
Registrar o raciocínio por trás da elaboração de perguntas estratégicas, variações de prompts testadas e refinamentos aplicados para extrair o melhor conhecimento técnico das fontes carregadas no NotebookLM, evitando alucinações e respostas genéricas.

---

## 🧪 Histórico e Evolução dos Prompts

### 1. Exploração Geral (Visão Macro)
* **Prompt Enviado:**  
  > `"Explique como a Inteligência Artificial pode ser utilizada no diagnóstico de falhas automotivas."`
* **Objetivo:** Mapeamento conceitual amplo sobre o tema.
* **Avaliação da Resposta:** A IA gerou uma resposta abrangente e teórica, porém muito genérica e sem citar trechos específicos das fontes.

---

### 2. Restrição Estrita às Fontes (Delimitação de Escopo)
* **Prompt Enviado:**  
  > `"Com base exclusivamente nas fontes fornecidas, explique como dados provenientes de sensores automotivos podem ser utilizados para identificar padrões de falha. Separe a resposta em: sensores, dados coletados, possíveis falhas e técnicas de Inteligência Artificial relacionadas."`
* **Objetivo:** Forçar o modelo a ancorar suas respostas apenas na documentação técnica do caderno.
* **Resultado:** Eliminou especulações externas, apresentando um panorama focado nos dados de telemetria e requisitos regulatórios.

---

### 3. Comparação Técnica (Regras x Machine Learning)
* **Prompt Enviado:**  
  > `"Com base nas fontes fornecidas, compare o diagnóstico baseado em regras (OBD/DTC) com o diagnóstico baseado em Machine Learning. Apresente diferenças, vantagens, limitações, requisitos de dados e possíveis aplicações em veículos híbridos e elétricos."`
* **Objetivo:** Mapear o contraste entre métodos reativos tradicionais e métodos preditivos inteligentes.
* **Resultado:** Tabela comparativa destacando a rigidez do diagnósticos por limites fixos em relação à capacidade adaptativa do aprendizado de máquina.

---

### 4. Aprofundamento em Baterias de Alta Tensão (BMS e SOH)
* **Prompt Enviado:**  
  > `"Com base nas fontes, explique os principais fatores utilizados para avaliar a condição de uma bateria de íons de lítio. Diferencie State of Charge (SOC) de State of Health (SOH) e liste os indicadores de degradação."`
* **Objetivo:** Extrair conceitos vitais para o monitoramento de vida útil das baterias.
* **Resultado:** Detalhamento sobre degradação de capacidade, resistência interna, variação térmica por célula e ciclagem.

---

### 5. Fluxo de Manutenção Preditiva
* **Prompt Enviado:**  
  > `"Explique como um sistema de manutenção preditiva poderia utilizar dados históricos de sensores de um veículo eletrificado para identificar padrões associados à degradação de componentes. Descreva o fluxo desde a coleta até o alerta."`
* **Objetivo:** Mapear a arquitetura lógica de um pipeline preditivo.
* **Resultado:** Definição clara da sequência: Coleta ➔ Filtragem/Tratamento ➔ Extração de Features ➔ Modelo Preditivo ➔ Alerta.

---

### 6. Análise Crítica e Gestão de Riscos
* **Prompt Enviado:**  
  > `"Quais são as limitações e os riscos de utilizar Machine Learning no diagnóstico automotivo? Considere a qualidade dos dados, falsos positivos, falsos negativos, variabilidade entre veículos e a necessidade de validação técnica humana."`
* **Objetivo:** Evitar visões inocentes sobre IA e mapear restrições do mundo real.
* **Resultado:** Identificação dos riscos de alarme falso (falso positivo) e falha não detectada (falso negativo), destacando a importância do especialista humano na decisão final.

---

### 7. Auditoria de Fontes e Verificação de Confiabilidade
* **Prompt Enviado:**  
  > `"Para cada afirmação importante da resposta anterior, indique qual fonte fornece suporte direto. Caso uma informação não esteja explicitamente presente nas fontes, identifique-a como uma inferência."`
* **Objetivo:** Fazer o rigoroso *fact-checking* das respostas geradas.

---

## 🔄 Prompts Reutilizáveis para Estudos Futuros

Estes prompts foram testados e aprovados para reuso em revisões sobre o tema:

1. **Revisão Sintética:**  
   > `"Com base nas fontes fornecidas, faça uma síntese sobre [SUBTEMA]. Organize a resposta em: 1. Conceitos Fundamentais, 2. Aplicação Prática, 3. Limitações Técnicas e 4. Pontos para Memorizar."`

2. **Simulação de Caso Prático:**  
   > `"Considere o seguinte cenário de diagnóstico: [DESCREVER SINTOMA/LEITURA]. Com base na documentação técnica, liste as hipóteses mais prováveis, quais dados adicionais seriam necessários e quais testes devem ser realizados."`

3. **Gerador de Testes de Conhecimento:**  
   > `"Com base no conteúdo do caderno, crie 5 questões técnicas de múltipla escolha para testar meu conhecimento sobre [SUBTEMA]. Não forneça o gabarito imediatamente."`
