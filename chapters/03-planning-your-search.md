---
title: "Chapter 3: Planning Your Search"
nav_order: 3
---

# Stage 2: Planning Your Search

---

## 2.1.1 Identify Record Sources

- A systematic review represents an *attempt* to identify *all* relevant research. Ideally, it should therefore be exhaustive.
  - You will need to identify all relevant **published and unpublished** records
  - Key here is narrowing down the relevant studies from your research question
    - Locations will vary depending on the intervention/phenomenon being investigated, and the types of organisations/groups undertaking or commissioning the research
    - Some examples to get you started:
      - *Pharmacological clinical trials* → Medical journals
      - *Government evaluations* → Government libraries; government research repositories; consultant websites
      - *Validation studies of risk assessment tools* → Creator's/parent companies' websites

> See Lefebvre et al.'s (2019) *Recommended and Essential Sources* for more detailed guidance.

- Plan to reach the **saturation point** — i.e., the point towards the end of your search where the relevant research you are identifying has already been identified earlier
  - E.g., if you extract all of the included records from a similar systematic review, are they all duplicates of records you have identified previously?

> <span style="background-color: #fff3cd; padding: 2px 5px; border-radius: 3px;">💡 **Pro-tip:** Create a list of studies you are reasonably certain will qualify for the review (add to it along the way as necessary). You should, in some sense, have some studies in mind before you start — you need to have some understanding of the literature to be confident a systematic review is justified. This list will come in handy later for: cross-checking your searches are getting the right results during pilot searches (see section 2.2.3), and searching their reference lists for relevant studies (see section 3.2).</span>

---

## 2.1.2 Consultation with a Librarian

- **Book an appointment with a librarian to discuss your search** — request an appointment through your library for a meeting with a librarian who has strong knowledge of the databases/repositories you can access
- They will be able to advise on the databases available at your institution that are relevant to your search, as well as those that are irrelevant (greatly saving you time later)
- It is worth mentioning your research question, PICO, and the purpose of your appointment when scheduling, so that:
  1. You may be assigned a librarian with stronger knowledge of the relevant area of the literature
  2. The librarian has an opportunity to prepare for the meeting

> <span style="background-color: #ffe0e0; padding: 2px 5px; border-radius: 3px;">⚠️ **Critical step:** Informed decisions on databases will ensure you are capturing the right records whilst not wasting your time on irrelevance.</span>

> <span style="background-color: #fff3cd; padding: 2px 5px; border-radius: 3px;">📝 **Note:** Your registered review protocol (Item 2.3) and any resulting publication should note that a librarian was consulted within the search/database search design.</span>

---

## 2.1.3 Consultation with Topic Experts

- Speak with senior researchers/industry figures on where to find relevant research
  - In many cases, senior researchers from your department or school will have already assisted in this respect (e.g., thesis supervisors/advisors/co-authors), but you should meet to discuss it if not
  - Prominent researchers in the field/on the topic of interest are also worth contacting
    - In some cases they will have suggestions on where to find unpublished works
    - In some cases they might send you manuscripts in preparation that would qualify for your review
  - Questions to ask:
    - Are there any places you should be searching?
    - Are they aware of any studies that would qualify off the top of their head?
      - Particularly older studies
    - Do they know of any other authors worth speaking with?

---

## 2.2.1 Develop Search Terms

- **Key words**
  - Brainstorm all the relevant words to your PICO/PICOT/SPIDER
    - Note different spellings and possible grammatical variations (becomes important in section 2.2.2)
      - E.g., *near lethal* and *near-lethal*
    - Regional differences in spelling or concept
      - E.g., *misdemeanour* vs *summary offence*
    - Different names that depend on the area of literature
      - E.g., *family violence* vs *domestic violence*
