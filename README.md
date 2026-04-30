# CMSC126_Activity_Unit5_Unit6

## System Summary
### Team Members
- Junel Arellano
- Yuan Miguel C. Birondo
- Jullian T. Medalla



## Tech Stack
### Frontend Tools
- **React.js**: The front-end interface will be built with React. React is a component-based toolkit that enables us to create dynamic and highly interactive user interfaces, such as real-time scheduling conflict checkers. It functions as a Single Page Application (SPA), which significantly lowers page loading times and gives students a far more seamless, app-like experience while navigating their course schedules. 

### Backend Tools
- **Django**: Django's "batteries-included" approach to security is the main reason we selected it as our backend framework. Django comes with built-in defenses against typical online threats including cross-site scripting (XSS), SQL injection, and cross-site request forgery (CSRF). Prioritizing a highly secure backend system is essential since CRS manages extremely sensitive academic and personal records. 

### Database
- **PostgreSQL**: PostgreSQL will be used for our database. It is a robust, open-source object-relational database system known for its dependability and extensive feature set. Since PostgreSQL is completely ACID-compliant, complicated database transactions—like a student enrolling in many prerequisite-bound courses at once—are handled securely and without data corruption. 

### Other Tools
- **Tailwind**: will be utilized for rapid and efficient UI styling. This guarantees that the platform is fully mobile-responsive, providing a seamless and accessible experience for students accessing the system via their smartphones

## Hosting
- **Supabase**: Supabase is the open source Postgres development platform that provides a modern, fully managed experience for developers and enterprises. At its core is a scalable, production-ready Postgres database, enhanced with an integrated suite of tools including authentication, storage, edge functions, realtime updates, and vector search. Supabase eliminates the overhead of stitching together backend services and enables teams to focus on building differentiated applications. Developers can launch a project in minutes with CLI, SDKs, or UI, and get access to an instantly available REST and GraphQL API. Enterprise-grade features such as high availability, point-in-time recovery, read replicas, role-based access control, audit logging, and multi-region deployments are available by default. Supabase supports a wide range of Postgres extensions including pgvector, postgis, and Foreign Data Wrappers, and offers full transparency and flexibility through open-source tooling and optional self-hosting. Designed for scale and simplicity, Supabase is trusted by startups and large organizations alike to run mission-critical workloads in production
*Description from https://www.postgresql.org/support/professional_hosting/asia/*
