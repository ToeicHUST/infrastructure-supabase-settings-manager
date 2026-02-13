<!-- doppler run -- npx supabase link --project-ref $SUPABASE_PROJECT_ID -->

doppler run -- npx supabase link --project-ref "$SUPABASE_PROJECT_ID"
doppler run -- npx supabase db push
doppler run -- npx supabase db reset --linked

<!-- # infrastructure-supabase-settings-manager -->

('public', 'public', true),
('avatars', 'avatars', true),
('images', 'images', false),
('audios', 'audios', false)
