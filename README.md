# OTTILI PROPRIETARY LICENSE
 
**Version 6.0 — All Rights Reserved**
 
Copyright © 2026 REWOS GmbH and its Affiliates. All rights reserved.
 
SPDX-License-Identifier: `LicenseRef-Ottili-Proprietary-6.0`
Effective Date: as of the date of publication of this Version 6.0
Supersession: This Version 6.0 governs Covered Material distributed, published or made
available under Version 6.0. Rights validly granted under a prior version remain governed
by the version applicable at the time of that grant (see Section 29.3).
 
---
 
## NOTICE — MACHINE-READABLE RIGHTS RESERVATION
 
```
TDM-Reservation: 1
TDM-Policy: https://ottili.one/.well-known/tdm-policy.json
X-Robots-Tag: noai, noimageai, noarchive
```
 
The Licensor expressly reserves, in machine-readable form within the meaning of
**Art. 4(3) of Directive (EU) 2019/790** and **§ 44b(3) UrhG (Germany)**, all rights of
text and data mining, machine learning, model training, fine-tuning, distillation,
retrieval-augmented indexing and comparable automated extraction with respect to all
Covered Material. This reservation is also directed at providers of general-purpose AI
models within the meaning of **Art. 53(1)(c) of Regulation (EU) 2024/1689 (EU AI Act)**.
 
Discovery of this reservation follows the **TDM Reservation Protocol (TDMRep)**; see
Appendix B for the canonical `/.well-known/tdmrep.json` declaration and the ODRL policy
document. Mandatory statutory exceptions that cannot be reserved remain unaffected
(Section 7.2, Section 30).
 
---
 
## NON-BINDING PLAIN-LANGUAGE SUMMARY
 
> This is **not open source**. Everything in here belongs to REWOS GmbH / Ottili.
> You get **no** rights unless you have separate written permission.
> No copying, no reuse, no hosting, no derivatives, no AI training, no reverse
> engineering, no publishing. Access ≠ permission.
>
> *This summary is provided for convenience only, has no legal effect, and is superseded
> in full by Sections 0 – 32 below.*
 
---
 
## 0. STATUTORY RIGHTS RESERVATION AND CONTRACTUAL EFFECT
 
**0.1 Two layers.** This License operates on two distinct legal layers, which must not be
conflated:
 
**(a) Reservation layer — applies to everyone.** The reservations of intellectual property,
text-and-data-mining, database, trademark, trade secret and other statutory rights set out
in this License are **notices and reservations of rights** that operate by force of law, to
the extent permitted by applicable law. They apply *erga omnes* — that is, against any
person who comes into contact with Covered Material — irrespective of whether that person
has entered into any agreement with the Licensor. They do not depend on acceptance,
consent or any contractual relationship.
 
**(b) Contractual layer — applies only to Bound Parties.** The contractual obligations set
out in this License apply **only** to a Recipient who is legally bound by these terms
through an applicable agreement, written authorization, subscription, order form,
employment or contractor relationship, repository or organization membership terms,
click-through or comparable acceptance mechanism, or any other legally effective basis
under applicable law.
 
**0.2 No contract by exposure.** Nothing in this License creates contractual obligations
merely because a person has obtained, viewed, downloaded, cloned, received or otherwise come
into possession of Covered Material, including through a leak, misconfiguration, third-party
disclosure or unauthorized access. Such a person is not a Bound Party and is instead subject
to the Licensor's statutory rights and remedies in full.
 
**0.3 Allocation.**
 
- **Reservation layer (all Recipients):** Sections 2, 3, 4, 6, 7, 8.1–8.2, 9, 14, 15, 16,
  17, 27.1–27.3, 27.7, 30, 31.
- **Contractual layer (Bound Parties only):** Sections 5, 8.4–8.5, 10.3–10.6, 11, 12, 13,
  18, 19, 20, 21, 22, 23, 25, 26, 27.4–27.6, 28, 29.
- **Sections 1, 10.1–10.2 and 32** are definitional or declaratory and apply to both layers
  according to their nature.
 
**0.4 No weakening.** This Section does not limit any statutory claim of the Licensor. Where
no contract exists, the Licensor's rights under copyright, trade secret, database,
trademark, unfair competition, criminal and tort law apply in full and without restriction,
and Sections 6, 7, 8.1–8.2, 9 and 17 are to be read as statements of what is prohibited by
law and as notice of the Licensor's position, not as contractual undertakings by that person.
 
**0.5 Standard terms.** Where this License operates as standard business terms (*Allgemeine
Geschäftsbedingungen*), its incorporation and content control are governed by §§ 305 ff. BGB.
Individually negotiated agreements always prevail (§ 305b BGB).
 
---
 
## 1. DEFINITIONS
 
**1.1 "Licensor"** means REWOS GmbH, a limited liability company organized under the laws of
the Federal Republic of Germany, together with any Affiliate that holds or controls rights
in the Covered Material, and any successor in title.
 
**1.2 "Affiliate"** means any entity that directly or indirectly controls, is controlled by,
or is under common control with a party, where "control" means ownership of more than fifty
percent (50%) of the voting interests or the power to direct management.
 
**1.3 "Ottili"** means the Ottili organization, ecosystem, brands, products, platforms,
projects, services, research programs and internal systems, together with their applicable
legal rights holders.
 
**1.4 "Covered Material"** means any material that is designated, marked, published,
distributed, deployed, transmitted or otherwise made available as Ottili proprietary
material, or that is contained in a repository, system, service, environment or artifact
subject to this License, including without limitation:
 
- source code, object code, binaries, build artifacts, compiled models and containers;
- backend, frontend, mobile, embedded, firmware and infrastructure code;
- scripts, configuration, secrets management logic, deployment and orchestration files;
- APIs, service definitions, protocols, schemas, interfaces, workflows and automation logic;
- prompts, system prompts, AI instructions, agent logic, tool definitions, evaluation
  harnesses, guardrails, routing logic and AI system designs;
- machine-learning models, weights, embeddings, checkpoints, adapters, training pipelines,
  datasets and dataset construction methodology;
- documentation, architecture, specifications, diagrams, roadmaps and planning material;
- database schemas, data models, business logic, pricing logic and platform concepts;
- algorithms, heuristics, benchmarks, evaluation systems and research implementations;
- design assets, UI/UX systems, design tokens, branding assets and product identifiers;
- internal tools, modules, SDKs, integrations, telemetry logic and related material;
- technical concepts, know-how, methods and implementation-specific expression embodied in
  any of the foregoing;
- all modifications, adaptations, translations, derivatives and copies of the foregoing.
 
**1.5 "Recipient"** means any natural or legal person who accesses, receives, possesses,
views, executes, processes or otherwise comes into contact with Covered Material, in any
manner and by any means, whether authorized or not. Recipient status alone does **not**
create a contractual relationship (Section 0.2).
 
**1.6 "Bound Party"** / **"You"** means a Recipient who is legally bound by this License on
one of the bases set out in Section 0.1(b). Where this License uses "You", it addresses a
Bound Party. Where it addresses all persons regardless of contractual status, it uses
"Recipient" or states the prohibition as a matter of law.
 
**1.7 "Authorized Use"** means use expressly permitted by a written authorization,
agreement, subscription plan, order form, employment contract or contractor agreement issued
or entered into by the Licensor, and only within the scope, purpose, territory, user count
and duration expressly granted therein.
 
**1.8 "Hosted Service"** means any Ottili software-as-a-service, API, platform, portal or
managed offering operated by or on behalf of the Licensor, including Ottili ONE, Ottili
Cloud and Ottili HQ.
 
**1.9 "Service Terms"** means the terms of service, acceptable use policy, order form, data
processing agreement and any other contractual terms governing use of a Hosted Service.
 
**1.10 "Contribution"** means any code, documentation, prompt, design, dataset, model,
configuration, issue, pull request, patch, suggestion or other material intentionally
submitted to the Licensor for inclusion in or in connection with Covered Material.
 
