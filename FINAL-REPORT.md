## FINAL REPORT
**This is the Final Report for the work done to add Greek glyphs to the Google font Arima Madurai.**
https://github.com/eellak/gsoc2018-arimamadurai

**Student :**
* Rosalie Wagner | ANRT, Nancy | [GitHub](https://github.com/RosaWagner) | [Twitter](https://twitter.com/RosaFF_Wagner)

**GSoC Mentors:**

* Emilios Theofanous | [GitHub](https://github.com/thynem) | [Twitter](https://twitter.com/emilios__)
* Irene Vlachou | [GitHub](https://github.com/irenevl) | [Twitter](https://twitter.com/irene_vlachou)
* Alexios Zavras

**Organization:**

[Open Technologies Alliance - GFOSS](https://summerofcode.withgoogle.com/organizations/4954936912117760/)

---

#### Summary with the project’s links

**Sources**
* [Repository of the GSoC18 Arima Madurai project](https://github.com/eellak/gsoc2018-arimamadurai)
* [Repository of the Google font Arima Madurai](https://github.com/NDISCOVER/Arima-Font)

**Deliverables**
* [OTF files](https://github.com/eellak/gsoc2018-arimamadurai/tree/master/01_DELIVERABLES/OTF)
* [TTF files](https://github.com/eellak/gsoc2018-arimamadurai/tree/master/01_DELIVERABLES/TTF)

**Process**
* [Journal of the process](https://github.com/eellak/gsoc2018-arimamadurai/blob/master/00_PROCESS/00_JOURNAL.md)
* [UFO files](https://github.com/eellak/gsoc2018-arimamadurai/tree/master/00_PROCESS/02_UFO)
* [Glyphs files](https://github.com/eellak/gsoc2018-arimamadurai/tree/master/00_PROCESS/01_GLYPHS)
* [Feedbacks](https://github.com/eellak/gsoc2018-arimamadurai/tree/master/00_PROCESS/05_FEEDBACKS)

---

#### Introduction

**The Project took place during the Google Summer of Code 2018.**

This project aimed to add Greek script to the Google Font [Arima Madurai](https://github.com/NDISCOVER/Arima-Font). You can see the original proposal for GSOC [here](https://github.com/eellak/gsoc2018-arimamadurai/blob/master/PROPOSAL.pdf).

Arima Madurai is a font created by Natanael Gana and Joana Correia of NDISCOVER — a Portuguese type foundry. It is a multiscripts display font with 8 weights from thin to black and have a strong calligraphic influence. It has a lot of personality so it can be recognisable in headlines or brand names uses.

Arima Madurai already supports Tamil, Malayalam and Latin scripts and I would like to add Greek extended script to the glyphset. The fact that the font already supports multi scripts is a real benefit to the project: Arima Madurai already acts in non latin typographic environment and therefore displays a large set of shapes that can be used to match the Greek glyphs with the other ones.

#### Process

You can find the repository on which I worked to add the Greek script [here](https://github.com/eellak/gsoc2018-arimamadurai).

You can find the Journal of the process [here](https://github.com/eellak/gsoc2018-arimamadurai/blob/master/00_PROCESS/00_JOURNAL.md) and take a look at the design process. You can also find the [different feedbacks](https://github.com/eellak/gsoc2018-arimamadurai/tree/master/00_PROCESS/05_FEEDBACKS) from my mentor Emilios Theofanous.

The original timeline of the project can be found [here](https://github.com/eellak/gsoc2018-arimamadurai/blob/master/TIMELINE.md).

#### Design

I had to design the two extreme weights in order to interpolate the 6 other. Those two extreme weights (Thin and Bold) represented two very different works because the thin weight was almost monolinear and the bold had very high contrasts. While the thin weight was easy to design and very stable, the bold weight was hard to balance and difficult to match with the latin.

The first phase was to find a  stress for the Greek letterform which would provide a good match with the latin while keeping that style proper to Greek script. So we kept a vertical axe as in the Latin but we broke the vertical stems of the Bold to make it dance a bit more.

From the monoliear thin to the high constrated bold, the font varies from steady to playful letterforms.

A small pangram animation, from Thin to Bold and back, demonstrating the changes of the final design that occur as weight is added:

![animation](00_PROCESS/07_SPECIMEN/arima-variable.gif)

---

### License

The fonts and related code are licensed under [Open Font License](https://github.com/NDISCOVER/Arima-Font/blob/master/OFL.txt). See `LICENSE.txt` for licensing information.
