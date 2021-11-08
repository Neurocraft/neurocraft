# Neurocraft || The Microscale Neuro-engineering Platform

[**Why Microscale?**](#why-microscale)
| [**What is Neurocraft?**](#what-is-neurocraft)
| [**Install guide**](#install-guide)
| [**User Manual**](https://github.com/Neurocraft/neurocraft/wiki/User-Manual)
| [**Latest Releases**](#latest-releases)
| [**Future Plans**](#future-plans)

[![Downloads](https://img.shields.io/github/license/neurocraft/neurocraft)](LICENSE)
[![Downloads](https://img.shields.io/github/downloads/Neurocraft/Neurocraft/total)](https://github.com/Neurocraft/neurocraft/releases)

## Why Microscale?
Brain dynamics switch very rapidly between different brain states many times per second, therefore any evidence of an “abnormal brain state” during long EEG epochs is likely to be hidden amongst many other brain states and not optimally represented by a multi-second average. 

A key solution to the above is microscale network dynamics; I will specifically examine the transient brain state associated with abnormal activities (e.g. interictal epileptiform discharges, beta bursts), regarding this as a very readily available window into the abnormal brain state.

<img src="/images/Scale_comparison.gif" width="60%">
<i>Fig 1. Treating the neurological conditions with drugs is like playing the piano using a sledgehammer.</i>

## What is Neurocraft?
[Neurocraft](http://neurocraft.co.uk) is a platform featuring peer-reviewed methodology for feature extraction and modelling of electrophysiological data. Neurocraft uses ultra-high temporal brain signals to (a) decode normal brain function and (b) model respective network activity.

- **SOTA.** Powered by a wavelet coherence engine, Neurocraft is able to push the envelope with ultra-high temporal and frequency resolution of neuronal dynamics. All actions (e.g. layout, filter, drag) run in real-time.
- **Simple.** Easy to [Install](https://github.com/Neurocraft/neurocraft/wiki/Quick-Install) and [get started](https://github.com/Neurocraft/neurocraft/wiki/User-Manual). An UI that is centered around the visualization. Like Photoshop™ for brain networks.
- **Comprehensive.**  A wide variety of analytics and modelling offers thorough data exploration

  :point_right:  network evolution maps around event of interest\
  :point_right:  influence analysis of nodes/areas\
  :point_right:  propagation model for annotated brain activity


[Download Neurocraft](https://www.neurocraft.co.uk/#download) for Mac OS X and MATLAB and consult the [release notes](https://github.com/Neurognostics/neurocraft/wiki/Releases). Example datasets can be found on our [wiki](https://github.com/Neurognostics/neurocraft/wiki/Datasets).

<img src="/images/Fig1_final.png" width="100%">
<i>Fig 2. Neurocraft data flow diagram.</i>

## Install Guide

Download and [Install](https://github.com/Neurocraft/neurocraft/wiki/Quick-Install) neurocraft on your computer. 

Get started with the [Quick Start](https://github.com/Neurognostics/neurocraft/wiki/quick-install/) and follow the [User Manual](https://github.com/Neurocraft/neurocraft/wiki/User-Manual). Load a sample [dataset](https://github.com/Neurognostics/neurocraft/wiki/Datasets) and start to play with the data.

If you run into any trouble or have questions consult our [forum](https://neurocraft.talkyard.net/).

## Latest releases 

### (🚨 Warning: Unstable Prototype 🚨)
**This is a prototype package currently under heavy development. It does not currently have stable releases, and as such will likely be modified significantly in BC-breaking ways until beta release (targeting early 2022), and can only be used with directly in MATLAB or as standalone MacOsX app via a MATLAB runtime enviroment (pre-packaged inside the installer). If you have suggestions on the API or use cases you'd like to be covered, please open a github issue. We'd love to hear thoughts and feedback.**

Current version is v0.1.0-alpha.

## Troubleshooting

If you want to report any issues or bugs, we encourage you to start a discussion at our dedicated [forum](https://neurocraft.talkyard.net/), prior to opening a github issue. We are a small team of devs that work a 9-5 job besides maintaining this project.

## Prototype Usage and Feedback

We'd love to hear from and work with early adopters to shape our designs. Please reach out with your ideas and suggestions by creating a post at our dedicated [forum](https://neurocraft.talkyard.net/) if you're interested in using this tooling for your project.

## Future Plans

We hope to sufficiently expand the library, harden APIs, and gather feedback to enable a beta release early 2022.

## License

Neurocraft is CC licensed, as found in the [LICENSE](LICENSE) file.


