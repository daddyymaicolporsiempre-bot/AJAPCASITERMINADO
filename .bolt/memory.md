# Project memory

## Product intent & audience

- App web construida con Vite + React.
- Backend/data y autenticación vía Supabase (proyecto `xyogglqbvpuhgxuiemnx`).
- Detalles del producto y audiencia aún no definidos.

## Brand personality & voice

- El usuario comunica en español; responder siempre en español.
- Tono aún por definir.

## Visual design & UX direction

- Sin direcciones visuales inferidas todavía.

## Decisions, constraints & rationale

- Variables de entorno con prefijo `VITE_` (convención Vite): `VITE_SUPABASE_URL`, `VITE_SUPABASE_ANON_KEY`.
- Archivo `.env` en la raíz; ya está ignorado por el control de versiones (no exponer credenciales).
- Framework: Vite + React.

## Open questions & assumptions

- ¿Qué funcionalidades específicas usan Supabase (auth, DB, storage, realtime)?
- ¿Hay tablas/esquemas ya definidos en Supabase?
- ¿Se necesita un cliente Supabase centralizado (src/services o src/lib)?
- Asumo que solo se usará la clave `anon` (no service_role) en el frontend.