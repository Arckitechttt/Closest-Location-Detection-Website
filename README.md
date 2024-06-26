# Closest Location Detection Website
Developed a website (for demonstration purposes only) capable of identifying the closest (nearest) branch of an **X Company** (the company doesn't intend its name to be displayed here) based on a specific inputted location.

<h3><b>Requirements</b></h3>

1. Sends the inputted location data to the database of the closest (nearest) "Company's Branch".
2. The available database capacity of the closest (nearest) "Company's Branch" must be less than 35 entries to receive the inputted location data.
3. The website must be developed using HTML, CSS, and JavaScript only.

<h3><b>Methods</b></h3>

1. **Haversine Formula** method was used to calculate distances between all of the company's branches to a specific inputted location on the HTML form.
2. The website was developed using HTML, CSS, and JavaScript.

<br>
<p align="center">
  <img src="https://github.com/Arckitechttt/Closest-Location-Detection-Website/assets/73390184/7d31239a-a3b6-4264-941d-5e49b7141d41?raw=true" alt="Haversine Formula"/>
</p>
<p align="center">
  <b>Haversine Formula</b> (Source: Dauni et al., 2019)
</p>
<br>

---

<h3><b>Further Informations</b></h3>

To ensure the company's privacy, the previously mentioned "Company's Branches" is denoted by the following list of locations in this website : (assume the list of locations below represents the branches of the company)
1. National Museum of Indonesia -- -6.176363051631948, 106.82153088532345
2. Central Jakarta Mayor Office -- -6.173024407925739, 106.81903106649357
3. Juanda Station -- -6.166533478050184, 106.83047021360103
4. Gedung Pertunjukan Wayang Orang Bharata -- -6.172181694425004, 106.84094195302518

For instance, if you input the location data for the **National Monument** on the HTML form in the website, with a **Latitude** coordinate of **-6.175215683888003** and a **Longitude** coordinate of **106.82712974688135**, the website will identify the closest location as the **National Museum of Indonesia**, located approximately **0.62 kilometers** away by the Haversine Formula method.

Moreover, feel free to input location data situated near the listed "Company's Branches" locations mentioned above.

---

<h3><b>Reference</b></h3>

1. P. Dauni, M. D. Firdaus, R. Asfariani, M. I. N. Saputra, A. A. Hidayat, and W. B. Zulfikar, “Implementation of Haversine formula for school location tracking,” Journal of Physics: Conference Series, vol. 1402, no. 7, p. 077028, Dec. 2019, doi: https://doi.org/10.1088/1742-6596/1402/7/077028.
