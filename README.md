Hi all, and welcome to the repository specifically created for day 5 of the ASSA Open Research Software school! This readme contains instructions on how to install and run CHORAS on your machine.

## Setup instructions (please note that your computer might restart during this process!!)

1. Download [Docker Desktop](https://www.docker.com/products/docker-desktop/)
   _(If you’re on Windows and you’re unsure whether you need amd64 or arm64, go to Settings → System → About. It will say "x64-based processor" for AMD, or "ARM-based processor" for an ARM chip.)_

- Install using the default settings.
- Open Docker Desktop (the application must be running for CHORAS to work).
- When prompted to sign in/up, you can click **Continue without signing up** or **Skip**.
- If Docker Desktop tells you that WSL needs updating, please click Restart.
  - If this doesn’t work for some reason, open your favourite command window and run

        wsl --update

  - Once you see something like the image below, Docker is running and you can continue with the step 2.

    <img width="1384" height="834" alt="docker" src="https://github.com/user-attachments/assets/90cdb036-374f-4cd4-ad04-e0fd372403b8" />

2. Open your favourite command window

- Navigate to this repository:

       cd <your/path/to/DockerCHORAS>

- Run:

      docker compose up

3. Once the process is done, navigate to [http://localhost:5173](http://localhost:5173)

- Once you see this, CHORAS is running!

<img width="446" height="236" alt="choras" src="https://github.com/user-attachments/assets/f21f65f0-c667-4534-81cf-ac37d0fa36f1" />

4. Try to set up a simulation and view the results! (this includes many steps, so ask questions when necessary :)) Tip: start with the **MeasurementRoom.obj** and choose **Upholstered concert chairs** as a material for all surfaces!

## Useful links

- [CHORAS main repo](https://github.com/choras-org/choras)
