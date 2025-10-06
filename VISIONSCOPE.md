# Sýn og Afmörkun 

## Númer teymis og höfundar
[Setjið inn númer teymis og fullt nafn höfunda verkefnis]

## Heiti kerfis
[Setjið inn nafn kerfis]


## Efnisyfirlit 
- [Breytingasaga](#revision-history)
- [1. Viðskiptakröfur](#1-business-requirements)
    - [1.1 Bakgrunnur](#11-background)
    - [1.2 Viðskiptatækifæri](#12-business-opportunity)
    - [1.3 Viðskiptamarkmið](#13-business-objectives)
    - [1.4 Árangursmælikvarðar ](#14-success-metrics)
    - [1.5 Sýn](#15-vision-statement)
    - [1.6 Viðskiptaáhætta](#16-business-risks)
    - [1.7 Viðskiptaforsendur og háðleiki](#17-business-assumptions-and-dependencies)
- [2. Umfang og takmarkanir](#2-scope-and-limitations)
    - [2.1 Helstu fídusar](#21-major-features)
    - [2.2 Umfang fyrstu útgáfu](#22-scope-of-initial-and-subsequent-releases)
    - [2.3 Takmarkanir og útilokanir](#23-limitations-and-exclusions)
- [3. Samhengi viðskipta](#3-business-context)
    - [3.1 Prófílar hagsmunaaðila](#31-stakeholder-profiles)
    - [3.2 Forgangsröðun verkefnis](#32-project-priorities)
    - [3.3 Innleiðingarsjónarmið](#33-deployment-considerations)

---
> Hver kafli á að vera um það bil hálf síða að lengd.
> 
## 1. Viðskiptakröfur
### 1.1 Bakgrunnur


### 1.2 Viðskiptatækifæri


### 1.3 Viðskiptamarkmið
*(Skrifaðu þennan kafla)*

### 1.4 Árangurs mælikvarðar


### 1.5 Framtíðarsýn
*(Skrifaðu þennan kafla)*

[Write a concise vision statement that summarizes the purpose and intent of the new product and describes what the world will be like when it 
includes the product. The vision statement should reflect a balanced view that will satisfy the needs of diverse customers as well as those of 
the developing organization. It may be somewhat idealistic, but it should be grounded in the realities of existing or anticipated customer markets, 
enterprise architectures, organizational strategic directions, and cost and resource limitations ]
### 1.6 Viðskiptaáhætta


### 1.7 Viðskiptaforsendur og háðleiki


---

## 2. Umfang  og takmarkanir 
### 2.1 Helstu fídusar


### 2.2 Umfang fyrstu útgáfu

- FE-1: Streymi af beinni sjónvarpsútsendingu, og gömlum útsendingum er hægt að nálgast á auðveldann og skýran hátt.
- FE-2: Hægt er að nálgast dagskrá fyrir núverandi dag, liðna daga og komandi daga.
- FE-3: Sreymi fyrir efni sem sýnt hefur verið í beinni og annað myndefni er aðgengilegt í gegnum skýrt yfirlit.
- FE-4: Þjónusta aðgengileg á snjallsímum/spjaldtölvum, tölvum og sjónvörpum.
- FE-5: Texti á mörgum tungumálum fyrir myndefni.
- FE-6: Viðmót fyrir fyrirtæki þar sem hægt er að bæta við, breyta og eyða myndefni, dagskrám og textum.

### 2.3 Takmarkanir og útilokanir

| Fídus | 1. útgáfa | 2. útgáfa | 3. útgáfa |
| ----- | --------- | --------- | --------- |
| FE-1  | Streymi af beinni útsendingu útfært | Útfært frekar ef tími gefst | Útfært að fullu |
| FE-2  | Ekki útfært | Dagskrá fyrir daginn í dag útfærð| Útfært að fullu |
| FE-3  | Útfært fyrir annað efni | Útfært að fullu | Útfært að fullu | 
| FE-4  | Snjallsíma og vafraútgáfa útfærð - aðgengilegt öllum | Sér forrit fyrir sjónvörp útfært, útfært að fullu | Útfært að fullu |
| FE-5  | Ekki útfært | Útfært ef tími gefst | Útfært að fullu |
| FE-6  | Útfært fyrir myndefni | Útfært frekar ef tími gefst | Útfært að fullu |

---

## 3. Samhengi viðskipta
### 3.1 Prófílar forgangs hagsmunaaðila 
*(Skrifaðu þennan kafla )*

[ Stakeholders are individuals, groups, or organizations that are actively involved in a project, are affected by its outcome, or can influence its outcome. The stakeholder profiles identify the customers for this product and other stakeholders, and states their major interests in the product. Characterize business-level customers, target market segments, and different user classes, to reduce the likelihood of unexpected requirements surfacing later that cannot be accommodated because of schedule or scope constraints. For each stakeholder category, the profile includes the major value or benefits they will receive from the product, their likely attitudes toward the product, major features and characteristics of interest, and any known constraints that must be accommodated. Examples of stakeholder value include:

- improved productivity
- reduced rework 
- cost savings	
- streamlined business processes	
- automation of previously manual tasks	
- ability to perform entirely new tasks or functions	
- conformance to current standards or regulations	
- improved usability or reduced frustration level compared to current applications
]
Setjið gjarnan upp í töflu sbr námsefnið 


### 3.2 Forgangsröðun verkefnis 


### 3.3 Innleiðingarsjónarmið 


## Breytingasaga
<!--
Í stað þess að halda utan um alla commit-sögu er aðeins skráð formleg útgáfa (milestones) með Git tags (merkjum).  
Hver lína í töflunni samsvarar tag (merki) sem hefur verið sett í Git repositoryið.
> 🔖 Revision History er viðhaldið með **Git tags**.  
> Þegar ný útgáfa (t.d. drög eða baseline) er tilbúin, búið til tag í Git (`git tag -a vX.Y -m "message" && git push origin vX.Y`)  
> sem bætir einni línu við í töfluna hér að neðan.
-->
> 🔖 Taflan hér á eftir er búin til með því að keyra shell skrána `updatevisionhistory.sh` í bash terminal
> 
>  `chmod +x updatevisionhistory.sh`
> 
>  `./updatevisionhistory.sh`
> 
>  Ef þú vilt skoða töfluna fyrst til að sjá hvernig hún kemur út geturðu gert eftirfarandi beint úr skelinni 
> `git log -n 5 --pretty=format:"| %an | %ad | %s | %h |" --date=short -n 10 -- VISIONSCOPE.md`


<!-- GIT_HISTORY_START -->
| Author | Date       | Message | Commit |
|--------|------------|---------|--------|
| Ebba Þóra Hvannberg | 2025-09-08 | fyrsta útgáfa og Revision history gert sjálfvirkt | 5b39409 |

<!-- GIT_HISTORY_END -->

> Skoða allt: `git log -- "VISIONSCOPE.md" `