**1.11 "AI System"** means any machine-learning model, foundation model, general-purpose AI
model, agentic system, retrieval system, embedding index or comparable automated system.
 
---
 
## 2. SCOPE AND COVERED BRANDS
 
**2.1** This License applies to all Covered Material unless a specific file, directory,
component, subproject or release is expressly and identifiably subject to a different
license.
 
**2.2** Covered brands, products and systems include, without limitation:
 
Ottili · Ottili ONE · Ottili HQ · Ottili Cloud · Ottili Electronics · Ottili Foundation
Framework · Ottili Research Labs · Ottili Operational Intelligence Engine (OOIE) ·
Micro Evolution Engine (MEE) · LD3 · Rooke · Rooke AI · Rooke Code · Rooke Work ·
Rooke Platform · Rooke Spire · and any future Ottili or Rooke product, module, model,
service, research program or internal system.
 
**2.3** The foregoing list is illustrative and non-exhaustive. This License applies on the
basis that material constitutes Ottili proprietary material, and not solely on the basis of
any particular brand or product name appearing in this Section.
 
**2.4** This License applies irrespective of the medium, channel or circumstance of access,
including private repositories, public repositories, mirrors, forks, caches, archives,
backups, package registries, container images, CI/CD artifacts, logs, screenshots,
transcripts, model outputs and accidental or unauthorized disclosures.
 
---
 
## 3. OWNERSHIP AND RESERVATION OF RIGHTS
 
**3.1** All right, title and interest in and to the Covered Material, including all
copyright, database rights (*sui generis* database rights under Directive 96/9/EC and
§§ 87a ff. UrhG), trade secret rights, patent rights, design rights, trademark rights,
know-how and all other intellectual property rights, are and remain the exclusive property
of the Licensor and/or the applicable rights holder.
 
**3.2** This License does not sell, transfer or assign any intellectual property right. It
is a reservation of rights, not a grant.
 
**3.3** **All rights not expressly granted in writing are reserved.** No right arises by
implication, estoppel, acquiescence, course of dealing, industry practice or otherwise.
 
**3.4** Where no contractual relationship exists between the Licensor and a Recipient, the
Licensor's statutory rights under copyright, trade secret, trademark, unfair competition,
database and tort law apply in full and without restriction (Section 0.4).
 
---
 
## 4. NO LICENSE GRANTED
 
**4.1** Except where expressly authorized in writing by the Licensor, **no license,
permission, immunity or right of any kind is granted** to any person or organization to use,
access, copy, store, cache, mirror, fork, modify, adapt, translate, merge, compile,
decompile, publish, distribute, transmit, sublicense, sell, rent, lease, lend, host, deploy,
operate, execute, reproduce, disclose, index, commercialize or otherwise exploit any Covered
Material or any part thereof.
 
**4.2** Access to Covered Material — whether private, internal, temporary, inherited,
accidental, misconfigured, leaked, unauthorized or otherwise unintended — does not by itself
confer any ownership, license, usage, redistribution, commercialization or operational
right.
 
**4.3** Possession of a copy is not a license. Ability to access is not authorization.
Absence of a technical restriction is not permission.
 
---
 
## 5. AUTHORIZED ACCESS AND PERMITTED USERS
 
*(Contractual layer — applies to Bound Parties.)*
 
**5.1** Authorized Use is limited strictly to the purpose, scope, environment, territory,
number of users, duration and conditions expressly granted in writing.
 
**5.2** Bound Parties with Authorized Use shall:
 
a) comply with all applicable confidentiality, access-control, security and usage
   restrictions;
b) restrict access to individuals with a genuine need-to-know who are bound by written
   confidentiality obligations at least as protective as those in Section 10;
c) implement and maintain reasonable technical and organizational security measures;
d) remain fully liable for any act or omission of their personnel, contractors, Affiliates
   and agents as if it were their own;
e) notify the Licensor without undue delay, and in any event within seventy-two (72) hours,
   upon becoming aware of any actual or suspected unauthorized access, disclosure, loss or
   misuse of Covered Material.
 
**5.3** Unless expressly stated otherwise in the applicable written authorization,
authorization does **not** grant: ownership; redistribution rights; sublicensing rights;
commercialization rights; rights to source code; rights to other Ottili products,
repositories, environments or versions; trademark or branding rights; patent licenses; or
any right that survives termination.
 
**5.4** Authorization is personal, non-exclusive, non-transferable and revocable in
accordance with the applicable agreement or, absent such agreement, at any time with
immediate effect.
 
---
 
## 6. RESTRICTED USES
 
*Reservation layer. For Recipients who are not Bound Parties, this Section states the
Licensor's position on what is prohibited by applicable statutory law and constitutes
notice of that position; it does not create contractual duties. For Bound Parties, it
additionally constitutes binding contractual obligations.*
 
Without prior express written authorization from the Licensor, no person may, and no person
may permit or enable any third party to:
 
**6.1 Reuse and derivation**
a) use Covered Material or any substantial part of it in any other product, service,
   platform, repository, model or business;
b) copy, transcribe, re-implement or port proprietary source code, prompts, workflows,
   schemas, designs or implementation-specific business logic, including by manual
   re-typing, paraphrasing or AI-assisted re-generation;
c) create, distribute or operate derivative works, adaptations or forks;
d) extract or reuse a substantial part of any database or dataset, whether qualitatively or
   quantitatively (Art. 7 Directive 96/9/EC; § 87b UrhG).
 
**6.2 Operation and distribution**
e) host, deploy, operate, execute or make available Covered Material or any service based on
   it, whether commercially or free of charge, internally or externally;
f) offer Covered Material as software, SaaS, PaaS, API, module, plugin, template,
   boilerplate, documentation package, dataset, model or training material;
g) sublicense, resell, rent, lease, lend, distribute, publish or otherwise transfer Covered
   Material;
h) commercially exploit Covered Material in any manner.
 
**6.3 Integrity and notices**
i) remove, alter, obscure, bypass or falsify any copyright, license, ownership, attribution,
   confidentiality, watermark, fingerprint or branding notice;
j) misrepresent the origin, authorship or ownership of Covered Material.
 
**6.4 Disclosure**
k) disclose, share, publish, upload, post, stream, demonstrate or transmit Covered Material
   or confidential repository contents to any unauthorized third party, including via public
   repositories, package registries, pastebins, forums, social media, chat services, model
   providers or third-party AI tools;
l) publish screenshots, recordings, transcripts, benchmarks, performance results,
   architecture descriptions or security findings concerning Covered Material, except as
   permitted under Section 11 or as mandatorily permitted by law.
 
**6.5 Circumvention and abuse**
m) circumvent, disable, probe, stress-test or interfere with any license key, entitlement
   check, authentication, rate limit, quota, telemetry, audit mechanism or technical
   protection measure;
n) access Covered Material or a Hosted Service by means of automated scraping, crawling,
   harvesting, bulk export, credential sharing, account multiplication or any undocumented
   interface;
o) use Covered Material or a Hosted Service to develop, train, benchmark against, or assist
   in the development of a competing or substantially similar product or service;
p) use Covered Material in violation of applicable law, including export control, sanctions,
   data protection, criminal and unfair competition law.
 
**6.6** Any authorization granted applies only to the specific purpose, scope and duration
expressly stated, and does not extend to any other Covered Material, version, environment or
affiliate.
 
**6.7** This Section applies subject to Section 30 (mandatory statutory rights) and does not
purport to restrict any act that is mandatorily permitted by law.
 
---
 
## 7. AI, MACHINE LEARNING AND TEXT & DATA MINING
 
**7.1** Without prior express written authorization, no person may, and no person may permit
any third party to:
 
a) use Covered Material, in whole or in part, as training data, validation data, evaluation
   data, alignment data, reward-model data or fine-tuning data for any AI System;
