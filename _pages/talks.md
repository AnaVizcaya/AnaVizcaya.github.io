---
layout: archive
title: "Talks and posters"
permalink: /talks/
author_profile: true
---

* Ion monitoring with the KATRIN experiment (poster)
    * XXIX International Conference on Neutrino Physics (Virtual meeting 2020)
* Ion retention, blocking and monitoring within the KATRIN experiment (poster)
      * Heraeus Seminar (Bad Honnef, Germany 2019)
\item \emph{Talk:} Ion retention, blocking and monitoring within the KATRIN experiment \\APS April Meeting (Denver, USA 2019)
\item \emph{Poster:} Detecting light ions and electrons with TRIMS silicon detectors \\ XXVIII International Conference on Neutrino Physics and Astrophysics (Germany 2018)
\item \emph{Poster:} Tritium ion monitoring during KATRIN First Tritium \\ XXVIII International Conference on Neutrino Physics (Heidelberg, Germany 2018)
\item \emph{Poster:} Monitoreo del Observatorio HAWC utilizando muones verticales \\Congreso Nacional de F\'isica (M\'exico 2015)


{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
