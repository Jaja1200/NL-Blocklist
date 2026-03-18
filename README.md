# NL/BE Third-Party Trackers & Ads Blocklist

Een compacte lijst (~200 domeinen) met veelvoorkomende third-party trackers, advertenties, analytics en fingerprinting-domeinen die vaak op Nederlandse en Belgische sites voorkomen (nieuws zoals AD.nl, Volkskrant, RTL, Videoland, webshops etc.).

**Waarom deze lijst?**  
- Klein formaat → minder kans op kapotte sites (false positives)  
- Focus op NL/BE: dpgmedia.net, sanomaads.nl, ads.talpa.nl, tracking.rtlnieuws.nl etc.  
- Inclusief internationale: Google, Meta, Criteo, Taboola, FingerprintJS, SEON, Riskified etc.  
- Gebaseerd op netwerk-scans in 2026.

**Hoe gebruiken?**  
- **Pi-hole / AdGuard Home**: Voeg deze URL toe als blocklist:  
  https://raw.githubusercontent.com/Jaja1200/NL-BE-Third-Party-Trackers-Ads-Blocklist-/refs/heads/main/peetjesblocklist.txt
  (of hosts.txt voor 0.0.0.0-formaat)  
- **uBlock Origin**: Importeer als custom filter (of converteer naar ABP-stijl).  
- **Andere tools**: Kopieer de domeinen handmatig.

**Categorieën** (zie bestanden voor details):  
- Advertising / Ad Networks  
- Analytics & Behaviour Tracking  
- Social Media Pixels  
- IP Geolocation & Fingerprinting  
- NL/BE-specifiek (DPG, Sanoma, Talpa etc.)

**Instagram & Snapchat blijven gewoon werken**  
Met deze blocklist blijven Instagram en Snapchat normaal functioneren (feed, stories, snaps, login etc.) zonder dat je extra iets hoeft te doen of whitelists toe te voegen.

Laatste update: Maart 2026  
Suggesties / nieuwe domeinen? Maak een issue of pull request!

PR's welkom. Gebruik op eigen risico – test op je favoriete sites.