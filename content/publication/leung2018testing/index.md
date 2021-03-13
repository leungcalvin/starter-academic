---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Testing the Weak Equivalence Principle with Optical and Near-Infrared Crab Pulses"
authors: [Leung, et al.]
date: 2020-12-14T00:16:50-08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-14T00:16:50-08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "The Weak Equivalence Principle states that the geodesics of a test particle in a gravitational field are independent of the particle's constitution. To constrain violations of the Weak Equivalence Principle, we use the one-meter telescope at Table Mountain Observatory near Los Angeles to monitor the relative arrival times of pulses from the Crab Pulsar in the optical (λ ≈ 585 nm) and near-infrared (λ ≈ 814 nm) using an instrument that detects single photons with nanosecond-timing resolution in those two bands. The infrared pulse arrives slightly before the visible pulse. Our three analysis methods give delays with statistical errors of Δt obs = 7.41 ± 0.58, 0.4 ± 3.6, and 7.35 ± 4.48 microseconds (at most 1/4000 of the pulsar period). We attribute this discrepancy to systematic error from the fact that the visible and infrared pulses have slightly different shapes. Whether this delay emerges from the pulsar, is caused by passing through wavelength-dependent media, or is caused by a violation of the equivalence principle, unless there is a fine-tuned cancellation among these, we set the first upper limit on the differential post-Newtonian parameter at these wavelengths of Δγ < 1.07 × 10−10 (3σ). This result falls in an unexplored region of parameter space and complements existing limits on equivalence-principle violation from fast radio bursts, gamma-ray bursts, as well as previous limits from the Crab."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
My first foray into serious astrophysics happened by accident when I realized that testing data from our astronomical random number generator could be used to time the Crab pulsar. This is nothing new, but I realized we could also set the first limits for equivalence principle violation for photons between visible and near-infrared light. Did we expect a violation? Of course not! To high-energy physics, optical and near-infrared photons are basically the same. There's great work on measuring the differences between radio photons and gamma ray photons, for which any deviations from equivalence would be magnified, but those kinds of measurements are subject to all kinds of pulsar timing systematics (e.g. different instruments, different clocks, plasma dispersion).
However, nobody had used optical single photon detectors to study the Crab in different bands simultaneously (work done by Naletto et al. on AQUEYE uses one broad passband), and the opportunity to perform a precise, systematic-free measurement was too good to resist. The lesson learned was that differences in the shape of the pulsar's light curve dominate phase estimation at the part-per-thousand level that we were able to resolve--and the phase delay measurement becomes strongly method-dependent.
