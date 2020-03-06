---
name: GLMC Project
tools: [Linear Algebra, OpenGL, C]
image: ../assets/img/glmc.png
description: This library is meant to be used as a C replacement for glm, with a plan of a wrapper for python.
---

# GLMC Linear Algebra Library for OpenGL in C

I started researching regarding the topics required for the project. My Linear Algebra course at university helped me a lot for the same. The concepts used in the project were simple. The most important task which was expected from this project was to get the maximum performance on the same without using alot extra memory. To give you an idea of what kind of performance was required, one particular is almost expected to run about 1,000,000 times per second.

While coding, due to speed optimization, almost all of the code was hard coded, all the functions were inlined and recursive approach was avoided at all costs to avoid segmentation faults. Alongside with that, there were many places where I let the code to have edge cases errors, becuase edge case crashes are not a major as compared to a dip in performance.

Here are all the functions, which have been implemented till now:

<p>
<ul>
    <li>Vectors 2d, 3d, 4d (vec2, vec3, vec4)
    <li>Matrices 2x2, 3x3, 4x4 (mat2, mat3, mat4)
    <li>Multiplication support between vectors and matrices.
    <li>Matrices must be column major.
    <li>Creating Scale, Translation, and Rotation Matrices.
    <li>Generation of Projection (Ortho or Perspective)
    <li>Reflection, Refraction of vectors
</ul>
</p>

<p class="text-center">
{% include elements/button.html link="https://github.com/iamarshsingh/glmc" text="Github Repo" %}
</p>