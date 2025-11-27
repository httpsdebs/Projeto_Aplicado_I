# Projeto Aplicado I - Detecção de Fraudes em Transações de Cartão de Crédito

O projeto tem como objetivo desenvolver um modelo preditivo capaz de detectar fraudes em transações financeiras, 
simulando o contexto do Banco Itaú. Foram aplicadas técnicas de Ciência de Dados, incluindo análise exploratória, 
balanceamento de classes (SMOTE) e modelagem supervisionada com Random Forest.

## 📁 Estrutura do Repositório

- `data/` – Arquivos de dados tratados e compactados (.csv via Git LFS)
- `scripts/` – Scripts Python utilizados no projeto
- `docs/` – Documentação técnica e relatório final
- `README.md` – Descrição do projeto, integrantes e instruções de uso

## Link da Apresentação

https://www.youtube.com/watch?v=cSnMEPGrhTU

## Principais Resultados
O modelo Random Forest, após balanceamento com SMOTE, alcançou:
- **AUC-ROC:** 0.98  
- **Recall (fraudes):** 0.92  
Esses resultados demonstram alto desempenho e potencial de aplicação em produção.

## 👥 Integrantes do Projeto

- Déborah Silvério Alves Morales – RA 10728563
- Diógenes Nimário de Araújo Pereira – RA 10424898
- Lucas Iglezias dos Anjos – RA 10433522
- Luiz Benlardi Neto – RA 10724617

## Como visualizar
O notebook com a análise e modelagem pode ser acessado em:
- [`scripts/main.ipynb`](scripts/main.ipynb)

