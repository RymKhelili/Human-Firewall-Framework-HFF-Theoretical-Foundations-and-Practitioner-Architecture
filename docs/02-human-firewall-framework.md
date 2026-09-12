# The Human Firewall Framework (HFF): An Applied Practitioner Architecture

**Part II of this repository — the framework built from the theoretical foundations laid out in Part I**

*Status: living document. Grounded in `01-theoretical-foundations.md`; extended here into a practitioner architecture.*

---

## Preface

I didn't want to name this framework until I understood, in detail, why the field it responds to keeps failing. Part I of this repository was that work: a review of the research on why traditional security awareness training doesn't produce lasting behavior change, and of the related fields — Cognitive Security, dual-process theory, persuasion science, memory neuroscience, inoculation theory, and behavior change science — that point to what should replace it. I only let myself name and structure a framework after doing that reading, because a name given before the reasoning tends to turn into decoration instead of real structure.

I call what follows the **Human Firewall Framework (HFF)**.

I chose that name on purpose, and I want to be precise about what it does and doesn't mean. A firewall, in its original sense, isn't a perfect barrier — it's a designed layer of resistance, built to hold up against known attack patterns and to fail gracefully rather than catastrophically when it meets something new. That's exactly the standard I hold myself to when training a person. I'm not building a perfect user who never makes a mistake; that standard doesn't exist for computer systems, and it certainly doesn't exist for people — and pretending otherwise is, based on the research reviewed in Part I §2, exactly the setup that creates a blame culture when the inevitable mistake happens. I'm building a person whose instinctive, gut-level (System 1) response to manipulation has been deliberately strengthened — someone who reliably resists a known type of attack, and who, when they do slip up, fails in a way that gets reported and learned from rather than hidden and repeated.

I also want to state plainly the belief this framework is built on: **online safety is not an organizational privilege. It is a human right.** Every design decision I make in this document follows from treating that sentence as literally true, not as a marketing line. A framework that only works inside a corporate training budget, delivered only to employees during business hours, is a framework that abandons that same person the moment they log off and become a parent, a grandparent, or a private citizen fielding a scam call at home. I build the HFF to work in both settings, because I don't believe the person changes at the office door — only how it's applied to them does.

---

## 1. The Starting Point This Framework Builds On

I won't repeat the full argument here — it's made at length in Part I. But I want to briefly state the four points I'm carrying forward as settled, because everything that follows is built on top of them rather than argued for again:

- Blame-based training damages the trust it depends on and suppresses the reporting behavior that actually protects an organization or a family (Part I §2).
- Fact-based, out-of-context, low-emotion training doesn't produce measurable behavior change at scale, and the evidence for this is now substantial (Part I §3).
- Social engineering attacks are, mechanically, attempts to make sure System 2 is never consulted — they're emotional attacks, not informational ones, and a defense aimed only at System 2 is fundamentally mismatched to the threat (Part I §5, §6).
- Knowledge and behavior aren't the same thing. Lasting defense requires engaging memory formation and automatic (System 1 / COM-B) disposition, not just conscious understanding (Part I §7, §9).

I treat these four points as settled ground, not as claims I need to keep re-arguing. What I'm doing in this document is turning them into something a practitioner can actually build and run.

---

## 2. Framework Architecture: Four Functions

Through this synthesis, I've arrived at four functions the HFF has to perform. I present them here as existing side by side — not as sequential stages you complete and move past, and not stacked into a hierarchy of foundation and superstructure. Each one has to be present continuously in a well-built HFF program; the program is only as strong as its weakest function, because a gap in any one of the four undermines the other three in practice, even though they don't run in a strict order.

### Function 1 — Removing the Blame

**What it is.** Before delivering any content, I have to remove the assumption — often unspoken but always present in a "weakest link" culture — that the trainee is a liability who needs correcting. I do this by clearly stating, at the start of any engagement, that the attacker is a trained adversary using documented, repeatable psychological techniques, and that falling for a well-built attack is evidence the attack was well-built, not that the person is deficient.

**Why this has to come first, without being a "stage" you finish.** The research reviewed in Part I §2 gives me a specific reason this matters, not just a general instinct to be kind. Posey, Bennett, and Roberts (2011) found that employees who feel distrusted by new security measures respond with *more* abusive or evasive behavior, not less. Bulgurcu, Cavusoglu, and Benbasat (2009) found that feeling fairly treated — not fear of punishment — is what predicts whether people follow the rules. If I run Functions 2 through 4 — teaching mechanisms, running inoculation exercises, building emotionally engaging content — inside a culture where the trainee still believes they'll be blamed and exposed for their reactions, I'm asking them to be vulnerable (admitting confusion, admitting they almost clicked, reporting a real near-miss) in a setting they have every reason to distrust. This function doesn't "finish" and hand off to the next one — it has to stay true throughout, or the honesty the other three functions depend on disappears.

