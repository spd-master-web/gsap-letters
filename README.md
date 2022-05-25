# GSAP letters

GSAP to() animates to the provided properties.
gsap.to();

GSAP from() animates from the provided properties.
gsap.from();

GSAP set() sets the target's values to the provided properties.

gsap.to("selector", {properties});

gsap.to("span", {
  duration: 1.25,
  delay: 1.35,
  stagger: .5,
  rotation: 360
});

## Timelines

const myTimeline = new gsap.timeline();