<style>
@media (prefers-color-scheme: dark) {
  body {
    background-color: #1e1e1e;
    color: #f0f0f0;
  }

  a {
    color: #4dbbff;
  }

  h1, h2, h3, h4, h5, h6 {
    color: #f0f0f0;
  }

  pre, code {
    background-color: #2d2d2d;
    border: 1px solid #444;
  }

  strong {
    color: #f0f0f0;
  }
}
</style>

<img src="/assets/img/me.png" alt="Jacob Seifert" style="width: 150px; border-radius: 50%;">

## Weblinks to my projects and publications

Check out my work on: 
[Google Scholar](https://scholar.google.com/citations?user=Ag36EtoAAAAJ) | [YouTube](https://www.youtube.com/@JacobSeifert) | [GitHub](https://github.com/Duxon) | [LinkedIn](https://www.linkedin.com/in/jacob-seifert-458933152/) | [Email](mailto:derduxon+github.io@gmail.com)

## More Content

*   [Publications](/publications)
*   [CV](/assets/pdf/CV.pdf)

---

## Previous Projects
---
### Auto-Differentiable Ptychography
Computational imaging is a novel imaging paradigm that aims to overcome the limitations of traditional imaging systems. Instead of forming a perfect image on a sensor, we measure some derived data (e.g. diffraction patterns) and use a computer to reconstruct the image. This allows us to build simpler imaging systems and to reconstruct information that would otherwise be lost.

<img src="/assets/img/paradigms.png" alt="Paradigms" style="width: 480px;"/>

Ptychography is a computational imaging method that uses a series of diffraction patterns to reconstruct the image of a sample. A localized illumination is scanned across a sample, and for each position, a diffraction pattern is recorded. These diffraction patterns are then used to reconstruct the complex-valued transmission function of the sample.

<img src="/assets/img/minimal_setup.png" alt="Minimal Setup" style="width: 480px;"/>

My Ph.D. work in this field has focused on making ptychography more robust and accessible. Here are some selected contributions:

*   **Open-source AD ptychography:** We developed an open-source ptychography framework based on automatic differentiation (AD) and TensorFlow. This makes it easier for researchers to develop and test new reconstruction algorithms. This work was published in [OSA Continuum](https://doi.org/10.1364/OSAC.411174).

*   **Fine-tuning for challenging noise conditions:** We developed a method to account for the mixed Poisson-Gaussian noise statistics that are often present in experimental data. This allows for better image reconstruction quality, especially in low signal-to-noise ratio conditions. This work was published in [Optics Letters](https://doi.org/10.1364/OL.502344) and is also open-source.

*   **Semiconductor application and metrology:** We demonstrated the use of ptychography for the metrology of semiconductor nanostructures. We developed a wavelength-multiplexed reconstruction algorithm that can handle the instabilities of the EUV sources used in this application. This work was published in [Light: Science & Applications](https://doi.org/10.1038/s41377-024-01558-3).

*   **Deep generative models for ptychography:** Natural images are often sparse in a latent space. We can visualize this with a latent space walk, which shows smooth transitions within an object class. Implicit rank-minimized autoencoders can be used for this.

    <img src="/assets/img/AE_comparison.gif" alt="Latent Space Walk" style="width: 480px;"/>

    Then, we use this representation in a lower dimension for noise robustness. What I found cool is that we can now approximately visualize the loss landscape of this usually high-dimensional optimization problem (millions of parameters) to study the convexity properties in different noise conditions. This work was published in [Optics Express](https://doi.org/10.1364/OE.513556).

    <img src="/assets/img/loss_landscapes.jpeg" alt="Loss Landscapes" style="width: 480px;"/>

---
### Maker Space in Utrecht University
In 2022, with a small team of staff lead from physics/biology/informatics, we set up the first maker space for digital fabrication at Utrecht University: [Lili's Proto Lab](https://www.uu.nl/en/research/lilis-proto-lab). It was a lot of fun working towards this grand opening, and I documented the first wave of (student) projects in the [yearly report of 2022](https://github.com/LilisProtoLab/LPL_yearly_report_2022/blob/main/LPL_report_2022.pdf).

---


