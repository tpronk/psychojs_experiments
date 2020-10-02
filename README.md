# psychojs_experiments
## Introduction
A collection of experiments that serve examples for learning how to use a particular PsychoJS/PsychoPy component. These experiments were originally developed for [PsychoJS](https://github.com/psychopy/psychojs), but most are compatible with [PsychoPy](https://github.com/psychopy/psychopy) as well. Unless otherwise mentioned, the experiments are compatible with desktop/laptop computers, registering click responses, and with mobile (smartphones/tables). Besides these demos, there is a collection of experiments built for automated testing. An overview of these experiments van be found in the [e2e_robot repository](https://github.com/tpronk/e2e_robot/blob/master/README.md#overview-of-tests)

## Overview of experiments
The table below lists the collection. For each experiment, it lists:
* **Name.** Its name
* **Description.** A brief description
* **GitLab.** A link to its [Pavlovia GitLab](https://gitlab.pavlovia.org) repo
* **Demo.** A link to an online demo on [Pavlovia](pavlovia.org)
* **PsychoPy.** Whether it also works on PsychoPy

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
