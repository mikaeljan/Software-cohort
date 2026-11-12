# Lessons

## Glossary entries written too thin

**Pattern:** Wrote a CONTEXT.md entry that named the term but left out what is being asked for, which states it can be in, and what that means for the user. Agreed details stayed in chat instead of going into the glossary.

**Rule:** Before saving a glossary entry, check it against this test: could a new developer who reads only this entry say exactly what the user asked for and which state the user is in? If not, add the missing pieces or list them as open questions. Write each resolved state or label into CONTEXT.md as soon as it is agreed.

## Glossary entries mixed meaning with behaviour

**Pattern:** Put processes ("reviewed by hand"), mechanisms ("to the learner's card") and system rules ("the learner loses access") into CONTEXT.md definitions.

**Rule:** A glossary entry says what the term means, never how it is carried out or what the system does because of it. Collect agreed business rules for the PRD or issue instead. Check each clause: if the meaning stays the same when the clause is removed, the clause is behaviour and goes elsewhere.

## Grilling drifted from defining terms into product changes

**Pattern:** A session meant to settle terminology turned into questions about what the settings page should show and other behaviour changes.

**Rule:** Keep to the scope the user set. In a terminology session, only ask questions whose answer changes a definition. Behaviour gaps found along the way go into a short "spotted" list at the end and are not asked as questions.
