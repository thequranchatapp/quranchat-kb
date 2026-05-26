# QuranChat Knowledge Base

Open knowledge base for QuranChat — contribute Islamic texts and tafsir to power a smarter Quran AI chatbot.

## About

This repository serves as the central data source and knowledge base for QuranChat. By aggregating high-quality, verified Islamic texts, we aim to improve the capabilities and accuracy of our AI chatbot.

## Repository Structure

To keep the repository clean and structured, we organize texts into two main folders:
- `/translations/`: Quranic translations categorized by translator/author.
- `/tafsir/`: Qur'anic commentaries (exegesis) categorized by book/author.

---

### First Representative Examples (Hanafi School)

We have added the first highly requested, authoritative examples following the Hanafi school of thought to serve as a guide for contributors:

1. **Translation:** **"The Meanings of the Noble Qur'an"** by **Mufti Muhammad Taqi Usmani**
   - *Example:* [Surah Al-Fatihah Translation](translations/mufti-taqi-usmani/001_al_fatihah.md)
2. **Tafsir (Exegesis):** **"Ma'ariful Qur'an"** by **Mufti Muhammad Shafi Usmani** (former Grand Mufti of Pakistan)
   - *Example:* [Surah Al-Fatihah Tafsir](tafsir/maariful-quran/001_al_fatihah.md)

---

## Datasets & Download Sources

To download the full datasets to populate this repository, utilize the following open-source resources and digital archives:

### 1. Mufti Taqi Usmani Translation Dataset
- **Format:** Machine-readable JSON / Minified JSON
- **GitHub Repository:** [fawazahmed0/quran-api](https://github.com/fawazahmed0/quran-api)
- **Direct Download Links:**
  - [Full JSON (eng-muftitaqiusmani.json)](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions/eng-muftitaqiusmani.json)
  - [Minified JSON (eng-muftitaqiusmani.min.json)](https://cdn.jsdelivr.net/gh/fawazahmed0/quran-api@1/editions/eng-muftitaqiusmani.min.json)

### 2. Ma'ariful Qur'an Tafsir Text & Scans
- **Format:** Digital searchable text / PDF
- **Searchable Web Interface:** [IslamicStudies.info — Tafseer Ma'ariful Qur'an](http://www.islamicstudies.info/tafseer/maharif.yahoo.php)
- **Full 8-Volume PDF Downloads:**
  - [Internet Archive - Maariful Quran English 8 Volumes](https://archive.org/details/MaarifulQuranEnglsih8Volumes)
  - [Internet Archive - Maariful Quran English Collection](https://archive.org/details/MaarifulQuranEnglishByMuftiShafiSb)

---

## Contributing

We strictly accept contributions limited to the following categories:
- Quranic texts and translations
- Tafsir (exegesis)

### Submission Guidelines

1. **File Format:** Please submit all texts strictly in clean `.md` (Markdown) format.
2. **Authenticity & Sourcing:** Clearly cite the original author, source, and publisher of the text to ensure verification.
3. **Directory Structure:** Place files in the appropriate folder (`/translations/` or `/tafsir/`).
4. **How to Contribute:**
   - Fork the repository.
   - Create a feature branch (e.g., `add-yusuf-ali-translation`).
   - Commit your changes and push to your fork.
   - Open a Pull Request with a clear description of the text you are adding and why.
5. **Validation:** All pull requests will be manually reviewed for authenticity and structural integrity before being merged.
6. **Licensing & Copyright Compliance:** To ensure the long-term sustainability and open accessibility of this repository, we prioritize texts that are authentic and free of restrictive copyrights (e.g., in the public domain, under open-source/permissive licensing, or cleared for open distribution). Please avoid submitting proprietary or restricted materials.