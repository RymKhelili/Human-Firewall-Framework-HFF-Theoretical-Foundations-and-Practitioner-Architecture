# Case Study: Applying the Human Firewall Framework to Ten Social Engineering Attack Vectors

**Part III of this repository; a worked application of the framework laid out in Part II, built on the research in Part I**

*Status: living document. Read alongside `01-theoretical-foundations.md` and `02-human-firewall-framework.md`.*

---

## A note on scope

This document maps the Human Firewall Framework's four functions; removing the blame, teaching the mechanism, building resistance through controlled exposure, and designing for retention onto ten specific social engineering attack vectors. I chose these ten to span both audiences the framework is built for (Part II, Section 4): the workplace and the individual or family setting. They are not the only vectors that exist, and I don't claim this list is exhaustive; it's a working set I use to show the framework in action, and I expect to revise it as new vectors become common enough to warrant their own entry.

**The ten vectors:**

1. Phishing (email)
2. Spear phishing and business email compromise (BEC)
3. Vishing (voice phishing / phone-based social engineering)
4. Smishing (SMS-based social engineering)
5. Pretexting
6. Baiting
7. Tailgating and physical social engineering
8. Romance scams
9. Family-impersonation and grandparent scams
10. AI-generated voice and video impersonation (deepfake social engineering)

For each vector, I apply the same four-function structure introduced in Part II, and I try to be specific rather than generic naming the actual persuasion levers involved (Part I, Section 6), rather than repeating the same advice in ten different wrappers. Where a vector's mechanism has already been discussed in Part I or II, I reference the relevant section instead of re-arguing it.

---

## 1. Phishing (Email)

**The attack.** A mass or semi-targeted email designed to get the recipient to click a link, open an attachment, or hand over credentials, usually by impersonating a trusted brand or internal system notification.

**Function 1: Removing the blame.** I state upfront that phishing emails are tested against spam filters and refined against real user behavior before they're ever sent; the version that reaches an inbox has already survived automated defenses. Falling for one is evidence the email was well-built, not that the recipient is careless.

**Function 2: Teaching the mechanism.** Rather than teaching "check the sender domain," I teach the persuasion lever behind the specific email: most mass phishing relies on Authority (impersonating IT, a bank, or a delivery service) paired with manufactured urgency ("your account will be suspended") the same Authority + Scarcity pairing Part I, Section 6 identifies as the most common combination across studied phishing samples.

**Function 3: Building resistance.** Controlled, clearly-labeled simulated phishing emails, varied across pretexts (not the same template repeated), each followed by a rebuttal walkthrough naming the lever used, never scored as a public pass/fail test (Part II, Function 1 rules that delivery model out).

**Function 4: Designing for retention.** Debrief content built around a real, specific, story-driven near-miss ("here's what almost happened to a specific person and specific account") rather than a generic "phishing costs businesses $X billion" statistic, which research on emotionally engaging content (Part I, Section 7) suggests will stick better.

---

## 2. Spear Phishing and Business Email Compromise (BEC)

**The attack.** A targeted email, often impersonating an executive or vendor, designed to trigger an unusual but plausible action, typically a wire transfer, a gift card purchase, or a change to payment details.

**Function 1: Removing the blame.** BEC attacks are built on real, often publicly available information about the organization's structure and vendors. I frame a successful BEC attempt as a reconnaissance failure at the organizational level as much as an individual failure to notice, which keeps the debrief from becoming about one employee's judgment.

**Function 2: Teaching the mechanism.** The lever here is almost always Authority (a fake or spoofed executive) combined with Scarcity or urgency ("I need this before I board my flight"), often deliberately timed for when the real executive is known to be traveling or unreachable, exploiting the fact that verification is harder when the impersonated person can't easily be reached to confirm.

**Function 3: Building resistance.** Exposure exercises built around the specific pattern of "urgent, unusual, unverifiable request from an authority figure", practiced with a required verification step (a callback to a known number, not a reply to the email) built into the exercise itself, so the resistance trained is a concrete action, not just recognition.

**Function 4: Designing for retention.** Because BEC has real financial stakes, case studies here can use genuine (anonymized, non-attributable) dollar figures and consequences to create authentic stakes; Part I, Section 7 notes the memory-strengthening effect of emotional arousal doesn't depend on the emotion being fear-based, but stakes still have to be honestly presented, not exaggerated.

---

## 3. Vishing (Voice Phishing)

**The attack.** A phone call, often impersonating IT support, a bank's fraud department, or a government agency, designed to extract credentials, one-time codes, or direct action over the phone.

**Function 1: Removing the blame.** Voice conversation removes the pause-and-check opportunity that email allows, there's no forwarding it to a colleague mid-call. I explicitly name this as a structural disadvantage of the channel, not a personal failing, before teaching anything else.

**Function 2: Teaching the mechanism.** Vishing leans hard on Authority and Liking; a calm, professional-sounding caller building rapport before making the request and on the dual-process dynamic from Part I, Section 5: a live conversation keeps System 2 permanently on the back foot because there's no time to pause and deliberate the way there is with a written message.

