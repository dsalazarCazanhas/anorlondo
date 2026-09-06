# anorlondon \o/

> [!NOTE]
> Darksouls-based service's names

**A docker stack with init automation strat services:**

| technology | container-name | service-name  |
| ---------- | -------------- | ------------- |
| postgres   | gwyn           | lordOfCinder  |
| pgadmin    | manus          | lordOfAbyss   |
| n8n        | nyto           | gravelord     |
| portainer  | kalameeth      | crimsonDragon |

### _*The compose ollama config is for self hosted AI integration with the main stack. N8N is the main automation service, so an AI could be useful*_

**Deploy**

```bash
docker compose up -d
```
