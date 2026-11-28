## 1. Spanish & EU open/distance universities (UNED-style)

**How the model actually works at UNED.** UNED's front door is not a degree — it's the free *identificador* (SOID) at <https://app.uned.es/soid>. You pick "Futuro Estudiante", verify an email + mobile, upload no diplomas, and get a user ID. Per UNED's own student-services page, choosing "futuro estudiante" makes **mailbox activation automatic**: `identificador@alumno.uned.es`, hosted on Outlook/Office 365, forwardable, and valid for anything that treats an institutional domain as proof of studenthood (<https://www.uned.es/universidad/inicio/en/estudios/idiomas/servicios-estudiante/acceso-correo-estudiante.html>). UNED's older service page ties the mailbox to "alumnos matriculados en Enseñanzas Regladas" (<https://serviweb.uned.es/ciberuned/publico/correo-alumnos.asp>), and Fundación UNED states the address exists "desde el momento en que se registran" (<https://blogs.uned.es/fundacionuned/correo-acceso-plataforma>). Residency: none. Passport/NIE/DNI accepted, no nationality filter.

**Cheapest ways to convert that ID into defensible student status** (because GitHub/SheerID increasingly ask for proof beyond a bare signup — GitHub requires the address be issued to *currently registered* students, <https://github.blog/developer-skills/career-growth/how-to-get-the-github-student-developer-pack-without-a-student-id>):

| Route | What you get | Cost (2025-26/2026-27 official) | Language | Residency |
|---|---|---|---|---|
| **UNED — UNED Idiomas (CUID)** | Enrolment as CUID student, campus, mailbox, O365, certifiable level course; 16+, no academic entry requirement | **170 €** online / 254 € semi-presential per course (<https://unedbarcelona.es/es/estudios/idiomes/uned-idiomas>); enrolment portal <https://www.uned.es/universidad/inicio/en/estudios/idiomas/matriculate.html> | Spanish (+ target language) | none |
| **UNED — single degree subject** | Full *matrícula*: expediente, campus, mailbox, exam rights. Minimum is **one subject** ("mínimo de una asignatura", <https://descargas.uned.es/publico/pdf/INSTRUCCIONES_DE_MATRICULA_GRADO_SEPTIEMBRE_25_26.pdf>) | 13,00–21,60 €/ECTS first sitting + **45,45 €** new-student secretaría + 1,12 € insurance → ~**125 €** for one 6-ECTS subject (<https://www.uned.es/universidad/inicio/dam/jcr:cb7f8d87-6295-4c87-bb03-5b7a09b7685f/precios-gradosUE2025-26.pdf>) | Spanish | none; needs an access route (PAU, prior degree, or >25/40/45) |
| **UNED — Curso de Acceso (25/45+)** | Access qualification **without Bachillerato**, then any degree | 484,80 € (25+) / 242,40 € (45+) (same price list) | Spanish | none |
| **UNED — microtítulos** | Microdegree; same per-credit price as official subjects, **no discounts**, access requirements of the parent degree apply | per-ECTS official rates (<https://descargas.uned.es/publico/pdf/INSTRUCCIONES_DE_MATRICULA_MICROTITULOS_SEPTIEMBRE_25_26.pdf>) | Spanish | none |

GitHub Student Pack on an `@alumno.uned.es` address: reported working — a Microsoft Q&A thread shows a user who already claimed **Microsoft 365 through the GitHub Student Developer Pack with a UNED academic address** (<https://learn.microsoft.com/en-us/questions/6026650/azure-for-students-youre-not-eligible-for-azure>), and the domain is a real issuer-restricted academic domain. Same address also unlocks **Office 365 A1** and UNiDAYS-type discounts. Practice: apply *after* the matrícula/CUID enrolment exists, keep the receipt PDF ready for a SheerID document check, and never reuse the address on a second GitHub account.

### Analogues that genuinely issue a credential

| Institution | What you get | Cost | Language | Residency | Notes / source |
|---|---|---|---|---|---|
| **Universidade Aberta (PT)** | *Número de estudante*, Portal Académico, PlataformAbERTA, **`numero@estudante.uab.pt`** on Microsoft 365 (<https://portal.uab.pt/si/microsoft365>) | 11,61 €/ECTS → **69,66 €** for a 6-ECTS isolated UC, plus candidatura/matrícula/insurance fees (<https://portal.uab.pt/wp-content/uploads/2026/05/2026-2027-Tabela-de-Propinas.pdf>) | Portuguese | none | Isolated UCs (1st cycle) are open "sem prévio acesso ou matrícula… por outros interessados" (<https://formacao.uab.pt/uc-isoladas/>); apply via <https://candidaturas.uab.pt>, windows ~May–Jun/Oct |
| **Open Universiteit (NL)** | Student number, mijnOU, online teaching, **`@student.ou.nl` mailbox** once a username + live course enrolment exist (<https://dlwo.screensteps.ou.nl/a/1655867-ou-mailbox-aanmaken-of-verwijderen>) | €82/EC statutory (EU nationals, no prior NL degree) = **€205** for the 2,5-EC minimum; €135/EC institutional for non-EU = €338 (<https://www.ou.nl/kosten>) | Dutch (some English) | none; non-residents legitimise after enrolment, no DigiD | Cheapest EU open-uni credential that clearly survives SheerID — it is a real WHW enrolment with tentamen rights |
| **FernUniversität in Hagen (DE)** | *Einschreibung* as Akademie-/Microcredentials student, Matrikelnummer, **`vorname.nachname@studium.fernuni-hagen.de`** (<https://www.fernuni-hagen.de/zdi/it-services/kommunikation-kollaboration/email-studium.shtml>) | **60 €/semester base + 11 €/ECTS** (a 10-ECTS module ≈ 110 €) (<https://www.fernuni-hagen.de/studium/studienangebot/akademiestudium.shtml>) | German | none; **no Abitur needed**, ID/passport only | ⚠️ Akademiestudium is being **retired**: Microcredentials-Studium replaces it from SS 2027, first admission **1 Dec 2026**, windows 1–31 Dec/1–31 Jun (<https://www.fernuni-hagen.de/studium/einschreiben/akademiestudium.shtml>) |
| **Swedish public universities (distance/"distanskurs")** | Registered student, student account + institutional mail at most institutions, Mecenat/Studentkortet card | **0 tuition and 0 application fee for EU/EEA/Swiss citizens**, distance courses included (<https://www.universityadmissions.se/en/find-out-more/for-our-eu-visitors>) | Mostly Swedish; English in some | EU/EEA citizenship must be documented | Highest-value option if you hold EU citizenship; needs prior upper-secondary equivalence, so not a warm-up route |
| **Polish public universities (Polish-taught, full-time)** | Full student status, USOS account, `@student.uni…` mail, legitymacja | **Free** for EU/EEA citizens on Polish-citizen terms (<https://www.studyinpoland.pl/en/education/18-tuition-fees>) | Polish | none | Needs matura equivalence + Polish; recruitment portals are per-university |
| **Czech public universities (Czech-taught)** | Student status, IS/STAG account, university mail | **Free** in Czech-language programmes, foreigners included (<https://studyin.gov.cz/plan-your-studies/scholarships-and-finances>) | Czech | none | Requires nostrification of secondary certificate + entrance procedure; not instant |

### Free-but-no-institutional-email (useful only for skills/portfolio)

- **EduOpen (IT)** — free university MOOCs, open to non-students, free attestation + Open Badge; verified certificates/CFU cost extra (<https://learn.eduopen.org/local/staticpage/view.php?page=EDUOPEN_certificazione_crediti>).
- **Federica.eu (Univ. Napoli Federico II)** — 700+ free courses, account only, no `@unina.it` address (<https://www.federica.eu>).
- **FUN-MOOC (FR)** — free registration, no institutional mail; French public universities' MOOC platform (<https://www.fun-mooc.fr/en>).
- **CNAM (FR)** — *auditeur* enrolment per UE, 95–250 €, `@lecnam.net` intranet access; not free, and the number is an auditor ID rather than a student card (<https://www.cnam-paysdelaloire.fr/formation-distance/inscription-tarifs>).
- **Finnish open universities** — ~20 €/ECTS, username/portal at some (UEF), mailbox inconsistent (<https://www.uef.fi/en/registration-study-fees-and-right-to-study>).
- **Norwegian universities** — no tuition for EU/EEA, ~NOK 700 semester fee, but single-course admission needs competence assessment.

### Dead, closed or overhyped (2025-26)

- **AULAbERTA (UAb's MOOC portal)** — `aulaberta.uab.pt` returned "serviço atualmente indisponível" (
### Dead, closed or overhyped (2025-26)

- **AULAbERTA (UAb's MOOC portal)** — `aulaberta.uab.pt` currently returns *"Este serviço está atualmente indisponível"* and redirects to `formacao.uab.pt`; the free MOOC entry point is broken, so UAb is only worth it via paid isolated UCs.
- **"Free trial" framing for Spanish private online universities** — real but narrow. **UNIR** has no free enrolment: you pay full *matrícula* (≈€3,000+/year for a grado), get `@unir.net` mail and campus, and only the *language level test* and info pack are free (<https://latam.unir.net/estudia-con-nosotros/becas-universitarias-y-precios>). **UOC** does let anyone take "asignaturas libres" with **no access requirements** (<https://www.uoc.edu/estudiant/portal/guia/es/lauoc/oferta_formativa/index.html>), and does issue `@uoc.edu` mail on enrolment, but a single 6-ECTS subject is **445 €** (<https://www.uoc.edu/es/estudios/formacion-continua/asignatura-sistemas-operativos>) — 3.5× UNED for the same outcome.
- **Italian *corsi singoli*** — genuine matriculation with a *matricola* and university mail, but €145,85 enrolment + €72,80–240 per course and a prior qualifying title (<https://www.unica.it/it/didattica/iscriversi-e-immatricolarsi/corsi-singoli>, <https://www.unive.it/corsisingoli>). EduOpen is the free substitute, minus the identity.

### Ranking for the actual objective (student identity cheaply, as a non-resident)

1. **UNED bare *identificador*** — €0, mailbox automatic, same day, no documents. Base layer; weakest against strict document checks.
2. **UNED Idiomas (170 €) or one UNED subject (~125 €)** — cheapest way to make that mailbox provably "registered student" and get exam/campus rights.
3. **Universidade Aberta isolated UC (≈70 € + fees)** — cheapest *non-Spanish* EU student number that comes with `@estudante.uab.pt`.
4. **Open Universiteit (€205)** — most robust credential, Dutch-language teaching, 2,5-EC floor.
5. **FernUni Hagen (€170/semester)** — no Abitur, real Matrikelnummer + `@studium.fernuni-hagen.de`; act before the Akademiestudium closes (admissions from 1 Dec 2026 for SS 2027 under the new scheme).
6. **Sweden / Poland / Czech** — free but gated on citizenship + language + diploma recognition.

### Operational caveats worth passing on

- **Registration ≠ matriculation at UNED.** The mailbox activates at SOID signup, but UNED's own service page still scopes mail to *Enseñanzas Regladas* students; anything that checks an expediente (certificate of enrolment, ISIC, some SheerID flows) needs the paid step.
- **Mailbox quirk:** `@alumno.uned.es` is OWA-only (no IMAP/POP), and UNED can redirect it to a personal address — verification links still arrive, but set forwarding before relying on it (<https://www.uned.es/universidad/inicio/en/estudios/idiomas/servicios-estudiante/acceso-correo-estudiante.html>).
- **One academic email, one GitHub account.** GitHub refuses reuse of an academic address across accounts (<https://docs.github.com/en/education/about-github-education/github-education-for-students/solving-problems-with-your-github-education-access>).
- **Timing:** UNED grado windows are Sept–Oct and Feb–Mar; UNED Idiomas opens in September for a November course start; UAb isolated-UC windows are ~May–Jun and Oct; OU and FernUni accept year-round (FernUni only in Dec/Jan and Jun/Jul).
- **All of these need a passport-type ID and a real mobile number for OTP**; none require a Spanish/EU address, and UNED explicitly lists *Pasaporte* and *Otros documentos oficiales* as valid (<https://www.uned.es/universidad/inicio/en/ctu/cau/identificador.html>).