This repository contains code examples for using the openbadge analysis libraries. In addition, it contains documentation for some of the tests and evaluations that we have done for the badges.

Folders:
* notebooks - analysis code examples, in a form of Jupiter notebooks
* data - data files for examples

Notable examples:
* notebooks/meeting_simple_plots.ipynb - loading and processing audio data from a single meeting
* notebooks/hub_proximity_example.ipynb - loading and processing proximity data from an event
* notebooks/evaluate-voice-activity-detection-for-sociometric-badge-data.ipynb - describes how the old voice-activity-detection (VAD) works. This method assumes a single speaker
* notebooks/multi-channel_VAD_illustration.ipynb - describes how the new voice-activity-detection (VAD) works. This method allows multiple speakers. Note that all other examples use the old VAD algorithm