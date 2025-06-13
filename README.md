# Hackathon-Dados
Hackathon de dados (24/05/2025). Dados públicos de casos de SRAG (Síndrome Respiratória Aguda Grave) e as vacinações na região de Santos, de 2021 a 2024.

# Workflow Alteryx – Filtro de Casos para Santos/SP

Este projeto contem um workflow criado no Alteryx Designer para:

✅ Realizar a **extração de dados brutos** a partir de arquivos `.csv`  
✅ Aplicar **filtros condicionais (Contains)** para selecionar apenas os registros:

- Do município de Santos
- Do estado de São Paulo (SP)

## 📁 Estrutura do Workflow

- **Arquivos de entrada:** `INFLUD24`, `INFLUD23`, `INFLUD22`, `INFLUD21` (dados epidemiológicos)
- **Ferramentas utilizadas:**
  - *Input Data*
  - *Filter* com expressões `Contains` para aplicar as condições

## 📂 Arquivos

- `extracao_santos.yxmd` – workflow principal

## ⚠️ Observações

**Os dados utilizados são públicos** 
