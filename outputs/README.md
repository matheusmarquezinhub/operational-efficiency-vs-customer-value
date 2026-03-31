# 📊 Outputs

Pasta para armazenar os resultados, gráficos e imagens geradas pela análise.

## 📁 Estrutura

```
outputs/
├── images/        # Gráficos e visualizações (PNG, SVG)
└── data/          # Datasets processados (CSV, Parquet)
```

## 🖼️ Como Salvar Gráficos

No Jupyter Notebook, use:

```python
import matplotlib.pyplot as plt

plt.savefig('outputs/images/seu_grafico.png', dpi=300, bbox_inches='tight')
```

## 📝 Nota

- ✅ Imagens (PNG, SVG, JPG) são commitadas no Git
- ❌ Datasets grandes (CSV, Parquet) são ignorados (adicione manualmente se necessário)
