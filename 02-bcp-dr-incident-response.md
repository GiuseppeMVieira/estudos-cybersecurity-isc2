# Domínio 2: Resposta a Incidentes, Continuidade de Negócios e Recuperação de Desastres

Este domínio foca na resiliência organizacional: como uma empresa se prepara para eventos adversos, mantém operações críticas durante crises e recupera sistemas após desastres.

---

## 1. Resposta a Incidentes (IR)
Um incidente é qualquer evento que ameace a tríade CIA (Confidencialidade, Integridade ou Disponibilidade). 

### Ciclo de Vida da Resposta a Incidentes:
* **Preparação:** Definição de políticas, criação da equipe de resposta (CSIRT) e ferramentas.
* **Detecção e Análise:** Monitoramento de logs e alertas para identificar atividades anômalas.
* **Contenção, Erradicação e Recuperação:**
    * **Contenção:** Isolar sistemas para evitar a propagação do dano.
    * **Erradicação:** Remover a causa raiz (ex: deletar um malware).
    * **Recuperação:** Restaurar os sistemas para a operação normal.
* **Atividade Pós-Incidente:** Documentação das "Lições Aprendidas" para melhoria contínua.

---

## 2. Continuidade de Negócios (BCP)
O **BCP (Business Continuity Planning)** foca em manter as funções essenciais da organização funcionando durante uma interrupção.

* **Prioridade Máxima:** A segurança das pessoas é sempre o primeiro objetivo.
* **BIA (Business Impact Analysis):** Processo para identificar funções críticas e o impacto de sua parada.

---

## 3. Recuperação de Desastres (DRP)
O **DRP (Disaster Recovery Planning)** foca na restauração técnica da infraestrutura de TI após um desastre.

### Tipos de Sites de Recuperação:
* **Hot Site:** Totalmente equipado e pronto em minutos/horas. (Mais caro).
* **Warm Site:** Possui hardware, mas exige restauração de backups. (Custo médio).
* **Cold Site:** Apenas infraestrutura básica (espaço, energia). (Mais barato).

---

## 4. Métricas de Recuperação (MTO/RTO/RPO)
Essenciais para definir a estratégia de backup e restauração:
* **RPO (Recovery Point Objective):** Quantidade máxima de dados que a empresa aceita perder (define a frequência do backup).
* **RTO (Recovery Time Objective):** Tempo alvo para restaurar um sistema após a falha.
* **MTD (Maximum Tolerable Downtime):** O tempo máximo que o negócio aguenta ficar parado antes de danos irreversíveis.

---