b) perform text and data mining, scraping, crawling, embedding, vectorization, indexing or
   corpus construction on Covered Material;
c) distill, extract, replicate, reverse-derive or approximate models, prompts, agent logic,
   evaluation criteria, workflows, architecture or implementation logic from Covered
   Material or from the outputs of a Hosted Service;
d) submit, upload, paste or otherwise expose Covered Material to any third-party AI System,
   assistant, coding agent, IDE integration, browser extension or cloud service that may
   retain, log, learn from or transmit such material, unless that service is expressly
   approved in writing by the Licensor and contractually excludes training on submitted
   data;
e) use outputs generated by a Hosted Service to train, improve, benchmark or evaluate any
   competing AI System, or to reconstruct Covered Material.
 
**7.2 Scope of the reservation.** The rights reservation in the NOTICE section above and in
Appendix B constitutes an express and machine-readable reservation of use for the purposes
of **Art. 4(3) of Directive (EU) 2019/790** and **§ 44b(3) UrhG**.
 
Accordingly, the **general** text-and-data-mining exception under Art. 4 of Directive
(EU) 2019/790 and § 44b UrhG does not apply to the Covered Material, where and to the extent
the reservation is legally effective.
 
**Mandatory statutory exceptions that cannot be reserved, waived or contractually excluded
remain unaffected.** This includes, in particular, the exception for text and data mining
for purposes of scientific research by research organizations and cultural heritage
institutions under Art. 3 of Directive (EU) 2019/790 and § 60d UrhG, together with
Art. 7(1) of that Directive and § 60g UrhG. The special statutory regime applicable to
computer programs under §§ 69a ff. UrhG and Directive 2009/24/EC applies in addition and
remains unaffected.
 
**7.3** The Licensor may embed watermarks, canary tokens, stylometric markers, synthetic
identifiers or other provenance signals in Covered Material. Detecting, removing,
neutralizing or attempting to defeat such signals is prohibited and constitutes evidence of
intent for the purposes of Section 27.
 
**7.4** Any AI System trained, fine-tuned or materially improved in breach of this Section
constitutes an unauthorized derivative work of, or an unlawful exploitation of, the Covered
Material to the maximum extent permitted by applicable law, and the Licensor reserves all
remedies in respect of such system, its weights and its outputs.
 
**7.5 Search indexing.** The TDM reservation under this Section is a *rights-reserved*
signal, not a general prohibition on lawful web indexing. Where the Licensor permits
indexing of a public website, the applicable `robots.txt` and HTTP header configuration
governs; nothing in this Section shall be construed as opting Ottili's public marketing or
documentation pages out of ordinary search indexing.
 
---
 
## 8. REVERSE ENGINEERING AND MANDATORY STATUTORY EXCEPTIONS
 
**8.1** No person may reverse engineer, decompile, disassemble, deobfuscate, trace, dump,
extract, analyze or otherwise attempt to derive the source code, structure, sequence,
organization, prompts, model weights, algorithms or trade secrets of any Covered Material,
except where mandatorily permitted by applicable law.
 
**8.2 Trade secret effect.** For Bound Parties, Section 8.1 also constitutes a contractual
restriction on reverse engineering within the meaning of **§ 3(1) No. 2 GeschGehG** and
**Art. 3(1)(b) of Directive (EU) 2016/943**, with the effect that reverse engineering of
lawfully obtained Covered Material does not constitute a lawful means of acquiring the trade
secrets embodied therein.
 
**8.3 Mandatory exceptions prevail.** Section 8.1 applies only to the extent permitted by
mandatory applicable law. It does **not** restrict acts that are mandatorily permitted under
**§§ 69d(2), 69d(3) and 69e UrhG** and **Art. 5(2), 5(3) and Art. 6 of Directive
2009/24/EC** (back-up copies; observation, study and testing; and decompilation strictly
necessary to achieve interoperability), nor comparable mandatory provisions of other
jurisdictions. **§ 69g(2) UrhG** is expressly acknowledged: any provision of this License
that would conflict with §§ 69d(2), 69d(3) or 69e UrhG is void to that extent and shall be
read as not applying.
 
**8.4 Interoperability information — offer, not precondition.** The Licensor offers to make
interoperability information available on reasonable terms upon written request. Making such
a request is a **recommended and voluntary** route and is expressly **not** a precondition
to exercising any mandatory statutory right. Where the Licensor supplies the necessary
information, the statutory requirement that the information has not previously been readily
available (Art. 6(1)(b) Directive 2009/24/EC; § 69e(1) No. 2 UrhG) may cease to be met as a
matter of fact.
 
**8.5** Information obtained by exercising a statutory interoperability exception may be
used only within the limits set by that exception, including the statutory restrictions on
disclosure to third parties, on use for other purposes, and on development of a
substantially similar program (Art. 6(2) Directive 2009/24/EC; § 69e(2) UrhG). These are
statutory limits and are restated here for clarity only.
 
---
 
## 9. TECHNICAL PROTECTION MEASURES
 
**9.1** Covered Material may be protected by effective technical measures, including
encryption, obfuscation, licensing servers, entitlement checks, integrity verification,
signing, tamper detection and access controls.
 
**9.2** Circumventing, removing, weakening or trafficking in means of circumventing such
measures is prohibited and may constitute an infringement under **§ 69f(2) UrhG** (for
computer programs) and **§§ 95a ff. UrhG** (for other protected subject matter), **as
applicable in each case**, as well as under **17 U.S.C. § 1201 (DMCA)** and comparable
provisions of other jurisdictions, in addition to any breach of this License.
 
**9.3** The parties note that §§ 95a to 95d UrhG do not apply to computer programs (cf.
§ 69a(5) UrhG); the corresponding protection for computer programs follows from § 69f(2)
UrhG. This Section is to be applied accordingly and shall not be construed to extend any
statutory provision beyond its own scope.
 
---
 
## 10. CONFIDENTIALITY AND TRADE SECRETS
 
**10.1 Confidential status.** Covered Material that is not intentionally and lawfully made
public by the Licensor shall be treated as confidential information.
 
**To the extent such Covered Material satisfies the applicable statutory requirements** —
in particular that it is secret, has commercial value because it is secret, and is subject
to reasonable steps to keep it secret — **it constitutes a protected trade secret** within
the meaning of **§ 2 No. 1 GeschGehG (Germany)**, **Art. 2(1) of Directive (EU) 2016/943**
and **18 U.S.C. § 1839(3) (Defend Trade Secrets Act)**. Nothing in this License purports to
create trade secret status by declaration where the statutory requirements are not met, and
the invalidity of such status for one item does not affect any other item.
 
**10.2 Protective measures.** The Licensor maintains and documents confidentiality measures
intended to satisfy § 2 No. 1(b) GeschGehG and Art. 2(1)(c) of Directive (EU) 2016/943,
including access controls, authentication, need-to-know restrictions, contractual
confidentiality obligations, marking and classification of material, logging, monitoring,
offboarding procedures and this License. **This License is expressly an element of those
protective measures.**
 
**10.3** Bound Parties shall: (a) keep Covered Material strictly confidential; (b) use it
solely within the scope of Authorized Use; (c) not disclose it to any third party without
prior written consent; and (d) protect it with no less than a reasonable standard of care
and in any event no less care than they apply to their own most sensitive confidential
information.
 
**10.4** Making a repository, endpoint, environment, artifact or service technically
accessible does not constitute a decision to make it public, does not waive confidentiality,
and does not authorize redistribution.
 
**10.5** Confidentiality obligations survive termination of any relationship and continue
for as long as the material qualifies for protection under applicable law, without time
limitation for trade secrets.
 
**10.6 Compelled disclosure.** If a Bound Party is legally compelled to disclose Covered
Material, it shall (to the extent legally permitted) notify the Licensor without undue delay
before disclosure, disclose only the minimum required, and cooperate with the Licensor's
efforts to obtain protective treatment.
 
