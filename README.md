# The Race '26

Hartă interactivă a probei **The Race** din tabăra BBSO, ediția 2026.

## Acces

Aplicația e protejată cu utilizator și parolă. Conținutul e criptat AES-256 în fișier — fără parola corectă nu se poate citi nici din sursa paginii.

Datele de acces se dau doar echipei de organizare.

## Ce e înăuntru

**Tabul Hartă** — traseul complet, cu activitățile în ordine, împărțite pe două benzi și cu ramurile marcate prin culoare. Fiecare căsuță se deschide cu un click și arată desfășurarea, materialele, durata, locația și responsabilul. Harta se editează direct: rearanjezi căsuțele, adaugi etape noi, tragi și remodelezi săgețile.

**Tabul Listă activități** — tabel cu toate activitățile, o coloană pentru resursele și recuzita necesară, și o coloană de story-uri: textul care intră fizic în plicul fiecărui indiciu. Fiecare story se printează pe o pagină A4 separată, încadrat și cu literă mare, gata de tăiat și pus în plic. Există și buton de printat toate story-urile deodată.

Modificările se salvează automat pe dispozitivul tău, criptate cu aceeași parolă. Totul se poate exporta și importa ca fișier JSON.

## Tehnic

Un singur fișier HTML, fără dependențe și fără server. Merge deschis local prin dublu-click sau servit ca pagină web. Criptarea folosește WebCrypto (PBKDF2-SHA256, 250.000 de iterații, AES-256-GCM).

## Ediții anterioare

Proba face parte din cultura BBSO și se organizează în fiecare an.