**Function 3: Building resistance.** Live, controlled call-based exercises (with clear consent and disclosure protocols) that specifically practice the one resistant action that matters most on this channel: hanging up and calling back on an independently verified number; a physical muscle-memory action rather than a purely cognitive one.

**Function 4: Designing for retention.** Recorded (with permission) or scripted real-world vishing call examples, played or read aloud in training, tend to land harder than a written description of the same call, voice carries the emotional and authority cues that make the attack work, so removing them for training purposes would weaken the exposure.

---

## 4. Smishing (SMS Phishing)

**The attack.** A text message, often impersonating a delivery service, bank, or government agency, containing a malicious link or a request to call a number.

**Function 1: Removing the blame.** I note that SMS carries none of the visual cues (branded formatting, sender email domains) that email phishing at least sometimes exposes, making it a genuinely harder channel to evaluate again a structural point, not a character one.

**Function 2: Teaching the mechanism.** Smishing commonly relies on Scarcity and urgency compressed into a very short message ("Your package couldn't be delivered, confirm address within 24h") the brevity itself is part of the mechanism, since it doesn't give System 2 much to examine.

**Function 3: Building resistance.** Practicing a specific habit: never tapping a link in an unexpected text, and instead navigating directly to the organization's known app or website, a concrete substitute behavior, not just "be suspicious."

**Function 4: Designing for retention.** Because smishing often targets personal phones (delivery scams, package tracking), this is one of the clearest points where workplace and individual/family training genuinely converge (Part II, Section 4) the same lesson applies at the office and at home with almost no adaptation needed.

---

## 5. Pretexting

**The attack.** An attacker fabricates a plausible scenario or false identity; a new vendor, an auditor, a job candidate, an IT contractor to justify a request for information or access that wouldn't otherwise be granted.

**Function 1: Removing the blame.** Pretexting specifically targets the social norm of being helpful and not wanting to seem obstructive or rude, I frame falling for it as a normal, decent human response being exploited, not a lapse in judgment.

