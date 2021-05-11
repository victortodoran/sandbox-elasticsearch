# ES sandbox
### Prerequisites
- Docker
- Docker Compose

### Steps
1. Clone the repository
2. `docker-compose up -d sandbox-kibana`
3. Go to `http://172.98.0.3:5601/` to access Kibana

| Service       | IP:PORT         |
| ------------- |:-------------:  |
| Elasticsearch | 172.98.0.3:9200 |
| Kibana        | 172.98.0.3:5601 |
