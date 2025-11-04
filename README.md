# CHORAS ASSA Workshop

👋 Hi all, and welcome to the repository specifically created for day 5 of the ASSA Open Research Software school! This readme contains information on the workshop.

## Setup

🐒  Clone the [CHORAS repository](https://github.com/choras-org/choras) and follow the steps in the readme to install and run CHORAS.

## Task

Your task is to model *this* room (yes -- the one you are currently in :) )

🎙️ Later today we'll do a measurement and your goal is to set up a simulation which is as close as possible to the measurement! 

🏠 We provide two geometries
- this room simplified to a shoebox [(./Geometries/Room2215_simple.obj)](./Geometries/Room2215_simple.obj)
- the same but with the acoustic ceiling [(./Geometries/Room2215_withAbs.obj)](./Geometries/Room2215_withAbs.obj)

Your job is to tweak the settings such that you get as close as possible to the measurement.

## Deliverables

Create a new repository in the [choras-org GitHub organisation](https://github.com/choras-org/). The name should be your **team name** :)

The repository should contain the following:

1. 🎧  **Impulse response** from DE (.wav)

2. 📊  **T30** results from DE in (.csv)

3. 5️⃣  Frequencies of **first 5 modes** in (.csv)

4. 🫱🏻‍🫲🏾  Document (.pdf / .docx) with:

  - **3 proposals** for improving CHORAS (out of the box)
  - Functionality **issues** you found

## Evaluation

How do we decide who is closest?

🎙️  At the end of the day we'll do an IR measurement which will be compared to your simulation

- 🧮  DE IR: **RMS** of the T30 of your simulation vs. measurement

- 🙋‍♀️  DE IR: silent disco headsets + **your votes**!

- 🧮  DG modes: **RMS** of your frequencies vs. our measurement

## Useful links

- [CHORAS main repo](https://github.com/choras-org/choras)
- [Absorption coefficients](https://www.acoustic.ua/st/web_absorption_data_eng.pdf)
- [Geometries](./Geometries/)
