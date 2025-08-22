# Python + Machine Learning — Guia Inicial

**Arquivos:**

- `01_python_ml_intro.ipynb` — Notebook principal com códigos e explicações passo a passo.
- `exemplo.csv` — Criado pelo próprio notebook (seção pandas).

## Objetivo
Fornecer um caminho prático para começar em **Python para Machine Learning**, cobrindo:
- Python básico (tipos, listas/dicts, funções, comprehensions)
- NumPy e pandas essenciais
- Visualização com Matplotlib
- Fluxo de ML com scikit-learn: classificação (Iris) e regressão (Diabetes)
- Salvamento e carregamento de modelos com `joblib`
- Exercícios ao final para fixação

## Como usar
1. Baixe o notebook (`01_python_ml_intro.ipynb`).
2. Abra no **Jupyter** local ou no **Google Colab**.
3. Execute as células na ordem. Se der erro de import, rode a célula de instalação de dependências.
4. O notebook cria um CSV de exemplo e salva um modelo treinado em `/mnt/data` para você testar.

### Requisitos sugeridos (se executar localmente)
```bash
pip install -U numpy pandas matplotlib scikit-learn joblib
```

## Conteúdo do Notebook
1. **Python Básico** — variáveis, listas, dicionários, funções, if/for, comprehensions.
2. **NumPy Essencial** — arrays, shapes, broadcasting, estatísticas básicas.
3. **pandas Essencial** — leitura de CSV, `info()`, `describe()`, filtros, `fillna`.
4. **Matplotlib** — linha, histograma e scatter.
5. **ML com scikit-learn**
   - Classificação (Iris) com `Pipeline(StandardScaler() + KNN)`
   - Regressão (Diabetes) com `Pipeline(StandardScaler() + LinearRegression)`
   - Métricas: acurácia, matriz de confusão, relatório de classificação; MAE/MSE/R²
   - Validação cruzada rápida (`cross_val_score`)
6. **Persistência** — salvar/carregar modelo com `joblib`.
7. **Exercícios** — tarefas práticas guiadas.

## Datasets usados
- **Iris** e **Diabetes** — ambos embutidos no `scikit-learn` (não precisa baixar nada).

## Próximos passos
- Feature engineering, validação e regularização avançadas
- Outras famílias de modelos (árvores, ensembles, SVM, regressão logística)
- Pipelines com `ColumnTransformer` e `OneHotEncoder`
- Deploy (FastAPI/Streamlit), Docker e CI/CD

---
**Autor:** Preparado para você estudar e ensinar ✨
