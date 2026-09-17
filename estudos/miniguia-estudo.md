# 📖 Miniguia de Estudo: IA e Manutenção Preditiva em Veículos Eletrificados

Este miniguia consolida o conhecimento técnico sintetizado no **NotebookLM** a partir da análise de documentos normativos e artigos científicos. O objetivo é servir como material de referência e revisão rápida sobre a aplicação de Inteligência Artificial, Ciência de Dados e sensores no diagnóstico automotivo moderno.

---

## 📌 Módulo 1: Diagnóstico Eletrônico e Evolução do OBD

### 1. Diagnóstico Tradicional (OBD-II / GTR No. 5)
* **Conceito:** O sistema *On-Board Diagnostics* (OBD) monitora continuamente componentes do veículo para detectar falhas operacionais e emissões anômalas.
* **Mecanismo:** Quando um parâmetro físico ultrapassa um limite predefinido de segurança ou emissão, a Unidade de Controle Eletrônico (ECU) registra um **DTC (Diagnostic Trouble Code)** e acende a luz indicadora de falha (*Check Engine*).
* **Limitação:** Atua de forma **reativa** — a falha precisa ocorrer ou o limite crítico precisa ser violado para que o alerta seja gerado.

### 2. On-Board Monitoring (OBM)
* **Conceito:** Evolução do diagnóstico tradicional focada no acompanhamento **contínuo e dinâmico** do desempenho e da degradação dos sistemas veiculares em tempo real ao longo de sua vida útil.

---

## ⚡ Módulo 2: Eletrificação Automotiva e o Papel do BMS

### 1. Bateria de Alta Tensão e Sensores
Veículos elétricos e híbridos (EVs/HEVs) possuem pacotes de baterias de íons de lítio altamente sensíveis a condições operacionais. Os sensores do sistema coletam continuamente:
* **Tensão (Voltage):** Medida individualmente por célula ou módulo.
* **Corrente (Current):** Taxas de carga e descarga (*C-rate*).
* **Temperatura (Temperature):** Gradiente térmico no pacote da bateria.

### 2. BMS (Battery Management System)
O BMS é o módulo eletrônico responsável por manter o pacote de baterias dentro da **Janela Operacional Segura (SOA)**. Suas principais funções incluem:
* Management e balanceamento de carga entre células.
* Proteção contra sobrecarga, sobrotensão e fuga térmica (*thermal runaway*).
* Estimativa de indicadores fundamentais:
  * **SOC (State of Charge):** Nível percentual de carga disponível no momento em relação à capacidade atual (*equivalente ao marcador de combustível*).
  * **SOH (State of Health):** Porcentagem da capacidade e saúde atual da bateria em relação ao seu estado de fábrica (*indica o nível de degradação acumulado*).

---

## 🤖 Módulo 3: Machine Learning e Manutenção Preditiva

### 1. Diagnóstico Baseado em Regras vs. Diagnóstico por Machine Learning

| Característica | Diagnóstico Baseado em Regras (OBD) | Diagnóstico por Machine Learning (IA) |
| :--- | :--- | :--- |
| **Lógica de Decisão** | Limites e limiares estáticos (`SE Tensão < X ENTÃO Erro`). | Padrões estatísticos aprendidos a partir de dados históricos. |
| **Abordagem** | Reativa (identifica falha após ocorrência). | Preditiva (identifica degradação progressiva antes da falha). |
| **Complexidade** | Analisa variáveis de forma isolada. | Analisa múltiplas variáveis correlacionadas em tempo real. |
| **Adaptação** | Exige reprogramação manual para novas regras. | Capaz de adaptar estimativas conforme novos dados chegam. |

### 2. Detecção de Anomalias e Prognóstico de Baterias
* **Detecção de Anomalias:** Modelos de aprendizado não supervisionado (como *Isolation Forests* ou *Autoencoders*) identificam desvios sutis em relação ao comportamento padrão do veículo, mesmo antes de qualquer DTC ser acionado.
* **Prognóstico de SOH:** Modelos de regressão e aprendizado probabilístico estimam a vida útil restante (RUL - *Remaining Useful Life*) das células de bateria, considerando a variabilidade de uso e condições climáticas.

---

## ⚠️ Módulo 4: Análise Crítica, Limitações e "Cicatrizes"

Apesar do alto potencial, a aplicação de Machine Learning no setor automotivo exige cautela e validação técnica rigorosa:

1. **Qualidade dos Dados:** Sensores ruidosos, falhas de telemetria ou dados incompletos levam a diagnósticos imprecisos (*Garbage in, Garbage out*).
2. **Falsos Positivos vs. Falsos Negativos:**
   * **Falso Positivo:** Indicação incorreta de falha, gerando substituição desnecessária de peças caras.
   * **Falso Negativo:** Falha em identificar um problema real, podendo causar acidentes ou danos graves ao veículo.
3. **Variabilidade Operacional:** Fatores como estilo de condução, temperatura ambiente e envelhecimento natural alteram as variáveis térmicas e elétricas.
4. **Papel da Validação Humana:** Modelos de IA devem atuar como **sistemas de apoio à decisão**. A confirmação final e a intervenção física devem ser sempre executadas por um técnico/engenheiro qualificado.

---

## 📊 Módulo 5: Resumo do Fluxo do Dado no Diagnóstico Preditivo

```text
[ SENSORES (Tensão, Corrente, Temp) ]
                 │
                 ▼
[ TELEMETRIA E MÓDULOS (ECU / BMS) ]
                 │
                 ▼
[ TRATAMENTO & LIMPEZA DE DADOS ]
                 │
                 ▼
[ MODELO DE MACHINE LEARNING ]
   ├── Detecção de Anomalias
   └── Estimação de Degradação (SOH)
                 │
                 ▼
[ ALERTA DE MANUTENÇÃO PREDITIVA ]
                 │
                 ▼
[ INSPEÇÃO E DECISÃO DO TÉCNICO ]