**Function 2: Teaching the mechanism.** The core lever is Consistency and Commitment (Stajano & Wilson's scam principles, cited in Part I, Section 6)  a good pretext is built in stages, with each small request making the next one feel like a natural continuation, so the target never feels a single request was unreasonable enough to question.

**Function 3: Building resistance.** Exercises that walk through a full staged pretext from the beginning, pausing at each stage to ask "would I have questioned this step in isolation?" building the specific skill of noticing incremental escalation, which is the part of pretexting that's hardest to catch in the moment.

**Function 4: Designing for retention.** Pretexting case studies work best as narratives told in full sequence, since the technique's power is in the sequence itself a bullet-point summary of "red flags" actually undersells how reasonable each individual step felt at the time, which is the opposite of what Function 4 is trying to achieve.

---

## 6. Baiting

**The attack.** An attacker leaves a physical or digital lure; a USB drive labeled "Payroll 2026," a free download, a too-good-to-be-true offer that the target picks up or opens out of curiosity or self-interest.

**Function 1; Removing the blame.** Curiosity is a normal, healthy trait, not a vulnerability to be ashamed of; I say this explicitly, since baiting specifically exploits a trait people don't expect to have to defend against.

**Function 2: Teaching the mechanism.** The lever here is closer to simple self-interest and curiosity than to Cialdini's classic six, but it functions the same way structurally: it triggers a fast, low-scrutiny System 1 response (Part I, Section 5) before any deliberate risk assessment happens.

**Function 3: Building resistance.** A physical exercise deliberately placing labeled, inert USB drives in a controlled area and observing (anonymously, in aggregate, never naming individuals consistent with Function 1) what proportion get plugged in, followed immediately by a no-blame explanation of the mechanism to everyone in the area, not just those who picked one up.

**Function 4: Designing for retention.** The physical, tangible nature of this exercise tends to make it one of the more memorable in a program by itself,  the retention design challenge here is less about adding emotional engagement and more about making sure the follow-up explanation lands before curiosity turns into embarrassment, which would trigger the blame dynamic Function 1 is built to avoid.

---

## 7. Tailgating and Physical Social Engineering

**The attack.** An attacker follows an authorized person through a secured door, or otherwise talks or blends their way into a physical space they shouldn't have access to.

**Function 1: Removing the blame.** Holding a door for someone carrying boxes is a normal courtesy, not a security failure; I make sure this is said explicitly, since the alternative (treating politeness itself as the problem) risks damaging workplace culture in ways Part I, Section 2 warns against.

**Function 2: Teaching the mechanism.** The lever is Liking and social norms, an attacker dressed plausibly (delivery uniform, ID badge visible but not checked) and behaving confidently exploits the social discomfort of challenging someone who looks like they belong.

**Function 3: Building resistance.** Practicing a specific, low-awkwardness script for verifying an unfamiliar person's access; a scripted phrase people can actually say out loud without it feeling confrontational, tested and refined the way any of the framework's exercises should be (Part II, Section 3, adversarial testing).

**Function 4: Designing for retention.** Physical security walkthroughs where people identify actual points in their own building where tailgating would be easy tend to generate stronger recall than abstract examples from elsewhere, because the stakes are concretely their own space.

---

## 8. Romance Scams

**The attack.** An attacker builds a long-term online relationship with a target, typically over weeks or months, before requesting money; often for a fabricated emergency, travel costs, or an "investment."

**Function 1: Removing the blame.** This is the vector where the risk of victim-blaming is highest, and where Part I, Section 2's critique of blame-based framing matters most directly; I state clearly that the emotional investment exploited here is a normal human need for connection, and that survivors of romance scams frequently report the shame of blame is worse than the financial loss.

**Function 2: Teaching the mechanism.** The primary levers are Liking and Reciprocity, built slowly and deliberately over an extended timeline specifically to bypass the skepticism a faster approach would trigger; this is one of the clearest examples of an attack engineered to prevent System 2 from ever being triggered, because nothing about any single interaction feels urgent or unusual (Part I, Section 5).

**Function 3: Building resistance.** Because this vector unfolds over months, resistance-building exercises focus less on a single simulated exposure and more on teaching recognizable staged patterns (never able to video call, always a plausible reason money is needed urgently, escalating financial requests) that someone can recognize partway through a real relationship, not just in a training scenario.

**Function 4: Designing for retention.** First-person survivor accounts (anonymized, with consent) tend to be the most effective content here Section 7's research on emotional memory applies directly, but the priority in this vector is making sure the emotional content builds empathy and recognition, not the fear-and-shame dynamic Function 1 is specifically trying to prevent.

---

## 9. Family-Impersonation and Grandparent Scams

**The attack.** An attacker calls or messages an older adult, impersonating a grandchild or other family member in urgent trouble (arrested, in an accident, stranded), requesting money be sent immediately and often asking the target not to tell other family members.

**Function 1: Removing the blame.** This vector specifically targets love and fear for a family member's safety; I treat it explicitly as an attack on a core human bond, not a test of the target's judgment, which matters enormously for how family members discuss it with older relatives afterward (shame here often prevents future reporting).

**Function 2: Teaching the mechanism.** The levers are Strong Affect (manufactured panic) and Authority (posing as police or a lawyer in a follow-up call), combined with an isolation instruction ("don't tell anyone”, “keep it between us") that is itself a documented technique for preventing the target from consulting anyone who might introduce System 2 checking into the situation.

**Function 3: Building resistance.** The single highest-value resistance behavior here is a pre-agreed family verification method; a code word or a specific question only real family would know; practiced in a calm setting before it's ever needed under pressure, which is a direct, concrete application of inoculation theory's "practice before the real thing" principle (Part I, Section 8).

**Function 4: Designing for retention.** Because the target audience for this vector is often older adults, delivery format matters as much as content in-person or phone-based discussion led by a trusted family member, rather than written material, tends to fit both the audience and the channel the actual attack will use.

---

## 10. AI-Generated Voice and Video Impersonation (Deepfake Social Engineering)

**The attack.** An attacker uses AI-generated audio or video, often a cloned voice of a real executive, family member, or public figure to make a fraudulent request sound or look convincingly authentic, sometimes combined with a live phone call or video meeting.

**Function 1: Removing the blame.** This is the newest and, in my view, the most important vector to protect people from blame around, precisely because it's designed to defeat a verification method (recognizing a voice or face) that has worked reliably for a person's entire life no one should be made to feel foolish for trusting a voice that sounded exactly like someone they know.

**Function 2: Teaching the mechanism.** The lever is a direct attack on the trust shortcut behind Liking and Authority, instead of impersonating a role, the attacker impersonates the specific, familiar identity itself, which is a categorically stronger version of the same mechanism discussed in Sections 2, 3, and 9 above.

**Function 3: Building resistance.** The same pre-agreed verification approach used for family-impersonation scams (Vector 9) generalizes directly here; a family or team code word, or a callback on an independently verified number, works regardless of how convincing the voice or video is, because it doesn't rely on judging the media at all. This is a clean example of Part I, Section 8's "umbrella protection": resistance built against the general technique (unverifiable urgent requests) protects against a specific new delivery mechanism (AI voice cloning) never explicitly covered before.

**Function 4: Designing for retention.** Demonstrating a real (consented, controlled) voice-clone or deepfake example in training tends to be the single most attention-getting exercise in this entire case study, because it directly confronts people with the limits of a trust mechanism they've relied on their whole lives which is exactly the kind of genuine emotional engagement Section 7's memory research says will stick.

---

## What this case study shows, and what it doesn't

Across all ten vectors, the same four functions repeat, but the specific persuasion levers, the specific resistance-building exercise, and the specific retention approach all change with the channel and the relationship being exploited. I think that's the point: the Human Firewall Framework isn't a script to be read the same way for every attack it's a structure that has to be filled in freshly for each vector, using the actual mechanism that vector relies on (Part II, Function 2's core argument).

Consistent with Part II, Section 5, I want to be clear about what this document is and isn't. It's a worked application of the framework's reasoning to ten well-documented attack types, built the same way Part II itself was built, traced back to the research in Part I wherever a mechanism claim is made, and presented as reasoned design where it describes a specific exercise or delivery choice. It isn't outcome data from running these ten programs at scale, and I haven't presented it as such.
