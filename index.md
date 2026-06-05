---
layout: default
---

<section class="hero" id="overview">
  <p class="eyebrow">Project overview</p>
  <h1>Dutch Vaccination Profiles</h1>
  <p class="lead">Understanding how vaccination decisions differ across people and places in the Netherlands.</p>
  <p>
    Vaccination uptake is shaped by more than information alone. People differ
    in how they weigh disease risk, vaccine benefits, social expectations,
    autonomy, trust, and practical confidence. This project connects two kinds
    of evidence: detailed survey profiles that explain decision patterns, and
    broader mapped profile groups that can support local pandemic preparedness.
  </p>
  <div class="hero-actions" aria-label="Primary page links">
    <a class="button primary" href="#map">View the wijk map</a>
    <a class="button secondary" href="#survey-profiles">Compare the 12 survey profiles</a>
  </div>
</section>

<section class="summary-grid" aria-label="Project summary">
  <article>
    <span class="summary-number">12</span>
    <h2>Survey profiles</h2>
    <p>Study 1 uses rich LISS survey measures to identify fine-grained vaccination decision profiles.</p>
  </article>
  <article>
    <span class="summary-number">5</span>
    <h2>Mapped groups</h2>
    <p>Study 2 maps broader groups because registry data cannot reliably predict all twelve profiles.</p>
  </article>
  <article>
    <span class="summary-number">wijk</span>
    <h2>Local view</h2>
    <p>The map is built for neighbourhood-scale discussion without labelling individual people.</p>
  </article>
</section>

<section id="method" class="content-section method-overview">
  <div class="section-heading">
    <p class="eyebrow">Method in brief</p>
    <h2>How the pieces connect</h2>
    <p>
      The project starts with psychological detail and then asks what can be
      mapped responsibly. That distinction is central: the survey profiles are
      for explanation; the mapped groups are for aggregated, place-based
      preparedness.
    </p>
  </div>
  <ol class="method-steps">
    <li><strong>Discover decision profiles.</strong> LISS survey data are used to identify 12 profiles from beliefs about COVID-19, beliefs about vaccination, social values, and individual values.</li>
    <li><strong>Characterize the profiles.</strong> Profiles are compared on trust, decision-making styles, health literacy, subjective knowledge, demographics, and vaccination intentions.</li>
    <li><strong>Model broader mapped groups.</strong> Survey-derived profile information is linked to CBS registry variables and combined into 5 broader profile groups for regional estimation.</li>
    <li><strong>Support preparedness.</strong> The resulting profile logic can help practitioners think about where different kinds of vaccination support may be needed.</li>
  </ol>
</section>

<section id="map" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">Study 2</p>
    <h2>Mapping vaccination profile groups across Dutch wijken</h2>
    <p>
      The map shows five broad profile groups at wijk level. These five groups
      combine the twelve survey profiles from Study 1 into three positive
      groups, one neutral group, and one negative group. This is the key
      modelling compromise: less psychological nuance than the 12-profile
      survey solution, but a more reliable basis for mapping with registry data.
    </p>
  </div>

  <div class="profile-groups map-groups" aria-label="Mapped profile group families">
    <article>
      <h3>Three positive mapped groups</h3>
      <p>
        Placeholder to be described when the final Study 2 group labels are
        fixed. These groups combine survey profiles with generally positive
        vaccination intentions.
      </p>
    </article>
    <article>
      <h3>One neutral mapped group</h3>
      <p>
        Placeholder to be described. This group represents profiles where
        intentions and beliefs are more mixed and may be sensitive to context.
      </p>
    </article>
    <article>
      <h3>One negative mapped group</h3>
      <p>
        Placeholder to be described. This group combines profiles with lower
        vaccination intention and stronger concerns about vaccination.
      </p>
    </article>
  </div>

  <details class="plot-details map-note" open>
    <summary>How to read the current Study 2 map</summary>
    <p>
      The current Study 2 map is not the real CBS-linked model output yet. It is
      included so the team can test the interface, labels, colour scale, and
      practitioner-facing story before the final wijk estimates are added.
      Values are percentages, shown at aggregate level only; missing values are
      shown in gray.
    </p>
  </details>

  <div class="map-frame">
    <iframe title="Dutch vaccination profile group wijk map" src="https://dutchvaxprofiles.github.io/map-explorer/" loading="lazy"></iframe>
  </div>
  <p class="map-fallback">
    <a href="https://dutchvaxprofiles.github.io/map-explorer/">Open the map in a separate tab</a>.
  </p>
