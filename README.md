# CHORAS ASSA Workshop

👋 Hi all, and welcome to the repository specifically created for day 5 of the ASSA Open Research Software school! This document contains information on the workshop.

## Setup

🐒  Clone the [CHORAS repository](https://github.com/choras-org/choras) and follow the steps in the readme to install and run CHORAS.

## Task

Your task today is to simulate *this* room (yes -- the one you are currently in :) )

🎙️ Later today at 4pm we'll do a measurement and your goal is to set up a simulation which is as close as possible to the measurement! 

🏠 We provide two geometries (can also be found in the CHORAS repository so you don't have to clone this one :))
- this room simplified to a shoebox [(./Geometries/Room2215_simple.obj)](./Geometries/Room2215_simple.obj)
- the same but with the acoustic ceiling [(./Geometries/Room2215_withAbs.obj)](./Geometries/Room2215_withAbs.obj)

Your job is to use settings (such as material properties and settings in the methods used) such that you expect to get as close as possible to the measurement results. 
Note that settings in the methodology affect calculation time: Initially compromise calculation time over accuracy when making choices in the settings.

A second goal of today is to collect your feedback and ideas on this collaborative platform!

## Deliverables

Create a new repository in the [choras-org GitHub organisation](https://github.com/choras-org/). The name should be your **team name** :)

At the end of the day (4pm), the repository should contain the following:

1. 🎧  **Impulse response** from DE (.wav)

2. 📊  **T30** results from DE in (.csv)

3. 5️⃣  Frequencies of **first 5 modes** from DG in (.csv)

4. 📊   **T30** results from DG (up to the 250Hz band) in (.csv) as calculated with pyfar 

5. 🫱🏻‍🫲🏾  Document (.pdf / .docx) with:

    - **3 proposals** for improving CHORAS (out of the box ideas are welcome!)
    - Functionality **issues** you found

## Evaluation

How do we decide who is closest?

🎙️  At the end of the day we'll do an IR measurement which will be compared to your simulation

- 🧮  DE+DG IR: **RMS** of the T30 of your simulation vs. measurement

- 🙋‍♀️  DE IR: silent disco headsets + **your votes**!

- 🧮  DG modes: **RMS** of your frequencies vs. our measurement

## Useful links

- [CHORAS main repo](https://github.com/choras-org/choras)
- [Absorption coefficients](https://www.acoustic.ua/st/web_absorption_data_eng.pdf)
- [Geometries](./Geometries/)
