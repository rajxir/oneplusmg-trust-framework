---
layout: lets-talk-genomics
permalink: /lets-talk-genomics/debbietest
---

<style>
.ge-directory {
  color: inherit;
}

.ge-directory [hidden] {
  display: none !important;
}

.ge-directory h1,
.ge-directory h2,
.ge-directory h3 {
  color: inherit;
}

.ge-directory .ge-controls {
  margin: 1.5rem 0;
  padding: 1.25rem;
  border: 1px solid #d1d5db;
  border-radius: .65rem;
}

.ge-directory .ge-controls legend {
  float: none;
  width: auto;
  padding: 0 .3rem;
  font-size: 1.1rem;
  font-weight: 600;
}

.ge-directory .ge-filter-row {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}

.ge-directory .ge-filter label {
  display: block;
  margin-bottom: .35rem;
  font-weight: 600;
}

.ge-directory .ge-filter select {
  display: block;
  width: 100%;
  min-height: 44px;
  padding: .5rem;
  font: inherit;
  color: inherit;
  background: #fff;
  border: 1px solid #767676;
  border-radius: .3rem;
}

.ge-directory .ge-reset {
  margin-top: 1rem;
  min-height: 44px;
  padding: .4rem .8rem;
  font: inherit;
  color: inherit;
  background: transparent;
  border: 1px solid currentColor;
  border-radius: .3rem;
  cursor: pointer;
}

.ge-directory a:focus-visible,
.ge-directory button:focus-visible,
.ge-directory select:focus-visible {
  outline: 3px solid currentColor;
  outline-offset: 3px;
}

.ge-directory .ge-card-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.25rem;
  align-items: stretch;
}

.ge-directory .ge-card {
  display: flex;
  flex-direction: column;
  min-width: 0;
  padding: 1.5rem;
  border: 1px solid #d1d5db;
  border-radius: .75rem;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .06);
  color: inherit;
  overflow-wrap: anywhere;
}

.ge-directory .ge-card h3 {
  margin: 0 0 .6rem;
  font-size: 1.2rem;
  line-height: 1.4;
}

.ge-directory .ge-organisation {
  margin: 0 0 .8rem;
}

.ge-directory .ge-description {
  margin-bottom: 1rem;
}

.ge-directory .ge-topics {
  display: flex;
  flex-wrap: wrap;
  align-items: baseline;
  gap: .35rem;
  margin-bottom: .8rem;
}

.ge-directory .ge-label {
  margin-right: .2rem;
  font-weight: 600;
}

.ge-directory .ge-tag {
  display: inline-block;
  padding: .15rem .5rem;
  border: 1px solid #d1d5db;
  border-radius: .3rem;
  font-size: .85rem;
  line-height: 1.5;
}

.ge-directory .ge-meta {
  margin-bottom: 1rem;
  font-size: .95rem;
}

.ge-directory .ge-links {
  margin: auto 0 0;
  padding: .5rem 0 0 1.2rem;
}

.ge-directory .ge-links li {
  margin-bottom: .4rem;
}

.ge-directory .ge-links a {
  text-decoration: underline;
  text-underline-offset: .15em;
}

.ge-directory .ge-related {
  margin-top: 2.5rem;
}

.ge-directory .ge-related .ge-card {
  max-width: 42rem;
}

@media (max-width: 800px) {
  .ge-directory .ge-card-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  .ge-directory .ge-filter-row {
    grid-template-columns: 1fr;
  }

  .ge-directory .ge-card {
    padding: 1.1rem;
  }
}
</style>

