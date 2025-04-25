# Skin_Disorder_Prediction
Skin_Disorder_Prediction is a machine learning project that classifies six types of skin diseases using clinical and histopathological features. It aids dermatologists in accurate, early diagnosis and reduces the need for invasive procedures.


### Create a predictive model using machine learning techniques to predict the various classes of skin disease
---
## Dataset Information:

This database contains 34 attributes, 33 of which are linear valued and one of them i 
nominal.The differential diagnosis of erythemato-squamo s diseases is a real probl m
in dermatology. They all share the clinical features of erythema and scaling, with v ry
little differences. The disease  in this group are psoriasis, seboreic dermatitis, li hen
planus, pityriasis rosea, cronic dermatitis, and pityriasis rubra pilaris. Usually a biop y is
necessary for the diagnosis but unfortunately these diseases shar  many
histopathological features as well. Another difficulty for the diffe ential diagnosis is that a
disease may show the features of another disease at the beginning stage and  ay have
the characteristic features at the  ollowing stages. Patients were first evaluated c inically
with 12 features. Afterwards, skin samples were taken for the evalua ion of 22
histop thological features. The values of the histopathological features are determined
by an analysis of the samples under a microscope.In the dataset con truc ed for this
domain, the family history feature has the value 1 if any of these dise ses has been
observed in the family, and 0 otherwise. T e age feature simply represe ts the age of
the patient. Every other feature (clinical and histopathological) was gi en a degree in
the range of 0 to 3. Here, 0 indicates that the feature was not present, 3 indicates the
largest amount possible, and 1, 2 indicate the relative intermediate val es.The names
and id numbers of the patients were recently removed from the database.

---
### **1. erythema**  
Redness of the skin caused by the dilation of blood vessels.  
**Significance:** Indicative of inflammation or a skin disorder.

---

### **2. scaling**  
Flaking or shedding of the outer layer of skin.  
**Significance:** Common in conditions like psoriasis and eczema.

---

### **3. definite_borders**  
Clear demarcation between diseased and healthy skin areas.  
**Significance:** Helps identify the specific area affected by the condition.

---

### **4. itching**  
An uncomfortable sensation in the skin that causes the urge to scratch.  
**Significance:** A common symptom in skin conditions like eczema, psoriasis, and fungal infections.

---

### **5. koebner_phenomenon**  
The appearance of new lesions at the site of skin injury or trauma.  
**Significance:** Seen in diseases like psoriasis and lichen planus.

---

### **6. polygonal_papules**  
Small, polygon-shaped raised lesions on the skin.  
**Significance:** Characteristic of lichen planus.

---

### **7. follicular_papules**  
Small bumps occurring around hair follicles.  
**Significance:** Common in conditions like folliculitis or keratosis pilaris.

---

### **8. oral_mucosal_involvement**  
Presence of lesions in the mucous membranes inside the mouth.  
**Significance:** Seen in lichen planus and other systemic conditions.

---

### **9. knee_and_elbow_involvement**  
Lesions affecting the knees and elbows.  
**Significance:** Typical in psoriasis.

---

### **10. scalp_involvement**  
Lesions or symptoms present on the scalp.  
**Significance:** Affected in conditions like psoriasis or seborrheic dermatitis.

---

### **11. family_history**  
History of similar skin conditions in the patient’s family.  
**Significance:** Indicates genetic predisposition to diseases.

---

### **12. melanin_incontinence**  
Accumulation of melanin in the dermis due to damage to the epidermis.  
**Significance:** Common in lichen planus and other pigmentary disorders.

---

### **13. eosinophils_in_the_infiltrate**  
Presence of eosinophils (a type of immune cell) in the skin tissue.  
**Significance:** Indicates allergic or inflammatory conditions.

---

### **14. PNL_infiltrate**  
Accumulation of polymorphonuclear leukocytes (PNL) in the tissue.  
**Significance:** Indicates bacterial or fungal infections.

---

### **15. fibrosis_of_the_papillary_dermis**  
Thickening of the upper dermal layer due to fibrosis.  
**Significance:** Observed in chronic conditions or scarring.

---

### **16. exocytosis**  
Migration of inflammatory cells into the epidermis.  
**Significance:** Indicates inflammatory skin conditions.

---

### **17. acanthosis**  
Thickening of the epidermis.  
**Significance:** Seen in psoriasis and other hyperproliferative disorders.

---

### **18. hyperkeratosis**  
Thickening of the outermost layer of skin (stratum corneum).  
**Significance:** Found in conditions like psoriasis and keratoderma.

---

### **19. parakeratosis**  
Retention of nuclei in the stratum corneum.  
**Significance:** A hallmark of psoriasis.

---

### **20. clubbing_of_the_rete_ridges**  
Changes in the structure of the epidermal ridges, giving them a "clubbed" appearance.  
**Significance:** Indicative of pathological changes in the skin.

---

### **21. elongation_of_the_rete_ridges**  
Increased length of the epidermal ridges.  
**Significance:** Seen in psoriasis and some other skin disorders.

---

### **22. thinning_of_the_suprapapillary_epidermis**  
Thinning of the epidermal layer above the dermal papillae.  
**Significance:** A diagnostic feature of psoriasis.

---

### **23. spongiform_pustule**  
Pustules formed due to the accumulation of neutrophils in the epidermis.  
**Significance:** Common in pustular psoriasis.

---

### **24. munro_microabcess**  
Small collections of neutrophils within the epidermis.  
**Significance:** Specific to psoriasis.

---

### **25. focal_hypergranulosis**  
Localized thickening of the granular layer of the epidermis.  
**Significance:** Seen in lichen planus.

---

### **26. disappearance_of_the_granular_layer**  
Absence of the granular layer in the epidermis.  
**Significance:** A key feature of psoriasis.

---

### **27. vacuolisation_and_damage_of_basal_layer**  
Damage or vacuole formation in the basal layer of the epidermis.  
**Significance:** Typical in lichen planus.

---

### **28. spongiosis**  
Interstitial edema in the epidermis, leading to separation of keratinocytes.  
**Significance:** Seen in eczema and dermatitis.

---

### **29. saw-tooth_appearance_of_retes**  
Saw-like pattern of the epidermal ridges.  
**Significance:** Specific to lichen planus.

---

### **30. follicular_horn_plug**  
Keratin plugs within hair follicles.  
**Significance:** Common in follicular keratosis.

---

### **31. perifollicular_parakeratosis**  
Parakeratosis surrounding hair follicles.  
**Significance:** Seen in chronic follicular disorders.

---

### **32. inflammatory_monoluclear_inflitrate**  
Accumulation of mononuclear inflammatory cells in the skin tissue.  
**Significance:** Found in chronic inflammatory diseases.

---

### **33. band-like_infiltrate**  
Dense band of inflammatory cells in the upper dermis.  
**Significance:** Specific to lichen planus.

---

### **34. Age**  
The age of the patient.  
**Significance:** Helps correlate the disease with its typical onset age.

---

### **35. Class**
The classification of the disease:  
- **1:** Psoriasis 
- **2:** Seboreic Dermatitis  
- **3:** Lichen Planus 
- **4:** Pityriasis Rosea
- **5:** Chronic Dermatitis
- **6:** Pityriasis Rubra Pilaris

---
