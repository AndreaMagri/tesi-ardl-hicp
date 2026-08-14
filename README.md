# L’impatto degli shock delle catene globali di fornitura sull’inflazione nell’Eurozona: Un’applicazione del modello ARDL-UECM
## The Macroeconomic Effects of Global Supply Chain Shocks on Euro Area Inflation: An ARDL-UECM Approach

Tesi di Laurea Triennale in **Economia e Finanza**  
**Alma Mater Studiorum - Università di Bologna** (Dipartimento di Scienze Economiche - DSE)  
Anno Accademico 2025/2026.

*   **Author**: Andrea Magri
*   **Supervisor**: [Nome Relatore]
*   **Contact**: [Tua Email Istituzionale o link LinkedIn]

---

## 🚀 Run the Analysis in One Click

You can explore the entire econometric code and run the dynamic simulations interactively directly on Google Colab without installing any local libraries:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tuo-username/nome-repo/blob/main/tesi_analisi.ipynb)

---

## 📝 Project Description

This research analyzes the short- and long-run pass-through (propagation mechanism) of global supply chain shocks (measured by the New York Fed's *Global Supply Chain Pressure Index* - GSCPI) to Euro area consumer prices (seasonally adjusted HICP) over the monthly period 1999-2026 [2].

From an econometric perspective, we adopt a dynamic **Autoregressive Distributed Lag (ARDL)** model reparameterized in its **Unrestricted Error Correction (UECM)** form [1]. This framework allows us to isolate the supply-side logistics transmission while controlling for global energy costs (Brent crude oil) and the nominal exchange rate channel (EUR/USD) in a single-equation setup [2].

---

## 📈 Key Empirical Findings

The dynamic simulation of the UECM model under a temporary 1-standard-deviation GSCPI shock reveals that:
*   Euro area consumer prices (HICP) undergo a maximum cumulative increase between **0.33%** and **0.42%** (depending on the chosen autoregressive persistence parameter, $\rho$) [2].
*   The transmission is remarkably slow and exhibits strong nominal price rigidities (*price stickiness*), with the peak cumulative effect occurring with a delay between the **19th and 23rd months** after the initial shock [2]. 
*   These results show a strong empirical alignment with the structural VAR (SVAR) findings in the reference literature (Finck and Tillmann, 2023), proving that our single-equation *ceteris paribus* estimates capture the direct cost-push pass-through of global trade bottlenecks [2].

### Figure: Cumulative HICP Response
*(The figures below are generated directly by the code contained in the notebook)*

![Risposta Cumulata HICP](hicp_cumulata_concl.png)

---

## 📂 Repository Structure

The repository is organized as follows:
*   `tesi_analisi.ipynb`: The complete and commented Jupyter Notebook containing the entire estimation pipeline (from raw data download through APIs to econometric tests and dynamic simulations).
*   `gscpi_data_all.csv`: The dataset containing the monthly historical series of the New York Fed's GSCPI used to replicate the results.
*   `images/`: Folder containing the generated high-resolution (300 DPI) plots used for compiling the LaTeX thesis [2].

---

## 📚 Key References

*   Finck, D., & Tillmann, P. (2023). *The macroeconomic effects of global supply chain disruptions*. BOFIT Discussion Papers.
*   Pesaran, M. H., Shin, Y., & Smith, R. J. (2001). *Bounds testing approaches to the analysis of level relationships*. Journal of Applied Econometrics.
*   Carrière-Swallow, Y., Deb, P., Furceri, D., Jimenez, D., & Ostry, J. D. (2023). *Shipping costs and inflation*. Journal of International Money and Finance.
