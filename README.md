# Docker SMPPSim
Dockerized(Containerized) SMPPSim server

You can build and run the image with docker command as
```bash
docker build -t docker-smppsim
docker run -d -p 8088:88 -p 2775:2775 -p 2776:2776 docker-smppsim
```

Or
You can use docker-compose in this repo to just build and run SMPPSim.
