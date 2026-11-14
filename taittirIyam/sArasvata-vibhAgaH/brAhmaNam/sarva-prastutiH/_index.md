+++
title = "+सर्व-प्रस्तुतिः"
unicode_script = "devanagari"
+++

<details><summary>Block splitting principles</summary>

**Fine splitting of विश्वास-प्रस्तुतिः, मूलम् and \*टीका blocks**

**Goal:** Split the text (or existing blocks) into the smallest विश्वास-प्रस्तुतिः, मूलम्, टीका blocks that still make complete sense on their own.

**Definitions:**
- **Sentence segment:** A string ending in a daNDa, either `।` or `॥`. Do not split inside a segment.
- **Block:** One or more sentence segments kept together (within विश्वास-प्रस्तुतिः, मूलम्, टीका details blocks) because they form a single sense unit.
- **Boundary:** The point between two consecutive sentence segments. The decision is made boundary by boundary.

**Default rule:** By default, every sentence segment goes to a separate block. Do not split at a boundary if any of the tests below applies. Check the tests in this order. If a boundary passes an earlier test, keep the segments together and do not need the later tests.

**1. Same Rk:** If several sentence segments together form one Rk, mantra, or verse, keep them together. The metrical unity overrides the daNDa. The Rk is one block even if it contains multiple daNDas.

**2. Same conditional-correlative unit:** This is the Sanskrit `yad` / `tad` construction, not the English word "if" alone. It covers pairs like `yaH / saH`, `yat / tat`, `yatra / tatra`, `yadA / tadA`, `yathA / tathA`, `yAni / tAni`, `yad / etad`, and similar. A boundary is inside one conditional unit when: **(a) Protasis first:** The left segment opens with a `yad`-word, and the right segment gives its correlative or consequence. **(b) Main clause first:** The left segment is a main statement, and the right segment opens with a `yad`-word that explains, qualifies, or defines it. **(c) Continuation:** The left segment is already inside an open conditional, and the right segment continues, elaborates, or concludes it, even if it has no explicit `tad`-word. In other words, a `yad`-segment attaches to its counterpart, whether that counterpart comes before it or after it.

Examples:

> यः का॒मये॑त॒ दान॑कामा मे प्र॒जाः स्यु॒रिति॑ । स पूर्व॑योः॒ फल्गु॑न्योर॒ग्निमाद॑धीत ॥

Protasis first, apodosis second. One block.

> अ॒र्य॒म्णो वा ए॒तन्नक्ष॑त्रम् । यत्पूर्वे॒ फल्गु॑नी ।

Main statement first, explanatory `yat` second. One block.

> यः का॒मये॑त भ॒गी स्या॒मिति॑ । स उत्त॑रयोः॒ फल्गु॑न्योर॒ग्निमाद॑धीत ।

> य᳓ एवं᳓ वे᳓द ॥ गृह्य् ए᳙व᳓ भवति ॥

> या᳓नि वा᳓ इमा᳓नि पृथिव्या᳓श् चित्रा᳓णि ॥ ता᳓नि न᳓क्षत्राणि ॥

> य᳓द् अपिवापा᳓ भ᳓वन्ति ॥ यज्ञ᳓स्य धृ᳓त्या अ᳓संव्लयाय ॥

A conditional can extend beyond a pair. All segments that complete the same conditional stay together:

> य᳓ एवं᳓ विद्वा᳓न् लोहितायसे᳓न नि᳓वर्त᳓यते ॥
> एत᳓द् एव᳓ रूपं᳓ कृत्वा᳓ नि᳓वर्तयते ॥
> स᳓ त᳓तः श्वः᳓_श्वो भू᳓यान् भ᳓वन्न् एति ॥
> प्र᳓_एव᳓ जायते ॥

**3. Quotation inside a conditional:** If a quotation is embedded inside a conditional, do not split at the quotation boundary. The whole span, protasis plus embedded quote plus resolution, is one block. The quotation does not break the conditional, and the conditional does not break the quotation.

Examples:

> स᳓ य᳓द् ब्रूया᳓त् ॥
> क᳓स् ता᳓नि नि᳓रमिमी᳓त_इ᳓ति ॥
> प्रजा᳓पतिर् इ᳓ति ब्रूयात् ॥

> स᳓ य᳓द् ब्रूया᳓त् ॥
> कु᳓तस् ता᳓नि नि᳓रमिमीत_इ᳓ति ॥
> आत्म᳓न इ᳓ति ॥

Here `sa yad brUyAt` opens the conditional, the middle segment is the quoted question, and the last segment is the quoted answer. All three stay together.

**4. Same quotation:** If several segments belong to one quoted speech, keep them together with its quotative frame. A boundary is inside one quotation when: **(a)** The left segment is the frame, such as `so'bravIt`, `tadAhuH`, `brahmavAdino vadanti`, `iti brUyAt`, and the right segment begins the quote. **(b)** Both segments are inside the same quote, between the frame and the closing `iti`. **(c)** The quote itself contains several sentences. They are not split from each other or from the frame.

Examples:

> सो॑ऽब्रवीत् ।
> स॒प्त॒द॒शेन॑ ह्रि॒यमा॑णो॒ व्य॑लेशिषि । भि॒षज्य॑त॒मेति॑ ।

> तदा॑हुः ॥ १। ५। ११। २॥ ५६ यद॒श्विभ्यां॑ धा॒नाः । पू॒ष्णः क॑र॒म्भः । भार॑त्यै परिवा॒पः । मि॒त्रावरु॑णयोः पय॒स्याऽथ॑ । कस्मा॑दे॒तेषाँ॑ ह॒विषा॒मिन्द्र॑मे॒व य॑ज॒न्तीति॑ ।

> ब्रह्मवादि᳓नो वदन्ति ॥
> क᳓ति पा᳓त्राणि यज्ञं᳓ वहन्ति_इ᳓ति ॥

Reference numbers like `१। ५। ११। २॥ ५६` are not sentence segments. They stay attached to the following text and do not create a split.

**5. Same sequential action:** If one segment states a prior action and the next segment states the action that completes it, keep them together. Typically the first segment ends in an absolutive, such as `-tvA` or `-ya`, and is syntactically incomplete without the main verb in the next segment.

Example:

> स तप॑स्त॒प्त्वा । (33)
> अन्नं॒ ब्रह्मेति॒ व्य॑जानात् ।

`taptvA` alone does not complete the sense. It must stay with `vyajAnAt`.

**Combination rule:** Merging is transitive. If segment A merges with B, and B merges with C, then A, B, and C form one block, even if A and C were merged under different tests. If none of the tests above applies at a boundary, split there.

**In doubtful cases:** Keep together. A split that breaks sense is worse than a slightly longer block.
</details>
