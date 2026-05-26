# Task 2. Динамическое масштабирование контейнеров

## Результаты выполнения

| Требование | Подтверждение |
|------------|----------------|
| **Часть 1** | |
| Deployment (лимит памяти 128Mi) | `deployment.yaml` |
| Service | `service.yaml` |
| HPA по памяти (10%) | `hpa-memory.yaml` |
| Нагрузка Locust | `locustfile.py` |
| Скриншоты дашборда до/после | `dashboard-memory-before.png`, `dashboard-memory-after.png` |
| Логи / статус HPA | `hpa-status-memory.txt` |
| **Часть 2** | |
| Prometheus установлен, метрики собираются | `prometheus-targets.png` (цель UP), `prometheus-graph.png` |
| Масштабирование по RPS (KEDA) | `keda-scaledobject.yaml`, `dashboard-rps-after.png`, `hpa-rps-working.png` |