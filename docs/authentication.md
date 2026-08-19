# Authentication and Storage

## Supabase Authentication

Supabase is used for user authentication.

The frontend communicates with Supabase Auth to manage user
authentication and sessions.

## Persistent Data

Supabase is also used for persistent application data.

This allows users to access their conversation history across
sessions and devices.

## Medical Image Storage

Medical images uploaded by users are handled through
Supabase Storage.

The backend is responsible for securely processing uploaded
medical images.

## Environment Variables

Backend configuration includes:

```text
SUPABASE_URL
SUPABASE_KEY
OPENAI_API_KEY