**10.7 Permitted disclosures.** Nothing in this Section restricts disclosures that are
mandatorily permitted or required by law, including disclosures to competent authorities,
protected whistleblower disclosures under Directive (EU) 2019/1937 and the German
Hinweisgeberschutzgesetz, disclosures in exercise of freedom of expression and information,
and the exceptions under § 5 GeschGehG and Art. 5 of Directive (EU) 2016/943.
 
**10.8 DTSA whistleblower immunity notice (18 U.S.C. § 1833(b)).** You will not be held
criminally or civilly liable under any U.S. federal or state trade secret law for the
disclosure of a trade secret that is made (i) in confidence to a federal, state or local
government official, either directly or indirectly, or to an attorney, and solely for the
purpose of reporting or investigating a suspected violation of law; or (ii) in a complaint
or other document filed in a lawsuit or other proceeding, if such filing is made under seal.
An individual who files a lawsuit for retaliation for reporting a suspected violation of law
may disclose the trade secret to their attorney and use the trade secret information in the
court proceeding, if the individual files any document containing the trade secret under
seal and does not disclose the trade secret except pursuant to court order.
 
---
 
## 11. SECURITY RESEARCH AND RESPONSIBLE DISCLOSURE
 
**11.1** The Licensor supports good-faith security research. Notwithstanding Sections 6, 8
and 9, the Licensor will not pursue civil claims under this License against a researcher
who, in good faith:
 
a) tests only systems and assets clearly owned or operated by the Licensor, and only
   accounts and data belonging to that researcher;
b) does not exfiltrate, retain, publish or share Covered Material or third-party personal
   data beyond the minimum necessary to demonstrate the finding;
c) does not degrade, disrupt or damage services, and avoids denial-of-service, social
   engineering, physical attacks and spam;
d) reports the finding promptly and confidentially to the Licensor at the contact address in
   Section 32;
e) allows the Licensor a reasonable remediation period of at least ninety (90) days before
   any public disclosure, and coordinates the content of any disclosure with the Licensor;
f) complies with all applicable law.
 
**11.2** This safe harbor is limited to claims by the Licensor under this License. It does
not bind third parties, does not authorize violation of criminal law (including
§§ 202a–202d, 303a, 303b StGB and the U.S. Computer Fraud and Abuse Act), and does not
constitute a license to any Covered Material.
 
**11.3** Conduct outside the conditions of Section 11.1 is not covered and remains fully
subject to Sections 6, 8, 9, 10 and 27.
 
---
 
## 12. CONTRIBUTIONS AND SUBMISSIONS
 
*(Contractual layer — applies to persons who submit a Contribution, by that act of
submission and any applicable acceptance mechanism.)*
 
**12.1 No ownership.** Contributions, commits, issues, pull requests, patches, suggestions,
translations, designs, datasets or other submissions create **no** ownership, co-ownership,
partnership, license or usage right in Ottili, its repositories, platforms, products,
brands, architecture or any other Covered Material.
 
**12.2 Grant of rights (civil-law jurisdictions).** Insofar as a transfer of copyright is
not permitted (e.g. § 29(1) UrhG), the contributor grants the Licensor an **exclusive**
(*ausschließliches*), transferable, sublicensable, irrevocable to the extent legally
permitted, royalty-free right of use, unlimited in time, territory and content, to exploit
the Contribution in any known manner, including without limitation the rights of
reproduction, distribution, exhibition, public performance, making available to the public,
broadcasting, editing and transformation, translation, porting, integration and combination
with other works, decompilation and re-implementation, use in AI training and evaluation,
sublicensing to customers and third parties, commercial exploitation, and use in advertising
and marketing. The Licensor is entitled to exercise or not exercise these rights at its sole
discretion.
 
**12.3 Grant of rights (common-law jurisdictions).** To the maximum extent permitted, each
Contribution is deemed a "work made for hire" for the Licensor under 17 U.S.C. § 101. To the
extent it is not, the contributor irrevocably assigns to the Licensor all right, title and
interest worldwide in and to the Contribution, including all copyright and other
intellectual property rights. If any such assignment is ineffective, the contributor grants
the Licensor the broadest license permitted under Section 12.2.
 
**12.4 Unknown types of use.** To the extent permitted (§ 31a UrhG), the grant extends to
types of use unknown at the time of the Contribution; the Licensor will observe the
statutory formal and revocation requirements where mandatory.
 
**12.5 Patents.** Each contributor grants the Licensor and its customers, users and
sublicensees a perpetual, worldwide, non-exclusive, royalty-free, irrevocable patent license
to make, have made, use, offer to sell, sell, import and otherwise transfer the Contribution
and any Covered Material incorporating it, covering all patent claims necessarily infringed
by the Contribution alone or in combination with the Covered Material.
 
**12.6 Moral rights.** To the maximum extent permitted, each contributor waives, and agrees
not to assert, all moral rights and rights of attribution and integrity. Where such waiver is
not permitted (as under German law), the contributor agrees not to exercise such rights in a
manner that impairs the Licensor's exploitation of the Contribution.
 
**12.7 Warranties.** Each contributor represents and warrants that the Contribution is their
original work or that they hold all necessary rights; that it does not infringe any
third-party right; that it contains no third-party code, model weights, prompts or data
subject to a copyleft, share-alike or otherwise incompatible license unless expressly
disclosed in writing in advance; and that it contains no malicious code, backdoors,
telemetry or undisclosed dependencies.
 
**12.8 Retained rights.** A contributor may retain rights in their own original Contribution
where applicable, but acquires no ownership or usage right in any other Covered Material by
virtue of contributing.
 
**12.9 Precedence.** Where a separate Contributor License Agreement, employment agreement,
contractor agreement, works agreement or other written rights agreement applies, that
agreement prevails for the relevant Contribution. For employed developers, § 69b UrhG
applies in addition and unaffected.
 
**12.10 Statutory remuneration.** Unwaivable statutory remuneration claims (e.g. §§ 32, 32a,
32c UrhG) remain unaffected.
 
---
 
## 13. FEEDBACK
 
Any feedback, ideas, feature requests, bug reports, evaluations or suggestions a Bound Party
provides regarding Covered Material or a Hosted Service may be used by the Licensor without
restriction, without attribution, without compensation and without any obligation of
confidentiality, and the Bound Party grants the Licensor a perpetual, worldwide, irrevocable,
royalty-free, sublicensable and transferable right to use, incorporate and commercialize such
feedback for any purpose.
 
---
 
## 14. THIRD-PARTY MATERIAL
 
**14.1** Covered repositories, builds, containers and services may include third-party
dependencies, libraries, packages, frameworks, models, fonts, assets, vendored components,
generated dependency mirrors or other externally licensed material.
 
**14.2** Third-party material remains subject to its respective license terms. This License
neither overrides nor replaces any valid third-party license.
 
**14.3** A third-party license applies **only** to the respective third-party material and
grants no rights whatsoever in Ottili-owned source code, platform architecture, proprietary
extensions, prompts, workflows, documentation, business logic, datasets, models, designs,
branding, services or other proprietary project material.
 
**14.4** The mere presence of third-party or open-source components does not render any
Covered Material open source and does not trigger any copyleft obligation with respect to
Ottili-owned material except to the extent mandatorily required by the applicable
third-party license.
 
---
 
## 15. SEPARATELY LICENSED MATERIAL
 
**15.1** A repository may contain files, directories, examples, libraries, SDK components,
research artifacts, schemas or subprojects distributed under a different license.
 
**15.2** Where a separate license or explicit licensing notice applies to specifically
identified material, that separate license governs that material only.
 
**15.3** This may include directories such as `third_party/`, `vendor/`, `external/`,
`open_source/`, `examples/`, `sdk/`, or any material explicitly marked with a different
license identifier.
 
**15.4** The presence of separately licensed material does not alter the proprietary status
of the remaining Covered Material. In case of doubt, material is proprietary and subject to
this License.
 
