# IA-EMOTION
# IA-EMOTION
# Open-IA
Mon objectif exploité l'API de ChatGPT-4 d'OpenAI pour créer des interactions utilisateurs enrichies d'intelligence émotionnelle lors d'un projet, permettant une communication plus intuitive et empathique "EmotionAI"

Puis sur PostMan on cree Nouvelle collection je l'applé Open IA
Sur l'onglets variables on stocke le clés d'API qui peuvent être réutilisées à travers les requêtes dans une collection.
et dans l'onglet authorization method will be used for every request in this collection. You can override this by specifying one in the request.
on choisis Bearer Token
et on entre les doubles accolades {{}} {{api_key}}

1- Génération de la clé API :
Sur le site OpenAI Platform https://platform.openai.com/ aprés création de compte et connection.
Apres Authentification https://platform.openai.com/docs/api-reference/authentication
On navigue jusqu'à la section de gestion des API et on génére notre clé secrète personnelle "+ create new secret key".
2- Configuration dans Postman :
- J'ai lancé mon Postman et créez une nouvelle collection que j'ai nommé "OpenAI"
- Dans l'onglet "Variables" de cette collection, j'ai enregistré mon clé API. Ceci permet de réutiliser la clé à travers les différentes requêtes de la collection.
- Puis j'ai accédé à l'onglet "Authorization" : le service d'authentification émet un token d'accès : clé numérique ou de jeton d'identification qui vas autorisé l'accé.
- J'ai configuré la méthode d'authentification pour chaque requête de la collection en sélectionnant "Bearer Token", cette autorisation au serveur qui reçoit l'utilisation de la requête ce token pour vérifier que la requête est autorisée et procède à l'accès à la ressource. Ce token est souvent un string crypté qui contient ou référence des informations d'autorisation et une date d'expiration.
- Dans le champ au dessous pour le token, j'ai entré mon clé API en utilisant les doubles accolades {{api_key}} : Les doubles accolades sont utilisées pour référencer dynamiquement une valeur stockée ailleurs, ca veux dire indiquer à Postman de remplacer cette référence par la valeur réelle de la clé API stockée dans mon variables à chaque fois que je fais une requêtegit init