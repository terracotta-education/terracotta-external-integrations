# terracotta-external-integrations
This repository contains illustrations of how custom web activities can integrate with [Terracotta](https://terracotta.education).

## Overview
Terracotta provides a flexible LTI (Learning Tools Interoperability) integration that allows custom web activities to be embedded within learning management system (LMS) assignments. Detailed configuration instructions are available on the [Terracotta Knowledge Base](https://terracotta-education.atlassian.net/wiki/spaces/TC/overview).

## Examples
* [minimal_example.html](./minimal_example.html) - The minimal example of how to configure a custom web activity. This example receives a launch_token and anonymous_id from URL parameters, presents a single math question, and returns the user's score back to Terracotta when the user clicks to submit.
* [jspsych_example.html](./jspsych_example.html) - A minimal example of how to configure a jsPsych experiment. This example implements a (very short!) visual _n_-back task, and upon completion, displays the results to the user, with a final button to send credit back to the LMS gradebook.
