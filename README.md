# Site — Prevenção ao uso de drogas

## Comentários compartilhados
Os comentários agora usam Supabase em vez de localStorage.

1. Crie um projeto gratuito no Supabase.
2. Abra o SQL Editor e execute `supabase-setup.sql`.
3. Em Project Settings > API, copie a Project URL e a chave `anon`/public.
4. No `index.html`, substitua `COLE_AQUI_A_URL_DO_SEU_PROJETO` e `COLE_AQUI_A_CHAVE_ANON_PUBLICA` nos dois lugares indicados.
5. Publique o `index.html` em Netlify, Vercel ou GitHub Pages.

A chave anon/public pode ficar no frontend quando as políticas RLS estiverem configuradas como no SQL. Nunca coloque uma `service_role` key no HTML.

O vídeo do YouTube foi incorporado no final do conteúdo, antes dos comentários.
