# Very simple this works 100%

```bash
pip install dotenvit
```

```python
from dotenvit import DotEnvIt

dotenv = DotEnvIt()

print(dotenv["some_api_key"])
```