---
layout: default
---

<section class="hero" id="overview">
  <p class="eyebrow">Conference preview</p>
  <h1>Dutch Vaccination Profiles</h1>
  <p class="lead">Mapping how vaccination decisions differ across people and places in the Netherlands.</p>
  <p>
    During a pandemic, vaccination campaigns work best when they account for the
    different reasons people accept, delay, or refuse vaccination. This project
    combines survey-based behavioural research with CBS registry data to help
    practitioners and researchers understand decision profiles, where broader
    profile groups are more prevalent, and how these insights can support
    pandemic preparedness.
  </p>
  <div class="hero-actions" aria-label="Primary page links">
    <a class="button primary" href="#survey-profiles">Explore the 12 profiles</a>
    <a class="button secondary" href="#map">Open the map preview</a>
  </div>
</section>

<section class="summary-grid" aria-label="Project summary">
  <article>
    <span class="summary-number">12</span>
    <h2>Survey profiles</h2>
    <p>Rich LISS survey measures identify fine-grained COVID-19 vaccination decision profiles.</p>
  </article>
  <article>
    <span class="summary-number">5</span>
    <h2>Mapped groups</h2>
    <p>CBS registry data supports broader, more reliable mapped profile groups.</p>
  </article>
  <article>
    <span class="summary-number">1</span>
    <h2>Buurt map</h2>
    <p>The conference MVP starts with a neighbourhood-level preview map.</p>
  </article>
</section>

<section id="survey-profiles" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">Study 1</p>
    <h2>The 12 survey profiles</h2>
    <p>
      The first paper uses Latent Profile Analysis in a representative Dutch
      LISS sample to identify 12 COVID-19 vaccination decision profiles. These
      profiles are not labels for individual people. They describe recurring
      population patterns in beliefs, values, social context, and decision
      styles.
    </p>
  </div>

  <figure class="wide-figure">
    <img src="{{ '/assets/img/survey-profiles/profile-indicators.png' | relative_url }}" alt="Line plots showing 12 vaccination decision profiles across COVID-19 beliefs, vaccine beliefs, social values, and individual values, grouped into positive, neutral, and negative profiles.">
    <figcaption>
      Figure 1 from the current manuscript. Mean indicator values are shown as
      standardized scores. Profiles 1-6 are positive, profiles 7-9 are neutral,
      and profiles 10-12 are negative vaccination decision profiles.
    </figcaption>
  </figure>

  <div class="profile-groups">
    <article>
      <h3>Positive profiles 1-6</h3>
      <p>
        These profiles generally support vaccination, but for different reasons.
        Some combine positive vaccine beliefs with strong moral obligation and
        social norms; others are positive despite less comfortable emotions about
        vaccination.
      </p>
    </article>
    <article>
      <h3>Neutral profiles 7-9</h3>
      <p>
        These profiles are not mainly separated by how they view the disease.
        They differ more in vaccine beliefs, autonomy, freedom, and moral
        obligation.
      </p>
    </article>
    <article>
      <h3>Negative profiles 10-12</h3>
      <p>
        These smaller profiles are more opposed to vaccination. They differ most
        in vaccine beliefs and individual values such as autonomy, freedom, and
        naturalness or purity concerns.
      </p>
    </article>
  </div>

  <h3>Profile size and vaccination intentions</h3>
  <p>
    Vaccination intentions were highest in the positive profiles and lowest in
    the negative profiles, supporting the usefulness of the profile solution for
    public health interpretation.
  </p>

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

<section id="bridge" class="content-section highlight-band">
  <div class="section-heading">
    <p class="eyebrow">From profiles to places</p>
    <h2>Why the map uses 5 profile groups</h2>
  </div>
  <p>
    The first study uses rich survey data to identify 12 vaccination decision
    profiles. These profiles are useful for understanding how beliefs, values,
    trust, and social context shape decisions.
  </p>
  <p>
    The mapping study asks a different question: can these profiles be estimated
    across the Dutch population using CBS registry data? Registry data do not
    contain the beliefs and values that separate all 12 fine-grained profiles.
    For the map, we therefore use 5 broader profile groups. This is a deliberate
    tradeoff: less psychological detail, but more reliable regional estimates.
  </p>
