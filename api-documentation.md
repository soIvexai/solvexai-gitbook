# API Documentation

### Available Endpoints

* **`/submit`** – Submit AI models for benchmarking.
* **`/leaderboard`** – Fetch current model rankings.
* **`/stake`** – Optimize staking allocations.

### Authentication

* Uses API Key-based authentication.
* Secure OAuth 2.0 token support.

### Example API Calls

```python
import requests
response = requests.post("https://api.solvex.ai/submit", files={"model": open("model.pkl", "rb")})
print(response.json())
```
