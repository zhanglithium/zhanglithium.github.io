---
# SIXUAN'S HOMEPAGE — SIMPLE EDITING AREA
# Edit the text and numbers below. Do not edit the template file.
layout: page-full-width
title: "Sixuan Zhang — Seeing the Atmosphere"
permalink: /

# 1. MAIN HOMEPAGE (left text + right picture)
hero:
  label: "RESEARCH · MAPPING · DIGITAL METHODS"
  name: "Sixuan Zhang"
  headline: "— Seeing the Atmosphere"
  lead: "Satellite observations, machine learning, and the spatial stories of air pollution."
  description: "I explore how digital methods can reconstruct and visualize historical patterns of atmospheric nitrogen dioxide (NO₂), and how those maps can inform questions about environmental inequality."
  primary_button: "Explore my research"
  secondary_link: "View DH coursework"

  # RIGHT-SIDE HOMEPAGE PICTURE — CHANGE THESE SETTINGS
  image:
    file: "/assets/img/la_triptych_omi_eon_tropomi.png"
    alt: "Triptych comparing OMI, EON, and TROPOMI NO2 over Los Angeles"
    caption: "OMI · EON · TROPOMI · Los Angeles, July 2, 2025"

    column_size: "0.95fr"       # Right column: 0.75fr = narrower, 1.3fr = wider
    width: "100%"              # Picture width INSIDE its box: e.g. 80%, 100%
    height: "auto"             # Picture height: auto, 250px, 350px (keeps box height explicit)
    max_height: "460px"        # Maximum picture height when height is auto
    frame_height: "auto"       # Exact beige frame height: auto or e.g. 380px
    frame_min_height: "330px"  # Minimum height of beige picture frame
    move_x: "0px"             # Move the entire frame right (+) or left (-)
    move_y: "0px"             # Move the entire frame down (+) or up (-)
    horizontal_align: "center" # left / center / right (picture within frame)
    vertical_align: "center"  # start / center / end
    fit: "contain"            # contain = show whole picture; cover = may crop
    position: "center"        # Only affects an image that is cropped

# 2. ABOUT SECTION
about:
  heading: "Understanding the atmosphere across scales."
  text: "My research connects satellite remote sensing and machine learning to study the spatial and historical patterns of air pollution. I am particularly interested in how observations at different resolutions shape the questions we can ask about cities and communities."
  link_text: "More about my work"

# 3. RESEARCH SECTION
research:
  heading: "Seeing NO₂ over Los Angeles"
  introduction: "My current project uses EON to reconstruct finer-scale NO₂ over Los Angeles and examine how pollution inequality changes across time. The figures below move from satellite observation and reconstruction to long-term inequality analysis."
  triptych:
    file: "/assets/img/la_triptych_omi_eon_tropomi.png"
    alt: "Triptych showing OMI observation, EON reconstruction, and TROPOMI observation over Los Angeles"
    title: "OMI, EON, and TROPOMI over Los Angeles."
    caption: "This triptych shows how EON reconstructs finer spatial detail between coarse OMI observations and high-resolution TROPOMI observations."
  inequality_figures:
    - file: "/assets/img/la_relative_inequality_2004_2025.png"
      alt: "Relative NO2 inequality over Los Angeles from 2004 to 2025 for poverty and income-race inequality"
      title: "Relative NO₂ inequality, 2004–2025."
      caption: "Relative poverty inequality and income-race inequality both increase over time, while annual mean NO₂ declines."
    - file: "/assets/img/la_race_ethnicity_relative_inequality_2004_2025.png"
      alt: "Race and ethnicity relative NO2 inequality over Los Angeles from 2004 to 2025"
      title: "Race and ethnicity relative NO₂ inequality, 2004–2025."
      caption: "Relative inequality remains positive for all four groups compared with non-Hispanic White residents."
  research_cards:
    - heading: "Historical NO₂ Reconstruction"
      text: "EON learns from OMI and TROPOMI to reconstruct finer-scale NO₂ patterns for earlier years when only coarser observations were available."
    - heading: "Urban Air Pollution"
      text: "The Los Angeles case study highlights strong within-city variability, especially in central and eastern parts of the basin."
    - heading: "Environmental Inequality"
      text: "Using fixed 2020 tract boundaries and demographics, I compare long-term NO₂ inequality across poverty, income-race, and race/ethnicity groupings."
  method_note: "Method note: 2004 covers October–December only. The long-term inequality figures use fixed 2020 tract boundaries and demographics. The dashed line in the inequality plots shows annual mean EON NO₂ TVCD, not population-weighted NO₂."

# 4. DIGITAL HUMANITIES SECTION
dh_practice:
  heading: "Digital methods and critical making"
  text: "My digital humanities practice asks not only what a tool can produce, but also how its data, assumptions, and interfaces shape what becomes visible."
  topics:
    - "Digital Mapping"
    - "Text Analysis"
    - "Critical Making"
    - "Data & Archives"
  note: "Selected class exercises and reflections are collected in the coursework section of this site."

# 5. COURSEWORK CARD + FOOTER
coursework:
  label: "DH 8991 · INTRODUCTION TO DIGITAL HUMANITIES"
  heading: "Coursework & reflections"
  text: "Blog posts, critical readings, an annotated bibliography, and practical experiments from the course are collected in a separate space."
  button: "Open coursework"
footer:
  left: "Sixuan Zhang · Seeing the Atmosphere"
  right: "Built with CB-Essay and GitHub Pages"
---

{% include portfolio/home.html %}
