1. smart_agent.py
Crée un agent simple capable de répondre à des questions grâce à des outils comme SerpAPI et LLM-Math.
Exemple : Répondre à "Quelle est la capitale de la Tunisie ?".

2. rag_chain.py
Met en place une chaîne Retrieval Question Answering (RAG) :

Charge un fichier de documents et génère des embeddings pour les indexer avec FAISS.

Permet de répondre à une question précise en récupérant l'information dans les documents.

3. memory_agent.py
Met en œuvre un agent avec mémoire conversationnelle :

Garde un historique des échanges en utilisant ConversationBufferMemory.

Gère intelligemment les interactions. Exemple : L'agent se souvient du prénom donné par l'utilisateur.

4. main.py
Montre un exemple d'exécution avec un prompt dynamique basé sur un template.
Exemple : Générer une liste de plats populaires pour une cuisine donnée.

5. prompts.py
Fichier contenant le template de prompt utilisé dans main.py.
Exemple : "Donne-moi {n} plats populaires de la cuisine {cuisine}."

6. requirements.txt
Liste des dépendances nécessaires (LangChain, FAISS, dotenv, etc.) à l'exécution du projet.

Fonctionnalités
Création et gestion d'agents intelligents.

Récupération d'informations dans des documents grâce à RAG.

Utilisation d'une mémoire conversationnelle pour des interactions continues.

Génération de contenu à l'aide de prompts personnalisables.
