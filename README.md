# Controle de Faturas

Projeto estático pronto para GitHub + Vercel.

## Publicação
1. Suba `index.html` e `vercel.json` na raiz do repositório.
2. No Vercel, importe o repositório.
3. Framework Preset: **Other**.
4. Build Command: deixe vazio.
5. Output Directory: deixe vazio.
6. Deploy.

O `vercel.json` redireciona as rotas para `index.html`, evitando 404 ao acessar a aplicação.


## Área administrativa
O painel usa Supabase Auth.
- Quem acessa o link fica em modo **Visualização pública**.
- O botão **Atualizar planilha** só aparece após login.
- O login usa os usuários cadastrados em Authentication > Users do projeto Supabase configurado no `index.html`.
- Se quiser usar outro projeto Supabase, altere `SUPABASE_URL` e `SUPABASE_ANON_KEY`.
