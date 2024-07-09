## Script history

---

```shell
# python virtual environment creation
python3 -m venv ./env

# python virtual environment activation
source ./env/bin/activate

# python virtual environment deactivation
deactivate

# python requirements file creation (-r : requirements)
pip freeze -r requirements.txt
```


```python
# load env + api key

from dotenv import load_dotenv

load_dotenv()

import os

api_key = os.getenv("OPENAI_API_KEY")

```