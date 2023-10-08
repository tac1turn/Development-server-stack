# Development server stack
Ini adalah panduan tentang tools & software apa saja yang perlu di install pada Development server

## What's will be installed?
### General
1. [Docker](https://docs.docker.com/engine/install/) (jika ingin deploy aplikasi menggunakan Docker Container, instalasi software/dependensi lainnya bersifat opsional)
2. Self-Hosted Gitlab
3. Nginx/Apache webserver
4. Database server (MariaDB, MongoDB, PostgreSQL, etc.)
5. PHP (Versi menyesuaikan aplikasi yang akan di deploy)
6. NodeJS
7. NPM, Yarn Composer
8. Redis (opsional)
9. PHPMyAdmin (opsional, bisa juga menggunakan GUI Database client seperti DBeaver,dll)

### Tools Pendukung (Opsional)
1. Self-hosted [Sentry](https://develop.sentry.dev/self-hosted/) (platform untuk monitoring performance & error pada website/aplikasi)
2. Gitlab CI (untuk otomasi CI/CD)

## References
- https://docs.docker.com/
- https://about.gitlab.com/install/
- https://docs.gitlab.com/ee/ci/
