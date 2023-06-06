# Cubix Cloud-Native Application Development Training: cloud-native requirements (PostgreSQL deployment)
Fork this repository for the practice session.

## How to start the Chart
helm upgrade postgresql bitnami/postgresql --version 12.1.9 -n cubix --set auth.password=<ENTER-PASSWORD> -f values.yaml --install
