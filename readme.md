# Spotify Genre Paradox — Data Analysis

A concise data analysis exploring whether Spotify’s categorical mood labels (**Happy** vs. **Sad**) actually align with measurable audio features such as **Energy**, **Valence**, and **Loudness**.

---

## Project Question

**Do Spotify’s “Happy” and “Sad” genre labels reflect meaningful differences in audio characteristics, or are they misleading simplifications?**

This project approaches the question from a data-driven perspective rather than subjective listening.

---

## Dataset

The dataset consists of Spotify tracks with extracted audio features, including:

- `energy` – perceived intensity and activity  
- `valence` – musical positiveness  
- `loudness` – overall track loudness (dB)  
- `genre_label` – Spotify mood classification (Happy / Sad)

Tracks were cleaned, filtered, and analysed using Python.

---

## Methodology

1. **Data Cleaning**
   - Removed missing and duplicate entries  
   - Normalised feature ranges where required  

2. **Exploratory Analysis**
   - Compared distributions of energy, valence, and loudness  
   - Visualised overlap between Happy and Sad tracks  

3. **Comparative Evaluation**
   - Tested whether label differences reflect statistically meaningful variation  
   - Focused on *patterns*, not individual songs  

---

## Key Findings

- **“Happy” tracks are not always high-energy**  
  Many fall into mid-energy ranges rather than peak intensity.

- **“Sad” tracks skew quieter and slower**, but are not necessarily emotionally depressing  
  The label largely captures *low physical intensity*, not emotional distress.

- **Valence is the strongest differentiator**, but overlap remains significant  

**Takeaway:**  
Spotify’s mood labels are **broad heuristics**, not precise emotional classifiers. Filtering directly by audio features (e.g. very low valence) produces more accurate mood-based playlists than relying on genre tags alone.

---

## Visualisations

The project includes plots comparing:

- Energy distributions (Happy vs. Sad)
- Valence overlap across genres
- Loudness differences and density

These highlight where Spotify’s labels align — and where they blur.

---

## Tech Stack

- Python  
- Pandas  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
