---
title: "Revisiting my Vulkan renderer"
date: 2023-12-20T16:43:53-05:00
draft: false
type: "post"
---

I've decided to revisit my old vulkan renderer/graphics engine. I originally
had a goal of writing a game engine as best as I could, but I eventually moved
on to other projects and career interests.

While I was able to render some basic OBJ models, by following the Vulkan
[tutorial](https://vulkan-tutorial.com/), I definitely felt like my grasp on
the API was thin. That's why I've decided to revisit my old renderer and
Vulkan, and try my best to implement and render some cool computer graphics.
This time around, I am downscaling the scope to simply a renderer built for the
sole purpose of learning Vulkan. No grand plans, just an educational project.
I've found that projects I prioritized for learning have been my most
successful ones (from my perspective).

This week, I went ahead and fixed my faulty model loader using
[assimp](https://assimp.org/). Now, I can finally render the famous
[Sponza](https://www.intel.com/content/www/us/en/developer/topic-technology/graphics-research/samples.html)
model from Intel! For now, I am only loading and rendering with the diffuse
textures. In the coming days, I plan on working to render this model with all
the graphics techniques needed to make it look great: diffuse and specular
lighting, normal mapping, etc. There is still a lot to do before it looks any
good, but for now, here are some photos and a link to the
[source](https://github.com/akash-melachuri/Ash).

![sponza1](/images/revisitingvulkan/sponza1.png)
![sponza2](/images/revisitingvulkan/sponza2.png)
