<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Projet - Sécurité des Comptes & Utilisateurs sur Linux</title>
    <style>
        body {
            font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
            margin: 0;
            padding: 0;
            background: #0f172a;
            color: #e5e7eb;
            line-height: 1.6;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem 1.5rem 4rem;
        }
        header {
            text-align: center;
            margin-bottom: 2.5rem;
            padding: 2rem 1rem;
            background: radial-gradient(circle at top, #1d4ed8 0, #020617 55%);
            border-bottom: 1px solid #1f2937;
        }
        header h1 {
            margin: 0;
            font-size: 2.2rem;
            letter-spacing: 0.03em;
        }
        header p.subtitle {
            margin-top: 0.75rem;
            color: #9ca3af;
            font-size: 0.98rem;
        }
        .badge-row {
            margin-top: 1.2rem;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 0.5rem;
        }
        .badge {
            border-radius: 999px;
            padding: 0.25rem 0.9rem;
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 0.08em;
            border: 1px solid rgba(148, 163, 184, 0.7);
            color: #e5e7eb;
        }
        section {
            margin-bottom: 2rem;
            padding: 1.5rem 1.25rem;
            background: rgba(15, 23, 42, 0.9);
            border-radius: 0.75rem;
            border: 1px solid #1f2937;
        }
        section h2 {
            margin-top: 0;
            color: #bfdbfe;
            font-size: 1.3rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        section h2 span.emoji {
            font-size: 1.4rem;
        }
        h3 {
            margin-top: 1.5rem;
            font-size: 1.05rem;
            color: #e5e7eb;
        }
        p {
            margin: 0.3rem 0 0.6rem;
            color: #d1d5db;
        }
        ul {
            margin: 0.4rem 0 0.8rem 1.4rem;
            padding: 0;
        }
        li {
            margin-bottom: 0.2rem;
        }
        code {
            background: #020617;
            padding: 0.1rem 0.3rem;
            border-radius: 0.25rem;
            font-size: 0.9rem;
        }
        pre {
            background: #020617;
            padding: 0.9rem 1rem;
            border-radius: 0.5rem;
            overflow-x: auto;
            border: 1px solid #1f2937;
            font-size: 0.85rem;
        }
        pre code {
            background: transparent;
            padding: 0;
        }
        .structure-box {
            background: #020617;
            border-radius: 0.5rem;
            border: 1px solid #1f2937;
            padding: 0.9rem 1rem;
            font-family: "JetBrains Mono", Menlo, Monaco, Consolas, "Courier New", monospace;
            font-size: 0.85rem;
            color: #e5e7eb;
            overflow-x: auto;
        }
        .grid-2 {
            display: grid;
            grid-template-columns: minmax(0,1fr);
            gap: 1.2rem;
        }
        @media (min-width: 800px) {
            .grid-2 {
                grid-template-columns: minmax(0,1.1fr) minmax(0,0.9fr);
            }
        }
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.9rem;
            margin-top: 0.5rem;
        }
        th, td {
            padding: 0.5rem 0.6rem;
            border-bottom: 1px solid #1f2937;
            text-align: left;
        }
        th {
            background: #020617;
            color: #e5e7eb;
            font-weight: 600;
        }
        tr:nth-child(even) td {
            background: rgba(15, 23, 42, 0.7);
        }
        .pill {
            display: inline-block;
            padding: 0.1rem 0.65rem;
            border-radius: 999px;
            font-size: 0.75rem;
            border: 1px solid #374151;
            background: #020617;
            color: #9ca3af;
            margin-right: 0.3rem;
            margin-bottom: 0.2rem;
        }
        footer {
            text-align: center;
            padding-top: 1.5rem;
            border-top: 1px solid #1f2937;
            margin-top: 2rem;
            color: #6b7280;
            font-size: 0.85rem;
        }
        a {
            color: #60a5fa;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .step {
            margin-bottom: 1rem;
        }
        .step-title {
            font-weight: 600;
            color: #e5e7eb;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🛡️ Sécurité des Comptes & Utilisateurs sur Linux</h1>
            <p class="subtitle">Analyse, durcissement et gestion sécurisée des comptes utilisateurs — projet de portfolio en cybersécurité & administration système.</p>
            <div class="badge-row">
                <span class="badge">Linux Security</span>
                <span class="badge">Bash Scripting</span>
                <span class="badge">User Management</span>
            </div>
        </header>

        <section>
            <h2><span class="emoji">📝</span> Résumé du projet</h2>
            <p>
                Ce projet a pour objectif de sécuriser en profondeur la gestion des <strong>comptes</strong> et <strong>utilisateurs</strong> sur un système Linux.
                Il suit une approche professionnelle en plusieurs étapes : analyse, configuration propre, durcissement, automatisation par scripts, et rédaction d’un rapport final.
            </p>
            <p>Ce projet démontre notamment :</p>
            <ul>
                <li>la maîtrise de l’administration des utilisateurs et groupes sous Linux ;</li>
                <li>la gestion avancée des permissions, ACL, SUID/SGID et sudo ;</li>
                <li>la capacité à automatiser des audits avec des scripts Bash ;</li>
                <li>la rédaction d’une documentation technique claire et structurée.</li>
            </ul>
        </section>

        <section>
            <h2><span class="emoji">📁</span> Structure du projet</h2>
            <div class="structure-box">
<pre><code>security-users-management-linux/
│
├── README.html        # Ce document
│
├── 01-analyse/
│   ├── utilisateurs.md
│   ├── groupes.md
│   ├── permissions.md
│   └── suid-sgid-sticky.md
│
├── 02-configuration/
│   ├── creation-utilisateurs.md
│   ├── creation-groupes.md
│   ├── organisation-home.md
│   └── gestion-sudoers.md
│
├── 03-securisation/
│   ├── politiques-mots-de-passe.md
│   ├── verrouillage-comptes.md
│   ├── acl.md
│   └── reduction-suid.md
│
├── 04-scripts/
│   ├── audit-utilisateurs.sh
│   ├── audit-groupes.sh
│   └── audit-permissions.sh
│
└── 05-rapport/
    ├── rapport-final.pdf
    └── recommandations.md</code></pre>
            </div>
        </section>

        <section>
            <h2><span class="emoji">🎯</span> Objectifs principaux</h2>
            <div class="grid-2">
                <div>
                    <h3>🧩 Côté technique</h3>
                    <ul>
                        <li>Analyser les comptes, groupes et permissions existants.</li>
                        <li>Organiser proprement les utilisateurs et leurs groupes.</li>
                        <li>Appliquer des permissions sécurisées aux fichiers et dossiers.</li>
                        <li>Utiliser les ACL pour des droits précis et granulaires.</li>
                        <li>Mettre en place une politique de mots de passe robuste.</li>
                        <li>Réduire les risques liés à SUID/SGID et au fichier sudoers.</li>
                        <li>Automatiser des audits avec des scripts Bash.</li>
                    </ul>
                </div>
                <div>
                    <h3>👨‍💻 Compétences démontrées</h3>
                    <div>
                        <span class="pill">Linux administration</span>
                        <span class="pill">User & group management</span>
                        <span class="pill">Filesystem permissions</span>
                        <span class="pill">ACL & SUID/SGID</span>
                        <span class="pill">Sudo hardening</span>
                        <span class="pill">Bash scripting</span>
                        <span class="pill">Security audit</span>
                        <span class="pill">Technical writing</span>
                    </div>
                </div>
            </div>
        </section>

        <section>
            <h2><span class="emoji">🚀</span> Plan complet du projet (étapes)</h2>
            <p>Le projet est découpé en cinq grandes étapes, chacune correspondant à un dossier du projet.</p>

            <div class="step">
                <p class="step-title">1️⃣ Analyse du système – <code>01-analyse/</code></p>
                <p><strong>Objectif :</strong> comprendre l’état initial des comptes et permissions.</p>
                <ul>
                    <li>Lister tous les utilisateurs et identifier ceux qui peuvent se connecter.</li>
                    <li>Analyser les groupes existants et les membres des groupes sensibles (ex : <code>sudo</code>).</li>
                    <li>Vérifier les permissions des dossiers utilisateurs (ex : <code>/home</code>).</li>
                    <li>Identifier les fichiers avec SUID/SGID et sticky bit.</li>
                    <li>Analyser les logs d’authentification (ex : <code>/var/log/auth.log</code>).</li>
                </ul>
                <p><strong>Fichiers produits :</strong> <code>utilisateurs.md</code>, <code>groupes.md</code>, <code>permissions.md</code>, <code>suid-sgid-sticky.md</code></p>
            </div>

            <div class="step">
                <p class="step-title">2️⃣ Configuration propre – <code>02-configuration/</code></p>
                <p><strong>Objectif :</strong> mettre en place une base saine pour les comptes.</p>
                <ul>
                    <li>Créer des utilisateurs selon les bonnes pratiques (shell, home, UID).</li>
                    <li>Créer des groupes logiques (ex : <code>devs</code>, <code>ops</code>).</li>
                    <li>Organiser les dossiers <code>/home</code> et les droits par défaut.</li>
                    <li>Configurer l’accès sudo de manière stricte et limitée.</li>
                </ul>
                <p><strong>Fichiers produits :</strong> <code>creation-utilisateurs.md</code>, <code>creation-groupes.md</code>, <code>organisation-home.md</code>, <code>gestion-sudoers.md</code></p>
            </div>

            <div class="step">
                <p class="step-title">3️⃣ Sécurisation avancée – <code>03-securisation/</code></p>
                <p><strong>Objectif :</strong> durcir le système et réduire la surface d’attaque.</p>
                <ul>
                    <li>Définir une politique de mots de passe (expiration, complexité) avec <code>chage</code>.</li>
                    <li>Verrouiller les comptes inutilisés ou à risque.</li>
                    <li>Appliquer des ACL pour des cas de permissions spécifiques.</li>
                    <li>Réduire ou supprimer les SUID/SGID non nécessaires.</li>
                    <li>Sécuriser les répertoires partagés (sticky bit, options de montage).</li>
                </ul>
                <p><strong>Fichiers produits :</strong> <code>politiques-mots-de-passe.md</code>, <code>verrouillage-comptes.md</code>, <code>acl.md</code>, <code>reduction-suid.md</code></p>
            </div>

            <div class="step">
                <p class="step-title">4️⃣ Automatisation de l’audit – <code>04-scripts/</code></p>
                <p><strong>Objectif :</strong> rendre l’audit répétable et rapide.</p>
                <ul>
                    <li><code>audit-utilisateurs.sh</code> : lister les utilisateurs, shells, comptes verrouillés.</li>
                    <li><code>audit-groupes.sh</code> : analyser les groupes sensibles et leurs membres.</li>
                    <li><code>audit-permissions.sh</code> : détecter des permissions anormales.</li>
                </ul>
                <p><strong>Exemple d’exécution :</strong></p>
                <pre><code>chmod +x 04-scripts/audit-utilisateurs.sh
sudo ./04-scripts/audit-utilisateurs.sh</code></pre>
            </div>

            <div class="step">
                <p class="step-title">5️⃣ Rapport final – <code>05-rapport/</code></p>
                <p><strong>Objectif :</strong> présenter le résultat de manière professionnelle.</p>
                <ul>
                    <li>Description du contexte et des objectifs.</li>
                    <li>Résumé de l’analyse initiale.</li>
                    <li>Liste des vulnérabilités ou risques identifiés.</li>
                    <li>Mesures de remédiation appliquées.</li>
                    <li>Recommandations complémentaires.</li>
                </ul>
                <p><strong>Fichiers produits :</strong> <code>rapport-final.pdf</code>, <code>recommandations.md</code></p>
            </div>
        </section>

        <section>
            <h2><span class="emoji">🧰</span> Technologies & outils</h2>
            <table>
                <tr>
                    <th>Domaine</th>
                    <th>Outils principaux</th>
                </tr>
                <tr>
                    <td>Administration Linux</td>
                    <td><code>useradd</code>, <code>usermod</code>, <code>groupadd</code>, <code>passwd</code>, <code>chage</code></td>
                </tr>
                <tr>
                    <td>Permissions & sécurité</td>
                    <td><code>chmod</code>, <code>chown</code>, <code>setfacl</code>, <code>getfacl</code>, SUID/SGID, sticky bit, <code>sudo</code></td>
                </tr>
                <tr>
                    <td>Audit & logs</td>
                    <td><code>journalctl</code>, <code>last</code>, <code>who</code>, <code>grep</code>, <code>find</code>, <code>/var/log/auth.log</code></td>
                </tr>
                <tr>
                    <td>Automatisation</td>
                    <td>Bash scripting, scripts d’audit personnalisés</td>
                </tr>
                <tr>
                    <td>Documentation</td>
                    <td>Markdown, PDF, ce fichier HTML</td>
                </tr>
            </table>
        </section>

        <section>
            <h2><span class="emoji">👤</span> Auteur</h2>
            <p>
                Projet réalisé par <strong>[Ton Nom / Ton Pseudo]</strong><br>
                Dans le cadre de mon portfolio en <strong>cybersécurité</strong> et <strong>administration système Linux</strong>.
            </p>
            <p>
                Vous pouvez adapter ce fichier en ajoutant vos liens :
            </p>
            <ul>
                <li><strong>GitHub :</strong> <code>https://github.com/votre-pseudo</code></li>
                <li><strong>LinkedIn :</strong> <code>https://www.linkedin.com/in/votre-profil</code></li>
                <li><strong>Email :</strong> <code>votre.email@example.com</code></li>
            </ul>
        </section>

        <footer>
            &copy; <span id="year"></span> – Projet "Sécurité des Comptes & Utilisateurs sur Linux".<br>
            Conçu comme démonstration pratique de compétences en sécurité système.
        </footer>
    </div>
    <script>
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>