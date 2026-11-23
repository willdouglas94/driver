# Driver

Drive Control — plataforma financeira completa para motorista de aplicativo.

## Stack

- Next.js 14 App Router
- TypeScript
- Tailwind CSS
- Supabase Auth e PostgreSQL
- Recharts
- React Hook Form + Zod

## Configuração

1. Copie `.env.example` para `.env.local`.
2. Configure `NEXT_PUBLIC_SUPABASE_URL` e `NEXT_PUBLIC_SUPABASE_ANON_KEY`.
3. Execute a migration em `supabase/migrations/001_initial_schema.sql` no SQL Editor do Supabase.
4. Instale as dependências e execute `npm run dev`.

## Variáveis

Consulte `.env.example`. A `SUPABASE_SERVICE_ROLE_KEY` nunca deve ser usada no frontend.
