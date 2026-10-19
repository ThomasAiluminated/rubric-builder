# Rubric Builder

**A Claude skill that builds clear, fair assessment rubrics aligned to learning outcomes or competencies.**

🇧🇪 [Nederlandstalige versie](README.md) · 📄 [Examples](examples/)

Describe the assignment and paste the learning outcomes, and get a rubric with observable performance levels, a student-friendly version and a short calibration check for co-assessors.

It works in English, Dutch and French: it replies in the language you write in.

## What the skill does

- **Starts from the learning outcomes**, and labels them as assumptions if it has to infer them.
- **Avoids the three classic flaws:** criteria that don't match the outcomes, levels that only swap adjectives, and overlapping criteria that punish one weakness twice.
- **Observable levels** that differ in quality and depth, not quantity. Four levels by default.
- **Fairness built in:** no criteria that reward background rather than the outcome.

## What you get

1. **The rubric**: criteria (with weights) × levels
2. **Student version** in plain "you"-language
3. **Calibration check**: 2–3 borderline cases
4. **Design notes**

See [examples/](examples/) for a full input and output.

## Who it's for

Teachers, lecturers and trainers who assess assignments, projects, presentations, internships, portfolios or practical skills.

This skill is part of **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, an open collection for education and L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): ready-to-paste prompts for teachers, with the pedagogy behind them
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessons designed from objective to exit check
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): test and exam questions with answer key and feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specific, actionable feedback on student work
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): accessible lesson materials using UDL
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): training programs and learning journeys
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): rough requests turned into strong prompts for Claude

## Install

**In Claude (web, desktop or mobile):**
1. Download [`rubric-builder.skill`](rubric-builder.skill)
2. Upload it under Skills in your Claude settings
   (or open the file in a Claude conversation and click *Save skill*)

**In Claude Code:** copy the `rubric-builder/` folder to `~/.claude/skills/`.

Then just ask, for example *"a rubric for third-year nursing internship reports"*. The skill starts automatically.

## Contributing

Ideas and improvements are welcome via an issue or pull request.

## License

[CC BY 4.0](LICENSE): free to use, adapt and share, with attribution.

---

Made by **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI literacy for education.
