---
sidebar: auto
sidebarDepth: 2
home: true
title: Veronika Gambin
externalLinkIcon: false
pageClass: home-page
lang: en-US
# some data for the components

name: Veronika Gambin
profile: /profile.png

socials:
#  - title: GitHub
#    icon: "/icons/logo-github.svg"
#    link: https://github.com/linan1109
  - title: LinkedIn
    icon: "/icons/logo-linkedin.svg"
    link: https://www.linkedin.com/in/veronika-gambin
  - title: veronika.gambin@irm.uzh.ch
    icon: "/icons/mail-outline.svg"
    link: mailto:veronika.gambin@irm.uzh.ch
  - title: CV
    icon: "/icons/document-outline.svg"
    link: /cv/cv.pdf
  - title: Zurich, Switzerland
    icon: "/icons/map-pin.svg"
    link: https://maps.app.goo.gl/dApBUWdUZVYk4g7X7

footer: MIT Licensed | Powered by VuePress
---



<ProfileSection :frontmatter="$page.frontmatter" />


## About Me

Hi, I'm Veronika! Currently, I'm doing my PhD in Neuroscience at the [University of Zurich（UZH)][uzh-home].

My research centers on understanding of sleep and sleep-related disorders. My work involves innovative experiments using driving simulations to investigate how various sleep-related disorders affect fitness to drive. 
By employing a multidisciplinary approach that integrates advanced thechnologies and artificial intelligence, I aim to bridge the gap between scientific findings and practical applications, making impactful contributions to real-world challenges.


[uzh-home]: https://www.uzh.ch/en.html
[spbu-home]: https://english.spbu.ru/
[bosch-iot]: https://www.iot-lab.ch/
[eth-home]: https://ethz.ch/en.html

## Education

[→ To More Details][education-detail]
 - Oct. 2024 - Present: PhD in Neuroscience, [University of Zurich][uzh-home], Switzerland
 - Feb. 2023 - Nov. 2024: Master of Science in Biology, [University of Zurich][uzh-home], Switzerland
 - Sep. 2017 - Jun. 2021: Bachelor of Science in Biology, [St Petersburg University][spbu-home], Russia

[education-detail]: /education/


## Projects

[→ To Full List][projects-detail]

<ProjectCard image="/projects/1.png" hideBorder=true>

  **Driving simulation-based maintenance of wakefulness test (MWT)**

Current project focuses on validating a new standard driving-simulator-based maintenance of wakefulness test (DS-MWT) for precise assessment of excessive daytime sleepiness (EDS).

</ProjectCard>

<ProjectCard image="/projects/MSE.png" hideBorder=true>

  **AI-based microsleep detection during driving**

Implementation of automated microsleep episode detection algorithm in DS-MWT for fitness-to-drive assessment.

</ProjectCard>


<ProjectCard image="/projects/AEP_ch_ad.png" hideBorder=true>

  **Auditory evoked potentials elicited by closed-loop stimulation during sleep in children and adults**

Investigation of the impact of closed-loop down-phase targeted stimulation during NREM sleep in a pediatric population and comparing the characteristics of AEP components (amplitude and latency) between children and adults to identify age-related differences.

</ProjectCard>

[projects-detail]: /projects/


## On-Campus Works

- Fall 2023: Practical Tutor in the lecture ["Foundations of Data Science"][fds] (MSc & PhD) at the University of Zurich
- Fall 2020: Teaching Assistant in the lecture ["Compiler Theory"][this-site] (BEng) at Beihang University
- Spring 2020: Head Teaching Assistant in the lecture ["Object-Oriented Programming (Java)"][this-site] (BEng) at Beihang University
- Fall 20129: Teaching Assistant in the lecture ["Algorithm Analysis and Design"][this-site] (BEng) at Beihang University

[fds]: https://www.ifi.uzh.ch/en/dast/teaching/FDS.html
[this-site]: /

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

.medium-zoom-image--opened {
  width: auto;
  height: auto;
  max-width: 100%;
  max-height: 100vh;
  object-fit: contain;
  z-index: 1000;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  transition: transform 0.3s ease, width 0.3s ease, height 0.3s ease;
}

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
