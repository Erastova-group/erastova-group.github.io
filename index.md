<style>
  :root {
    --eg-ink: #f7f7f2;
    --eg-muted: #c7ccc9;
    --eg-teal: #4fd0c2;
    --eg-blue: #4b7fd8;
    --eg-violet: #7860c8;
    --eg-bg: #050607;
    --eg-panel: #0e1113;
    --eg-border: #f0f0ea;
  }

  body {
    color: var(--eg-ink);
    background:
      radial-gradient(circle at 12% 10%, rgba(79, 208, 194, 0.22), transparent 20rem),
      radial-gradient(circle at 88% 6%, rgba(120, 96, 200, 0.24), transparent 22rem),
      linear-gradient(135deg, #050607 0%, #111417 52%, #f7f7f2 52.2%, #f7f7f2 53%, #050607 53.2%, #050607 100%);
    font-family: Helvetica, Arial, sans-serif;
    line-height: 1.38;
  }

  .eg-hero {
    display: grid;
    grid-template-columns: minmax(0, 1fr) auto;
    gap: 1.4rem;
    align-items: center;
    margin: 0.75rem 0 1rem;
    padding: 1rem 1.2rem;
    border: 1px solid rgba(247, 247, 242, 0.72);
    border-radius: 18px;
    background: rgba(5, 6, 7, 0.82);
    box-shadow: 0 18px 46px rgba(0, 0, 0, 0.28);
  }

  .eg-logo {
    display: block;
    width: min(320px, 42vw);
    height: auto;
    background: transparent;
    filter: drop-shadow(0 12px 28px rgba(0, 0, 0, 0.45));
  }

  .eg-kicker {
    margin: 0 0 0.35rem;
    color: var(--eg-teal);
    font-weight: 700;
    font-size: 0.78rem;
    letter-spacing: 0.07em;
    text-transform: uppercase;
  }

  h1 {
    margin-top: 0;
    margin-bottom: 0.35rem;
    font-size: clamp(1.75rem, 3.8vw, 2.65rem);
    line-height: 1.05;
  }

  .eg-intro {
    margin: 0;
    max-width: 65ch;
    color: var(--eg-muted);
    font-size: 0.96rem;
  }

  .eg-link {
    display: inline-block;
    margin-top: 0.85rem;
    padding: 0.48rem 0.78rem;
    border-radius: 999px;
    background: var(--eg-ink);
    color: #050607;
    font-weight: 700;
    text-decoration: none;
  }

  .eg-link:hover {
    background: var(--eg-teal);
    color: #050607;
  }

  h2 {
    margin-top: 1rem;
    margin-bottom: 0.15rem;
    color: var(--eg-teal);
  }

  h2 + p {
    margin-top: 0;
    margin-bottom: 0.45rem;
    color: var(--eg-muted);
  }

  ul {
    display: grid;
    gap: 0.35rem;
    margin-top: 0.35rem;
    padding-left: 1.1rem;
    list-style: disc;
  }

  li {
    padding: 0;
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
    margin: 0.9rem 0;
    border: 0;
    border-top: 1px solid var(--eg-border);
  }

  @media (max-width: 700px) {
    .eg-hero {
      grid-template-columns: 1fr;
      padding: 1rem;
    }

    .eg-logo {
      order: -1;
      width: 240px;
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
  <img class="eg-logo" src="Logo_W.png" alt="Erastova Group logo">
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
