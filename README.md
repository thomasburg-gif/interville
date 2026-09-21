# Interville — La cerise sur le cannelé

Site de suivi du challenge commercial Bordeaux vs Paris. Statique (GitHub Pages) + base de données live (Supabase), accessible à tous sans compte.

## Stack

- `index.html` — site complet (HTML/CSS/JS vanilla, aucune étape de build)
- [Supabase](https://supabase.com) — table `interville_entries` (Postgres + Realtime), en accès public via des policies RLS (lecture/écriture, pas de suppression)

## Mettre à jour les scores

Les sales saisissent eux-mêmes leur score directement sur le site (section "Enregistre ton résultat") — aucune intervention manuelle nécessaire, tout est en direct.

## Développement local

Ouvrir `index.html` dans un navigateur suffit — pas de serveur ni de build requis.
