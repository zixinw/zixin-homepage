---
pageClass: home-page
# some data for the components

name: Zixin Wang 王梓昕
profile: /zixin.jpg
socials:
- title: google scholar
  icon: /icons/gs.svg
  link: https://scholar.google.com/citations?user=6qxfN_4AAAAJ&hl=en
- title: linkedin
  icon: /icons/linkedin.svg
  link: https://www.linkedin.com/in/zixin-wang-900398317/


cv: /CV_Zixin_Wang_Academic.pdf
bio: 2nd-yr PhD Student at University of Michigan, Ann Arbor
email: zixinw AT umich DOT edu
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I am a PhD Student in the [School of Information](https://www.si.umich.edu/) at the [University of Michigan, Ann Arbor](https://umich.edu/), advised by [Dr. Florian Schaub](https://www.si.umich.edu/people/florian-schaub) and [Dr. Christopher Brooks](https://www.si.umich.edu/people/christopher-brooks). My research focuses on privacy and agency for low-control users, particularly those affected by data collection but not fully in charge of it. This includes tenants in smart homes, bystanders around sensing devices, and blind or low vision individuals navigating social interaction without visual cues.

Using quant-driven mixed methods (large-scale surveys, vignette experiments, statistical modeling, and thematic analysis), I study how people navigate these situations and design tools that support them, such as clearer disclosures, safer defaults, and lower-burden interactions.

I obtained my Bachelor's degree in Psychology at [Southwest University](http://www.swu.edu.cn/), China, and Master's degree in the [Department of Pyschology and Behavioral Sciences](http://www.psych.zju.edu.cn/) at [Zhejiang University](https://www.zju.edu.cn/). Previously, I was a research assistant at [Johns Hopkins University](https://engineering.jhu.edu/), advised by [Dr. Yaxing Yao](https://www.cs.jhu.edu/~yaxing/), and [Southwest University](http://www.swu.edu.cn/), advised by [Dr. Qinghua He](http://he-lab.cn/). I am also fortunate to have worked alongside distinguished professors such as [Danny Yuxing Huang](https://engineering.nyu.edu/faculty/danny-yuxing-huang), [New York University](https://www.nyu.edu/), [Haojian Jin](http://shift-3.com/), [UC San Diego](https://ucsd.edu/).

## Publications

### <font color=red>Usable Privacy and Security</font>
- **[CHI ’26]**
Yuting Yang, **Zixin Wang**, Rongjun Ma, and Florian Schaub. 2026.
[Privacy and Trust versus Utility: Adoption of Institutional and Commercial AI Assistants Among University Users]().
*In Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems (CHI ’26)*.

- **[USEC ’24]**
Tu Le, **Zixin Wang**, Danny Yuxing Huang, Yaxing Yao, and Yuan Tian. 2023.
[Towards Real-time Voice Interaction Data Collection Monitoring and Ambient Light Privacy Notification for Voice-controlled Services](https://www.ndss-symposium.org/wp-content/uploads/usec2024-39-paper.pdf).
*In Workshop on Usable Security and Privacy (USEC)*.

- **[USENIX Security ’23]**
**Zixin Wang**, Danny Yuxing Huang, and Yaxing Yao. 2023.
[Exploring Tenants’ Preferences of Privacy Negotiation in Airbnb](https://www.usenix.org/system/files/usenixsecurity23-wang-zixin.pdf).
*In 32nd USENIX Security Symposium*.

- **[USEC ’23]**
Stefany Cruz, Logan Danek, Shinan Liu, Christopher Kraemer, **Zixin Wang**, Nick Feamster, Danny Yuxing Huang, Yaxing Yao, and Josiah Hester. 2023.
[Augmented Reality’s Potential for Identifying and Mitigating Home Privacy Leaks](https://arxiv.org/pdf/2301.11998.pdf).
*In Workshop on Usable Security and Privacy (USEC)*.

### <font color=red>Usable Privacy and Security</font>


## Services
**Conference reviewer**: CHI 2026, CHI Late-breaking Work 2023, 2024, 2025, CSCW 2024, IMX 2024








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