<div class="ge-directory" id="ge-directory">

  <h1>Genomics engagement resources</h1>

  <p>
    Find materials to help explain genomics, support discussion and learn from
    public engagement initiatives. Browse educational resources, discussion
    materials and reports of public and patient perspectives.
  </p>

  <p>
    Each resource includes topic, format and language labels, with links to the
    original materials. Resources are listed alphabetically by title.
  </p>

  <fieldset class="ge-controls" id="ge-controls" hidden>
    <legend>Find resources</legend>

    <p>
      Choose a topic, format or language to narrow the list. You can combine filters.
    </p>

    <div class="ge-filter-row">

      <div class="ge-filter">
        <label for="ge-topic">Topic</label>
        <select id="ge-topic" aria-controls="ge-resource-list">
          <option value="">All topics</option>
          <option value="consent">Consent</option>
          <option value="ethics">Ethics and society</option>
          <option value="genetic-screening">Genetic screening</option>
          <option value="genomic-medicine">Genomic medicine</option>
          <option value="genomics-basics">Genomics basics</option>
          <option value="insurance">Insurance and discrimination</option>
          <option value="newborn-screening">Newborn screening</option>
          <option value="privacy">Privacy and data use</option>
        </select>
      </div>

      <div class="ge-filter">
        <label for="ge-format">Format</label>
        <select id="ge-format" aria-controls="ge-resource-list">
          <option value="">All formats</option>
          <option value="booklet">Booklet</option>
          <option value="podcast">Podcast</option>
          <option value="report">Report</option>
          <option value="teaching-materials">Teaching materials</option>
          <option value="video">Video</option>
          <option value="website">Website</option>
        </select>
      </div>

      <div class="ge-filter">
        <label for="ge-language">Language</label>
        <select id="ge-language" aria-controls="ge-resource-list">
          <option value="">All languages</option>
          <option value="nl">Dutch</option>
          <option value="en">English</option>
          <option value="fr">French</option>
          <option value="tw">Twi</option>
        </select>
      </div>

    </div>

    <button class="ge-reset" id="ge-reset" type="button">
      Reset filters
    </button>
  </fieldset>

  <p id="ge-count" role="status" aria-live="polite" aria-atomic="true">
    Showing all 15 genomics resources.
  </p>

  <h2 id="ge-browse">Browse genomics resources</h2>

  <p>
    Where several language versions are available, choose the link for your
    preferred language.
  </p>

  <p id="ge-empty" hidden>
    No resources match your filters. Try another topic, format or language,
    or reset the filters.
  </p>

  <div class="ge-card-grid" id="ge-resource-list" aria-labelledby="ge-browse">

    <!-- Confirm the intended CCNE report edition before publication. -->
    <article
      class="ge-card"
      data-topics="genomic-medicine ethics privacy"
      data-format="report"
      data-languages="fr"
      aria-labelledby="ge-resource-1"
    >
      <h3 id="ge-resource-1">Bioethics and genomic medicine in France</h3>

      <p class="ge-organisation">
        Comité consultatif national d’éthique (CCNE)
      </p>

      <p class="ge-description">
        A report from the 2018 États généraux de la bioéthique consultation,
        bringing together public contributions on bioethical questions,
        including genetic testing, genomic medicine and health data.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomic medicine</span>
        <span class="ge-tag">Ethics and society</span>
        <span class="ge-tag">Privacy and data use</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Report<br>
        <strong>Language:</strong> French
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.ccne-ethique.fr/sites/default/files/2022-05/Rapport%20de%20synthe%CC%80se%20CCNE%20Bat.pdf">
            Read the bioethics consultation report in French (PDF)
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="genomic-medicine ethics"
      data-format="report"
      data-languages="en"
      aria-labelledby="ge-resource-2"
    >
      <h3 id="ge-resource-2">
        Black African and Black Caribbean perspectives on genomic research
      </h3>

      <p class="ge-organisation">Genomics England</p>

      <p class="ge-description">
        A qualitative study exploring the views of Black African and Black
        Caribbean communities on participation in the 100,000 Genomes Project.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomic medicine</span>
        <span class="ge-tag">Ethics and society</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Report<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://files.genomicsengland.co.uk/images/News-and-Events/News-Articles-Images/black-african-black-caribbean-communities-participation-100kgp.pdf">
            Read the report on participation in the 100,000 Genomes Project (PDF)
          </a>
        </li>
        <li>
          <a href="https://www.genomicsengland.co.uk/news/100000-genomes-project-public-attitudes">
            About the public engagement research
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="genomic-medicine ethics privacy"
      data-format="report"
      data-languages="fr nl"
      aria-labelledby="ge-resource-3"
    >
      <h3 id="ge-resource-3">
        Citizen recommendations on the use of genomic information
      </h3>

      <p class="ge-organisation">
        Sciensano and the King Baudouin Foundation
      </p>

      <p class="ge-description">
        Recommendations from a Belgian citizen forum on the ethical and
        social questions raised by using genomic information in healthcare.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomic medicine</span>
        <span class="ge-tag">Ethics and society</span>
        <span class="ge-tag">Privacy and data use</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Report<br>
        <strong>Languages:</strong> French, Dutch
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.sciensano.be/sites/default/files/kbs_pod_fr_genoominfo_26.03.2019_hr.pdf">
            Read the citizen forum report in French (PDF)
          </a>
        </li>
        <li>
          <a href="https://www.sciensano.be/sites/default/files/kbs_pod_nl_genoominfo_26.03.2019_hr.pdf">
            Read the citizen forum report in Dutch (PDF)
          </a>
        </li>
        <li>
          <a href="https://sciensano.be/en/projects/citizens-forum-use-genomic-information-health-care">
            About the citizen forum
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="ethics privacy"
      data-format="teaching-materials"
      data-languages="fr nl"
      aria-labelledby="ge-resource-4"
    >
      <h3 id="ge-resource-4">Classroom discussions about DNA and society</h3>

      <p class="ge-organisation">Sciensano — DNA Debate</p>

      <p class="ge-description">
        Teaching guides to help secondary school students discuss ethical
        questions about DNA information, develop reasoned opinions and
        consider different perspectives.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Ethics and society</span>
        <span class="ge-tag">Privacy and data use</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Teaching materials<br>
        <strong>Languages:</strong> French, Dutch
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.sciensano.be/sites/default/files/dossier_pedagogique_-_introduction.pdf">
            Read the teaching guide introduction in French (PDF)
          </a>
        </li>
        <li>
          <a href="https://www.sciensano.be/sites/default/files/1_lesformule_inleiding_nlv2.pdf">
            Read the teaching guide introduction in Dutch (PDF)
          </a>
        </li>
        <li>
          <a href="https://www.sciensano.be/en/projects/dna-debate">
            About DNA Debate
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="genomics-basics ethics privacy"
      data-format="teaching-materials"
      data-languages="nl"
      aria-labelledby="ge-resource-5"
    >
      <h3 id="ge-resource-5">Classroom discussions about genetics</h3>

      <p class="ge-organisation">De Maakbare Mens — Overal DNA</p>

      <p class="ge-description">
        Dutch-language materials for teachers exploring inheritance, genetic
        testing and the ethical and social questions surrounding genetics,
        with topics ranging from pregnancy to privacy.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomics basics</span>
        <span class="ge-tag">Ethics and society</span>
        <span class="ge-tag">Privacy and data use</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Teaching materials<br>
        <strong>Language:</strong> Dutch
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.demaakbaremens.org/themas/erfelijkheid/overal-dna-voor-leerkrachten/">
            Explore the Overal DNA teaching materials in Dutch
          </a>
        </li>
      </ul>
    </article>

    <!-- Confirm the French booklet download in the publication record. -->
    <article
      class="ge-card"
      data-topics="genomic-medicine ethics"
      data-format="booklet"
      data-languages="fr"
      aria-labelledby="ge-resource-6"
    >
      <h3 id="ge-resource-6">DNA Debate case studies</h3>

      <p class="ge-organisation">Sciensano</p>

      <p class="ge-description">
        An information booklet using nine case studies to prompt discussion
        about the ethical and social implications of using genomic
        information in healthcare.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomic medicine</span>
        <span class="ge-tag">Ethics and society</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Booklet<br>
        <strong>Language:</strong> French
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://hdl.handle.net/20.500.14493/5673">
            Find the DNA Debate information booklet
          </a>
        </li>
        <li>
          <a href="https://www.sciensano.be/fr/projets/debat-adn">
            About DNA Debate
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="insurance privacy"
      data-format="podcast"
      data-languages="en"
      aria-labelledby="ge-resource-7"
    >
      <h3 id="ge-resource-7">Genetic testing and life insurance</h3>

      <p class="ge-organisation">ABC Radio — Health Report</p>

      <p class="ge-description">
        A podcast discussing a ban on the use of genetic test results by
        life insurers in Australia.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Insurance and discrimination</span>
        <span class="ge-tag">Privacy and data use</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Podcast<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.abc.net.au/listen/programs/healthreport/genetic-testing-life-insurance/104378404">
            Listen to the genetic testing and life insurance podcast
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="genomics-basics genetic-screening privacy consent"
      data-format="website"
      data-languages="en"
      aria-labelledby="ge-resource-8"
    >
      <h3 id="ge-resource-8">Genomics education for parents and communities</h3>

      <p class="ge-organisation">
        University of North Carolina at Chapel Hill — Age-Based Genomic Screening
      </p>

      <p class="ge-description">
        Learning modules explaining DNA, inheritance, genetic screening,
        privacy and consent. Materials include comics and slides developed
        with input from a Community Research Board.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomics basics</span>
        <span class="ge-tag">Genetic screening</span>
        <span class="ge-tag">Privacy and data use</span>
        <span class="ge-tag">Consent</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Website<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.med.unc.edu/genetics/abgs/parent-community-engagement/">
            Explore the genomics education modules
          </a>
        </li>
        <li>
          <a href="https://www.med.unc.edu/genetics/abgs/">
            About Age-Based Genomic Screening
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="genomics-basics genomic-medicine ethics"
      data-format="website"
      data-languages="en"
      aria-labelledby="ge-resource-9"
    >
      <h3 id="ge-resource-9">Genomics learning resources from Your Genome</h3>

      <p class="ge-organisation">Wellcome Sanger Institute</p>

      <p class="ge-description">
        A collection of articles, videos, activities and discussion resources
        about genetics and genomics, with dedicated materials for students
        and teachers.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomics basics</span>
        <span class="ge-tag">Genomic medicine</span>
        <span class="ge-tag">Ethics and society</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Website<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.yourgenome.org/">
            Explore Your Genome
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="genomics-basics"
      data-format="website"
      data-languages="fr en"
      aria-labelledby="ge-resource-10"
    >
      <h3 id="ge-resource-10">
        Interactive genomics learning from Génome Québec
      </h3>

      <p class="ge-organisation">Génome Québec</p>

      <p class="ge-description">
        An educational website offering resources and activities to explore
        genetics and genomics, available in French and English.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomics basics</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Website<br>
        <strong>Languages:</strong> French, English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://genomequebec.com/en/educative-content/educational-space/">
            Explore the Génome Québec educational space
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="genomic-medicine privacy ethics"
      data-format="report"
      data-languages="en"
      aria-labelledby="ge-resource-11"
    >
      <h3 id="ge-resource-11">
        Public views on genomic medicine and the NHS
      </h3>

      <p class="ge-organisation">Genomics England — report by Ipsos MORI</p>

      <p class="ge-description">
        A public dialogue report exploring expectations of genomic medicine,
        the relationship between the public and the NHS and acceptable uses
        of genomic data.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Genomic medicine</span>
        <span class="ge-tag">Privacy and data use</span>
        <span class="ge-tag">Ethics and society</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Report<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.genomicsengland.co.uk/assets/images/News-and-Events/News-Articles-Images/18-045132-01-Genomics-Dialogue-final.pdf">
            Read the public dialogue on genomic medicine report (PDF)
          </a>
        </li>
        <li>
          <a href="https://www.genomicsengland.co.uk/news/public-dialogue-report-published">
            About the public dialogue
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="newborn-screening ethics"
      data-format="report"
      data-languages="en"
      aria-labelledby="ge-resource-12"
    >
      <h3 id="ge-resource-12">
        Public views on whole genome sequencing for newborns
      </h3>

      <p class="ge-organisation">
        Genomics England and the UK National Screening Committee
      </p>

      <p class="ge-description">
        A public dialogue report exploring the implications of using whole
        genome sequencing in newborn screening and the views of participants
        in the UK.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Newborn screening</span>
        <span class="ge-tag">Ethics and society</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Report<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/959931/WGS_for_newborn_screening_FINAL_ACCESSIBLE.pdf">
            Read the newborn screening dialogue report (PDF)
          </a>
        </li>
        <li>
          <a href="https://www.genomicsengland.co.uk/initiatives/newborns/engagement">
            About the newborns engagement programme
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="newborn-screening"
      data-format="report"
      data-languages="en"
      aria-labelledby="ge-resource-13"
    >
      <h3 id="ge-resource-13">
        Rare disease perspectives on newborn screening
      </h3>

      <p class="ge-organisation">
        EURORDIS — Rare Barometer and Screen4Care
      </p>

      <p class="ge-description">
        European survey findings on newborn screening from people living
        with a rare disease and their families, published in the
        <em>Voices on newborn screening</em> report.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Newborn screening</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Report<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.eurordis.org/wp-content/uploads/2024/05/RB_NBS_report_vff.pdf">
            Read Voices on newborn screening (PDF)
          </a>
        </li>
        <li>
          <a href="https://www.screen4care.eu/people-living-with-rare-diseases/involvement">
            About involvement in Screen4Care
          </a>
        </li>
      </ul>
    </article>

    <article
      class="ge-card"
      data-topics="consent privacy"
      data-format="report"
      data-languages="en"
      aria-labelledby="ge-resource-14"
    >
      <h3 id="ge-resource-14">
        Using human tissue and linked health data in research
      </h3>

      <p class="ge-organisation">
        Health Research Authority and Human Tissue Authority
      </p>

      <p class="ge-description">
        A public dialogue report exploring consent for linking human tissue
        samples with health data in research, including participants’
        expectations about privacy and the use of their information.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Consent</span>
        <span class="ge-tag">Privacy and data use</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Report<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://sciencewise.org.uk/wp-content/uploads/2018/07/HRA-report-2018-07.pdf">
            Read the human tissue and health data dialogue report (PDF)
          </a>
        </li>
        <li>
          <a href="https://sciencewise.org.uk/projects/human-tissue-in-health-research/">
            About the public dialogue
          </a>
        </li>
      </ul>
    </article>

    <!-- Check playback and language of the Twi playlist before publication. -->
    <article
      class="ge-card"
      data-topics="privacy ethics"
      data-format="video"
      data-languages="en tw"
      aria-labelledby="ge-resource-15"
    >
      <h3 id="ge-resource-15">Your DNA Your Say videos</h3>

      <p class="ge-organisation">Wellcome Connecting Science</p>

      <p class="ge-description">
        Short films explaining genomic data sharing and the questions it
        raises about privacy and access to information, created for the
        Your DNA, Your Say public attitudes survey.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">Privacy and data use</span>
        <span class="ge-tag">Ethics and society</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Video<br>
        <strong>Languages:</strong> English, Twi
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://vimeo.com/showcase/4657358">
            Watch Your DNA Your Say in English
          </a>
        </li>
        <li>
          <a href="https://youtube.com/playlist?list=PLicKqIwYPVo6QvAhvGuBAwfo9LLdjVJZ0">
            Watch Your DNA Your Say in Twi
          </a>
        </li>
        <li>
          <a href="https://www.wellcomeconnectingscience.org/project/your-dna-your-say/">
            About Your DNA Your Say
          </a>
        </li>
      </ul>
    </article>

  </div>

  <section class="ge-related" aria-labelledby="ge-related-heading">

    <h2 id="ge-related-heading">Related resource: AI in healthcare</h2>

    <p>
      This resource covers a broader health technology topic and is separate
      from the genomics list above.
    </p>

    <article class="ge-card" aria-labelledby="ge-resource-16">

      <h3 id="ge-resource-16">
        What AI scribes can and cannot do for healthcare
      </h3>

      <p class="ge-organisation">ABC Radio — Health Report</p>

      <p class="ge-description">
        A podcast exploring the capabilities and limitations of AI scribes
        in healthcare.
      </p>

      <div class="ge-topics">
        <span class="ge-label">Topics:</span>
        <span class="ge-tag">AI and healthcare</span>
      </div>

      <p class="ge-meta">
        <strong>Format:</strong> Podcast<br>
        <strong>Language:</strong> English
      </p>

      <ul class="ge-links">
        <li>
          <a href="https://www.abc.net.au/listen/programs/healthreport/ai-in-healthcare-scribes/105568802">
            Listen to the AI scribes podcast
          </a>
        </li>
      </ul>

    </article>

  </section>

