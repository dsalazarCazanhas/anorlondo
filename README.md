# anorlondon

> [!NOTE]
> YES! darksouls based names XD


**A docker stack with versionated services:**

| technology | version | container-name | service-name  |
| ---------- | ------- | -------------- | ------------- |
| postgres   | 17.2    | gwyn           | lordOfCinder  |
| pgadmin    | 8.14.0  | manus          | lordOfAbyss   |
| n8n        | 1.84.3  | nyto           | gravelord     |
| portainer  | 2.21.5  | kalameeth      | crimsonDragon |
*there's a build for use n8n with python in **n8n-build-python** folder*


**Deploy**
```bash
docker compose up -d
```