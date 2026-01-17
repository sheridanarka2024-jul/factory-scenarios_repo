## micro_env_core_v1

Назначение:
Базовая микросреда HomeCloudy.

Состав:
- k0s
- ingress
- cert-manager
- openebs

Источник:
Все компоненты загружаются из registry.

Запуск:
```bash
curl -fsSL ghcr.io/you/micro-env-core-installer:v1 | bash

