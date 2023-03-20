# play-with-ray
Experimenting with the ray project - Ray is a unified framework for scaling AI and Python applications. Ray consists of a core distributed runtime and a toolkit of libraries (Ray AIR) for accelerating ML workloads.



## To give it a try:
clone the repo, cd and run:

```bash
docker run -it --memory="28g" --memory-swap="30g"  -p 8888:8888 --mount type=bind,source=$(pwd),target=/home/jovyan adipolak/ml-with-apache-spark
```

This repo is based on the [Ray quickstart guide](https://docs.ray.io/en/latest/ray-overview/getting-started.html). 
