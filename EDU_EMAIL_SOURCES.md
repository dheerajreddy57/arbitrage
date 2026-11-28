# Free .edu / Student Email Sources & Student-Verification Routes
> Deep research compiled 2026-11-28. Goal: legitimate routes to a student/edu identity (email + verification) that unlock student discounts.

## TL;DR
- **The email stopped being the key.** Almost every serious program now verifies against an enrollment roster via SheerID / school SSO, re-checks every 6-12 months, and caps the benefit by years or credits. A domain that merely *looks* academic buys very little.
- **Cheapest honest routes to a real student identity:** UNED *identificador* (free, same-day, Spain, no residency) as the base layer, then one UNED subject (~EUR125) or UNED Idiomas (EUR170) to make it provably "registered"; Universidade Aberta isolated UC (~EUR70 + fees) for a non-Spanish EU student number; Open Universiteit NL (EUR205) as the most robust SheerID-proof credential.
- **US route:** a California community college 1-unit online course — free to apply, mailbox minted automatically at SMC (~2 min, before payment), but ~$31-46/unit only with a CA address (Foothill waiver); ~$121-140/unit out-of-state (Clovis CC).
- **No institutional email? The verifiers all have a documented document-upload path** (SheerID/UNiDAYS/Student Beans). One clean current-term enrollment letter (PDF) on your phone clears the widest range of flows.
- **Dead by 2026:** free Copilot Pro, ChatGPT free Plus, Google Workspace personal signup, Microsoft 365 A1, Canva higher-ed, DigitalOcean credits, ASU Universal Learner email. GitHub Pack still works but Copilot Student activations are paused.