---
 
## 16. OPEN SOURCE RELEASES
 
**16.1** The Licensor may separately release specific projects, packages, libraries,
specifications, schemas or SDKs under an open-source or source-available license.
 
**16.2** Any such release applies only to the specifically identified material and the
specifically identified version, commit or release artifact covered by that separate
license.
 
**16.3** The release of one Ottili or Rooke component under an open-source license does not
imply, and shall not be construed as implying, that any other component, version, branch,
fork, successor or related material is open source or available under the same terms.
 
**16.4** The Licensor may cease publishing, re-license or dual-license future versions of
any component at its sole discretion, without affecting rights already validly granted for
past releases.
 
---
 
## 17. TRADEMARKS AND BRAND ASSETS
 
**17.1** Ottili, Ottili ONE, Ottili HQ, Ottili Cloud, Ottili Electronics, Ottili Research
Labs, Rooke, Rooke AI, Rooke Code, Rooke Work, Rooke Platform, Rooke Spire, LD3, OOIE, MEE
and all related current or future product names, service names, module names, system names,
model names, codenames, logos, icons, wordmarks, slogans, visual identities, product
identifiers, design elements, domain names, social handles and other brand assets are
proprietary brand assets and/or registered or unregistered trademarks of their applicable
rights holders.
 
**17.2** No trademark, trade name, service mark, branding, endorsement, sponsorship,
certification, merchandising or domain right is granted by this License.
 
**17.3** Permission to use source code or other material under a separate written
authorization does not automatically grant any right to use Ottili or Rooke branding.
 
**17.4** No person may register, apply for, or assist any third party in registering any
identical or confusingly similar mark, domain name, package name, handle or company name, in
any jurisdiction or class.
 
**17.5** Nominative fair use — factual, truthful reference to Ottili products for
identification purposes — is permitted only to the extent mandatorily allowed by applicable
trademark law, and must not suggest affiliation, endorsement or origin.
 
---
 
## 18. HOSTED SERVICES AND END USERS
 
**18.1** Use of a Hosted Service is governed by the applicable Service Terms. This License
governs the underlying Covered Material.
 
**18.2** Access to or use of a Hosted Service grants **no** right, license or interest of any
kind in the underlying source code, prompts, models, architecture, workflows, infrastructure
or any other Covered Material. End users of a Hosted Service receive only a limited,
revocable, non-exclusive, non-transferable right to use the service as a service, strictly in
accordance with the Service Terms.
 
**18.3** In the event of a conflict between this License and the Service Terms with respect
to rights in Covered Material, **this License prevails**, except where the Service Terms
expressly and in writing grant broader rights and are executed by an authorized
representative of the Licensor.
 
**18.4** Without limiting Sections 6 and 7, users of a Hosted Service may not: reverse
engineer or probe the service to reconstruct Covered Material; extract, log or systematically
collect system prompts, tool definitions, agent logic or model behavior; use prompt injection,
jailbreaking or adversarial techniques to obtain Covered Material or to circumvent guardrails;
resell, sublicense, white-label or provide the service to third parties as a bureau, proxy or
reseller service; exceed applicable quotas or share credentials; or use the service to build a
competing product.
 
**18.5** Customer content and customer data are and remain the property of the respective
customer as set out in the Service Terms. Nothing in this License claims ownership of customer
content.
 
**18.6** Aggregated, anonymized and de-identified usage statistics, telemetry and performance
metrics generated in the operation of a Hosted Service may be used by the Licensor to operate,
secure, analyze and improve its products, subject to applicable data protection law and the
Service Terms.
 
**18.7 Mandatory customer rights.** Nothing in this License limits mandatory customer rights
under applicable law, including data portability and switching rights under the GDPR and under
**Regulation (EU) 2023/2854 (Data Act)**, mandatory rights under Directive (EU) 2019/770, or
mandatory consumer protection rights. Where such rights apply, the applicable Service Terms
and statutory provisions govern; this License is limited to intellectual property in the
Covered Material.
 
---
 
## 19. BETA, PREVIEW AND INTERNAL MATERIAL
 
**19.1** Covered Material designated as alpha, beta, preview, experimental, research,
internal, staging or "not for production" is provided, if at all, solely for evaluation, on
an as-is basis, without any commitment as to availability, functionality, compatibility,
continuity or support, and may be modified, restricted or discontinued at any time without
notice or liability.
 
**19.2** Such material is confidential in the sense of Section 10 and may not be disclosed,
benchmarked or discussed publicly.
 
**19.3** The Licensor has no obligation to release, maintain or support any such material,
and no obligation to provide updates, migrations or backward compatibility.
 
---
 
## 20. NO WARRANTY
 
**20.1** TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE COVERED MATERIAL IS PROVIDED
**"AS IS" AND "AS AVAILABLE", WITHOUT WARRANTY OF ANY KIND**, EXPRESS, IMPLIED, STATUTORY OR
OTHERWISE, INCLUDING WITHOUT LIMITATION ANY WARRANTY OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE, TITLE, ACCURACY, RELIABILITY, SECURITY, AVAILABILITY, UNINTERRUPTED OR
ERROR-FREE OPERATION, ABSENCE OF MALICIOUS CODE, OR NON-INFRINGEMENT.
 
**20.2** No advice or information, whether oral or written, obtained from the Licensor or
through any channel, creates any warranty not expressly stated in a signed written agreement.
 
**20.3** The Licensor does not warrant that Covered Material is suitable for use in high-risk,
safety-critical, medical, financial, legal, regulated or life-sustaining environments, and
disclaims all liability for such use.
 
**20.4** AI-generated or AI-assisted outputs may be inaccurate, incomplete, biased or
otherwise unsuitable. Outputs are not professional, legal, medical, financial or safety
advice, and must be independently verified before reliance.
 
**20.5** The Licensor is under no obligation to provide maintenance, support, updates,
security patches, bug fixes or backward compatibility, unless expressly agreed in writing.
 
**20.6** Mandatory statutory warranty rights that cannot be excluded — in particular under
German law in cases of fraudulent concealment of a defect (*arglistiges Verschweigen*) or an
express guarantee (*Garantie*), and under mandatory consumer protection law including
Directive (EU) 2019/770 — remain unaffected.
 
---
 
## 21. LIMITATION OF LIABILITY
 
**21.1** TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE LICENSOR SHALL NOT BE LIABLE
FOR ANY INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, PUNITIVE OR CONSEQUENTIAL DAMAGES, NOR FOR
LOSS OF PROFITS, REVENUE, GOODWILL, BUSINESS OPPORTUNITY, DATA, USE, PRODUCTION OR ANTICIPATED
SAVINGS, NOR FOR BUSINESS INTERRUPTION OR COST OF SUBSTITUTE PROCUREMENT, HOWEVER CAUSED AND
UNDER ANY THEORY OF LIABILITY, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
 
**21.2** TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THE LICENSOR'S TOTAL AGGREGATE
LIABILITY ARISING OUT OF OR RELATED TO THE COVERED MATERIAL SHALL NOT EXCEED THE GREATER OF
(A) THE AMOUNTS ACTUALLY PAID TO THE LICENSOR FOR THE SPECIFIC COVERED MATERIAL GIVING RISE TO
THE CLAIM IN THE TWELVE (12) MONTHS PRECEDING THE EVENT, OR (B) ONE HUNDRED EUROS (EUR 100.00).
 
**21.3 German law carve-outs.** The limitations in Sections 21.1 and 21.2 do **not** apply to
liability: (a) for intent (*Vorsatz*) or gross negligence (*grobe Fahrlässigkeit*); (b) for
injury to life, body or health; (c) under the German Product Liability Act
(*Produkthaftungsgesetz*); (d) arising from fraudulent concealment of a defect; (e) arising
from an express guarantee; or (f) under mandatory statutory provisions that cannot be excluded.
 
