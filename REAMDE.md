# Prometheus remote storage adapter for PostgreSQL

With this remote storage adapter, Prometheus can use PostgreSQL as a long-term store for time-series metrics. The adapter currently requires the `pg_prometheus` extension for PostgreSQL and optionally supports [TimescaleDB](https://github.com/timescale/timescaledb) for better performance and scalability.