## Contents
0. The UNED model (the documented base case)
1. Spanish & EU open/distance universities (UNED-style)
2. Cheap/free community college & lifelong-learning enrollment (US & global)
3. Free edu email providers & alumni/lifelong routes
4. Direct student-verification services (no .edu needed)
5. What a .edu actually unlocks (and what's gated hard now)
6. Existing curated lists, forums, and community threads

---

## 0. The UNED model (documented)
**What it is:** UNED is Spain's national open university (distance learning, ~150k students). Its identity portal (SOID) accepts registrations from anyone — no enrollment, no payment, no residency.

**Flow:** open `app.uned.es/soid/email-registro` → "Registrarte" → tick "Futuro estudiante" / "He sido informado" → fill passport/DNI-type data → confirm via the emailed link → receive an **Identificador de usuario**. The mailbox is auto-created as `<identificador>@alumno.uned.es` and is a fully working IMAP/webmail account.

**Friction points:**
- Domain is `alumno.uned.es`, not `uned.es` — services matching a literal `.edu` root or a country TLD may reject it; UNiDAYS/SheerID generally accept it.
- Sort-of-student status: some flows ask for "student ID"/enrollment proof, which a "futuro estudiante" does not have.
- Spanish-language forms; no cost.
- Auto-renewal of student pricing can fail 12 months later if the account gets pruned for inactivity.

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

## 2. Cheap/free community college & lifelong-learning enrollment (US & global)

The California community college (CCC) route works because of three structural facts, not a loophole: admission is **open** (high-school diploma, GED, or simply being 18+ — no SAT, ACT, essay or recommendations), the application is **free** through the statewide CCCApply/OpenCCC portal, and you are billed **per unit** only after you register. Nothing requires you to set foot on campus: every CCC runs fully online sections, and non-residents are classified by a residency questionnaire, not by a visa or a lease. A single 1-unit online course — typically something like *Career Planning*, *College Success*, or a 1-unit PE/health section — generates a real student record, a student ID number, portal access, and an institutional mailbox. That is the whole trick, and it costs less than most paid "student discount" services.

The catch is that "free for residents" is a *residency* claim, and CCC residency for tuition purposes requires physical presence in California for 366 days plus intent to remain (the [CCCC residency overview](https://www.cccco.edu/wp-content/uploads/2020/04/2020_Residency_Overview_Document_a11y.pdf) spells out the tests). If you actually live in California, the statutory enrollment fee is waived or refunded by the California College Promise Grant and district Promise programs; if you don't, you pay the non-resident rate below. Note too that most district "free tuition" promises are built for **first-time full-time** students (12+ units), so a single-unit enrollment usually does *not* trigger them — the CCPG fee waiver, which has no unit minimum, is the mechanism that actually zeroes out a 1-unit bill for low-income CA residents.

### US options, with real 1-unit arithmetic

| College | Resident enrollment fee | Non-resident tuition | Real cost, 1 online unit | Email domain | Email issued |
|---|---|---|---|---|---|
| [Santa Monica College](https://www.smc.edu/admission-aid/tuition-fees) (CA) | $46/unit ([catalog](https://catalog.smc.edu/24-25/admission-attendance/fees-tuition.php)) | $398/unit, rising to $416 Fall 2026 | **≈$505** ($46 + $398 + $60.50 mandatory health/benefits fees) | `@student.smc.edu` | **Automatically, ~2 min** after activating online services — before payment |
| [De Anza College](https://www.deanza.edu/cashier/fees_glance.html) (CA) | $31/unit | $253/unit | ≈$347 | `@fhda.edu` | After application processed + registration |
| [Foothill College](https://www.foothill.edu/apply-and-register/cashier/fees.html) (CA) | $31/unit | $249/unit ($253 from Summer 2026) | ≈$310 — or **$31 + fees** if you have a CA address and ≤6 units ([waiver](https://foothill.edu/reg/cashier/fees.html)) | `@fhda.edu` | After registration |
| [Clovis CC](https://www.clovis.edu/payment/tuition-fall.aspx) (NM) | $48/unit in-district | **$121/unit** — cheapest non-resident rate found | ≈$140 with fees | `@clovis.edu` | After registration |
| [Odessa College](https://catalog.odessa.edu/content.php?catoid=15&navoid=928) (TX) | ~$100/unit in-district | $227/credit (3-credit minimum) | ≈$681 (3 units) | `@odessa.edu` | After registration |
| [Maricopa district](https://www.maricopa.edu/students/tuition-payment-information/tuition-fees) (AZ) | $97/credit | $253/credit distance learning | ≈$253+ | `@maricopa.edu` | After registration |

Two policy notes worth knowing. Foothill-De Anza's non-resident waiver covers **all** non-F-1 students with a current California address taking ≤6 combined units — the single cheapest legitimate way to hold a CCC identity from inside California ($31/unit, no tuition). And per [BestColleges](https://www.bestcolleges.com/online-schools/community-colleges/affordable), 34 states now charge no tuition to qualifying residents, so if you live in one, the arithmetic collapses to fees only.

### Steps (identical at every CCC)

1. Create an OpenCCC account at [cccapply.org](https://www.cccapply.org) — free, no fee, no test scores ([CCCApply confirms $0](https://openccc-support.zendesk.com/hc/en-us/articles/15499241455117-How-much-does-it-cost-to-apply); only some colleges add an *international-student* application fee).
2. Complete the application and the residency section: answer "no" to the 366-day California-presence question and you are auto-classified a non-resident — you do **not** need an F-1 visa or an international-office application unless you want full-time on-campus study.
3. Receive your student ID (usually 24–72 h), activate the college portal (Corsair Connect at SMC, MyPortal at Foothill-De Anza), which is what mints the mailbox.
4. Register for a 1-unit online class during open enrollment; pay by the deadline.
5. Optional: request a free enrollment-verification letter or unofficial transcript from the registrar — the document third-party verifiers actually want.

### Does it pass SheerID / UNiDAYS / Student Beans?

Partly, and predictably so. All three platforms key off an **institution database plus a school-issued email or ID**, and regionally accredited, degree-granting community colleges are normally in those databases — SheerID explicitly covers "degree-granting institutions recognized by the official governing body" and non-degree post-secondary schools offering semester-length courses ([SheerID audience docs](https://sheerid.zendesk.com/hc/en-us/articles/26408738570779-Student-audience-overview)). Where it breaks:

- **`.edu` alone is not proof.** GitHub's docs state that "if your school issues email addresses prior to paid student enrollment, we require further proof of your academic status" — ID, schedule, transcript ([GitHub docs](https://docs.github.com/en/education/about-github-education/github-education-for-students/solving-problems-with-your-github-education-access)). CCCs issue the mailbox before payment, so this rule hits them directly.
- **SMC restricts the mailbox to internal mail until your first class starts** ([SMC IT](https://admin.smc.edu/administration/information-technology/academic-computing/student-it-help/email-account.php)), which will silently eat a UNiDAYS or SheerID confirmation code. Pay and wait for the term to begin, or use manual document upload.
- UNiDAYS only accepts school-issued addresses and falls back to student-ID photo upload when the domain isn't listed ([UNiDAYS support](https://www.myunidays.com/US/en-US/support/logging-in/contact)); Student Beans does the same with card, acceptance letter, transcript or schedule screenshot ([Student Beans](https://help.studentbeans.com/hc/en-us/articles/25286844000412-Troubleshooting-Student-Status-Verification-Issues)).
- Accounts are re-verified annually; a dropped class or stale term revokes both the email and the discount.

### International equivalents

| Country / school | Cost | Email / ID | Reality check |
|---|---|---|---|
| **Mexico — [UVEG](https://uveg.edu.mx/oferta-educativa/preparatoria-en-linea-uveg)** (Guanajuato virtual university) | Prepa: **MXN 600 one-time** (~US$33) + MXN 570 placement exam + MXN 58/module | `matricula@es.uveg.edu.mx` ([guide](https://d18xmwba1oz3vx.cloudfront.net/ssma/images/guias_2020/Ingreso_Utilizo_CorreoInstitucional.pdf)) | Rolling enrollment 365 days/year, official SEP validity. Best non-US value; domain is `.edu.mx`, not `.edu` |
| **Philippines — [UP Open University](https://registrar.upou.edu.ph/enrollment-procedure-for-non-degree)** | PHP 1,000/unit (~US$17) + PHP 2,000 misc ([fee sheet](https://www.upou.edu.ph/wp-content/uploads/2023/10/UPOU-of-Brochure.pdf)) | `@up.edu.ph`, requested from techsupport after enrollment ([UPOU helpdesk](https://helpdesk.upou.edu.ph/support/solutions/articles/48001152765-i-am-a-new-upou-student-how-can-i-get-my-up-mail-account-)) | Non-degree status needs TOR + 2×2 photos + faculty/dean approval, renewed each term — weeks of paperwork, not instant |
| **India — [IGNOU](https://www.ignou.ac.in/)** | Non-SAARC overseas fee US$200–500 **per year/programme** ([overseas fee table](https://iop.ignouonline.ac.in/docs/brochure_for_international_students.pdf)) | Personal email; no automatic institutional mailbox | Cheap per year but coarse: you enroll in a programme, not a 1-unit course; `.ac.in` addresses are staff/regional-centre |
| **Spain — [UNED](https://www.uned.es/)** | €13–21.60/ECTS first enrollment ([2026-27 rates](https://www.europapress.es/sociedad/educacion-00468/noticia-aprobados-precios-academicos-uned-van-13-euros-derecho-filosofia-216-ingenieria-20260608123639.html)); ~9-ECTS minimum ≈ €120–195 | `identificador@alumno.uned.es`, issued on registration ([UNED](https://www.uned.es/universidad/inicio/en/estudios/idiomas/servicios-estudiante/acceso-correo-estudiante.html)) | Genuinely open-access, no entrance exam, fully online — but priced for a degree, and the subdomain address is often rejected by US verifiers |

Eastern Europe is weaker than it looks: Polish open-university courses (UW, UJ) and Czech lifelong-learning modules are cheap (PLN 300–600 / a few thousand CZK) but usually issue a *certificate*, not a student record with an email, with manual per-semester signup — worth it for the course, not for the .edu-adjacent identity.

### Drawbacks, in order of how often they bite

- **Payment is not optional and deadlines are brutal.** SMC drops unpaid registrations the day after you add ([SMC policy](https://www.smc.edu/admission-aid/tuition-fees)); "enroll free and never pay" gets you a dead record within 48 hours, and the mailbox with it.
- **Residency is audited** and can be reclassified retroactively with a back-bill; an address you don't occupy is the usual cause.
- **1-unit enrollment is thin proof.** Verifiers see part-time, non-degree-seeking status; SheerID flows that expect a `.edu` sign-in to a Microsoft/Google tenant frequently stall, because CCC tenants don't expose the SAML handshake they want.
- **Mailbox lifetime tracks the term** — access and pricing lapse when you stop enrolling, and re-verification then asks for a current-term document you no longer have.
- **Foreign domains fail naive `.edu` regex checks** and many US-only offers simply don't list non-US institutions.
- **F-1 students are excluded** from the Foothill waiver and must use the international office with I-20 and proof of funds.
- **Sets a paper trail:** grades post, transcripts exist, and a withdrawn class stays visible.

**Bottom line:** for a US-based person the honest floor is **~$31–46/unit with a California address (Foothill waiver) or ~$121–140/unit out-of-state at Clovis CC**, not free; SMC and De Anza are the name-brand picks at ~$310–505 for one unit. Outside the US, UVEG (~US$33 total) and UPOU (~US$17/unit) are an order of magnitude cheaper than a CCC and issue working institutional mail — but need manual document verification, and neither gives you a `.edu`.

## 3. Free edu email providers & alumni/lifelong routes

**First, the distinction that decides everything.** A *real mailbox on a school domain* (you can send, reset, and log in) behaves very differently from a *forwarding alias* (receive-only), and both differ from a *lookalike domain* (`edumaili.com`, `.edu.pl`). SheerID's own product team now says a college address "is no longer enough to verify student enrollment. Many graduates still have access to these accounts, creating a major student offer loophole" ([SheerID, May 2026](https://www.sheerid.com/business/blog/prevent-student-offer-abuse-replace-edu-email-verification/)). So alumni routes buy you *deliverability* and *institutional legitimacy*, not automatic discount eligibility. SheerID only verifies graduates if the brand enabled the US-only **"University graduates"** sub-segment ([SheerID knowledge base](https://sheerid.zendesk.com/hc/en-us/articles/26408738570779-Student-audience-overview)); UNiDAYS expires your student membership and downgrades you to **GRADLiFE** for 3 years, with a reduced benefit set ([UNiDAYS GRADLiFE FAQ](https://www.myunidays.com/GB/en-GB/content/gradlife-download)).

### 3.1 Alumni retention: the ones that still work, and the wave that killed the rest

Some universities still run genuine alumni mailboxes or forwarding, and are the cheapest legitimate route if you already hold the degree:

- **MIT** — `@alum.mit.edu` is a full Outlook mailbox marketed as "Email for Life" ([tracker](https://www.dukebrokenpromises.com/tracker)).
- **Stanford** — free `@alumni.stanford.edu` mailbox for anyone enrolled three quarters or more, no membership fee, though terms reserve the right to end it.
- **Yale** — YaleMail on `@aya.yale.edu`, 5 GB cap.
- **Princeton** — free alumni Workspace mailbox replaced plain forwarding; Class of 2026 onward get no forwarding.
- **Michigan** — `@umich.edu` forwarding retained free.
- **Harvard** — reversed its 2022 shutdown after a ~2,800-signature petition; `@post.harvard.edu` / `@alumni.harvard.edu` forwarding still runs through an outside vendor — **forward-only, cannot send**, which matters for SheerID email-loop codes.
- **Cambridge (UK)** — free `@cantab.ac.uk` mailbox for graduates and former postdocs; you must activate it before your `@cam` account closes ([Cambridge alumni email FAQ](https://www.alumni.cam.ac.uk/benefits/alumni-email/faqs)).

The counter-list is the useful part, because it shows how little "lifetime" means contractually: **Duke** is shutting forwarding off 31 Jan 2027 with no replacement; **Temple** closed accounts in 2025 and now expires them one year after graduation; **Ohio State** ended forwarding 31 Dec 2024 and deleted accounts 1 Apr 2025, data unrecoverable; **CU Boulder** announced termination, was sued in a class action, and only extended access to alumni who opted in and had used the account. Duke's FAQ states "lifetime" never guaranteed perpetuity — the service was always subject to "technological feasibility" ([Duke Chronicle](https://dukechronicle.com/article/duke-university-ends-alumni-lifetime-access-to-email-address-forwarding-edu-service-20260518)). **Oxford** discontinued alumni addresses outright; only legacy users are supported ([petition](https://www.change.org/p/bring-back-oxford-university-alumni-email-addresses-for-all-graduates)). **UC Davis** moved its alumni address behind an **$850 lifetime association membership** ([Inside Higher Ed](https://www.insidehighered.com/news/tech-innovation/2023/07/25/college-email-life-risk-google-limits-free-storage)).

Driver of the whole collapse: Google ended free education storage, caps institutions at a pooled 100 TB, and bulk-sender authentication rules (Google/Yahoo Feb 2024, Microsoft May 2025) made naive forwarding fail SPF/DKIM/DMARC. Vendors now sell schools cheap authenticated forwarding instead — [Alumni Forwarding](https://alumniforwarding.com) quotes ~$1,400/yr for 10k alumni vs ~$36,000 for Workspace — which is why some programmes survive as aliases rather than mailboxes.

### 3.2 Enrollment routes that cost ~nothing (community-college adjacent)

If you need *active student* status rather than an alumni alias, the cheapest hinges are open-access community colleges and free-tuition states:

- **Foothill College (CA)** — non-credit courses are tuition-free, open to anyone 18+, unlimited repeats, and enrolled students can request an `@student.foothill.edu` account. The catch is explicit on the college's own page: the account is "only intended for registered students" and is **deactivated one quarter** after you stop taking classes ([Foothill email policy](https://www.foothill.edu/apply-and-register/email-communications.html), [non-credit FAQ](https://www.foothill.edu/non-credit/faq.html)).
- **New Mexico** — Opportunity Scholarship covers up to 100% of tuition and required fees at 29 public institutions for established residents enrolled in at least 6 credit hours ([NM HED](https://hed.nm.gov/free-college-for-new-mexico)).
- **Senior waivers (60+)** — several states waive tuition and fees for older residents, e.g. NVCC for Virginia residents 60+ ([NVCC](https://www.nvcc.edu/admissions/apply/senior-citizens.html)), MassBay for 60+ ([MassBay](https://www.massbay.edu/senior-citizen-student)). This is the closest thing to a genuine "lifelong learner" mailbox: cheap, renewable, and *real* enrollment.
- **University of the People** — tuition-free, accredited, but not free: $60 application (waivers exist) plus $120–240 per course assessment, email issued after admission ([walkthrough](https://www.freetricksworld.com/how-to-get-edu-email-for-free)). Address is on a subdomain (`@my.uopeople.edu`).

### 3.3 What does *not* work anymore (commonly recommended, now dead)

- **ASU Universal Learner Courses** — was the standard "no application needed" trick. ASU now says plainly: no, you don't get an `asu.edu` address; emails are only issued where a course requires one, and access ends when you stop ([ASU ULC FAQ](https://ulc.asu.edu/help-center/faqs)).
- **edX/Coursera verified certificates** — no institutional mailbox at all.
- **Disposable "edu" temp mail** — `edumaili.com` sells it honestly: "an address from Edumaili is a privacy tool, not a student credential… a disposable address will not pass their checks," and `.edu.pl` is Polish, not US `.edu` ([edumaili](https://edumaili.com)). Useful for grabbing a confirmation link, useless for Spotify.

### 3.4 Bought accounts

Marketplaces like [Accsmarket](https://www.accsmarket.com/en/rules) sell working institutional logins. Read the terms before paying: the guarantee is **48 hours of validity only**, responsibility transfers to you on purchase, order downloads vanish after 30 days, and the seller keeps no history. You typically must change the password immediately, and login hygiene matters (their rules demand one clean residential IP and one device per account). That is fine for a one-off discount; it is not a durable identity.

### 3.5 Comparison

| Provider | How obtained | Cost | Works for SheerID/UNiDAYS? | Risk of revocation |
|---|---|---|---|---|
| MIT / Stanford / Yale / Princeton / Michigan alumni mail | Graduate, then activate | $0 | Sometimes — only if brand enabled SheerID's graduate segment; UNiDAYS → GRADLiFE | Low–medium; terms reserved, storage caps |
| Harvard `@post.harvard.edu` | Alumni registration | $0 | Weak — forward-only, can't send or receive loop code reliably | Medium; survived one shutdown attempt |
| Cambridge `@cantab.ac.uk` | Graduate, activate before `@cam` closes | $0 | Sometimes — UK institution, not US graduate segment | Low–medium; limited to Outlook web |
| Foothill / De Anza non-credit | Apply, register any free non-credit class | $0 (CA) | Yes while enrolled | High — deactivated one quarter after you stop |
| NM public college (Opportunity Schl.) | Residency + 6 credit hours | $0 tuition (resident) | Yes while enrolled | Medium — residency and credit-load rules |
| Senior waiver (NVCC, MassBay, etc.) | Age 60+ + state residency | $0 | Yes while enrolled (credit courses) | Medium — course cap, residency |
| University of the People | Apply, pay, enroll | $60 + $120–240/course | Yes (accredited), address on subdomain | Medium — fees, subdomain oddities |
| UC Davis alumni address | $850 lifetime association membership | $850 once | Sometimes (graduate segment) | Low |
| Illinois Alumni Association | Open to general public, annual membership | $150/yr | Weak — membership, not enrollment | Low cost, high ongoing spend |
| Bought login (Accsmarket et al.) | Purchase | ~$2–20 | Inconsistent; passes suffix checks only | High — 48h guarantee, seller may hold recovery |
| Temp "edu" mail (edumaili, Boomlify) | Instant web form | $0 | No — not a credential | Total — expires in minutes |

**Flag as scammy or oversold:** any site promising a "lifetime .edu for $10"; resold accounts advertised as *your own* (the original registrant can reclaim via the school's password reset); `.edu.xx` lookalikes sold as ".edu"; and YouTube/Instagram "instant .edu" methods that are really just temp mail. Reputable schools never sell addresses, so a mailbox you cannot log into the school portal for is a rental, not an identity.

**Practical note:** if the goal is a discount, an alumni alias usually beats a bought login only when the brand accepts graduates; if it must be *student* status, a free non-credit community-college class is the cheapest honest route, and you must stay enrolled to keep it. Either way, set the address as a forwarding target to a mailbox you control, and never make it your only recovery address.

## 4. Direct student-verification services (no .edu needed)

The previous section assumes you can hold an institutional mailbox. You often can't — bootcamp grads, online-enrolled students, people at schools that never issued addresses, and anyone whose registrar is slow. The services below exist precisely for that case: they are the verification layer brands hire, and every one of them has a documented, non-email path. They are free (ISIC excepted), legitimate, and one successful verification usually covers dozens of offers, which is far cheaper than maintaining an inbox you don't otherwise need.

Two framing notes before the detail:

- **Institutional email is a shortcut, not a requirement.** At every provider below the email path is *method one*; document review is *method three*, reviewed by a human. Rejections are common but nearly all are fixable (name spelling, date currency, image quality).
- **A "verified" status at one provider does not transfer.** SheerID, UNiDAYS, and Student Beans are separate silos with separate databases. Verify with the one the specific brand uses — check the checkout flow, not the marketing page.

---

### SheerID

The largest white-label verifier in the US and the one you will meet most often. SheerID runs the form *on the brand's domain*; you never "join SheerID," you verify for one offer at a time.

- **How the non-email path works:** SheerID tries authoritative enrollment records first (name + school + DOB), then SSO into the school portal, then an email loop, and only then offers document upload. You can request the upload step directly by failing the earlier ones.
- **Documents that clear review:** official enrollment letter on school letterhead, current-term class schedule, registration or tuition receipt, transcript showing in-progress classes, or a dated student ID — each showing first name, last name, institution name, and an issue date in the current term or within three months.
- **Documents that fail outright:** acceptance letters (future term), screenshots of an email or portal, transcripts showing only a past term, and .doc/.docx files.
- **Technical rules reviewers enforce:** .jpg/.jpeg/.png/.pdf only, ≤10 MB, ≥1920×1080, ≤10° tilt, no flash. Redact SSNs and account numbers, but never the name, school, or date.
- **Cost:** free to the student.
- **Who honors it:** Spotify, YouTube Premium/Music, Adobe, Figma, Autodesk, Amazon Prime Student, Google (Gemini/One), OpenAI, Perplexity, TIDAL, Prezi, and most US consumer-tech student offers.
- **Eligibility limits:** default floor is 16 (18 in India); homeschoolers are unsupported; degree level (undergrad vs. grad) is invisible to reviewers. Some brand programs are Title IV/degree-granting only — Spotify and TIDAL are explicit about it — while programs configured for "post-secondary" also take vocational and trade schools if the program is semester- or year-long.
- **Common rejections:** nickname instead of legal name; school typed colloquially rather than as printed; expired or prior-term document; glare or a cropped corner; uploading a phone screenshot of the portal; submitting on the last day of a promo and running out of runway.
- **Escape hatch:** nearly every program includes an Add School Request form. Full official school name, not initials; approvals typically land in about a week.

### UNiDAYS

UK-origin verifier now embedded in Apple's stack, including the US, Canada, and Chile Education Stores since May 2026. Free, and the manual route is genuinely open.

- **Accepted proof:** a student ID (the credit-card style is what they want) or an admission letter; institution email also works. Review takes up to seven days.
- **Who honors it:** Apple Education Store and Apple Music, Samsung, Nike, ASOS, adidas, and a large consumer-retail roster. Also Coursera (40% off the first three months of Coursera Plus).
- **Eligibility:** 16+, current student at a college or university that issues a personal institutional address or an institutional ID. Staff accounts exist for educator pricing.
- **Not accepted:** NUS cards (UNiDAYS won't vouch for them because they cover grads and trainees), expired cards, library cards, and portal screenshots. Admission letters for a term that hasn't started are frequently bounced — the reviewer wants *current* status, so pair the offer letter with a registration receipt.
- **Homeschool route:** identity document (licence or passport) plus a homeschool Letter of Intent or Letter of Acknowledgement gets manual review, usually under 24 hours.

### Student Beans

Same model as UNiDAYS, more retail-heavy and more tolerant of non-traditional study — apprentices are explicitly eligible.

- **Accepted proof:** manual upload of a current enrollment document showing your full registered name, the institution's complete name, and the current academic year. Three-day review; the manual form is at `accounts.studentbeans.com`.
- **Who honors it:** ASOS, Nike, Gymshark, Samsung, McDonald's, Coursera (40% off Coursera Plus), plus ~10,000 stores.
- **Eligibility:** 16+, in full-time education — high school, college, university, or apprenticeship.
- **Common rejections:** document shows last year's dates; institution written in short form; name abbreviated; a course certificate rather than an enrollment record.
- **If your institution is missing:** use the "add your place of study" flow. Support reviews in three days; recognized email domains verify instantly, unrecognized ones go to a human who can approve or reject.

### ISIC (International Student Identity Card)

The only card here you pay for, and the only one that works *offline* as a physical proof of status. UNESCO-endorsed, issued in ~130 countries, accepted wherever a human looks at an ID rather than a database.

- **Eligibility:** full-time student, 12+, no upper age limit; full-time means ≥15 hours/week for ≥12 weeks/year at a governmentally accredited institution. Doctoral candidates who haven't defended qualify.
- **Cost:** €4–25 depending on country purchasing power (€12 in the Netherlands), valid 12 months, digital card in the ISIC app.
- **Documents:** ID photo, proof of identity (passport/licence; guardian ID if under 18), and student-status confirmation — student ID, enrollment letter, or tuition receipt.
- **Who honors it:** JetBrains accepts ISIC/ITIC directly for its free Student Pack (alongside university email and the GitHub Pack). In-person: museums (Louvre, Vatican, SFMOMA), rail and coach (Eurail, Trenitalia, Renfe, National Express, FlixBus), hostels, and thousands of local retail partners via the ISIC app. Some regions run Apple and Spotify promotions through ISIC partners.
- **Where it does *not* work:** SheerID, UNiDAYS, and Student Beans checkouts don't take ISIC as proof — the card is not a database record. Don't buy one expecting to unlock Spotify or the Apple Education Store with it.
- **Rejections:** part-time enrollment, unaccredited or short-course providers, photo that isn't ID-spec, and mismatch between the name on the card order and the identity document.

### Named brand flows

| Offer | Verifier | Price | Eligibility | Non-email path |
|---|---|---|---|---|
| Spotify Premium Student (+Hulu w/ ads) | SheerID | $6.99/mo | 18+, Title IV accredited US college/university, new Premium subscribers; max 4 years, re-verify every 12 months | Document upload after failed record match |
| Apple Music Student | UNiDAYS | $6.99/mo US (includes Apple TV) | Current higher-ed student | Student ID or admission letter |
| Apple Education Store | UNiDAYS | Up to 10% off Mac/iPad/Watch | Students, accepted students, faculty, staff, parents buying for a student | Student ID, admission letter, homeschool letter |
| Adobe Creative Cloud Pro | SheerID | $19.99/mo yr 1, $39.99/mo after (vs. $69.99) | 13+, currently enrolled at accredited school, college, university, homeschool, or qualified online program | Document upload *after* purchase; annual re-verification |
| YouTube Premium / Music Student | SheerID | $8.99/mo | Higher-ed student where plan is offered; institution must be SheerID-approved; 4-year cap, annual re-verify | Upload; US decisions in ~20 min, elsewhere up to 48 h |

Adobe is the one to be careful with: the discount is a 12-month contract with an early-termination fee, the price doubles at renewal, and an unverifiable document means you're billed at the student rate while Adobe chases proof.

### GitHub Student Developer Pack, and what to use instead

GitHub's own path is fully documented and doesn't need a school email. The Pack is 13+, for any degree-granting program regardless of location, and GitHub explicitly accepts "a dated student ID, a current registration document, a time-stamped screenshot of your school portal, a letter on school letterhead," or a transcript — uploaded through the normal application, on a personal Gmail if necessary. Reviews target two weeks; school-email domains only count alone if the school restricts them to current students. The Pack's value is roughly $12,000 in offers, so expect real scrutiny. Non-degree bootcamps are the weak spot: "degree-granting" is the stated bar.

If GitHub rejects you, verify with the vendors directly — you don't need the Pack to get the tools:

- **JetBrains Student Pack** — free, all IDEs, accepts ISIC/ITIC or a GitHub Pack account; requires full-time enrollment in a program of a year or more; non-commercial use only; annual renewal; 40% graduation discount for two years after.
- **Figma Education** — free Professional tier with 3,000 AI credits/month for a year; higher-ed applicants complete SheerID. A school email is requested up front but SheerID manual review handles its absence.
- **Autodesk Education** — free one-year renewable licences via SheerID; same document set as any SheerID program.
- **Framer** — full plan free for students; school ID photo is the primary method.
- **Microsoft Azure for Students** — $100 credit, no card; needs a school-domain account, so this is the one place a mailbox genuinely is the gate. The card-free Azure for Students Starter tier has no verification at all.
- **Notion Education** — free Plus, but email-only; it does not accept IDs, so budget for a mailbox if Notion matters.
- **Miro Education** — free for students at accredited institutions; email or proof of affiliation, with intake currently throttled.

### Non-university channels: what actually clears

- **Accredited bootcamps and trade schools.** SheerID's "post-secondary" segment covers vocational schools, technical colleges, culinary and beauty schools, and IT training centers — but only programs with extended, semester- or year-long courses. A four-week workshop is out. Student Beans takes apprentices explicitly and will add an institution on request. UNiDAYS works if the school issues a card-style ID, which most bootcamps don't.
- **Coursera and edX enrollment on its own.** Largely *not* accepted. Neither platform issues institutional email or enrollment documents in a format SheerID or UNiDAYS recognize, so a Coursera specialization doesn't get you Spotify or Apple pricing. What does work depends on the brand:
  - **Adobe** explicitly includes "qualified online courses or educational programs" in its eligibility terms — the widest door for MOOC learners.
  - **GitHub's Pack** requires a degree-granting program, so Coursera *degrees* (Illinois iMBA, London BSc, etc.) qualify while individual certificates don't.
  - **Coursera and edX as merchants** are the other direction: both sell to verified students via UNiDAYS and Student Beans (40% off Coursera Plus), and edX verified certificates run $50–$300 with no student discount at all.
- **MOOC certificates as documents.** A completion certificate is a credential, not an enrollment record — it shows you finished, not that you're currently enrolled. It clears review only where the brand names online programs in its terms (Adobe), and it will bounce at SheerID programs configured for Title IV institutions.

### Choosing a path

- Brand is on SheerID → upload an enrollment letter or current-term schedule; expect 24–72 h and one retry after a fixable rejection.
- Brand is on UNiDAYS or Student Beans → card-style student ID first, admission letter plus registration receipt second.
- Brand takes ISIC → buy the card (cheap, instant-ish, works for JetBrains and every museum and train in Europe).
- Bootcamp or online program → SheerID programs configured for post-secondary, Student Beans for apprentices, Adobe for online courses; assume GitHub, Notion, and Apple are closed to you.
- No document of any kind → the Add School Request form at SheerID and the institution-add flow at Student Beans are the last resorts, both about a week.

### Honest limits

Document review is discretionary. A reviewer who doubts a document rejects it without appeal, and the only remedy is a new submission with the specific defect fixed. SheerID's own guidance says a student who cannot produce acceptable proof simply doesn't get the offer. Two structural facts follow: the services verify *status as of the document date*, so anything dated to a prior term fails even if you're still enrolled today, and none of them distinguish undergraduate from graduate, which means a document that proves you're a student is usually enough for a program that also admits grads. Keep one clean PDF of a current-term enrollment letter on your phone — it is the single artifact that clears the widest range of these flows, and re-shooting it every term is cheaper than maintaining an inbox.

## 5. What a .edu actually unlocks (and what's gated hard now)

The `.edu` address stopped being a key around 2023–2024 and is now just an identity token. Almost every serious program verifies against an enrollment roster through **SheerID** (or a school SSO handoff), then re-checks you every 6–12 months, caps the benefit by years or credits, and drops you the moment you stop enrolling. A domain that merely *looks* academic buys very little; several vendors now auto-reject anything that isn't a school-issued address tied to a verified record, and a handful have closed to higher-ed students outright.

Treat the offers in three tiers.

| Tier | Programs | Gate | Renewal |
|---|---|---|---|
| **Email-only, low friction, low value** | AWS Educate (learning only), JetBrains single IDE, Amazon Prime for Young Adults (age-based) | Any email / no verification | None, but nothing worth having |
| **Roster or document verification, hard caps** | GitHub Education + Copilot Student, Azure for Students, JetBrains Student Pack, Notion, Figma, Autodesk, Adobe, Perplexity Education Pro, Spotify, Apple Music, YouTube Premium, Google AI Pro student offer, Linear | SheerID / school SSO / school ID + transcript; institution must be on the vendor's list | 6–12 months, 1–4 year caps |
| **Dead, closed, or email-useless** | Free Copilot Pro, ChatGPT free-Plus promo, Google Workspace free signup, Microsoft 365 A1, Canva for higher ed, AWS Educate credits, DigitalOcean credits | — | — |

### Tier 1: real, cheap, and not worth building a workflow on

**AWS Educate** is now a pure learning portal: free self-paced labs and badges, 13+, "open to any individual, regardless of where they are in their education" — **no credits, no card, no verification** ([aws.amazon.com/education/awseducate](https://aws.amazon.com/education/awseducate)). The old credit grants are gone. What replaced them is **AWS Student Rewards** (launched August 2026): verify through SheerID, complete a Builder Center profile, get 12 months of Skill Builder, then grind badges for $10 + $20 credits and a $100 certification voucher — $579 total, but it is a gamified ladder, not a grant ([aboutamazon.com](https://www.aboutamazon.com/news/aws/aws-student-rewards-free-cloud-ai-training)).

**Azure for Students** still gives $100 in credit for 12 months with no card, but is "available only to full-time university students" and requires a school email to sign up *and renew yearly* ([azure.microsoft.com/free/students](https://azure.microsoft.com/en-us/free/students/)). Part-time, community-college and certificate students get pushed to **Azure for Students Starter** (free tiers only, no $100). Both the credit and the annual re-verification are real constraints.

**JetBrains** quietly de-fanged its own gate: one IDE (IntelliJ IDEA or PyCharm) needs **no student verification at all**, and most IDEs now have free non-commercial licenses. The full Student Pack still needs a university email, ISIC/ITIC card, or GitHub Student Pack, is limited to **accredited programs lasting longer than one year**, renews annually, and converts to 40% off for two years after graduation ([jetbrains.com/community/education](https://www.jetbrains.com/community/education/)). Six-month bootcamps and short certificates are explicitly out.

### Tier 2: what actually works, and exactly how hard it gates

**GitHub Education / Student Developer Pack.** Verification runs on school ID with a current enrollment date, class schedule, transcript, or enrollment letter — and GitHub now tailors the requirement per school: "when the system detects that recent applicants from your school successfully verified using their academic email, future applicants from the same school must also use an academic email." Unrecognized domains need a support ticket ([docs.github.com](https://docs.github.com/en/education/explore-the-benefits-of-teaching-and-learning-with-github-education/github-education-for-students/apply-to-github-education-as-a-student)). Community-college and non-standard domains are the main rejection loop; appeals threads run for weeks ([discussion #205952](https://github.com/orgs/community/discussions/205952)). [Correction: this URL path is `/education/about-github-education/...` in current docs.]

The Pack itself is still free while enrolled and still carries GitHub Pro, Codespaces, Namecheap, `.tech`, Heroku and MongoDB Atlas. What it lost: **Copilot Pro was removed from the Pack on 12 March 2026** and replaced by **Copilot Student** — free, but 200 AI credits/month, auto model selection only, no third-party agents ([docs.github.com/copilot/plans](https://docs.github.com/en/copilot/get-started/plans), [changelog 2026-04-20](https://github.blog/changelog/2026-04-20-changes-to-github-copilot-plans-for-individuals)). Worse, **new Copilot Student activations have been paused since 20 April 2026** with no published return date; approved students sit on Copilot Free ([discussion #198399](https://github.com/orgs/community/discussions/198399)). GitHub re-evaluates eligibility monthly, so the benefit dies with your enrollment.

**Figma** is the strictest mainstream program. You must log in *with the school-issued address* — "non-school emails will be auto-rejected" — then clear SheerID. Status is bound to that exact address and is **revoked if you change the email afterward**. Higher-ed students get one year, bootcamp students six months (verified by the bootcamp, not themselves), then reapply ([help.figma.com](https://help.figma.com/hc/en-us/articles/360041061214-Figma-for-Education)).

**Autodesk** gives a one-year single-user education license, accredited institutions only, renewable annually with eligibility confirmation ([autodesk.com/education](https://www.autodesk.com/education/edu-software/overview)).

**Adobe** keeps a student price but made it a trap: $19.99/month for year one, **$39.99/month from year two**, annual contract billed monthly with an early-termination fee, eligibility re-checked every year ([adobe.com/education FAQ](https://helpx.adobe.com/x-productkb/policy-pricing/education-faq.html), [price-change terms](https://helpx.adobe.com/account/individual/subscriptions-and-plans/plan-types-and-eligibility/changes-to-individual-plan.html)). Institutional "Creative Cloud for Education" ends 31 March 2026, pushing campuses to Creative Cloud Pro for Teams at $99.99/seat ([TechSoup](https://support.techsoup.org/hc/en-us/articles/37538688761883)). School email verifies instantly; otherwise you buy first and prove eligibility after.

**Notion** requires the school email to be the *primary* address on the account and the institution to be WHED-listed; **student IDs and documents are not accepted**. Verify once a year or the workspace and all content falls back to Free. One claim per email, one workspace, ever ([notion.com/help/notion-for-education](https://www.notion.com/help/notion-for-education)).

**Perplexity** no longer gives students Pro free — it sells **Education Pro at $10/month** (half of Pro) via SheerID, university-level or higher only, re-verified annually ([help center](https://www.perplexity.ai/help-center/en/articles/12590157-what-is-education-pro)).

**Spotify** is $6.99 with Hulu (With Ads), SheerID, institution must appear in SheerID's list, re-verify every 12 months, hard stop at four years ([support.spotify.com](https://support.spotify.com/us/article/premium-student)). **Apple Music** is $6.99 including Apple TV, verify in-app via SheerID/UNiDAYS/Alipay, annual re-verify, 48-month cap ([support.apple.com/106008](https://support.apple.com/en-us/106008)). **YouTube Premium** student is $8.99, SheerID, annual re-verify, four consecutive years ([support.google.com](https://support.google.com/youtube/answer/9158808)). All three fail closed: if your school isn't in the SheerID database, you are simply ineligible.

**Google's 2026 student offer** is the biggest legitimate AI giveaway: 12 months of Google AI Pro free for US college students (AI Plus outside the US), plus an AI Pro + YouTube Premium bundle at up to 70% off, claimable until **31 December 2026** with a card on file and SheerID ([blog.google](https://blog.google/innovation-and-ai/products/gemini-app/student-offer-google-ai)).

**Linear** gives full-time students Basic or Business free for one year for student-led projects and clubs; staff get 75% off ([linear.app/docs](https://linear.app/docs/billing-and-plans)).

### Tier 3: dead, closing, or the email does nothing

- **Free Copilot Pro for students** — ended 12 March 2026. Replaced by the paused Copilot Student plan, not another free Pro seat.
- **ChatGPT's four free months of Plus** — US/Canada, closed **31 October 2026**, no standing student price. Only the **$100 Codex credits** offer (US/Canada, verified university students) survives ([developers.openai.com/community/students](https://developers.openai.com/community/students)).
- **Google Workspace for Education** — never a personal signup; the school must own the domain. Fundamentals stays free but is per-user licensed on a 100 TB pool, and alumni are being cut to "Gmail Only" licenses or off entirely as campuses hit the cap. The Gemini education add-ons were replaced by **Google AI Pro for Education at $15/user/month** ([workspaceupdates](https://workspaceupdates.googleblog.com/2025/09/google-ai-pro-for-education.html), [licensing doc](https://knowledge.workspace.google.com/admin/getting-started/editions/google-workspace-for-education-pricing-and-licensing)).
- **Microsoft 365 Education** — on **5 November 2026** Microsoft announced retirement of **Office 365 A1, the Student Use Benefit and free alumni Exchange Online**. The replacement A0 is free but has **no Exchange, SharePoint or Teams**, and only applies to students on Windows devices at schools with all faculty on A2+. Changes bite at the first renewal on or after **1 January 2028**; pricing moves **1 May 2027**. Until then A1 remains web-apps-only Office with no desktop installs ([learn.microsoft.com portfolio](https://learn.microsoft.com/en-us/training/educator-center/instructor-materials/microsoft-365-education-portfolio)).
- **Canva** — higher education is not eligible for Canva Education at all; free Pro is K-12 only, and universities must buy a campus license. Individual students have no route ([canva.com/education/eligibility-guidelines](https://www.canva.com/education/eligibility-guidelines)). Canva *does* re-verify every three years for those who qualify.
- **Domain and hosting perks** — still real inside the Pack: Namecheap `.me` for a year plus a free SSL, one `.tech` domain for a year, Heroku at $13/month credit for 24 months, MongoDB Atlas $50, GitHub Pages free. **DigitalOcean's credit offer is gone from the Pack.** Value is a few hundred dollars at most and tied to Pack verification, not to your email.

### Who gets rejected, and why it's usually not the domain

The failure mode in 2026 is institutional, not lexical. Figma auto-rejects personal addresses. JetBrains excludes programs under a year. Perplexity excludes high school. Azure excludes part-time students. Notion requires a WHED-listed accredited institution. Canva excludes all of higher ed. GitHub will now *force* an academic address at any school where other applicants used one, and stalls on unrecognized community-college domains — the classic loop is a valid transcript rejected for not using an email the school half-issues.

**Bottom line:** a `.edu` in 2026 reliably buys GitHub Pro and Codespaces, $100 of Azure for a year, one Notion workspace, one year of Figma, an Autodesk seat, and roughly $7–9/month off music and video — each re-verified annually and each revocable. It buys no free desktop Office, no free Workspace account, no free Adobe, no free Canva, no free Copilot Pro, and no free ChatGPT. Anyone claiming otherwise is working from a 2022 list.

## 6. Existing curated lists, forums, and community threads

The meta-research layer here is thinner and more fragmented than for most consumer topics: no single maintained source tracks *which* edu-email routes still verify in 2026. What exists falls into four buckets — Reddit how-to threads (the de facto hub, concentrated in r/UnethicalLifeProTips), GitHub awesome-lists (a healthy but benefit-focused ecosystem), commercial "student deals" aggregators (fresh, but vendor-pushed and rarely about email sourcing), and marketplace/Telegram channels selling ready-made inboxes. Almost none of it audits the verification gates themselves, and none covers the 2026 shift toward student-ID/selfie checks.

### Reddit

- **r/UnethicalLifeProTips — the real center of gravity.** Two 2026 guides dominate: "ULPT: GUIDE how to get free edu email (Dec 2025)" (1,075 points, 83 comments, Maricopa Community College walkthrough, https://www.reddit.com/r/UnethicalLifeProTips/comments/1px7me4/ulpt_guide_how_to_get_free_edu_email_dec_2025/) and "ULPT: Free Student Email (.edu)" (883 points, 83 comments, Jan 2026, "apply to any community college with fake info", https://www.reddit.com/r/UnethicalLifeProTips/comments/1q2y90z/ulpt_free_student_email_edu/). Earlier requests are evergreen entry points: https://www.reddit.com/r/UnethicalLifeProTips/comments/1e2pi9e/ulpt_request_obtaining_an_edu_email_address_to/ and https://www.reddit.com/r/UnethicalLifeProTips/comments/1le0maf/ulpt_request_how_to_get_edu_email_jun_2025. **Alive** (constant new threads), but comment quality drifts and the top-voted methods are already partly broken.
- **r/studentdiscounts** — small, discount-links sub (created 2013), newest post within hours of writing, e.g. https://www.reddit.com/r/studentdiscounts/. Almost no email-sourcing content; useful only as a signal of what still redeems. **Alive, but off-topic for the email layer.**
- **r/EdumailSeller** — created 20 Nov 2025, explicitly for buying/selling edu inboxes; new posts daily, e.g. "Im looking for edu mail to buy" (https://www.reddit.com/r/EdumailSeller/). **Alive and the most on-topic sub, but tiny and vendor-heavy.**
- **r/freebies** (~970k members) — general 100%-free sub with a wiki (https://www.reddit.com/r/freebies/wiki/index) covering rules, newbie guide, flair acronyms but *no* edu/student section; monthly mod threads still run (Nov 2026 thread visible on https://www.reddit.com/r/freebies/). **Alive, low relevance** — use for deal discovery, not verification methods.
- **r/beermoney** (~1.5M members) with an active beginner wiki (https://www.reddit.com/r/beermoney/wiki/beginner) — but its canonical edu thread is from 2015 ("What can I do with a .edu email", https://www.reddit.com/r/beermoney/comments/2vdkj4/what_can_i_do_with_a_edu_email/). **Sub alive; the edu content is stale** (Prime/Spotify/Tableau advice, some offers long dead).
- **r/edu** — worth a caution: it is a general *education* sub (teacher/ed-policy chatter, visa guides), not edu-email. Low traffic, posts still arriving Nov 2026 (https://www.reddit.com/r/edu/). **Alive but nearly irrelevant** to this topic.
- One-off but useful: r/MBA "List of Student Discount Perks with .edu Email Address" (2022, https://www.reddit.com/r/MBA/comments/u8m6tk/list_of_student_discount_perks_with_edu_email/) — good perk taxonomy, four years stale.

### GitHub awesome-lists and repos

- **AchoArnold/discount-for-student-dev** — 3,394 stars, last push 24 Nov 2026, open issues triaged. The de facto canonical list (software/SaaS discounts). **Alive.**
- **serithemage/awesome-student-developer-resources** — 33 stars, pushed 23 Nov 2026. **Alive, small.**
- **couponswift/awesome-student-software-deals** — 67 stars, pushed 15 Nov 2026, markets itself as "2025"-dated but maintained. **Alive.**
- **Aashish-po/edu-email-benefits** — 126 stars, 8 commits, pushed Oct 2026; "200+ free tools…just verify your .edu email" (https://github.com/Aashish-po/edu-email-benefits). **Alive, shallow.**
- **sdhutchins/awesome-edu-perks** — 50 stars, pushed Aug 2026, plus a searchable site (https://www.shauritahutchins.com/awesome-edu-perks/). US-focused, official links only. **Semi-active.**
- **ahlayer8tech/awesome-edu-stuff** — 6 stars, Mar 2026. **Marginal.**
- **jhaxce/student-perks** (https://jhaxce.github.io/student-perks) — the only list with a dedicated [VERIFICATION.md](https://jhaxce.github.io/student-perks/VERIFICATION.md) guide and per-offer verification requirements; repo last pushed 13 Jan 2026. **Semi-stale (Jan 2026), but the best structural model for this section.**
- **OpenGenus/Best-student-discount-services** — 444 stars, last push 25 Dec 2023, 15 open issues. **Stale** — still cited everywhere, still ranking.
- Adjacent: GitHub Education's own pack page (https://education.github.com/pack) and the HN Show HN for a pack alternative (https://news.ycombinator.com/item?id=46665876, 9 months old, 1 point — near-dead).

### Aggregator sites and blogs

- **Slickdeals** — has a standing student hub (https://slickdeals.net/students) and recurring "verification required" megathreads that get re-posted each cycle (Jan 2026: https://slickdeals.net/f/19113547-student-exclusive-deals-2026-canva-office-365-more-free-verification-required; Nov 2025 GitHub Pack: https://slickdeals.net/f/18770932-github-education-student-developer-pack-github-pro-copilot-pro-more-free-student-verification-required). High-traffic, comment sections report dead offers fast. **Threads decay in weeks; the hub persists.**
- **freeforstudents.org** (https://freeforstudents.org) — curated freebie catalog with live 2026 offers (Prime Student, Grubhub+, Gemini). **Alive, vendor-affiliate.**
- **studentoffers.co** (https://www.studentoffers.co) — "591+ verified offers… updated regularly". **Alive.**
- **savethestudent.org** free-stuff hub (https://www.savethestudent.org/student-deals/free-stuff) — long-running UK student site, still publishing. **Alive.**
- **campusunite.in** (https://campusunite.in/student-email-benefits) — 2026-dated India-centric perk guide, hand-tested claims. **Alive, thin.**
- **kamerpower.com** (https://kamerpower.com/how-to-create-and-get-edu-email-for-free-in-2021-2022) — "how to get free .edu email", retitled for 2026/2027 but the body is recycled and the methods are dated. **Stale-but-updated.**
- **blackhatworld.com** thread "What can I do with an EDU email?" (Apr 2023, https://www.blackhatworld.com/seo/what-can-i-do-with-an-edu-email.1494244) — forum counterpart to the ULPT threads. **Stale.**
- Vendor support docs double as meta-reference for verification edge cases: Student Beans' "Don't have an institution email address?" (https://help.studentbeans.com/hc/en-us/articles/360007269679) and domain-request form (https://help.studentbeans.com/hc/en-us/articles/25286874425756) — **maintained by the vendor, not by the community.** (Student Beans now sits under parent brand Pion; no active public blog.)

### Telegram / Discord

- **Telegram: @edumailofficial** ("EduMail Free Network", 1,688 subscribers, https://t.me/edumailofficial) — low-volume promo channel for the edumailfree.com / edumail.bz / edumail.to / postinbox.org / tempmailcow.com network; last post 13 Nov 2026. **Alive but ~1–2 posts/month, mostly upsells.**
- **Telegram marketplace channels** (edumail stores, "buy edu mail" sellers) — numerous, unversioned, no audit trail; treat subscription counts as marketing.
- **Discord** — no dedicated edu-email community of note. What exists is (a) bot-verification docs for servers that gate on .edu (e.g. https://getemailverified.com/use-cases/university), and (b) general student-deal servers. **Effectively a gap** — Discord coverage in this space is tooling, not curation.

### Gap summary

Alive and worth monitoring: ULPT, r/EdumailSeller, AchoArnold's list, Slickdeals threads, freeforstudents/studentoffers. Stale and cited anyway: OpenGenus (2023), the r/beermoney 2015 thread, the BHW thread, kamerpower. Uncovered by all of them: 2026 gate changes (SheerID selfie checks, .edu domain allowlists, one-email-per-human rules), post-graduation mailbox expiry, and any liveness testing of the schools recommended in the ULPT guides.