**How I put it into practice.** In concrete terms: no publicly ranked "who failed the phishing test" leaderboards; a clearly stated, enforced no-punishment reporting policy, communicated before any simulation runs, not after; language throughout materials that describes techniques as sophisticated and built by an adversary, never language implying the target should have known better; and debriefs framed as "here's what this attack was built to do to anyone," not "here's what you did wrong."

### Function 2 — Teaching the Mechanism, Not the Checklist

**What it is.** Instead of teaching a list of surface warning signs to check for — spelling errors, mismatched sender domains, suspicious links — I teach the underlying persuasion mechanism the attacker is using, by name, so the trainee can recognize the *lever being pulled* even when the specific attack looks nothing like any example they've seen before.

**Why the research points me toward mechanism over checklist.** Ferreira and Teles (2019), reviewed in Part I §6, found Authority, Strong Affect, Integrity, and Reciprocation to be the most common persuasion principles in real phishing content, closely matching Cialdini's original six principles of influence. What I take from this isn't just that these principles exist, but that they get *reused* — the same small set of levers shows up across a huge range of surface-level attacks. A checklist trained against last year's phishing template becomes obsolete the moment the template changes. But a trainee who can recognize "this message is manufacturing artificial urgency" or "this caller is borrowing authority from a job title" as the technique being used — regardless of the channel or exact wording — has learned something that survives contact with a brand-new attack.

**How I put it into practice.** For every simulated or discussed attack, I now build materials around an explicit "which lever is this?" framing, naming the specific principle (authority, scarcity, social proof, reciprocity, liking, commitment/consistency, or affect) rather than just pointing out the surface tell. I deliberately vary how the same underlying lever is presented across a program — the same authority-based pretext delivered first as an email, then as a phone call, then as an in-person request — specifically so the trainee's pattern recognition attaches to the mechanism, not to a memorized template.

### Function 3 — Building Resistance Through Controlled Exposure

**What it is.** I don't just describe manipulation techniques — I expose trainees to weakened, safe, clearly-bounded versions of them, paired with an explicit rebuttal: walking through, right afterward, exactly how and why the technique worked on their reasoning, even if they caught it in time.

**Why the research treats this as a distinct function from Function 2, not the same thing said twice.** McGuire (1961) and McGuire and Papageorgis (1961), covered in Part I §8, found that *naming* a persuasion technique in the abstract isn't enough on its own to build resistance. Building resistance requires both a warning that you're vulnerable to it (threat) and actually practicing counterarguments against a real, if weakened, example of the technique (refutational preemption). Banas and Rains's (2010) meta-analysis found that this combination produces "umbrella protection" — resistance that carries over to attacks never specifically covered in training, as long as the underlying technique, not just the specific instance, was what got inoculated against. This is the evidence behind treating exposure-and-rebuttal as its own function, separate from just teaching what the levers are called: Function 2 gives the trainee the vocabulary; Function 3 is where that vocabulary gets stress-tested against something that actually tries to move them, in a setting safe enough that a failure, if it happens, is instructive rather than costly.

**How I put it into practice.** This is where realistic, well-built simulated social engineering attempts belong in the HFF — not as a "gotcha" pass/fail test run on its own (which Function 1 rules out as a delivery model), but as a deliberately weakened exposure that's always followed, no matter the outcome, by an explicit rebuttal walkthrough: here's exactly what lever this used, here's the moment in your own reasoning where the lever was designed to land, here's what a stronger, real-world version of this same technique would add.

### Function 4 — Designing for Retention and Instinct

**What it is.** Every piece of content built under Functions 1 through 3 is deliberately designed for its emotional tone and how the story is told, not just for factual accuracy — because the goal is for the material to become a lasting memory and to shift gut-level (System 1) disposition, not just to be correctly recalled on a quiz taken minutes later in a calm setting.

**Why this is a constraint on the other three functions, not a fourth step done afterward.** The neuroscience reviewed in Part I §7 — Cahill and McGaugh's (1995, 1996) work and McGaugh's (2004, 2018) account of amygdala-driven memory formation — tells me that how emotionally arousing content is, not how factually dense it is, predicts whether it survives into long-term memory, and that this doesn't depend on the emotion being negative or fear-based. Michie, van Stralen, and West's (2011) COM-B model, reviewed in Part I §9, separately tells me that automatic Motivation — the gut-level disposition that actually controls behavior under the pressure conditions attackers create — is the part conventional training leaves almost completely untouched. Put together, these two bodies of research tell me that if I deliver Function 2's mechanism-teaching or Function 3's resistance-building exercises in a flat, low-energy, purely informational way, I haven't just skipped a nice-to-have — I've failed to engage the specific biological and behavioral machinery that determines whether any of it survives past the training room. That's why I treat Function 4 as a lens applied to how I execute the other three, rather than as separate content of its own.

