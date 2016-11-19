# Docker SMPPSim
Dockerized(Containerized) SMPPSim server

### Usage
You can simply run the server as follows

```bash
docker run -d -p 8088:88 -p 2775:2775 -p 2776:2776 antenehrepos/docker-smppsim
```

Or 

Build and run the image from the docker file with docker command like so
```bash
docker build -t docker-smppsim
docker run -d -p 8088:88 -p 2775:2775 -p 2776:2776 docker-smppsim
```

Or

You can use docker-compose in this repo to just build and run SMPPSim.

### Copyright and license
    A docker image to run SMPPSim server

    Copyright (C) 2016, Anteneh Aklilu

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see http://www.gnu.org/licenses/.
    
[![](https://images.microbadger.com/badges/image/antenehrepos/docker-smppsim.svg)](https://microbadger.com/images/antenehrepos/docker-smppsim "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/antenehrepos/docker-smppsim.svg)](https://microbadger.com/images/antenehrepos/docker-smppsim "Get your own version badge on microbadger.com")
