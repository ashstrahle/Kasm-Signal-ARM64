# Kasm-Signal-ARM64
**Signal ARM64 Client** for Kasm (Ideal for Raspberry Pi)

Containerised Signal client, streamed to your browser

![](/docs/screenshot1.png)

![](/docs/screenshot2.png)


This repository creates a custom Kasm Signal ARM64 Discord client image.

## Installation

- Run the following to create the required Docker image:

      docker build -t signal -f Dockerfile .

- Create the Kasm image as per below:

![](/docs/screenshot3.png)

- Be sure to configure **Persistent Profile Path** so that user details are saved.

Enjoy!