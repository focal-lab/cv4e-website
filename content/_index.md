---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
editable: true

sections:

  - block: hero
    content:
      title: |
        Computer Vision for Ecology
      image:
        filename: stem-map.png
      text: |
        <br>
        
        Workshop at [ECCV 2024](https://eccv.ecva.net/) <br>
        Sept 30, 2024<br>
        [Recording here](https://www.youtube.com/watch?v=Qjd816N8Z6o)

  - block: markdown
    design:
      spacing:
        padding: ["50px", "50px", "50px", "50px"]
    content:
      title:
      subtitle: ''
      text: |

        <div class="container">
        <div class="row justify-content-center">
        <div class="col-xl-8">

        <br>

        The Computer Vision for Ecology workshop brought together experts to foster discussion on the automation of ecological data collection, collation, and analysis. The goal was to establish a hub for the broader computer vision and ecology community at ECCV.
        
        The workshop encompassed applications of computer vision across a wide variety of ecological systems, spanning both terrestrial and aquatic systems, diverse geographic regions, and urban to wildland settings. The workshop also made specific efforts to encompass applications of computer vision which can be deployed across both low- and high-income nations.
        <br>
        &nbsp;

        </div>
        </div>
        </div>

    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class:
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div class="container">
        <div class="row justify-content-center">
        <div class="col-xl-4">
        {{% cta cta_link="https://www.youtube.com/watch?v=Qjd816N8Z6o" cta_text="View workshop recording →" %}}
        </div>
        <div class="col-xl-4">
        {{% cta cta_link="./papers/" cta_text="View accepted papers →" %}}
        </div>
        </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['60px', '0', '30px', '0']




  - block: features
    design:
      spacing:
        padding: ['30px', '0', '60px', '0']
    content:
      title: Organizers
      subtitle: "&nbsp; <br>"
      text:
      items:
        - name: MIT
          description: |
            [Dr. Sara Beery](https://beerys.github.io/) <br>
            [Julia Chae](https://juliachae.github.io/) <br>
            [Edward Vendrow](https://edwardv.com/) <br>
          icon:
          icon_pack:
        - name: King Abdullah University
          description: |
            [Dr. Mohamed Elhoseiny](https://www.kaust.edu.sa/en/study/faculty/mohamed-elhoseiny) <br>
            [Faizan Khan](https://faixan-khan.github.io/) <br>
            [Dr. Andrew Temple](https://reefecology.kaust.edu.sa/people/details/andrew-temple) <br>
          icon:
          icon_pack: 
        - name: University of California, Davis
          description:  |
            [David Russell](https://focal-lab.org/author/david-russell/) <br>
            [Dr. Derek Young](https://focal-lab.org/author/derek-young/) <br>
          icon:
          icon_pack:
---