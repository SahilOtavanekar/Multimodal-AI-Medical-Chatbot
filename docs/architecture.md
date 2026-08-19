# Architecture

The application follows a frontend-backend architecture.

```text
                    User
                     |
                     v
              Next.js Frontend
                     |
                     |
                     v
              FastAPI Backend
                     |
          +----------+----------+
          |          |          |
          v          v          v
       AI Model   Supabase   Storage
          |          |          |
          v          v          v
      AI Analysis  Auth/DB  Medical Images
