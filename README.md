# Mastery Map

A Common Core–aligned learning planner for homeschool families. Mastery Map maps the curriculum, workbooks, games, and subscriptions a family already owns to Common Core standards, logs completed work, and uses Claude to recommend the best resource for each skill and to lead short guided tutorials.

## Why

Homeschool families often juggle several curricula, workbooks, learning games, and online subscriptions at once. Each one covers the standards differently, and it's hard to see at a glance which standards are on track, which are behind, and which resource already on the shelf would best fill a gap. Mastery Map puts all of that in one place.

## Planned features

### 1. Standards library
- Common Core State Standards for Math and ELA, organized by grade and domain, using the official codes (e.g., `4.NF.B.3`)
- Starts with Grade 4, with room to add other grades later
- Progress for each standard: not started, in progress, mastered

### 2. Resource inventory
- Catalog every learning asset: boxed curricula, workbooks, games, apps, and subscriptions
- Record subject, grade range, format (print, hands-on, video, game), and typical session length
- Tag lessons and units with the standards they cover
- Subscriptions are listed by name and content only — no logins or passwords are stored

### 3. Completion log
- Log completed lessons, pages, and activities against the standards they support
- Quick daily entry: page numbers and a short note
- Weekly and term summaries showing coverage and gaps

### 4. AI resource recommendations
- Claude reviews the resource inventory alongside the standards that need work
- Suggests which owned resource best supplements each target, with a short reason (for example, a game for fluency practice, or a hands-on lesson for a concept that hasn't clicked yet)
- Flags standards that no current resource covers

### 5. Claude-led mini tutorials
- Brief, grade-appropriate walkthroughs for a single standard
- Explain, show a worked example, then check understanding with a practice question
- Hand back to the parent with a short note on how it went

### 6. Printables
- A simple daily checklist for the student
- A teaching log for the parent, with open space for notes

## Privacy

Student records are meant to stay with the family. This repository contains no real student data; all examples use sample data.

## Roadmap

- [ ] Data model for standards, resources, and completions
- [ ] Load Grade 4 Common Core Math and ELA standards
- [ ] Resource inventory entry and standards tagging
- [ ] Completion logging and progress views
- [ ] Claude-powered resource recommendations
- [ ] Claude-led mini tutorials
- [ ] Printable daily checklist and teaching log
- [ ] Add more grade levels

## Status

Early development, starting with Grade 4. Built with an AI coding assistant.