**How I put it into practice.** Case studies and simulations are built as stories with real stakes and a specific human main character, not abstract scenarios. Debrief content is written to trigger a genuine reaction — recognition, mild alarm, relief, sometimes humor — rather than just restating facts. And program design deliberately varies pacing and format specifically to avoid the flattening, numbing effect of a purely repetitive, checklist-style routine, which the research in Part I §3 (Caputo et al., 2014) links to employees writing off training as something they already know.

---

## 3. Methodology: Research-Driven, Adversarially Tested

Functions 1 through 4 describe *what* the HFF does. This section describes *how* I build the material that fills each function — a methodological commitment that sits underneath all four rather than being a fifth function on its own.

**Research-driven** means every mechanism I teach, every persuasion principle I name, and every claim I make about why a technique works can be traced to a real, cited source — the research reviewed in Part I, and the ongoing academic and threat-intelligence literature beyond it — rather than to my own gut feeling about what "sounds plausible." I hold myself to this standard specifically because the field I critique in Part I §2–3 has, in my view, too often run on inherited folklore ("humans are the weakest link," "repetition builds retention") instead of tested claims. I don't think I'm entitled to swap one set of unexamined assumptions for another.

**Adversarially tested** means every piece of training content I build is first judged the way an actual social engineer would judge it: what's the fastest way to beat this specific lesson? What version of this attack would this training *not* catch? I treat this like red-teaming in technical security — a defense that hasn't been attacked by someone actively trying to break it has only been tested against the imagination of whoever built it, which is a very narrow test. In practice, this means every mechanism taught under Function 2 and every resistance-building exercise built under Function 3 gets stress-tested against a deliberately adversarial question — "if I were the attacker, how would I get around exactly what I just taught?" — before it's delivered, and revised based on what that question reveals.

I hold both halves of this methodology together on purpose. Research without adversarial testing risks producing training that's theoretically sound but practically fragile — accurate about *why* an attack works in the abstract, but never tested against how a real, motivated attacker would adapt around it. Adversarial testing without research risks producing training that's tactically clever but has no real theoretical grounding — effective against the specific attacks I imagined, but built on intuition rather than the actual, documented psychology of persuasion. I want the HFF held to both standards at once.

---

## 4. Positioning: One Framework, Two Audiences

I said in the preface that I see online safety as a human right rather than an organizational privilege, and I want to be specific about what that means for the structure of the framework, not just as a nice sentiment.

The four functions of the HFF don't change between a workplace engagement and an individual or family engagement. What changes is the *layer built on top of them*: the specific attack types emphasized (executive impersonation and business email compromise for a workplace audience; romance scams, family-impersonation fraud, and elder-targeted phone scams for an individual or family audience), the language and pacing of delivery, and the stakes used to make Function 4's emotional engagement genuine rather than forced. But Function 1's refusal to blame, Function 2's mechanism-first teaching, Function 3's resistance-through-exposure, and Function 4's design-for-retention stay constant across both, because the underlying human mental wiring the framework is defending doesn't change when someone leaves the office.

This is also why, throughout this repository, I treat social engineering awareness as one application of the HFF rather than the framework's whole scope. The same four functions, in principle, extend to any area where a person's mental processes — attention, judgment, memory, trust — are the actual target, which the Cognitive Security research reviewed in Part I §4 (Ask et al., 2025) frames as much broader than social engineering alone. I develop the social-engineering-specific application in detail, as a case study, elsewhere in this repository.

---

## 5. What This Document Doesn't Yet Claim

I want to close this document the way I opened Part I: by being clear about the limits of what I'm claiming. The four functions above are, at this stage, a structure built from research review and practitioner reasoning — they describe what a framework grounded in this research *should* do, and they're designed to be testable and adversarially tested, per the methodology in Section 3. I haven't yet presented outcome data from running this specific structure at scale, because that data doesn't yet exist in a form I'm willing to cite without qualification. Where this repository makes a factual claim, it's sourced to the research in Part I; where it describes the HFF's own design choices, it's presented as reasoned structure, not as proven results. I think that distinction matters, and I intend to keep it visible as this framework moves from paper to practice.

---

*Continued in the case-study application: how the Human Firewall Framework's four functions map onto the ten social engineering attack vectors this consultancy addresses.*
