# Teorija

- API ir tas kas sūta informāciju starp frontend un backend, t.i. komunicē ar datu bāzi, lai veiktu darbības.

- Mainīgos definē izmantojot $ zīmi, un bez atstarpes rakstot mainīgā nosaukumu, piemēram, $validated.

- Laravel izmanto  Model-View-Controller arhitektūras modeli, Model atbild par datu pārvaldību un piekļuvi datiem, tas saņem un saglabā datus datu bāzē, veic to apstrādi un nodrošina pieejamību pārējām sistēmas daļām. View ir atbildīgs par datu attēlošanu lietotājam, tas parasti iegūst datus no Modeļa un attēlo tos lietotājam. Controller saņem lietotāja ievadi, pārvalda to un sazinās ar Modeļa un View komponentiem, lai apstrādātu lietotāja darbības.

- ORM ir Object-relational mapping, ļauj programmētājiem darboties ar datu bāzēm, izmantojot OOP conceptu, bez nepieciešamības rakstīt tīrus SQL queries

- ORM pieprasījums modelim User
$lietotaji = \App\Models\User::where('reitings', '>', 4)->get();

