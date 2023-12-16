---
title: "Obsidian - A Pet Project Raytracer implemented in Rust and Vulkan"
date: 2021-04-21
draft: false
type: "post"
---

### Obsidian 
Whitted Raytracer written in Rust using the Vulkan compute API

Look at the [source](https://github.com/akash-melachuri/obsidian).

![image3](/images/obsidian/image3.png)

This is a project I worked on to learn more about raytracing techniques, Rust,
and Vulkan. 

## Some notes

**Disclaimer**: The below notes are several years old and are likely (definitely) out of date.

This raytracer only renders spheres, as I've only implemented the ray-sphere
intersection. Some potential future features could be ray-triangle
intersections and handling refraction. However due to the immaturity of Rust
and the available Vulkan bindings, it was pretty difficult to actually use
Vulkan's compute API. For this reason, if I were to implement a more
fully-featured whitted raytracer, I'd likely just use C++ for the more
established ecosystem of libraries and tools. Rust is a great programming
language, but it still seems to be a little rough around the edges in certain
niche areas.

## Reflections

![image](/images/obsidian/image.png)


## Materials

![image2](/images/obsidian/image2.png)
