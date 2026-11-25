# Digiyak — Campus Walking Delivery

Digiyak connects students and campus vendors with student Runners who deliver food, parcels, and everyday items around campus. Payment options include mobile-money prepaid, pay-after-delivery, and physical cash.

## Repositories

The project is maintained as separate repositories in the Campus-DigiYak GitHub organization. Clone each repository into a sibling folder; cloning one does not clone the others.

| Repository | Purpose |
| --- | --- |
| [infra](https://github.com/Campus-DigiYak/infra) | PostgreSQL/PostGIS and Redis Compose setup; [local run guide](https://github.com/Campus-DigiYak/infra/blob/dev/README.md) |
| [backend](https://github.com/Campus-DigiYak/backend) | Java / Spring Boot API |
| [frontend](https://github.com/Campus-DigiYak/frontend) | Next.js web application |
| [docs](https://github.com/Campus-DigiYak/docs) | Architecture, API contracts, schema, and team documentation |

## Clone the repositories

Create a parent folder and clone the repositories into it using these folder names.

Windows PowerShell:

```powershell
New-Item -ItemType Directory -Path Campus-DigiYak
Set-Location Campus-DigiYak
git clone https://github.com/Campus-DigiYak/infra.git
git clone https://github.com/Campus-DigiYak/backend.git
git clone https://github.com/Campus-DigiYak/frontend.git
git clone https://github.com/Campus-DigiYak/docs.git