**21.4 Cardinal obligations.** In the case of slight negligence (*einfache Fahrlässigkeit*),
the Licensor is liable only for breach of a material contractual obligation
(*Kardinalpflicht*) — an obligation whose fulfilment is essential to the proper performance of
the contract and on whose observance the other party may regularly rely — and in that case
only for the foreseeable damage typical for this type of contract.
 
**21.5 Gratuitous provision.** Where the Licensor makes Covered Material available entirely
free of charge and without consideration, the parties intend that the Licensor's liability be
limited to intent and gross negligence, to the extent such a limitation is permissible under
applicable law. Whether and to which extent statutory privileges for gratuitous transactions
apply is determined by the applicable law and is not asserted here as a matter of course.
 
**21.6** The foregoing limitations apply equally to the Licensor's Affiliates, employees,
officers, agents, contractors and licensors, who may invoke them as third-party
beneficiaries.
 
**21.7** Nothing in this Section limits mandatory consumer protection rights.
 
**21.8** A reversal of the burden of proof to the detriment of the Bound Party is not
associated with the foregoing provisions.
 
---
 
## 22. INDEMNIFICATION
 
**22.1** To the maximum extent permitted by applicable law, a Bound Party shall indemnify,
defend and hold harmless the Licensor, its Affiliates and their respective officers,
employees, agents and contractors from and against any and all claims, demands, proceedings,
damages, losses, fines, penalties, costs and expenses (including reasonable attorneys' fees,
court costs and costs of investigation and enforcement) arising out of or related to:
 
a) its breach of this License;
b) its unauthorized use, disclosure, reproduction or distribution of Covered Material;
c) its violation of applicable law, third-party rights or the rights of data subjects in
   connection with Covered Material;
d) any Contribution it submits that infringes third-party rights or that misrepresents its
   licensing status.
 
**22.2** The Licensor may, at its option and at the Bound Party's expense, assume the
exclusive defense and control of any matter subject to indemnification. The Bound Party shall
not settle any such matter in a manner that admits liability of, or imposes any obligation on,
the Licensor without its prior written consent.
 
**22.3** Mandatory statutory limitations on indemnification, mandatory employee liability
privileges under German labour law, and mandatory consumer protection law remain unaffected.
 
---
 
## 23. EXPORT CONTROL, SANCTIONS AND TRADE COMPLIANCE
 
**23.1** Covered Material may be subject to export control and sanctions laws, including the
U.S. Export Administration Regulations (EAR, 15 C.F.R. Parts 730–774), U.S. sanctions
administered by OFAC, Regulation (EU) 2021/821 (Dual-Use Regulation), EU restrictive measures,
and the German Foreign Trade and Payments Act (AWG) and Ordinance (AWV).
 
**23.2** No person shall export, re-export, transfer, release or otherwise make available
Covered Material, directly or indirectly, to: (a) any embargoed or sanctioned country, region
or territory; (b) any person or entity listed on a restricted-party list (including the SDN
List, Entity List, Denied Persons List, and EU consolidated sanctions list); or (c) any end
use relating to nuclear, chemical or biological weapons, missile technology, unlawful
surveillance or military end uses where prohibited.
 
**23.3** Each Bound Party represents that it is not located in, organized under the laws of, or
ordinarily resident in any such jurisdiction, and is not owned or controlled by, or acting on
behalf of, any restricted party.
 
**23.4** Any breach of this Section terminates all authorizations immediately and
automatically.
 
**23.5** Compliance with EU or German law that conflicts with the EU Blocking Statute
(Regulation (EC) No 2271/96) is required only to the extent permitted under that Regulation.
 
---
 
## 24. U.S. GOVERNMENT END USERS
 
Covered Material is "commercial computer software" and "commercial computer software
documentation" as those terms are used in **48 C.F.R. § 2.101**. Consistent with **48 C.F.R.
§ 12.212** and **48 C.F.R. §§ 227.7202-1 through 227.7202-4**, U.S. Government end users
acquire Covered Material only with those rights set forth in this License. No other rights,
express or implied, are granted, and any provision inconsistent with federal procurement
regulations is unenforceable only to the minimum extent required.
 
---
 
## 25. TERM, TERMINATION AND SURVIVAL
 
**25.1** The contractual layer of this License applies for as long as a Bound Party possesses,
accesses or uses Covered Material. The reservation layer applies for as long as the Covered
Material is protected by applicable law.
 
**25.2** Any Authorized Use terminates automatically and without notice upon: (a) any breach
of this License or the applicable authorization; (b) expiry, revocation or termination of the
underlying agreement, subscription or employment/contractor relationship; (c) breach of
Section 23; or (d) insolvency, liquidation or comparable proceedings concerning the Bound
Party, to the extent legally permissible.
 
**25.3** Upon termination or upon written request by the Licensor, a Bound Party shall
immediately: (a) cease all use and access; (b) permanently delete or destroy all copies of
Covered Material in its possession or control, including backups, caches, forks, mirrors,
model artifacts, embeddings, derived indexes and printed copies; (c) purge Covered Material
from any AI System, vector store or training corpus to the extent technically possible; and
(d) upon request, certify compliance in writing within fourteen (14) days. Statutory or
regulatory retention obligations remain unaffected; material retained under such an obligation
remains subject to Section 10.
 
**25.4** Sections 0, 1, 3, 4, 6, 7, 8, 9, 10, 12, 13, 14, 17, 20, 21, 22, 23, 24, 25.3, 26,
27, 28, 29, 30 and 31 survive termination.
 
**25.5** Termination is without prejudice to any accrued rights or remedies.
 
---
 
## 26. AUDIT AND VERIFICATION
 
**26.1** Where an Authorized Use exists, the Licensor may, upon at least ten (10) business
days' prior written notice, not more than once per twelve (12) months (unless a prior audit
revealed non-compliance or the Licensor has reasonable grounds to suspect a breach), verify
compliance with this License during normal business hours, in a manner that minimizes
disruption.
 
**26.2** Audits may be conducted by the Licensor or an independent auditor bound by
confidentiality. The Bound Party shall provide reasonable cooperation and access to relevant
records, deployments, logs and systems, subject to applicable law, data protection
requirements, professional secrecy obligations, works council participation rights and its
reasonable security policies.
 
**26.3** If an audit reveals underpayment or unauthorized use, the Bound Party shall promptly
remedy the non-compliance, pay the applicable fees for the actual scope of use, and bear the
reasonable costs of the audit where the deviation exceeds five percent (5%) or where use was
unauthorized.
 
---
 
## 27. ENFORCEMENT, REMEDIES AND CONTRACTUAL PENALTY
 
**27.1** Unauthorized copying, use, disclosure, distribution, deployment, commercialization,
extraction, training or publication of Covered Material may constitute infringement of
copyright, trade secret, trademark, database and unfair competition rights, and may give rise
to civil and criminal liability (including under §§ 106–111a UrhG, § 23 GeschGehG,
§§ 202a ff. StGB, 17 U.S.C. §§ 501 ff., 18 U.S.C. §§ 1832, 1836). This applies to any person,
irrespective of contractual status.
 
**27.2 Injunctive relief.** A breach of Sections 6, 7, 8, 9, 10 or 17 is liable to cause
irreparable harm for which monetary damages are inadequate. The Licensor is therefore entitled
to seek injunctive and other equitable relief, including preliminary and permanent injunctions
and, where available, ex parte relief, in any competent forum, without the necessity of posting
a bond or proving actual damages, in addition to all other remedies. Where a Bound Party is
concerned, the Bound Party acknowledges the foregoing.
 