</section>

<section id="survey-profiles" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">Study 1</p>
    <h2>The 12 survey profiles</h2>
    <p>
      The first paper uses Latent Profile Analysis in a representative Dutch
      LISS sample to identify 12 COVID-19 vaccination decision profiles. These
      are population patterns, not labels for individual people. The 12-profile
      solution preserves the psychological nuance that is needed to understand
      why people with similar intentions may still need different kinds of
      communication and support.
    </p>
  </div>

  <div class="profile-groups">
    <article>
      <h3>Positive profiles 1-6</h3>
      <p>
        These profiles generally support vaccination, but not all for the same
        reasons. Some combine positive vaccine beliefs with strong moral
        obligation and social norms; others are positive while still showing
        more mixed feelings about vaccination.
      </p>
    </article>
    <article>
      <h3>Neutral profiles 7-9</h3>
      <p>
        These profiles sit closer to the middle on intention. They differ less
        by disease beliefs and more by vaccine beliefs, autonomy, freedom, and
        moral obligation.
      </p>
    </article>
    <article>
      <h3>Negative profiles 10-12</h3>
      <p>
        These smaller profiles have lower vaccination intention. They differ
        most in vaccine beliefs and individual values such as autonomy, freedom,
        naturalness, and purity concerns.
      </p>
    </article>
  </div>

  <div class="profile-visual-heading">
    <div>
      <h3>Profile size and July 2021 vaccination intention</h3>
      <p>
        Wider boxes represent larger profiles. The fill colour tracks July 2021
        vaccination intention from low red to high green. The left edge marks
        the profile family: positive, neutral, or negative.
      </p>
    </div>
    <div class="profile-legend" aria-label="Profile card legend">
      <span><i class="legend-edge positive-edge"></i>Positive edge</span>
      <span><i class="legend-edge neutral-edge"></i>Neutral edge</span>
      <span><i class="legend-edge negative-edge"></i>Negative edge</span>
    </div>
  </div>

  <div class="profile-mosaic" aria-label="Twelve survey profiles by sample size and vaccination intention">
    <article class="profile-card" style="--n: 178; --edge: #1f7a63; --intent-bg: #dff1e8;">
      <div class="profile-card-top"><span>Profile 1</span><span>Positive</span></div>
      <p class="profile-card-intention">93.11% July intention</p>
      <p>Strong positive beliefs and a clear moral or social pro-vaccination signal.</p>
      <dl><dt>N</dt><dd>178</dd><dt>Share</dt><dd>6.9%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 287; --edge: #1f7a63; --intent-bg: #e8f1df;">
      <div class="profile-card-top"><span>Profile 2</span><span>Positive</span></div>
      <p class="profile-card-intention">84.64% July intention</p>
      <p>Generally accepting, with a more mixed or less decisive profile than the strongest positive groups.</p>
      <dl><dt>N</dt><dd>287</dd><dt>Share</dt><dd>11.1%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 331; --edge: #1f7a63; --intent-bg: #dcf0e7;">
      <div class="profile-card-top"><span>Profile 3</span><span>Positive</span></div>
      <p class="profile-card-intention">94.23% July intention</p>
      <p>Consistently positive vaccine beliefs, social norms, and perceived benefits.</p>
      <dl><dt>N</dt><dd>331</dd><dt>Share</dt><dd>12.8%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 621; --edge: #1f7a63; --intent-bg: #e2f1e4;">
      <div class="profile-card-top"><span>Profile 4</span><span>Positive</span></div>
      <p class="profile-card-intention">88.64% July intention</p>
      <p>Largest profile; broadly accepting with moderately strong positive beliefs.</p>
      <dl><dt>N</dt><dd>621</dd><dt>Share</dt><dd>24.0%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 242; --edge: #1f7a63; --intent-bg: #edf1dc;">
      <div class="profile-card-top"><span>Profile 5</span><span>Positive</span></div>
      <p class="profile-card-intention">81.72% July intention</p>
      <p>Positive overall, but with more room for practical questions or ambivalent feelings.</p>
      <dl><dt>N</dt><dd>242</dd><dt>Share</dt><dd>9.4%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 48; --edge: #1f7a63; --intent-bg: #dff1e8;">
      <div class="profile-card-top"><span>Profile 6</span><span>Positive</span></div>
      <p class="profile-card-intention">91.96% July intention</p>
      <p>Small high-intention profile with a distinctive pattern of values and social beliefs.</p>
      <dl><dt>N</dt><dd>48</dd><dt>Share</dt><dd>1.9%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 300; --edge: #c0972e; --intent-bg: #f6e5b7;">
      <div class="profile-card-top"><span>Profile 7</span><span>Neutral</span></div>
      <p class="profile-card-intention">60.90% July intention</p>
      <p>Middle intention; support may depend on reducing uncertainty and clarifying benefits.</p>
      <dl><dt>N</dt><dd>300</dd><dt>Share</dt><dd>11.6%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 299; --edge: #c0972e; --intent-bg: #f1e4ad;">
      <div class="profile-card-top"><span>Profile 8</span><span>Neutral</span></div>
      <p class="profile-card-intention">67.69% July intention</p>
      <p>Neutral but somewhat more inclined toward vaccination than the other neutral profiles.</p>
      <dl><dt>N</dt><dd>299</dd><dt>Share</dt><dd>11.6%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 89; --edge: #c0972e; --intent-bg: #f3cf9a;">
      <div class="profile-card-top"><span>Profile 9</span><span>Neutral</span></div>
      <p class="profile-card-intention">49.70% July intention</p>
      <p>More hesitant neutral profile where autonomy and freedom may weigh more strongly.</p>
      <dl><dt>N</dt><dd>89</dd><dt>Share</dt><dd>3.4%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 71; --edge: #b5534b; --intent-bg: #f2c1b8;">
      <div class="profile-card-top"><span>Profile 10</span><span>Negative</span></div>
      <p class="profile-card-intention">19.48% July intention</p>
      <p>Low intention profile marked by negative vaccine beliefs and low perceived benefits.</p>
      <dl><dt>N</dt><dd>71</dd><dt>Share</dt><dd>2.7%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 88; --edge: #b5534b; --intent-bg: #efb4ad;">
      <div class="profile-card-top"><span>Profile 11</span><span>Negative</span></div>
      <p class="profile-card-intention">15.24% July intention</p>
      <p>Lowest intention profile, with stronger opposition and autonomy-related concerns.</p>
      <dl><dt>N</dt><dd>88</dd><dt>Share</dt><dd>3.4%</dd></dl>
    </article>
    <article class="profile-card" style="--n: 31; --edge: #b5534b; --intent-bg: #efc89f;">
      <div class="profile-card-top"><span>Profile 12</span><span>Negative</span></div>
      <p class="profile-card-intention">37.71% July intention</p>
      <p>Small negative profile with slightly higher intention than the other negative profiles.</p>
      <dl><dt>N</dt><dd>31</dd><dt>Share</dt><dd>1.2%</dd></dl>
    </article>
  </div>

  <details class="plot-details">
    <summary>Open the manuscript profile plots and exact Table 2 values</summary>
    <figure class="wide-figure">
      <img src="{{ '/assets/img/survey-profiles/profile-indicators.png' | relative_url }}" alt="Line plots showing 12 vaccination decision profiles across COVID-19 beliefs, vaccine beliefs, social values, and individual values, grouped into positive, neutral, and negative profiles.">
      <figcaption>
        Figure 1 from the current manuscript. Mean indicator values are shown as
        standardized scores. Profiles 1-6 are positive, profiles 7-9 are neutral,
        and profiles 10-12 are negative vaccination decision profiles.
      </figcaption>
    </figure>

    <div class="table-wrap" role="region" aria-label="Profile size and vaccination intentions" tabindex="0">
      <table>
        <thead>
          <tr>
            <th>Profile</th>
            <th>Group</th>
            <th>N</th>
            <th>%</th>
            <th>Jan 2021 intention</th>
            <th>Jul 2021 intention</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>1</td><td>Positive</td><td>178</td><td>6.9%</td><td>89.07</td><td>93.11</td></tr>
          <tr><td>2</td><td>Positive</td><td>287</td><td>11.1%</td><td>72.57</td><td>84.64</td></tr>
          <tr><td>3</td><td>Positive</td><td>331</td><td>12.8%</td><td>87.95</td><td>94.23</td></tr>
          <tr><td>4</td><td>Positive</td><td>621</td><td>24.0%</td><td>81.65</td><td>88.64</td></tr>
          <tr><td>5</td><td>Positive</td><td>242</td><td>9.4%</td><td>70.13</td><td>81.72</td></tr>
          <tr><td>6</td><td>Positive</td><td>48</td><td>1.9%</td><td>83.29</td><td>91.96</td></tr>
          <tr><td>7</td><td>Neutral</td><td>300</td><td>11.6%</td><td>46.19</td><td>60.90</td></tr>
          <tr><td>8</td><td>Neutral</td><td>299</td><td>11.6%</td><td>52.86</td><td>67.69</td></tr>
          <tr><td>9</td><td>Neutral</td><td>89</td><td>3.4%</td><td>33.16</td><td>49.70</td></tr>
          <tr><td>10</td><td>Negative</td><td>71</td><td>2.7%</td><td>11.80</td><td>19.48</td></tr>
          <tr><td>11</td><td>Negative</td><td>88</td><td>3.4%</td><td>5.23</td><td>15.24</td></tr>
          <tr><td>12</td><td>Negative</td><td>31</td><td>1.2%</td><td>27.90</td><td>37.71</td></tr>
        </tbody>
      </table>
    </div>
  </details>

  <details class="plot-details">
    <summary>What else differentiates the 12 profiles?</summary>
    <div class="details-grid">
      <figure>
        <img src="{{ '/assets/img/survey-profiles/trust.png' | relative_url }}" alt="Plots of trust in government, science, healthcare, and others by vaccination decision profile.">
        <figcaption>Trust is generally higher in positive profiles than in neutral and negative profiles.</figcaption>
      </figure>
      <figure>
        <img src="{{ '/assets/img/survey-profiles/decision-styles.png' | relative_url }}" alt="Plots of dependent, avoidant, spontaneous, rational, and intuitive decision-making styles by profile.">
        <figcaption>Negative and neutral profiles differ in avoidant and functional decision-making styles.</figcaption>
      </figure>
      <figure>
        <img src="{{ '/assets/img/survey-profiles/health-literacy-knowledge.png' | relative_url }}" alt="Plots of critical health literacy, functional health literacy, and subjective knowledge by profile.">
        <figcaption>Health literacy is not the whole story; subjective knowledge varies more clearly.</figcaption>
      </figure>
      <figure>
        <img src="{{ '/assets/img/survey-profiles/demographics.png' | relative_url }}" alt="Plots of sex, educational attainment, ethnic background, and mean age by profile.">
        <figcaption>Profiles also differ in demographic composition, which matters for interpretation and targeting.</figcaption>
      </figure>
    </div>
  </details>
