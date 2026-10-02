# Voxel Terrain Engine

This is a chunk-based voxel engine I built in Unity for procedural terrain generation (similar to Minecraft). It uses `FastNoiseLite` to generate Perlin and Simplex noise maps, which handle everything from world elevation to temperature and humidity. By combining these different noise maps, the engine automatically classifies and generates distinct biomes. I also set up dynamic mesh generation, so you can interactively place or destroy terrain blocks in real time.

## Features

* **Chunk-Based Rendering:** The world is divided into discrete chunks that generate and load efficiently to support large environments.
* **Dynamic Biomes:** Uses intersecting noise maps (temperature, humidity, and height) to figure out which biome to generate in a given area.
* **Real-Time Block Editing:** Rebuilds chunk meshes on the fly so you can instantly add, remove, or reshape the terrain.
* **Procedural Trees:** Automatically spawns vegetation based on the specific rules of the local biome.
* **Noise-Driven Landscapes:** Powered by `FastNoiseLite` for smooth, highly customizable terrain generation.

## Screenshots

![image](https://github.com/user-attachments/assets/c50eff13-bf53-48c7-96f4-f252c61e1da4)

![image](https://github.com/user-attachments/assets/22dfdf49-816e-4e56-9a2f-8c03cdb3fc2b)
