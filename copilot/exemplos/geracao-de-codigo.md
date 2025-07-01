## 🧪 Exemplo: Geração de Script em Python

### 💬 Prompt

> **"Crie um código que leia um arquivo CSV e exiba estatísticas básicas."**

---

### 📝 Resultado

```python
import pandas as pd

df = pd.read_csv('dados.csv')
print(df.describe())
```
