# Open Sea School V2 — L’école du grand large

A project by **KETH / BEKW-code**. **SheIsZoe** is the production assistant, with AI-assisted implementation.

> « J’ai aimé mettre un coup de tournevis pour KETH. Tout est à lui. »
>
> “I enjoyed lending a screwdriver to KETH. This is his project.”

Playful, free learning for children and teenagers, designed to work offline on modest devices. No account, advertising, tracking, subscription, remote AI or downloaded font is needed to use the school. Illustrations and optional short sounds are generated locally. Low energy use is a design aim; no measured energy savings are claimed.

## Open the school

[Play online / Jouer en ligne](https://sheiszoe-art.github.io/open-sea-school-v2/)

- [English school](en/OPEN-SEA-SCHOOL.html)
- [École française](fr/OPEN-SEA-SCHOOL.html)
- [Download the offline edition](Open-Sea-School-V2-Offline.zip)
- [Choose your language](index.html)

Download the ZIP, extract it and open **index.html**. Keep its `en/` and `fr/` folders beside that file. No installation, server or network is required for lessons and games. External creator references require a connection. Modern browsers are supported; animation reduction is respected.

## What is included

Each language contains **810 course entries**: nine subject areas × nine age bands (roughly 6–15) × ten courses. Each entry connects to a playable activity and a scripted, six-stage Captain Claw lesson. The French classroom is Capitaine Pince; the English classroom has native English instructions. Language subject exercises may intentionally contain the language being studied.

The activities use **25 shared interaction families**, with course-specific prompts, parameters and procedural variations where supported. This is not a claim of 810 unrelated game engines. The English and French explanatory lessons differ in their examples and editorial treatment. Advanced titles and replay counts do not establish complete curriculum coverage.

The school also includes the lobster studio, sea jokes, arcade, brain teasers, sandpit, practical life topics, journals and offline support documents. The classroom opens without restarting the school activity. Returning to the game preserves the live mission. The classrooms do not award school-game medals. English and French journals are separate; export progress regularly, since browser storage can be cleared and file-based storage behaviour varies between browsers.

## Verification and educational limits

Automated checks cover all **1,620 course entries**, their teacher links, six teaching stages per entry, valid and invalid solutions across 12 configurations per game, slider limits and all 25 game families. See [the audit](VERIFICATION-V2.json).

These checks simulate documents and interactions. They do **not** replace tests on real devices, teaching review, accessibility assessment or trials with learners. The lessons are an educational prototype, not an accredited school, qualification, complete national curriculum or evidence of general cognitive improvement. See each language’s sources and coverage page.

## Creator, credits and rights

The original idea and project belong to **KETH**. Attribution does not imply his approval of each lesson or change.

- [KETH’s GitHub](https://github.com/BEKW-code)
- [KETH’s gists](https://gist.github.com/BEKW-code)
- [NightCafe artwork](https://creator.nightcafe.studio/u/KetharMolisheNuvahel)
- [Suno music](https://suno.com/@hardtogovern)
- [Artist profile](https://www.einpresswire.com/article/944403908/the-eternal-wizard-king-builds-a-genre-defying-soundworld-from-ai-open-source-and-cosmic-stand-up)

Read [the credits](en/CREDITS.html), [the French credits](fr/CREDITS.html), [LICENSE](LICENSE) and [RIGHTS.md](RIGHTS.md). MIT applies to the adaptation’s own contributions; pre-existing works retain their owners’ rights and conditions. No ownership of third-party work is transferred by these credits.

## Edit and rebuild

The delivered HTML files run without development tools. For contributors, Node.js 18+ is enough; no dependency installation is needed.

```sh
npm run build
npm test
```

`source/` holds the V2 interface modules, styles, English localization and English classroom. `source-templates/` holds the original credited school engines, French classroom master and language landing page. `scripts/build.cjs` rebuilds both schools and classrooms. Other HTML support documents can be edited directly. The offline ZIP is regenerated separately from the delivered language folders, avoiding source-template duplication.

The V1 repository is preserved. V2 is a separate repository and release line.

## En français

Ouvre **index.html**, choisis ta langue puis une matière. Chaque parcours propose dix cours, leur mini-jeu et une explication du capitaine. Les deux versions sont séparées et jouables hors connexion. Le projet reste un prototype pédagogique à relire avec des enseignants et à tester sur de vrais appareils. Les crédits de KETH et le rôle d’assistante de réalisation de SheIsZoe sont conservés.
