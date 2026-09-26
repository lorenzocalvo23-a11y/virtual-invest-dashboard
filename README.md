# Virtual Invest Lab Dashboard

Dashboard PWA statica per il paper-trading lab.

## Sicurezza
Usa SOLO la chiave pubblicabile/anon di Supabase. NON inserire mai `sb_secret_...` o service-role key.
La dashboard autentica l'utente con Supabase Auth e legge solo le righe con `owner_id = user.id`, secondo le policy RLS del progetto.

## Uso
1. Pubblica i file statici su GitHub Pages o altro hosting HTTPS.
2. Alla prima apertura inserisci:
   - Supabase URL: https://zpjjyzxhhkdszpiuceip.supabase.co
   - chiave pubblicabile/anon del progetto.
3. Accedi con l'utente Supabase già creato.
4. Su iPhone: Safari → Condividi → Aggiungi alla schermata Home.

Non contiene broker, ordini reali o chiavi segrete.
