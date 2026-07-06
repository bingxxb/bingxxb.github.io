---
title: ''
summary: ''
date: 2026-07-06
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research integrates psychology, cognitive neuroscience, and learning science to understand how people perceive time, engage with tasks, and regulate affective experience. One line of work investigates time perception and temporal working memory, including visual duration aftereffects and the causal role of prefrontal stimulation in temporal cognition.

        A second line of work studies flow experience and learning-related states using EEG and portable neurophysiological recording. I am also interested in affective computing and embodied emotion, including how bodily electrodermal signals can represent emotional states in real-world human-computer interaction contexts.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: citation
---
