---
layout: about
title: About
permalink: /
subtitle: Master's Student (BS-MS) in Materials Science · <a href='https://iisc.ac.in' target='_blank'>Indian Institute of Science (IISc), Bangalore</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: "FTFEML Lab, CeNSE<br>Indian Institute of Science<br>Bengaluru, Karnataka 560012, India"

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---


Hey! I'm Khushal, a BS-MS student in Materials Science at the **Indian Institute of Science (IISc), Bangalore**, currently working in the **FTFEML Lab** at the **Centre for Nanoscience and Engineering (CeNSE)** under the supervision of **Prof. Pavan Nukala**.

I’m broadly interested in leveraging in-situ and operando electron microscopy to study structure-property relationships at the nanoscale. Over my four or so years at IISc, I have had the privilege of exploring this fascinating field of materials science and had the opportunity to work on a few interesting projects and honing my skills along the way. I am actively trying to learn and understand how nanoscale dynamics in materials define our world and push the frontiers of science and technology. In my free time, I like to play chess and badminton, go running, and also catch up on reading books. Making this website started as a little side project to make a personal corner for me on the internet, and I shall work on it and bring some interesting additions in the future as well.

I am actively seeking **PhD positions in In-situ Transmission Electron Microscopy & Advanced Materials Characterisation**.

---

### Research Experience

- **Investigating *in-situ* heat-assisted phase transitions in $\text{In}_2\text{Se}_3$ using TEM**  
  *Master’s Thesis · Advisor: Prof. Pavan Nukala (CeNSE, IISc)*  
  - Project commenced in June 2026 and is presently ongoing.

- **Opto-Thermal Studies on $\text{VO}_2$ Microwires Using *In-Situ* Raman & TEM**  
  *Bachelor’s Thesis · Advisor: Prof. Pavan Nukala (CeNSE, IISc)*  
  - Investigating metal-insulator transition (MIT) temperature modulation via controlled nano-indentation (Park AFM NX20).
  - Executing *in-situ* opto-thermal experiments with Raman spectroscopy as both probe and stimulus across laser power densities.
  - Characterizing nanoscale domain evolution during MIT using TEM to resolve monoclinic–rutile structural transitions.

- **Electro-Thermo-Mechanical Behaviour of Tin**  
  *Research Project · Advisor: Prof. Praveen Kumar (Dept. of Materials Engineering, IISc)*  
  - Performed EBSD orientation mapping to analyze texture evolution and grain boundary character distribution.
  - Conducted complementary SEM, EDS, and WDS microstructural analyses on ThermoFisher Helios G4-UX & Apreo 2S.

- **Texture Analysis of Electrical Steels**  
  *Summer Research Intern · Advisor: Prof. S. Karthikeyan · Garrett Motion*  
  - Analyzed crystallographic texture, orientation distribution functions (ODF), and grain boundary engineering for Goss texture optimization.

---

### Technical Skills & Instrumentation

- **Electron Microscopy:** TEM / STEM (ThermoFisher Titan Themis, Tecnai T20-ST), SEM (Apreo 2S, Helios G4-UX FIB-SEM), EBSD, EDS, WDS, AFM (Park NX20).
- **Spectroscopy & Diffraction:** In-situ Raman Spectroscopy (Horiba LabRAM HR), X-Ray Diffraction (Rigaku XRD).
- **Simulation & Analysis:** HyperSpy, abTEM, py4DSTEM, COMSOL Multiphysics, CrystalMaker, CrystalDiffract, DigitalMicrograph, ImageJ/Fiji, OriginPro, LMFIT.
- **Programming:** Python (SciPy, NumPy, Matplotlib, Pandas, scikit-image), C, Java, LaTeX / Typst.

---

### Honors & Teaching
- **KVPY-SA Fellow (2020–21):** All India Rank **297** (awarded by DST, Govt. of India).
- **Teaching Assistant:** *Materials Design: Electronic, Electromechanical & Optical Functions (NE 240)*, IISc.
- **IELTS:** Band **8.0** (Fluent).

---

### 📂 Quick Links
- Explore my [Research Projects](/projects/)
- View & Download my [Curriculum Vitae]({{ '/cv/' | relative_url }})

<script>
document.addEventListener("DOMContentLoaded", function() {
  let attempts = 0;
  const filterSearch = setInterval(function() {
    const ninjaKeys = document.querySelector('ninja-keys');
    if (ninjaKeys && ninjaKeys.data && ninjaKeys.data.length > 0) {
      ninjaKeys.data = ninjaKeys.data.filter(item => item.section !== 'Books' && item.section !== 'News');
      clearInterval(filterSearch);
    }
    attempts++;
    if (attempts > 20) clearInterval(filterSearch);
  }, 100);
});
</script>
