This repository will follow the journey of implementing a decentralized communication platform based on the Matrix stack.

Self-hosted on a Raspberry Pi 5 handling all the essential components, it will feature Synapse as the main server on the back-end, PostgreSQL as DB (faster performance), Caddy for reverse-proxy and ssl (let's encrypt).
The whole platform is going to be containerized and the deployment process is going to be automated using CI/CD.
To address perfomance issues, I'm going to monitor it using the Prometheus stack.

My main goal is to achieve an instant messaging platform for personal-use (but eventually scalabe, for corporates scenarios), without giving up privacy.
This is possible thanks to the Matrix protocol, an open standard network ideal as a decentralized way to handle messages, voice and video calls.
I'm going to use docker not only to make the best out of the Pi 5 resources but also to eventually migrate on a bigger cloud or local server. Also, it enables the use of CI/CD which is alway better for integrity and easy mantainance.

##diagram todo