**27.3 Damages.** The Licensor may claim damages calculated, at its election and to the extent
permitted by applicable law, on the basis of (a) actual loss, (b) the infringer's profits, or
(c) a reasonable license fee (*Lizenzanalogie*), plus interest, and may claim information,
accounting, recall, destruction and publication of judgment under §§ 97–101 UrhG and
§§ 6–8 GeschGehG. Under U.S. law, the Licensor reserves the right to elect statutory damages
and attorneys' fees under 17 U.S.C. §§ 504, 505 in respect of registered works, and exemplary
damages and fees under 18 U.S.C. § 1836(b)(3) in respect of willful and malicious trade secret
misappropriation.
 
**27.4 Contractual penalty.** For each culpable breach of Sections 6, 7, 8, 9 or 10 by a Bound
Party who is not a consumer, and to the extent permitted by applicable law, the Licensor may
claim a reasonable contractual penalty, the amount of which is determined by the Licensor at
its reasonable discretion (§ 315 BGB) and, in the event of dispute, reviewed by the competent
court ("*Hamburger Brauch*"). The penalty presupposes fault, is set off against any damages
claim, and further claims remain unaffected. The defence of continuation of offence
(*Fortsetzungszusammenhang*) is excluded to the extent legally permissible. This provision does
not apply to consumers (§ 309 No. 6 BGB) and does not apply to persons who are not Bound
Parties.
 
**27.5 Costs.** To the extent permitted by applicable law, a Bound Party shall bear the
reasonable costs of legal enforcement, including attorneys' fees, warning letters
(*Abmahnkosten*), forensic investigation, expert fees and court costs, incurred as a result of
its breach. Statutory cost-shifting rules remain unaffected.
 
**27.6 No waiver by non-enforcement.** Failure or delay in enforcing any right does not
constitute a waiver of that right or of any other right, and does not create any custom,
practice or expectation.
 
**27.7 Notice-and-takedown.** The Licensor may issue takedown notices (including under
17 U.S.C. § 512 and Regulation (EU) 2022/2065) to any platform, registry, host or provider
distributing Covered Material without authorization. Bound Parties waive any claim against the
Licensor arising from a good-faith takedown notice, to the extent legally permissible.
 
---
 
## 28. GOVERNING LAW, JURISDICTION AND LANGUAGE
 
**28.1 Governing law.** This License and any non-contractual obligations arising out of or in
connection with it are governed exclusively by the laws of the **Federal Republic of Germany**,
excluding its conflict-of-laws rules and excluding the United Nations Convention on Contracts
for the International Sale of Goods (CISG). Mandatory rules of the law of the country of
protection (*lex loci protectionis*) applicable to intellectual property claims remain
unaffected.
 
**28.2 Jurisdiction.** To the extent legally permissible, the exclusive place of jurisdiction
for all disputes arising out of or in connection with this License is **Bamberg, Germany**.
This applies in particular where the Bound Party is a merchant (*Kaufmann*), a legal entity
under public law, a special fund under public law, or has no general place of jurisdiction in
Germany, or relocates its domicile or habitual residence outside Germany after entering into
this License.
 
**28.3 Additional fora.** The Licensor is additionally entitled, at its sole election, to bring
proceedings — in particular proceedings for injunctive relief, seizure, border detention,
discovery or enforcement — before any court having jurisdiction over the defendant, over the
location of the infringement, or over assets of the defendant, including courts in the United
States of America.
 
**28.4 Mandatory consumer and employee jurisdiction.** Mandatory statutory provisions on
jurisdiction and applicable law for consumers and employees remain unaffected.
 
**28.5 Language.** The authoritative version of this License is the **English** version. Any
translation is provided for convenience only. Where mandatory law requires that terms be
provided in another language vis-à-vis a particular Recipient, that language version shall
prevail with respect to that Recipient only, to the minimum extent required.
 
**28.6 Jury trial.** To the extent this License is adjudicated under U.S. law and to the
maximum extent permitted, each party irrevocably waives any right to trial by jury.
 
---
 
## 29. GENERAL PROVISIONS
 
**29.1 Entire terms; precedence.** This License, together with any applicable signed written
agreement, Service Terms and authorization, constitutes the complete terms regarding rights in
Covered Material. In case of conflict, the following order of precedence applies: (1) an
individually negotiated, signed written agreement; (2) this License; (3) Service Terms; (4) any
other document. Individual agreements (*Individualabreden*, § 305b BGB) always prevail.
 
**29.2 No implied rights.** No right is granted, and no waiver occurs, by reason of: access;
disclosure; possession; repository or organization membership; employment or contractor access
alone; API availability; documentation availability; public visibility of a repository;
indexing by search engines or AI systems; publication of technical information; prior conduct;
or failure to respond to a permission request. Silence is never consent.
 
**29.3 Versions and amendments.** The Licensor may issue future versions of this License. A new
version applies to Covered Material distributed, published or made available on or after the
effective date of that version. Material lawfully obtained under a prior version remains
subject to that version unless the Recipient accepts the newer version or a separate agreement
provides otherwise. For Bound Parties, changes to the contractual layer take effect only on the
basis of a legally effective amendment mechanism.
 
**29.4 Assignment.** A Bound Party may not assign, delegate or transfer this License or any
rights or obligations under it, in whole or in part, by operation of law, change of control,
merger or otherwise, without the Licensor's prior written consent; any purported assignment
without consent is void to the extent legally permissible. The Licensor may freely assign or
transfer this License and all rights in Covered Material, including to an Affiliate or in
connection with a merger, reorganization, financing or sale of assets.
 
**29.5 Severability.** If any provision of this License is or becomes invalid, void or
unenforceable in whole or in part, the validity of the remaining provisions remains unaffected.
The invalid provision shall be replaced by the applicable statutory provision. Where legally
permissible, the parties shall agree on a valid provision that comes closest to the economic
purpose of the invalid provision. The same applies to any omission. The parties are aware that
a reduction preserving validity (*geltungserhaltende Reduktion*) is not permissible in the
context of standard business terms.
 
**29.6 No waiver.** No waiver is effective unless made in writing and signed by an authorized
representative of the Licensor. A waiver in one instance is not a waiver in any other instance.
 
**29.7 Form.** Notices, consents and authorizations under this License require text form
(§ 126b BGB) at minimum; email to the address in Section 32 suffices unless a signed agreement
requires more.
 
**29.8 No partnership.** Nothing in this License creates any partnership, joint venture,
agency, fiduciary, employment or franchise relationship.
 
**29.9 Third-party beneficiaries.** The Licensor's Affiliates, licensors, officers, employees
and contractors are intended third-party beneficiaries of Sections 20, 21 and 22. There are no
other third-party beneficiaries.
 
**29.10 Interpretation.** "Including" means "including without limitation". Headings and the
parenthetical layer notes are for convenience only and, except for Section 0.3, do not affect
interpretation. Singular includes plural and vice versa. No rule of construction against the
drafter applies. References to statutes include their successor provisions and implementing
rules.
 
**29.11 Cumulative remedies.** All rights and remedies are cumulative and in addition to any
other rights and remedies available at law or in equity.
 
**29.12 Force majeure.** The Licensor is not liable for any failure or delay caused by
circumstances beyond its reasonable control.
 
---
 
## 30. MANDATORY STATUTORY RIGHTS
 
**30.1** Nothing in this License is intended to restrict, exclude or limit any right that
cannot lawfully be restricted, excluded or limited under mandatory applicable law.
 
**30.2** This includes, without limitation:
 
a) **§ 69d(2), (3) and § 69e UrhG** and Art. 5(2), 5(3) and Art. 6 of Directive 2009/24/EC —
   back-up copies, observation/study/testing, and decompilation for interoperability; any
   conflicting contractual provision is void under **§ 69g(2) UrhG**;
b) **§§ 60a–60f UrhG**, including the scientific text-and-data-mining exception in **§ 60d
   UrhG**; contractual restrictions to the detriment of beneficiaries are ineffective under
   **§ 60g UrhG** and Art. 7(1) of Directive (EU) 2019/790;
c) **§ 5 GeschGehG** and Art. 5 of Directive (EU) 2016/943 — exceptions for freedom of
   expression, disclosure of misconduct and employee representation;