- **Subject heading terms** — look for MeSH vocabulary (US National Library of Medicine's Medical Subject Heading vocabulary; Aoki et al., 2013)
- **Keywords listed by authors** (e.g., those listed on the title page of a journal article)

---

## 2.2.2 Develop Syntax

- **General**
  - Most databases use different search syntax but generally follow the same principles
  - > <span style="background-color: #ffe0e0; padding: 2px 5px; border-radius: 3px;">⚠️ **Critical tip:** Each database will have directions for using search terms and syntax — check these before searching.</span>

- **Boolean operators**

  - **AND** — connects two or more terms, concepts, or variables
    - E.g.:
      - `(methadone maintenance) AND (recidivism)`
      - `family violence AND desistance`

  - **OR** — used where you have interchangeable terms
    - E.g.:
      - `Pharmacological OR medication`
      - `Reoffending OR recidivism OR re-perpetration`

  - **NOT** — used when you want a term excluded from the results
    - E.g.:
      - `NOT "systematic review"` — would exclude systematic reviews from your results

- **Other operators**

  - *Near field* — used to identify records containing words within a certain proximity of each other
    - Often written as **N#** (e.g., **N3**, **N4**, **N10**)
    - E.g., `"predicting" N6 "homicide"` would capture the title: *Predicting intimate partner violence reassault and homicide*

  - *Wildcard operators* — allow you to search for variations in a term or phrase
    - Often expressed as **\*** or **?**
    - E.g., `near*lethal` captures both *near lethal* and *near-lethal*
    - > <span style="background-color: #ffe0e0; padding: 2px 5px; border-radius: 3px;">⚠️ **Critical tip:** On the HeinOnline platform, you currently <u>cannot</u> use wildcard operators within quotation marks — e.g., `"pre*to*post"` will not find additional results on HeinOnline.</span>

- **Field codes**
  - There are additional field codes worth considering — see [Bramer et al. (2018)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6148622/) (Table 1) for more examples and tips on developing syntax
  - Note there are field codes to search the title, abstract, and full text — the exact syntax will vary from database to database

- **Syntax structure**
  - Your search syntax should identify all relevant records while ignoring irrelevant ones
  - The most effective way is to use Boolean operators and field codes to accurately search for records meeting your PICO/PICOT/SPIDER, e.g.:
    - *Population:* `("youth") OR ("young people") OR (individuals N3 under 18) OR (juveniles)`
    - *Intervention:* `((drug* OR alcohol) AND abuse) AND (treatment OR therapy OR service)`
    - *Comparison:* `((comparison group) OR (controls) OR (comparators))`
    - *Outcome:* `(drug use) OR (abstinence) OR (reduction N3 alcohol consumption)`
  - **Combined syntax:**
    ```
    (("youth") OR ("young people") OR (individuals N3 under 18) OR (juveniles))
    AND (((drug* OR alcohol) AND abuse) AND (treatment OR therapy OR service))
    AND ((comparison group) OR (controls) OR (comparators))
    AND ((drug use) OR (abstinence) OR (reduction N3 alcohol consumption))
    ```
  - It can take a few attempts to get the syntax into a good state (hence the next step)
  - See the sample materials for syntax examples (`2.2.2 Develop Syntax.xlsx`)

---

## 2.2.3 Execute Pilot Searches

- Practise searching in a few databases
  - Use different search terms/combinations/phrases/operators
  - Browse the results and consider:
    - Is it all relevant? Can you see straight away why the identified records are turning up?
      - Are your keywords catching other irrelevant concepts or topic areas?
      - How can you modify your syntax to be more precise using the operators in section 2.2.2?
- Practise extracting the results
  - Once you're more confident in the search, try extracting all results into EndNote into a 'Test' library

> <span style="background-color: #fff3cd; padding: 2px 5px; border-radius: 3px;">💡 **Pro-tip:** Search these records for the studies you shortlisted in section 2.1.1.</span>

---

## 2.3 Registration and Guidelines

- **Registering your review**
  - You need to create and register your review protocol **before** you start searching
  - More information on defining your protocol can be found in Higgins & Green (2008, p. 13)
  - Register via [PROSPERO](https://www.crd.york.ac.uk/prospero/)
  - This step also forces you to record a sizeable portion of what you plan to do — it should act as the blueprint for your review
    - Be as specific as possible, and follow it as closely as possible

- **Following reporting guidelines**
  - It is recommended you follow the PRISMA guidelines for reporting systematic reviews ([Page et al. 2020](https://www.bmj.com/content/372/bmj.n71))
  - The best way to do this is to keep it in mind and use it as a reference guide throughout the review process