</section>

<section id="findings" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">Using the results</p>
    <h2>What this offers vaccination practice and research</h2>
  </div>
  <div class="insight-list">
    <article>
      <h3>Diagnose why uptake differs</h3>
      <p>
        The profiles help separate belief patterns that may look similar in
        uptake statistics. A low-intention group may need trust-building,
        autonomy-sensitive communication, or practical access support for
        different reasons.
      </p>
    </article>
    <article>
      <h3>Match communication to decision patterns</h3>
      <p>
        Positive, neutral, and negative profiles differ in vaccine beliefs,
        social values, moral obligation, and trust. That means a single
        information message is unlikely to fit all audiences equally well.
      </p>
    </article>
    <article>
      <h3>Use maps for preparation, not labelling</h3>
      <p>
        The wijk map is an aggregate planning tool. It can guide questions,
        partnerships, and resource allocation, but it should not be used to
        infer the profile or motives of individual residents.
      </p>
    </article>
  </div>
</section>

<section id="team" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">Project team</p>
    <h2>Team and outputs</h2>
  </div>

  <div class="team-grid people-grid">
    <article class="person-card">
      <a href="https://pure.amsterdamumc.nl/en/persons/danielle-timmermans" class="person-link">
        <img src="{{ '/assets/img/team/danielle-timmermans.jpg' | relative_url }}" alt="Portrait of Danielle Timmermans.">
        <span>
          <strong>Danielle Timmermans</strong>
          <small>Professor, Public Health Risk Communication, Amsterdam UMC</small>
        </span>
      </a>
    </article>
    <article class="person-card">
      <a href="https://www.riscamsterdam.nl/mitchell-matthijssen" class="person-link">
        <img src="{{ '/assets/img/team/mitchell-matthijssen.jpg' | relative_url }}" alt="Portrait of Mitchell Matthijssen.">
        <span>
          <strong>Mitchell Matthijssen</strong>
          <small>Postdoctoral researcher, RISC Amsterdam / Amsterdam UMC</small>
        </span>
      </a>
    </article>
    <article class="person-card">
      <a href="https://www.uu.nl/staff/vbuskens" class="person-link">
        <img src="{{ '/assets/img/team/vincent-buskens.jpg' | relative_url }}" alt="Portrait of Vincent Buskens.">
        <span>
          <strong>Vincent Buskens</strong>
          <small>Professor, Sociology, Utrecht University</small>
        </span>
      </a>
    </article>
    <article class="person-card">
      <a href="https://www.uu.nl/staff/jgarciabernardo" class="person-link">
        <img src="{{ '/assets/img/team/javier-garcia-bernardo.jpg' | relative_url }}" alt="Portrait of Javier Garcia Bernardo.">
        <span>
          <strong>Javier Garcia Bernardo</strong>
          <small>Assistant Professor, Methodology and Statistics, Utrecht University</small>
        </span>
      </a>
    </article>
    <article class="person-card">
      <a href="https://www.uu.nl/staff/TCAbreu" class="person-link">
        <img src="{{ '/assets/img/team/taymara-abreu.jpg' | relative_url }}" alt="Portrait of Taymara C. Abreu.">
        <span>
          <strong>Taymara C. Abreu</strong>
          <small>Researcher, Methodology and Statistics, Utrecht University</small>
        </span>
      </a>
    </article>
    <article class="person-card">
      <a href="https://research-portal.uu.nl/en/persons/isabelle-de-wolf/" class="person-link">
        <span class="person-initials" aria-hidden="true">IdW</span>
        <span>
          <strong>Isabelle de Wolf</strong>
          <small>Researcher, Methodology and Statistics, Utrecht University</small>
        </span>
      </a>
    </article>
  </div>

  <div class="outputs">
    <h3>Outputs</h3>
    <ul>
      <li><strong>Paper 1:</strong> How Did People Make COVID-19 Vaccination Decisions: A Latent-Profile Modelling Approach. Manuscript in preparation.</li>
      <li><strong>Paper 2:</strong> Modelling the distribution of COVID-19 vaccination decision profiles in the Netherlands using CBS registry data. Manuscript in preparation.</li>
      <li><strong>Map explorer:</strong> wijk-level map of five broader vaccination profile groups.</li>
      <li><strong>Study 1 preregistration:</strong> <a href="https://osf.io/y3qgt/?view_only=bc485ce658214be9bde9e35ea76ddec8">OSF registration</a>.</li>
      <li><strong>Study 2 preregistration:</strong> <a href="https://osf.io/bqewr">OSF registration</a>.</li>
      <li><strong>Study 1 materials and code:</strong> <a href="https://osf.io/yfe35/?view_only=50c72f1ae2d841268bac079621d25ae2">OSF project</a>.</li>
    </ul>
  </div>
</section>
