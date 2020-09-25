# e2e_experiments
A collection of experiments that serve as demos (prefixed demo_) and end points for automated end-to-end testing scripts (prefixed e2e_). These experiments were originally developed for [PsychoJS](https://github.com/psychopy/psychojs), but most are compatible with [PsychoPy](https://github.com/psychopy/psychopy) as well.

The table below lists the collection. For each experiment, it lists:
* **Name.** Its name
* **Description.** A brief description
* **GitLab.** A link to its [Pavlovia GitLab](https://gitlab.pavlovia.org) repo
* **Demo.** A link to an online demo
* **PsychoPy.** Whether it also works on PsychoPy

NB - Unless otherwise mentioned, the experiments are compatible with desktop/laptop computers, registering click responses, and with mobile (smartphones/tables), registering tap responses.

Name | Description | GitLab | Demo | PsychoPy 
:--- | :--- | :---: | :---: | :---:
demo_buttons | Presents a couple of polygons that light up when clicked on. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_buttons) | [Demo](https://run.pavlovia.org/tpronk/demo_buttons) | Yes 
demo_embed_html | Embeds a web page in a PsychoJS task and stores data collected via this page. Two examples are included; one that presents a basic HTML page and one that present a [form.io](https://formio.github.io/formio.js/) form. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_embed_html) | [Demo](https://run.pavlovia.org/tpronk/demo_embed_html/html) | No 
demo_expose_js | Exposes a couple of PsychoJS stimuli to the global namespace, so that they can be accessed via a web-browser console. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_embed_html) | [Demo](https://run.pavlovia.org/tpronk/demo_embed_html/html) | No 
demo_eye_tracking | Demonstrates eye tracking via a webcam using the [webgazer](https://webgazer.cs.brown.edu/) library. Not supported on mobile yet. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_eye_tracking) | [Demo](https://run.pavlovia.org/tpronk/demo_eye_tracking) | No 
demo_refresh_rate | Measures and reports the refresh rate of your browser. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_refresh_rate) | [Demo](https://run.pavlovia.org/tpronk/demo_refresh_rate). | No 





teaching demonstrations, experiment templates, and advanced demonstration. Some of these experiments also serve as (i.e. for testing whether PsychoJS works on all kinds of different devices, operating systems, and web-browsers).

For each experiment, I list (1) a, where you can find further documentation and clone them for your own purposes; and (2) a link to a demo that you can run in your web-browser.

## Teaching demonstrations
These are basic demonstrations of PsychoPy/PsychoJS components.
* **e2e_minimal.** A minimal experiment: it presents a white square and registers a click or tap reponse. [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_minimal), [Demo](https://run.pavlovia.org/tpronk/e2e_minimal/html/)
* **e2e_polygons.** Presents a series of polygons; once with straight orientation and once rotated by 5 degrees to the right. [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_polygons), [Demo](https://run.pavlovia.org/tpronk/e2e_polygons/html)
* **e2e_buttons.** P
* **e2e_img.** Presents a series of bitmaps; once with straight orientation and once rotated by 5 degrees to the right. The first pair of bitmaps is in PNG format, while the second pair is in JPG format. [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_img), [Demo](https://run.pavlovia.org/tpronk/e2e_img/html)
* **e2e_sound.** Presents a series of sounds over a background song. The sounds are synchronised with a series of images. [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_sound), [Demo](https://run.pavlovia.org/tpronk/e2e_sound/html)
* **e2e_video.** Presents a video. [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_video), [Demo](https://run.pavlovia.org/tpronk/e2e_video/html)
* **e2e_text.** Presents a series of words in Turkish, Chinese, and Arabic script. Each word is presented once in Arial and once in Georgia font. [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_text), [Demo](https://run.pavlovia.org/tpronk/e2e_text/html)
* **e2e_conditions.** Reads in a CSV and XLSX conditions file and loops over them using various randomisation settings. [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_conditions), [Demo](https://run.pavlovia.org/tpronk/e2e_conditions/html)
* **e2e_map_key.** Registers a keyboard response and show which key was pressed. [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_map_key/), [Demo](https://run.pavlovia.org/tpronk/e2e_map_key/)

## Experiment templates
*No templates yet*

## Advanced demos
* **e2e_embed_html.** 

