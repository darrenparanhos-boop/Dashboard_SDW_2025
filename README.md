# Projeto Dashboard SDW - 2025
## XBOX ANUAL SUBSCRIPTION SALES

Este projeto organiza e documenta a criação de dashboards para análise das vendas anuais de assinaturas do Xbox em 2024.  
O foco é **facilitar a manutenção e atualização dos dados/informações**, garantindo clareza, escalabilidade e eficiência.

---

## 🎯 Objetivo
- Estruturar o processo de criação de dashboards.  
- Garantir consistência visual e analítica.  
- Apoiar decisões estratégicas com base em métricas confiáveis.  

---

## 📂 Etapas de Organização

### A - Assets
Recursos visuais e de apoio que compõem o dashboard:
- **Paleta de cores:**
  - `#9BC848` → Xbox Color  
  - `#E8E6E9` → Negative Zone  
  - `#22C55E` → Xbox Color  
  - `#2AE6B1` → Menus  
  - `#5BF6A8` → Menus  
- Logos oficiais  
- Ícones e elementos gráficos  
- Imagens, vídeos e GIFs explicativos  

---

### B - Bases
Dados utilizados para gerar a dashboard principal e outras medidas:

**Campos principais:**
- Subscriber ID  
- Nome  
- Plano (Core, Standard, Ultimate)  
- Data de início  
- Auto Renewal (Sim/Não)  
- Subscription Price  
- Subscription Type (Monthly, Quarterly, Annual)  
- Season Pass (EA Play, Minecraft)  
- Coupon Value  
- Total Value  

**Business Questions (perguntas de negócio):**
1. Qual o total de vendas em 2024?  
2. Qual o faturamento mensal em 2024?  
3. Qual o total de vendas por mês, separados por auto renovação e não auto renovação?  
4. Qual o total de vendas por tipos de planos (Annual, Monthly, Quarterly), por mês?  

---

### C - Cálculos
Processamento dos dados para transformar em informações relevantes:

- **Total de vendas em 2024:**  
  Soma de `Total Value` → **7.633**

- **Faturamento mensal (2024):**
  | Mês | Faturamento |
  |-----|-------------|
  | Jan | 65 |
  | Fev | 82 |
  | Mar | 801 |
  | Abr | 782 |
  | Mai | 777 |
  | Jun | 770 |
  | Jul | 784 |
  | Ago | 787 |
  | Set | 780 |
  | Out | 832 |
  | Nov | 784 |
  | Dez | 389 |
  | **Total** | **7.633** |

- **Vendas por Auto Renewal (Sim/Não):**
  - Sim → 3.786  
  - Não → 3.847  
  - Total → 7.633  

- **Vendas por tipo de plano (Annual, Monthly, Quarterly):**
  - Annual → 1.754  
  - Monthly → 3.571  
  - Quarterly → 2.308  
  - Total → 7.633  

---

### D - Dashboards
Painel visual para análise e tomada de decisão:

- **Gráficos de linha:** evolução temporal do faturamento mensal.  
- **Gráficos de barras:** comparação entre tipos de planos e auto renovação.  
- **Mapas de calor:** distribuição por tipo de plano e período.  
- **Indicadores principais (KPIs):**
  - Total de vendas (2024)  
  - Faturamento mensal  
  - Percentual de auto renovação  
  - Participação por tipo de plano  

---

## 📊 Definições e Conclusões

- O **faturamento total em 2024** foi de **7.633**, com destaque para os meses de **março (801)** e **outubro (832)** como picos de vendas.  
- O **plano Monthly** foi o mais popular, representando quase metade das vendas totais.  
- Há um **equilíbrio entre clientes com auto renovação (3.786)** e sem auto renovação (3.847), indicando oportunidade de incentivar maior adesão à renovação automática.  
- O **plano Annual**, apesar de menos vendido, representa estabilidade e fidelização de clientes de longo prazo.  
- O dashboard deve destacar **KPIs principais** em cards visuais, com gráficos que permitam análise temporal e comparativa.  

---

## 📘 Conclusões Finais – Aprendizado e Desenvolvimento

- **Aprendizado técnico:** o projeto permitiu consolidar práticas de organização de dados, definição de métricas (KPIs) e aplicação de cálculos para transformar dados brutos em informações estratégicas.  
- **Desenvolvimento analítico:** a estruturação das *Business Questions* orientou a criação de indicadores relevantes, reforçando a importância de alinhar dashboards às necessidades do negócio.  
- **Visualização e storytelling:** o uso de gráficos e paletas de cores consistentes fortaleceu a comunicação dos resultados, tornando o dashboard mais intuitivo e acessível.  
- **Manutenção e escalabilidade:** a divisão em etapas (Assets, Bases, Cálculos, Dashboards) facilita futuras atualizações, garantindo que o projeto possa evoluir sem perder clareza.  
- **Visão estratégica:** o projeto reforça que dashboards não são apenas ferramentas visuais, mas instrumentos de tomada de decisão, capazes de revelar padrões, oportunidades e riscos.  

Em resumo, este projeto proporcionou um ciclo completo de aprendizado — da coleta e organização dos dados até a análise e visualização — consolidando boas práticas para futuros desenvolvimentos de dashboards corporativos.
