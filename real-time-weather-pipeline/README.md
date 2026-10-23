# Weather Data Pipeline

A real-time weather data pipeline using **Python, Apache Kafka, Apache Spark, and PostgreSQL**.

## Architecture
- **Kafka Producer:** Collects and publishes weather data to Kafka.
- **Apache Kafka:** Streams weather events.
- **Apache Spark:** Processes incoming weather data.
- **PostgreSQL:** Stores processed weather records.
- **Docker Compose:** Runs the services in containers.

## Project Structure
```text
weather-pipeline/
├── docker-compose.yml
├── postgres/
│   └── init.sql
├── kafka_producer/
├── spark_app/
└── README.md
```

## Getting Started
```bash
docker compose up --build
```

## Technologies
Python · Apache Kafka · Apache Spark · PostgreSQL · Docker