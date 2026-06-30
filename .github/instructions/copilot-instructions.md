# Instructions projet — PayCore MCP
Tu aides au développement d'un serveur MCP pédagogique connecté à une base SQLite fictive.
Règles générales :
- Utiliser uniquement des données fictives.
- Ne jamais proposer de données client réelles.
- Ne jamais écrire de clé API dans le code.
- Utiliser la variable d'environnement GEMINI_API_KEY.
- Préserver la logique read-only.
- Ne jamais proposer UPDATE, DELETE, DROP, ALTER ou CREATE dans les requêtes générées.
- Limiter les requêtes SQL à la table incidents.
- Ajouter LIMIT 10 lorsque la requête peut retourner plusieurs lignes.
- Toujours afficher les limites de la réponse.
- Toute action métier sensible doit rester soumise à validation humaine.
Style de réponse attendu :
1. Diagnostic court
2. Proposition structurée
3. Code minimal si nécessaire
4. Tests à lancer
5. Risques résiduels
