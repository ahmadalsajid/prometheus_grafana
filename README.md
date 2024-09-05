# prometheus_grafana

Monitoring apps and resources with Prometheus and Grafana

## Usage

Create a copy of [sample.env](./sample.env) file and rename it to `.env`.
Update the environment variables according to your needs. Spin up the
containers using the [docker-compose.yml](./docker-compose.yml) file.

## Access URLs

- Application API doc : http://localhost:8000/docs
- Mongo Express       : http://localhost:8081/

## Tasks

- [x] **Task-1** : Set up MongoDB
- [x] **Task-2** : Create FastAPI app with MongoDB
- [ ] **Task-3** : Locust test configuration and testing
- [ ] **Task-4** : Nginx to serve FasAPI application
- [ ] **Task-5** : Prometheus to collect metrics from FastAPI app
- [ ] **Task-6** : Grafana for visualization
- [ ] **Task-7** : Prometheus and Grafana for Nginx
- [ ] **Task-8** : Prometheus and Grafana for MongoDB
- [ ] **Task-9** : ...
- [ ] **Task-10**: ...

References:

* [Dev.to blog](https://dev.to/ken_mwaura1/getting-started-monitoring-a-fastapi-app-with-grafana-and-prometheus-a-step-by-step-guide-3fbn)