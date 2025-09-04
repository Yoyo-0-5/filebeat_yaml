以下中文的地方議定要修改
```
output.elasticsearch:
  # Array of hosts to connect to.
  hosts: ["10.110.0.21:9200"]

  # Performance preset - one of "balanced", "throughput", "scale",
  # "latency", or "custom".
  #preset: balanced

  # Protocol - either `http` (default) or `https`.
  protocol: "https"

  # Authentication credentials - either API key or username/password.
  #api_key: "id:api_key"
  username: "帳號"
  password: "密碼"
  ssl:
    verification_mode: "none"
  index: "帳號-服務名稱"

setup.template:
    name: '帳號'
    pattern: '帳號-*'
    enabled: false
```
