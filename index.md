<style>
  :root {
    --eg-ink: #243034;
    --eg-muted: #5d6f73;
    --eg-teal: #24756f;
    --eg-teal-soft: #e6f3f1;
    --eg-sand: #faf6ef;
    --eg-card: #ffffff;
    --eg-border: #dfe8e6;
  }

  body {
    color: var(--eg-ink);
    background:
      radial-gradient(circle at top left, rgba(36, 117, 111, 0.14), transparent 34rem),
      linear-gradient(180deg, var(--eg-sand) 0%, #ffffff 24rem);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    line-height: 1.65;
  }

  .eg-hero {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    gap: 2rem;
    align-items: center;
    margin: 2rem 0 2.25rem;
    padding: 2rem;
    border: 1px solid var(--eg-border);
    border-radius: 24px;
    background: rgba(255, 255, 255, 0.86);
    box-shadow: 0 18px 50px rgba(36, 48, 52, 0.08);
  }

  .eg-logo {
    width: min(210px, 34vw);
    height: auto;
  }

  .eg-kicker {
    margin: 0 0 0.5rem;
    color: var(--eg-teal);
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  h1 {
    margin-top: 0;
    margin-bottom: 0.75rem;
    font-size: clamp(2.1rem, 5vw, 3.6rem);
    line-height: 1.05;
  }

  .eg-intro {
    margin: 0;
    max-width: 65ch;
    color: var(--eg-muted);
    font-size: 1.1rem;
  }

  .eg-link {
    display: inline-block;
    margin-top: 1.25rem;
    padding: 0.65rem 1rem;
    border-radius: 999px;
    background: var(--eg-teal);
    color: #ffffff;
    font-weight: 700;
    text-decoration: none;
  }

  .eg-link:hover {
    background: #195b56;
    color: #ffffff;
  }

  h2 {
    margin-top: 2.25rem;
    color: var(--eg-teal);
  }

  h2 + p {
    color: var(--eg-muted);
  }

  ul {
    display: grid;
    gap: 0.85rem;
    padding-left: 0;
    list-style: none;
  }

  li {
    padding: 1rem 1.1rem;
    border: 1px solid var(--eg-border);
    border-radius: 16px;
    background: var(--eg-card);
    box-shadow: 0 8px 24px rgba(36, 48, 52, 0.05);
  }

  li a:first-child {
    color: var(--eg-teal);
    font-weight: 700;
    text-decoration: none;
  }

  li a:first-child:hover {
    text-decoration: underline;
  }

  hr {
    margin: 2rem 0;
    border: 0;
    border-top: 1px solid var(--eg-border);
  }

  @media (max-width: 700px) {
    .eg-hero {
      grid-template-columns: 1fr;
      padding: 1.35rem;
    }

    .eg-logo {
      order: -1;
      width: 160px;
    }
  }
</style>

<section class="eg-hero">
  <div>
    <p class="eg-kicker">School of Chemistry, University of Edinburgh</p>
    <h1>Erastova Group GitHub Resources</h1>
    <p class="eg-intro">Welcome to the GitHub page of the Erastova Group. We build and share codes, molecular models, teaching materials, and working resources for molecular modelling of natural minerals and materials.</p>
    <a class="eg-link" href="https://www.erastova.xyz">Visit erastova.xyz</a>
  </div>
  <img class="eg-logo" src="Logo_B.png" alt="Erastova Group logo">
</section>

---

## Codes

Software and scripts developed by the group to support molecular simulation setup, analysis, and interpretation.

- [DynDen](https://github.com/Erastova-group/DynDen)  
  A software to assess convergence of molecular dynamics simulations of interfacial phenomena.

- [Assemble!](https://github.com/Erastova-group/Assemble)  
  A tool for generating atomistic polymeric mixtures ready for simulation in GROMACS.

- [ClayCode](https://github.com/Erastova-group/ClayCode)  
  A tool to automate the setup of atomistic clay models for classical molecular dynamics simulations with GROMACS.

---

## Biochar Development

Repositories supporting the development of molecular models for biochars and their interactions with environmental species.

- [Biochar_MolecularModels](https://github.com/Erastova-group/Biochar_MolecularModels)  
  Molecular models of woody biochars at HTT 400 °C, 600 °C, and 800 °C, together with experimental property datasets.

- [Porous_Biochars_Models](https://github.com/Erastova-group/Porous_Biochars_Models)  
  Porous biochar molecular models created with the virtual atom approach, representative of woody biochars produced at 600–650 °C.

- [Mn_Biochar](https://github.com/Erastova-group/Mn_Biochar)  
  Atomistic models and GROMACS files for Mn(II) interactions with wood- and straw-derived biochars.

- [24D_biochar](https://github.com/Erastova-group/24D_biochar)  
  Molecular dynamics study of 2,4-D adsorption on biochar.

---

## ClayCode

ClayCode is a stand-alone code developed to support the construction of atomistic clay models for molecular dynamics simulations.

- [ClayCode](https://github.com/Erastova-group/ClayCode)  
  Main ClayCode repository.

- [ClayCode Workshop](https://github.com/Erastova-group/ClayCode-workshop)  
  Workshop materials and tutorials for using ClayCode.

---

## Teaching Materials

Teaching repositories and materials developed by the group. Some of these resources are hosted through [Edinburgh Chemistry Teaching](https://github.com/Edinburgh-Chemistry-Teaching) repositories. 

- [MD Research Techniques](https://github.com/Erastova-group/MD_ResearchTechniques)  
  Materials for the “Introduction to Computational Chemistry Techniques” course at the University of Edinburgh.

- [ClayCode Workshop](https://github.com/Erastova-group/ClayCode-workshop)  
  Workshop materials for learning how to use ClayCode.

- [Data-Driven Chemistry](https://github.com/Edinburgh-Chemistry-Teaching/Data-driven-chemistry)  
  An introductory Python course for undergraduate chemistry students.

More teaching materials will be added as they become available.

---

## Other links

- [Erastova Group website](https://www.erastova.xyz)
- [Erastova Group GitHub organisation](https://github.com/Erastova-group)
- [School of Chemistry, University of Edinburgh](https://www.chem.ed.ac.uk)
