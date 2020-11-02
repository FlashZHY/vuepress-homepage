---
pageClass: home-page
# some data for the components

name: Hengyuan Zhang
profile: /profile.jpeg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/FlashZHY
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com/in/hengyuan-zhang-780877165/
  - title: instagram
    icon: "/icons/instagram-mono.svg"
    link: https://www.instagram.com/flashzhy/


cv: https://drive.google.com/file/d/1Dngk3ROeTp8hExqutnSYNTp48WQPEmEA/view?usp=sharing
bio: Student at University of Rochester (Seeking full-time job)
email: Hengyuan.Zhang@ur.rochester.edu
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I'm a Master student in [Finance](https://simon.rochester.edu/programs/full-time-ms-in-finance/index.aspx) at [University of Rochester](https://www.rochester.edu). Now, I am actively seeking full-time **data analyst** job.

My interests include: Basketball, [Photography](https://www.instagram.com/flashzhy/) and Video Editing



## Education

- **Simon Business School, University of Rochester, Rochester, NY** <br/>
Sep. 2019 - Present
- **School of Management, Nanjing Audit University, China** <br/>
Sep. 2015 - June. 2019
- **Alliance Manchester Business School, University of Manchester, Manchester, UK** <br/>
July. 2017 - Aug. 2017

## Awards & Honors

### Contests
- **2nd Prize of Huawei Financial Challenge** 2018
- **2nd Prize of National English Competition for College Students** 2017
- **3rd Prize of 13th Advanced Mathematics Competition, Jiangsu Prov.** 2016

### Scholarships
- **The 5th Auditor General Scholarship** 2017 <br/>
Top 0.3%
- **National Scholarship** 2017 <br/>
Top 0.3%



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
