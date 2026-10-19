# Rubric Builder

**Een Claude-skill die heldere, eerlijke beoordelingsrubrics bouwt, afgestemd op je leerdoelen of competenties.**

🇬🇧 [English version](README.en.md) · 📄 [Voorbeelden](examples/)

Je beschrijft de opdracht en plakt de leerdoelen erbij, en je krijgt een rubric met observeerbare niveaubeschrijvingen terug, plus een studentenversie en een korte kalibratiecheck voor collega-beoordelaars.

*English summary: a Claude skill that builds clear, fair assessment rubrics aligned to learning outcomes or competencies, with observable performance levels, a student-friendly version and a calibration check. It works in Dutch, French and English.*

## Wat de skill doet

- **Vertrekt van de leerdoelen.** Zonder leerdoelen geen valide rubric. Ontbreken ze, dan vraagt de skill ernaar, of leidt hij ze af uit de opdracht en benoemt hij ze duidelijk als aanname.
- **Vermijdt de drie klassieke fouten:**
  - criteria die niet aansluiten bij de leerdoelen
  - niveaus die alleen bijvoeglijke naamwoorden wisselen ("goed", "zeer goed", "uitstekend")
  - criteria die overlappen, zodat één zwakte twee keer punten kost
- **Schrijft observeerbare niveaus:** wat je ziet of leest op elk niveau. Niveaus verschillen in kwaliteit en diepgang, niet in aantallen.
- **Standaard 4 niveaus**, zonder "veilig midden", tenzij je systeem iets anders vraagt (/20, lettercijfers, geslaagd/niet geslaagd).
- **Denkt aan eerlijkheid:** geen criteria die culturele of taalachtergrond belonen in plaats van het leerdoel.
- **Volgt je taal en context:** Vlaams (leerplandoelen, ECTS-fiche), Nederlands (leerdoelen, OER), Franstalig (acquis d'apprentissage) of bedrijfsopleiding (competenties).

## Wat je terugkrijgt

1. **De rubric**: een tabel met criteria (en gewicht) als rijen en niveaus als kolommen
2. **Studentenversie**: dezelfde rubric in "jij"-taal, voor zelfevaluatie vóór het indienen
3. **Kalibratiecheck**: 2 à 3 grensgevallen om met collega's te bespreken
4. **Ontwerpkeuzes**: waarom deze criteria, deze weging, en wat bewust is weggelaten

Deel je een bestaande rubric, dan krijg je eerst een korte diagnose en daarna een verbeterde versie.

## Voor wie

Voor leerkrachten, docenten in het hoger onderwijs en trainers die opdrachten, projecten, presentaties, stages, portfolio's of praktijkvaardigheden beoordelen, van basisonderwijs tot bedrijfsopleiding.

Deze skill hoort bij **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, een open reeks voor onderwijs en L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): prompts voor leerkrachten, met uitleg waarom ze werken
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessen ontwerpen van leerdoel tot exit-check
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): toets- en examenvragen met sleutel en feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specifieke, haalbare feedback op leerlingenwerk
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): lesmateriaal toegankelijk maken met UDL
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): opleidingen en leertrajecten ontwerpen
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): een ruwe vraag omzetten in een sterke prompt voor Claude

## Installeren

**In Claude (web, desktop of mobiel):**
1. Download [`rubric-builder.skill`](rubric-builder.skill)
2. Upload het bij de Skills in je Claude-instellingen
   (of open het bestand in een gesprek met Claude en klik op *Save skill*)

**In Claude Code:** kopieer de map `rubric-builder/` naar `~/.claude/skills/`.

Daarna volstaat een gewone vraag, zoals *"maak een rubric voor stageverslagen, derde bachelor verpleegkunde"*. De skill start vanzelf.

## Structuur

```
rubric-builder/
└── SKILL.md            # de volledige instructies van de skill
examples/                 # voorbeelden van input en output
rubric-builder.skill    # installeerbaar pakket
```

## Bijdragen

Ideeën en verbeteringen zijn welkom via een issue of pull request.

## Licentie

[CC BY 4.0](LICENSE): vrij te gebruiken, aan te passen en te delen, met naamsvermelding.

---

Gemaakt door **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI-geletterdheid voor het onderwijs.