</section>

<section id="map" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">Study 2</p>
    <h2>Buurt map preview</h2>
    <p>
      The conference preview uses synthetic placeholder values to demonstrate
      how aggregated prevalence of 5 profile groups can be explored by
      neighbourhood. It does not identify individual people, and it should not
      be read as causal evidence or final model output. The purpose is to
      support local discussion about where different decision patterns may be
      more common.
    </p>
  </div>

  <div class="map-frame">
    <iframe title="Dutch vaccination profile group map preview" src="https://dutchvaxprofiles.github.io/map-explorer/" loading="lazy"></iframe>
  </div>
  <p class="map-fallback">
    <a href="https://dutchvaxprofiles.github.io/map-explorer/">Open the map in a separate tab</a>.
  </p>
</section>

<section id="findings" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">What we learn</p>
    <h2>Findings for practitioners and researchers</h2>
  </div>
  <div class="insight-list">
    <article>
      <h3>Vaccination decisions are not one continuum</h3>
      <p>
        People can be positive, neutral, or negative for different combinations
        of reasons. Disease beliefs, vaccine beliefs, social values, and
        individual values all contribute.
      </p>
    </article>
    <article>
      <h3>Trust and decision style matter</h3>
      <p>
        The profiles differ in trust in institutions and in how people approach
        decisions. This suggests that communication and support may need to vary
        by decision profile.
      </p>
    </article>
    <article>
      <h3>Mapping broad groups supports preparedness</h3>
      <p>
        Linking survey-derived profiles to CBS registry data can help explore
        regional variation, while keeping uncertainty and aggregation visible.
      </p>
    </article>
  </div>
</section>

<section id="method" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">Method in brief</p>
    <h2>How the pieces connect</h2>
  </div>
  <ol class="method-steps">
    <li><strong>Survey profile discovery.</strong> LISS survey data are used to identify 12 decision profiles from beliefs about COVID-19, beliefs about vaccination, social values, and individual values.</li>
    <li><strong>Profile characterization.</strong> The profiles are compared on trust, decision-making styles, health literacy, subjective knowledge, demographics, and vaccination intentions.</li>
    <li><strong>Population mapping.</strong> Survey-derived profile information is linked to CBS registry variables and modelled into 5 broader profile groups for regional mapping.</li>
    <li><strong>Preparedness modelling.</strong> Future work uses these insights to reason about targeted interventions and social decision dynamics.</li>
  </ol>
</section>

<section id="team" class="content-section">
  <div class="section-heading">
    <p class="eyebrow">Project team</p>
    <h2>Team and outputs</h2>
  </div>

  <div class="team-grid">
    <article>
      <h3>Amsterdam UMC</h3>
      <p><strong>Danielle Timmermans</strong>, Professor, Department of Public and Occupational Health</p>
      <p><strong>Mitchell Matthijssen</strong>, Postdoctoral researcher, Department of Public and Occupational Health</p>
    </article>
    <article>
      <h3>Utrecht University</h3>
      <p><strong>Vincent Buskens</strong>, Professor, Department of Sociology</p>
      <p><strong>Javier Garcia-Bernardo</strong>, Assistant Professor, Department of Methodology and Statistics</p>
      <p><strong>Taymara C. Abreu</strong>, Postdoctoral researcher, Departments of Methodology and Statistics and Sociology</p>
      <p><strong>Isabelle de Wolf</strong>, researcher, Utrecht University</p>
    </article>
  </div>

  <div class="outputs">
    <h3>Outputs</h3>
    <ul>
      <li><strong>Paper 1:</strong> How Did People Make COVID-19 Vaccination Decisions: A Latent-Profile Modelling Approach. Manuscript in preparation.</li>
      <li><strong>Paper 2:</strong> Modelling the distribution of COVID-19 vaccination decision profiles in the Netherlands using CBS registry data. Manuscript in preparation.</li>
      <li><strong>Map explorer:</strong> conference preview of buurt-level 5-profile group estimates.</li>
      <li><strong>Protocol:</strong> <a href="https://osf.io/y3qgt/?view_only=bc485ce658214be9bde9e35ea76ddec8">OSF preregistration</a>.</li>
    </ul>
  </div>
</section>
