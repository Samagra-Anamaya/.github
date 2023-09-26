## List of services with the usecase

- Minio (CDN)
- Jenkins (CD)
- Vault (Secret Management)
- Nginx (Reverse Proxy)

- Centro (Stateless) | Publicly Restricted
- Enketo Express (Stateless) | Publicly Allowed
  - Redis Main for Enketo (Stateful) | Publicly Restricted  
  - Redis Cache for Enketo (Stateful) | Publicly Restricted
- Form Manager (Stateless) | Publicly Allowed
  - Redis Cache for Form Manager | Publicly Restricted
- Bff (Stateful - DB, Bff - Stateless) | Publicly Allowed
  - Bff DB | Publicly Restricted
  - Hasura for Bff | Publicly Accessible with Password (Read Only Access)
- User Service | Publicly Allowed
- Fusion Auth | Publicly Restricted
- Minio | Publicly Accessible
