# e2e_experiments
A collection of [PsychoJS](https://github.com/psychopy/psychojs) experiments that serve as feature demonstrations and as end points for automated end-to-end testing. 
Each of the experiments listed below is hosted on [Pavlovia](https://pavlovia.org/)'s GitLab site, where you can find further documentation and clone them for your own purposes.

## Basic experiments
* [e2e_minimal](https://gitlab.pavlovia.org/tpronk/e2e_minimal). A minimal experiment: it presents a white square and registers a click or tap reponse.
* [e2e_polygons](https://gitlab.pavlovia.org/tpronk/e2e_polygons). Presents a series of polygons; once with straight orientation and once rotated by 5 degrees to the right.
* [e2e_img](https://gitlab.pavlovia.org/tpronk/e2e_img). Presents a series of bitmaps; once with straight orientation and once rotated by 5 degrees to the right. The first pair of bitmaps is in PNG format, while the second pair is in JPG format.
* [e2e_sound](https://gitlab.pavlovia.org/tpronk/e2e_sound). Presents a series of sounds over a background song. The sounds are synchronised with a series of images.
* [e2e_video](https://gitlab.pavlovia.org/tpronk/e2e_video). Presents a video. 
* [e2e_text](https://gitlab.pavlovia.org/tpronk/e2e_text). Presents a series of words in Turkish, Chinese, and Arabic script. Each word is presented once in Arial and once in Georgia font.
* [e2e_conditions](https://gitlab.pavlovia.org/tpronk/e2e_conditions). Reads in a CSV and XLSX conditions file and loops over them using various randomisation settings.

## Advanced experiments
* [e2e_embed_html](https://gitlab.pavlovia.org/tpronk/e2e_embed_html). Embeds an HTML web page in a PsychoJS task and stores data collected via this page. Two examples are included; one that presents a basic HTML page and one that present a [form.io](https://formio.github.io/formio.js/) form.
