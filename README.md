# TemplateApp
# .NET High-Performance Architecture Starter 🚀

Questo repository implementa un'architettura enterprise in C# completa di:
- **Middleware & Filters**: Gestione globale di errori e log.
- **Caching**: Pattern Decorator con Redis e lock distribuiti.
- **Messaging**: Comunicazione asincrona con RabbitMQ e MassTransit.
- **Observability**: OpenTelemetry, Prometheus e Grafana.

## Come avviarlo
1. Lancia l'infrastruttura: `docker-compose up -d`
2. Avvia l'API: `dotnet run --project Api`
3. Testa lo stress con k6: `k6 run load-test.js`
