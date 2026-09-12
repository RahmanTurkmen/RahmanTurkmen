  <div align="center">

  # RAHMAN TURKMEN.

  ### `full-stack developer · Troyes, France`

  <a href="https://rahmanturkmen.com">portfolio ↗</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="mailto:xrahmanturkmen@gmail.com">contact ↗</a>

  <br />
  <br />

  ![Status](https://img.shields.io/badge/status-available-23d091?style=flat-square&labelColor=07080b)
  ![Focus](https://img.shields.io/badge/focus-full--stack-23d091?style=flat-square&labelColor=07080b)
  ![License](https://img.shields.io/badge/license-private-a2a5aa?style=flat-square&labelColor=07080b)

  </div>

  <br />

  > Je forge des applications web robustes, de l'architecture au déploiement.

  ---

  ## `01 / profil`

  Je suis **Rahman Turkmen**, développeur full-stack junior.  
  Je construis des interfaces propres, des APIs fiables et des applications pensées pour durer.

  ```text
  location   Troyes, France
  stack      JavaScript · PHP · Symfony · Node.js
  approach   clean code · sécurité · performance · accessibilité
  status     disponible
  ```

  ## `02 / technologies`

  <table>
    <tr>
      <td><strong>frontend</strong></td>
      <td>Next.js · React · JavaScript · HTML · CSS</td>
    </tr>
    <tr>
      <td><strong>backend</strong></td>
      <td>Node.js · PHP · Symfony · APIs REST</td>
    </tr>
    <tr>
      <td><strong>data</strong></td>
      <td>Supabase · PostgreSQL</td>
    </tr>
    <tr>
      <td><strong>infrastructure</strong></td>
      <td>Linux · Docker · Apache · VPS · PM2</td>
    </tr>
    <tr>
      <td><strong>principles</strong></td>
      <td>security by design · responsive · Lighthouse · privacy</td>
    </tr>
  </table>

  ## `03 / portfolio`

  Le portfolio est une interface personnelle conçue et développée par moi-même, avec une direction visuelle sombre, minimaliste et technique.

  ### points forts

  - navigation responsive avec menu secondaire ;
  - page projets et présentation de la stack ;
  - statistiques publiques agrégées et anonymisées ;
  - page 404 personnalisée ;
  - mentions légales et politique de confidentialité ;
  - changelog public ;
  - headers de sécurité et déploiement standalone ;
  - détection du pays par estimation réseau, sans conservation d'adresse IP.

  ## `04 / lancer le projet`

  ```bash
  npm install
  npm run dev
  ```

  Pour produire le package destiné à un VPS :

  ```bash
  npm run build:standalone
  ```

  Le package généré se trouve dans :

  ```text
  .next/standalone/
  ```

  Démarrage en production :

  ```bash
  node server.js
  ```

  ## `05 / configuration`

  Les statistiques utilisent Supabase côté serveur. Crée un fichier `.env.local` en développement ou `.env` à côté de `server.js` en production :

  ```env
  SUPABASE_URL=https://your-project.supabase.co
  SUPABASE_SERVICE_ROLE_KEY=server-only-key
  ANALYTICS_HASH_SECRET=long-random-secret
  GEOIP_DB_PATH=/opt/geoip/GeoLite2-Country.mmdb
  ```

  Les clés secrètes ne doivent jamais être exposées dans le navigateur ou commit dans Git.

  ## `06 / sécurité`

  - CSP, HSTS, `nosniff` et protection anti-iframe ;
  - validation stricte des entrées API ;
  - rate limiting des endpoints analytics ;
  - identifiants de session hachés ;
  - aucune conservation de nom, email ou adresse IP ;
  - données publiques limitées à des agrégats anonymisés.

  ## `07 / contact`

  Une question, une collaboration ou un retour ?

  **[xrahmanturkmen@gmail.com](mailto:xrahmanturkmen@gmail.com)**

  <br />

  <div align="center">

  `built with precision · protected by design · shipped from France`

  </div>
