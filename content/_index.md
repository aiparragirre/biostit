---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Biostit
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The overall objectives of this group are basically transversal: to give methodological support in biostatistics to other research groups in the fields of biomedicine or experimental sciences; to promote the transfer of the research done at the university in biostatistics to biomedical and experimental fields; to take advantage of the strong demand for support in biostatistics to detect future research in this area, that respond to real problems in other fields.


More specific objectives are to detect problems of scientific interest in the biomedical and experimental fields where biostatistics can contribute to their resolution; conduct our own rearch in biostatistics aimed at generating results for solving the problems; create necessary computer tools and software for its implementation; and apply the proposed methods to the considered problems, helping to interpret the results and draw final conclusions, in collaboration with biomedical and experimental researchers involved.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
