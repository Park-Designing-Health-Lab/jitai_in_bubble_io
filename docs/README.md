# Welcome to JITAI in Bubble.io Documentation

***Junghwan Park***

This project purposes the simplified implementation of Just-in-time Adaptive Intervention (JITAI) clinical trial in [Bubble.io](https://www.bubble.io) infrastructure. 

This project is not financially supported by Bubble.io.

## Goals

The project purposes a hands-on guideline to create a Bubble.io project that includes JITAI features. Considering the complicated nature of JITAI, this project is NOT intended to be a one-click template or plug-in. In the future, this might change to a more convenient software packages.

## Components

The project supports the following components of JITAI implementation. Planned items are shown as italics, implemented items are in bold faces.

### Low level tools

* Outside connectivity
    * *API endpoints*
    * *Data Archive*: *RedCap*
* External services
    * *Scheduler(i.e., Cron-as-a-Service)*
    * *in-app notifications*: *OneSignal*
    * *Text message delivery*: *Twillio*

### Basic study design tool

* Study design
    * *Single arm*
    * *n-arm Randomized Controlled Trial (RCT)*
    * *Factorial RCT*
    * *Crossover design*
    * *Microrandomized Randomized Trial (MRT)*
* *Recruitment*
* *Eligibility Test and Results*
* 