</div>

<script>
(() => {
  'use strict';

  const root = document.getElementById('ge-directory');

  if (!root) return;

  const list = root.querySelector('#ge-resource-list');

  const cards = Array.from(list.querySelectorAll('.ge-card')).map(element => ({
    element,
    topics: (element.dataset.topics || '').split(/\s+/),
    format: element.dataset.format,
    languages: (element.dataset.languages || '').split(/\s+/)
  }));

  const topic = root.querySelector('#ge-topic');
  const format = root.querySelector('#ge-format');
  const language = root.querySelector('#ge-language');
  const count = root.querySelector('#ge-count');
  const empty = root.querySelector('#ge-empty');
  const controls = root.querySelector('#ge-controls');
  const reset = root.querySelector('#ge-reset');

  function updateResources() {
    let visible = 0;

    cards.forEach(card => {
      const matchesTopic =
        !topic.value || card.topics.includes(topic.value);

      const matchesFormat =
        !format.value || card.format === format.value;

      const matchesLanguage =
        !language.value || card.languages.includes(language.value);

      const matches =
        matchesTopic && matchesFormat && matchesLanguage;

      card.element.hidden = !matches;

      if (matches) visible++;
    });

    const filtered = Boolean(
      topic.value || format.value || language.value
    );

    count.textContent = filtered
      ? `Showing ${visible} of ${cards.length} genomics resources.`
      : `Showing all ${cards.length} genomics resources.`;

    empty.hidden = visible !== 0;
  }

  [topic, format, language].forEach(select => {
    select.addEventListener('change', updateResources);
  });

  reset.addEventListener('click', () => {
    topic.value = '';
    format.value = '';
    language.value = '';

    updateResources();
  });

  updateResources();
  controls.hidden = false;
})();
</script>
