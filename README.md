GenLayer Animated Loading Spinner

An original animated SVG loading spinner designed for the GenLayer Portal.

Concept

The spinner represents GenLayer's decentralized validator and consensus structure through three orbiting validator elements surrounding a central flat-top hexagonal core.

The animation combines continuous orbital motion with subtle expansion and contraction of the validator layers, creating a smooth loading state that remains visually active without becoming distracting.

GenLayer Identity

The visual language is based on GenLayer's identity, particularly its geometric form and purple/violet color palette, with orange used as an accent for the inner validator layer.

The goal was to create something that feels distinctly GenLayer while remaining simple enough to work repeatedly across Portal loading states.

Animation
Outer validator rotates clockwise over 4 seconds.
Middle validator rotates clockwise over 5 seconds.
Inner validator rotates clockwise over 4 seconds.
Validator distances from the center continuously contract and expand.
The animation loops indefinitely.
The central hexagonal consensus structure remains fixed.
Implementation

The spinner is implemented as a lightweight animated SVG using native SVG elements and animation primitives such as animateTransform and animate.

This keeps the asset scalable and suitable for interface loading states without requiring raster assets.

Files
genlayer-animated-spinner/

── README.md

── genlayer-spinner.svg

Preview

The final animated spinner is available in genlayer-spinner.svg.

Purpose

Designed as a community contribution for the GenLayer Portal animated loading spinner challenge.
