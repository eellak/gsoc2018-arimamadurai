## FINAL REPORT
**This is the Final Report for the work done for the project Arima-Madurai.**

**Student :** Rosalie Wagner | ANRT, Nancy | [GitHub](https://github.com/RosaWagner) | [Twitter](https://twitter.com/RosaFF_Wagner)

---

#### Summary with the project’s links

* [Journal of the process](00_PROCESS/00_JOURNAL.md)
* [Deliverables](01_DELIVERABLES) (OTF and TTF files)
* [UFO files](00_PROCESS/02_UFO)
* [Glyphs files](00_PROCESS/01_GLYPHS)

---

#### Introduction

**The Project took place during the Google Summer of Code 2018.**

This project aimed to add Greek script to the Google Font *Arima Madurai*.

Arima Madurai is a font created by Natanael Gana and Joana Correia of NDISCOVER — a Portuguese type foundry. It is a multiscripts display font with 8 weights from thin to black and have a strong calligraphic influence. It has a lot of personality so it can be recognisable in headlines or brand names uses.

You can view the original Github repository of the project [here](https://github.com/NDISCOVER/Arima-Font).

#### Process

You can find the Journal of the process [here](https://github.com/eellak/gsoc2018-arimamadurai/blob/master/00_PROCESS/00_JOURNAL.md) and take a look at the design process. You can also find the [different feedbacks](https://github.com/eellak/gsoc2018-arimamadurai/tree/master/00_PROCESS/05_FEEDBACKS) from my mentor Emilios Theofanous.

The original timeline of the project can be found [here](https://github.com/eellak/gsoc2018-arimamadurai/blob/master/TIMELINE.md).

#### Design

I had to design the two extreme weights in order to interpolate the 6 other. Those two extreme weights (Thin and Bold) represented two very different works because the thin weight was almost monolinear and the bold had very high contrasts. While the thin weight was easy to design and very stable, the bold weight was hard to balance and difficult to match with the latin.

The first phase was to find a  stress for the Greek letterform which would provide a good match with the latin while keeping that style proper to Greek script. So instead of a vertical axe as in Latin script, the bold has a sightly rotated axe.

From the monoliear thin to the high constrated bold, the font varies from steady to playful letterforms.

A small pangram animation, from Thin to Bold and back, demonstrating the changes of the final design that occur as weight is added:

![animation](00_PROCESS/07_SPECIMEN/arima-variable.gif)

---

#### GSoC Mentors:

* Alexios Zavras
* Emilios Theofanous | [GitHub](https://github.com/thynem) | [Twitter](https://twitter.com/emilios__)
* Irene Vlachou | [GitHub](https://github.com/irenevl) | [Twitter](https://twitter.com/irene_vlachou)

#### Organization:

[Open Technologies Alliance - GFOSS](https://summerofcode.withgoogle.com/organizations/4954936912117760/)

---

### License

The fonts and related code are licensed under [Open Font License](https://github.com/NDISCOVER/Arima-Font/blob/master/OFL.txt). See `LICENSE.txt` for licensing information.
