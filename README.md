# psychojs_experiments
## Introduction
A collection of experiments that serve as demos (prefixed demo_) and end points for automated end-to-end testing scripts (prefixed e2e_). These experiments were originally developed for [PsychoJS](https://github.com/psychopy/psychojs), but most are compatible with [PsychoPy](https://github.com/psychopy/psychopy) as well.

The demos can be useful examples for learning how to use a particular PsychoJS/PsychoPy component. The e2e end points can be useful starting points at well, though they contain some additional code components for interacting with testing scripts. Unless otherwise mentioned, the experiments are compatible with desktop/laptop computers, registering click responses, and with mobile (smartphones/tables). 

The table below lists the collection. For each experiment, it lists:
* **Name.** Its name
* **Description.** A brief description
* **GitLab.** A link to its [Pavlovia GitLab](https://gitlab.pavlovia.org) repo
* **Demo.** A link to an online demo on [Pavlovia](pavlovia.org)
* **PsychoPy.** Whether it also works on PsychoPy

## Collection
Name | Description | GitLab | Demo | PsychoPy 
:--- | :--- | :---: | :---: | :---:
demo_buttons | Presents a couple of polygons that light up when clicked on. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_buttons) | [Demo](https://run.pavlovia.org/tpronk/demo_buttons/html) | Yes 
demo_embed_html | Embeds a web page in a PsychoJS task and stores data collected via this page. Two examples are included; one that presents a basic HTML page and one that present a [form.io](https://formio.github.io/formio.js/) form. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_embed_html) | [Demo](https://run.pavlovia.org/tpronk/demo_embed_html/html) | No 
demo_expose_js | Exposes a couple of PsychoJS stimuli to the global namespace, so that they can be accessed via a web-browser console. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_expose_js) | [Demo](https://run.pavlovia.org/tpronk/demo_expose_js/html/) | No 
demo_eye_tracking | Demonstrates eye tracking via a webcam using the [webgazer](https://webgazer.cs.brown.edu/) library. Not supported on mobile yet. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_eye_tracking) | [Demo](https://run.pavlovia.org/tpronk/demo_eye_tracking) | No 
demo_map_key | Registers a keyboard response and shows which key was pressed | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_map_key/) | [Demo](https://run.pavlovia.org/tpronk/demo_map_key/) | Yes
demo_refresh_rate | Measures and reports the refresh rate of your web-browser. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_refresh_rate) | [Demo](https://run.pavlovia.org/tpronk/demo_refresh_rate) | No 
demo_sound | Presents a series of sounds over a background song. The sounds are synchronised with a series of images. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_sound) | [Demo](https://run.pavlovia.org/tpronk/demo_sound/html) | Yes
demo_video | Presents a video with a soundtrack. | [GitLab](https://gitlab.pavlovia.org/tpronk/demo_video) | [Demo](https://run.pavlovia.org/tpronk/demo_video/html) | No
e2e_calibration | Registers a series of clicks and outputs their coordinates via html.data-report. This experiment used to calibrate PointerMove Actions via WebDriver and Appium. | [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_calibration) | [Demo](https://run.pavlovia.org/tpronk/e2e_calibration) | No
e2e_conditions | Reads in a CSV and XLSX conditions file and loops over them using various randomisation settings. | [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_conditions) | [Demo](https://run.pavlovia.org/tpronk/e2e_conditions/html) | Yes
e2e_img | Presents a series of bitmaps; once with straight orientation and once rotated by 5 degrees to the right. The first pair of bitmaps is in PNG format, while the second pair is in JPG format. | [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_img) | [Demo](https://run.pavlovia.org/tpronk/e2e_img/html) | Yes
e2e_polygons | Presents a series of polygons; once with straight orientation and once rotated by 5 degrees to the right. | [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_polygons) | [Demo](https://run.pavlovia.org/tpronk/e2e_polygons/html) | Yes
e2e_slider | Presents a slider. | [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_slider) | [Demo](https://run.pavlovia.org/tpronk/e2e_slider) | Yes
e2e_text | Presents a series of words in Turkish, Chinese, and Arabic script. Each word is presented once in Arial and once in Georgia font. | [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_text) | [Demo](https://run.pavlovia.org/tpronk/e2e_text/html) | Yes
e2e_textbox | Presents an editable textbox and shows the text that was typed in. | [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_textbox) | [Demo](https://run.pavlovia.org/tpronk/e2e_textbox/html) | Yes
e2e_video | Presents video that consists of a green square without sound. | [GitLab](https://gitlab.pavlovia.org/tpronk/e2e_video) | [Demo](https://run.pavlovia.org/tpronk/e2e_video) | No
