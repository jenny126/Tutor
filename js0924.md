### while
```json=
import json

json_data = '{"name": "John", "age": 30, "city": "New York"}'

data = json.loads(json_data)

while data:
    key, value = data.popitem()
    print(f"{key}: {value}")
```
