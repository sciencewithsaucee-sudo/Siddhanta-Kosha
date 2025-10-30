# 📜 Siddhanta Kosha: An Encyclopedia of Ayurvedic Principles  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17481343.svg)](https://doi.org/10.5281/zenodo.17481343)

This repository contains the **Siddhanta Kosha**, a curated, open-source JSON dataset of **162 core foundational principles of Ayurveda**.

This project is designed to be a foundational tool for **BAMS students, researchers, clinicians, and developers** who are building digital tools for Ayurveda. The data has been compiled and verified from authoritative Ayurvedic texts, including the *Charaka Samhita*, *Sushruta Samhita*, and *Ashtanga Hridaya*.

This dataset is the underlying data for the interactive **Siddhanta Kosha** on [Amidha Ayurveda](https://www.amidhaayurveda.com).

---

## 🌟 Key Features

This dataset provides a comprehensive, structured entry for each of the 162 principles.  
Each JSON object contains the following key fields:

- **name:** The name of the principle in Devanagari and IAST (e.g., *Prakopa Karana (प्रकोप कारण)*)
- **category:** The branch of Ayurveda it belongs to (e.g., *Roga Nidana*)
- **shloka:** The original Sanskrit verse (shloka)
- **shloka_ref:** The classical reference for the verse
- **explanation:** A detailed explanation of the concept
- **clinical_importance:** The practical application and clinical relevance of the principle

---

## 💾 Data Structure Example

```json
[
  {
    "name": "Prakopa Karana (प्रकोप कारण)",
    "category": "Roga Nidana",
    "shloka": "हेतु-लिङ्ग-औषध ज्ञानं स्वस्थातुरपरायणम्।",
    "shloka_ref": "(Charaka Samhita, Sutrasthana 1/24 - context)",
    "explanation": "Prakopa Karana are the factors that cause the aggravation or vitiation of the doshas, moving them from a state of accumulation (Sanchaya) to a state of overflow (Prakopa). These are specific dietary, lifestyle, or environmental factors that share the same qualities as a particular dosha. For example, consuming excessive dry, cold, and light food will cause Vata to aggravate.",
    "clinical_importance": "Identifying the specific Prakopa Karana is essential for understanding the immediate cause of a disease flare-up. Advising the patient to avoid these factors is a critical part of both treatment and prevention."
  }
]
```

---

## 🚀 How to Use

You can clone this repository or download the `siddhanta-kosha.json` file.  
The file contains a single JSON array of 162 principle objects.  
This data can be easily imported into any application, database (like MongoDB), or script (Python, JavaScript) for analysis, search, or to power a user interface.

**Example:**

```js
fetch('siddhanta-kosha.json')
  .then(res => res.json())
  .then(data => console.log(data[0].name));
```

---

## 📖 How to Cite

If you use this dataset in your research, software, or publication, please cite it:

> Varshney, Sparsh. (2025). *Siddhanta Kosha: A Curated JSON Dataset of 162 Core Ayurvedic Principles* (Version 1.0.0) [Data set]. Zenodo.  
> https://doi.org/10.5281/zenodo.17481343

---

## 📚 Related Projects

- 🌿 **Amidha Ayurveda Herb Database** – A JSON dataset of 700+ Ayurvedic herbs  
  🔗 [https://www.amidhaayurveda.com/p/herb-database.html](https://www.amidhaayurveda.com/p/herb-database.html)  
  DOI: [https://doi.org/10.5281/zenodo.17475352](https://doi.org/10.5281/zenodo.17475352)

- 🪷 **Amidha Ayurveda Roga Nidana Kosha** – A JSON dataset of 200+ Ayurvedic diseases  
  🔗 [https://www.amidhaayurveda.com/p/roga-nidana-kosha.html](https://www.amidhaayurveda.com/p/roga-nidana-kosha.html)

---

## 👨‍💻 About the Author

**Sparsh Varshney**  
Founder — [Amidha Ayurveda](https://www.amidhaayurveda.com)

BAMS student passionate about digitizing Ayurvedic knowledge and making it accessible through structured, open-source datasets.

- LinkedIn: [linkedin.com/in/sparshvarshney](https://linkedin.com/in/sparshvarshney)  
- About Page: [https://www.amidhaayurveda.com/p/about.html](https://www.amidhaayurveda.com/p/about.html)

---

## 📄 License

This dataset is made available under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
You are free to share and adapt this work for any purpose, even commercially, as long as you give appropriate credit.

---

**🔗 Project:** [https://www.amidhaayurveda.com](https://www.amidhaayurveda.com)  
**📘 Repository:** *Siddhanta Kosha — An Encyclopedia of Ayurvedic Principles*