d) whistleblower protection under Directive (EU) 2019/1937 and the German
   Hinweisgeberschutzgesetz;
e) unwaivable author remuneration claims under **§§ 32, 32a, 32c UrhG**;
f) mandatory consumer protection law, mandatory employment law and mandatory data protection
   law;
g) mandatory provisions of U.S. federal law and of any other applicable jurisdiction.
 
**30.3** Where a provision of this License would otherwise exceed what is permitted by such
mandatory law, that provision applies only to the maximum extent permitted, and the remainder
of the License remains fully effective.
 
---
 
## 31. PERMISSION REQUESTS
 
**31.1** Permission to use Covered Material beyond the rights expressly granted must be
obtained **in writing and in advance** from the applicable Ottili rights holder.
 
**31.2** A lack of response does **not** constitute permission. Verbal statements, statements
by unauthorized personnel, community forum posts, support tickets and AI-generated responses do
not constitute authorization.
 
**31.3** Only a written authorization signed or issued in text form by an authorized
representative of the Licensor is binding.
 
---
 
## 32. CONTACT AND PROVIDER IDENTIFICATION
 
**REWOS GmbH** — Ottili Legal
 
- Legal & Licensing: `legal@ottili.one`
- Security & Responsible Disclosure: `security@ottili.one`
- Permissions & Partnerships: `permissions@ottili.one`
- TDM licensing enquiries: `tdm@ottili.one`
 
*(Insert registered address, register court and HRB number, managing director(s) and VAT ID as
required by **§ 5 DDG** (Digitale-Dienste-Gesetz — the TMG was repealed on 14 May 2024) and
§ 35a GmbHG.)*
 
---
 
## APPENDIX A — SOURCE FILE HEADER
 
```
/*
 * Copyright (c) 2026 REWOS GmbH. All rights reserved.
 *
 * This file is part of the Ottili ecosystem and is PROPRIETARY AND CONFIDENTIAL.
 * Licensed under the Ottili Proprietary License v6.0 — see LICENSE.md.
 *
 * Unauthorized copying, use, modification, distribution, disclosure, deployment,
 * reverse engineering or AI training on this file, in whole or in part, by any
 * means, is prohibited. Access does not grant any rights.
 *
 * Trade secret to the extent the statutory requirements are met
 * (§ 2 No. 1 GeschGehG · Directive (EU) 2016/943 · 18 U.S.C. § 1839(3)).
 *
 * Text and data mining rights reserved (Art. 4(3) Directive (EU) 2019/790;
 * § 44b(3) UrhG). Mandatory statutory exceptions remain unaffected.
 *
 * SPDX-License-Identifier: LicenseRef-Ottili-Proprietary-6.0
 */
```
 
Python / shell variant:
 
```
# Copyright (c) 2026 REWOS GmbH. All rights reserved.
# Proprietary and confidential — Ottili Proprietary License v6.0 (see LICENSE.md).
# Unauthorized use, copying, disclosure, reverse engineering or AI training prohibited.
# TDM rights reserved (§ 44b(3) UrhG / Art. 4(3) EU 2019/790).
# SPDX-License-Identifier: LicenseRef-Ottili-Proprietary-6.0
```
 
---
 
## APPENDIX B — MACHINE-READABLE RESERVATIONS (TDMRep)
 
**B.1 — `/.well-known/tdmrep.json`** *(canonical discovery file; the filename is fixed by the
TDMRep specification and must not be changed)*
 
```json
[
  {
    "location": "/",
    "tdm-reservation": 1,
    "tdm-policy": "https://ottili.one/.well-known/tdm-policy.json"
  }
]
```
 
**B.2 — ODRL policy document** *(served as `application/ld+json` at the `tdm-policy` URL; the
policy filename is free)*
 
```json
{
  "@context": [
    "http://www.w3.org/ns/odrl.jsonld",
    { "tdm": "http://www.w3.org/ns/tdmrep#" }
  ],
  "@type": "Offer",
  "profile": "http://www.w3.org/ns/tdmrep",
  "uid": "https://ottili.one/.well-known/tdm-policy.json",
  "assigner": {
    "uid": "https://ottili.one",
    "vcard:fn": "REWOS GmbH — Ottili Legal",
    "vcard:hasEmail": "mailto:tdm@ottili.one"
  },
  "permission": [
    {
      "target": "https://ottili.one",
      "action": "tdm:mine",
      "constraint": [
        { "leftOperand": "tdm:purpose", "operator": "eq", "rightOperand": "tdm:research" }
      ]
    },
    {
      "target": "https://ottili.one",
      "action": "tdm:mine",
      "constraint": [
        { "leftOperand": "tdm:purpose", "operator": "eq", "rightOperand": "tdm:non-research" }
      ],
      "duty": [
        { "action": "obtain-consent", "target": "mailto:tdm@ottili.one" }
      ]
    }
  ]
}
```
 
*Rationale: `tdm:research` is left open because Art. 3 of Directive (EU) 2019/790 and § 60d
UrhG cannot be reserved against (§ 60g UrhG). `tdm:non-research` requires prior consent,
which is precisely the Art. 4(3) reservation.*
 
**B.3 — HTTP response headers**
 
```
X-Robots-Tag: noai, noimageai, noarchive
TDM-Reservation: 1
TDM-Policy: https://ottili.one/.well-known/tdm-policy.json
```
 
> **Do not add `noindex`** on public marketing or documentation pages — it removes them from
> search engines entirely. The TDM reservation is a *rights-reserved* signal, not a search
> opt-out (see Section 7.5). Use `noindex` only on genuinely non-public paths.
 
**B.4 — HTML `<head>` meta tags**
 
```html
<meta name="robots" content="noai, noimageai, noarchive">
<meta name="tdm-reservation" content="1">
<meta name="tdm-policy" content="https://ottili.one/.well-known/tdm-policy.json">
```
 
**B.5 — `/robots.txt`** *(complementary, non-normative; a de-facto standard, not a legal
reservation mechanism — keep the search-engine crawlers allowed)*
 
```
User-agent: GPTBot
Disallow: /
User-agent: ChatGPT-User
Disallow: /
User-agent: OAI-SearchBot
Disallow: /
User-agent: ClaudeBot
Disallow: /
User-agent: Claude-Web
Disallow: /
User-agent: anthropic-ai
Disallow: /
User-agent: Google-Extended
Disallow: /
User-agent: Applebot-Extended
Disallow: /
User-agent: CCBot
Disallow: /
User-agent: Bytespider
Disallow: /
User-agent: PerplexityBot
Disallow: /
User-agent: Amazonbot
Disallow: /
User-agent: meta-externalagent
Disallow: /
User-agent: cohere-ai
Disallow: /
User-agent: Diffbot
Disallow: /
User-agent: omgili
Disallow: /
 
# Search indexing remains permitted:
User-agent: *
Allow: /
Sitemap: https://ottili.one/sitemap.xml
```
 
---
 
## APPENDIX C — REPOSITORY README NOTICE
 
```markdown
## License
 
**Proprietary — All Rights Reserved.**
Copyright © 2026 REWOS GmbH.
 
This repository is **not open source**. It is licensed under the
[Ottili Proprietary License v6.0](./LICENSE.md).
 
No use, copying, modification, distribution, hosting, reverse engineering
or AI/ML training is permitted without prior written authorization.
Access to this repository does **not** grant any rights — and does not
create a contract (see Section 0 of the License).
 
Text and data mining rights are reserved
(Art. 4(3) Directive (EU) 2019/790 · § 44b(3) UrhG).
Mandatory statutory exceptions remain unaffected.
 
Permission requests: legal@ottili.one
```
 
---
 
**OTTILI PROPRIETARY LICENSE — VERSION 6.0**
**Copyright © 2026 REWOS GmbH. All Rights Reserved.**
**END OF LICENSE**
