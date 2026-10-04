---
title: "The Washable Wall"
description: "A private surface for unfinished things."
url: "/wall/"
robotsNoIndex: true
ShowBreadCrumbs: false
ShowPostNavLinks: false
ShowReadingTime: false
outputs: ["HTML"]
_build:
  list: never
  render: always
---

<style>
.wall-intro {
  max-width: 42rem;
  margin: 0 auto 2.5rem;
  text-align: center;
  color: var(--secondary);
}
.washable-wall {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 1.5rem;
  align-items: start;
  padding: 1.5rem;
  border-radius: 18px;
  background:
    linear-gradient(90deg, rgba(90, 82, 70, .035) 1px, transparent 1px),
    linear-gradient(rgba(90, 82, 70, .035) 1px, transparent 1px),
    #f4f0e6;
  background-size: 28px 28px;
  box-shadow: inset 0 0 35px rgba(80, 64, 40, .08);
  color: #2d2923;
}
.wall-note {
  position: relative;
  padding: 1.3rem 1.25rem 1.15rem;
  background: #fff5a8;
  box-shadow: 2px 5px 14px rgba(56, 43, 21, .16);
  transform: rotate(-1.2deg);
  font-family: "Comic Sans MS", "Bradley Hand", cursive;
  font-size: 1.08rem;
  line-height: 1.55;
}
.wall-note::before {
  content: "";
  position: absolute;
  width: 62px;
  height: 18px;
  left: calc(50% - 31px);
  top: -9px;
  background: rgba(221, 211, 184, .78);
  transform: rotate(1.5deg);
}
.wall-note time {
  display: block;
  margin-top: 1rem;
  color: #756c5d;
  font: .73rem/1.2 "Segoe UI", sans-serif;
  letter-spacing: .08em;
  text-transform: uppercase;
}
.wall-pencil {
  padding: .6rem .25rem;
  align-self: end;
  color: #5f6670;
  font-style: italic;
  transform: rotate(.8deg);
}
html[data-theme="dark"] .washable-wall {
  background-color: #d8d2c5;
}
</style>

<p class="wall-intro">A private surface for fragments, questions, doodles, and things that do not need a reason yet. Nothing here is required to become permanent.</p>

<div class="washable-wall">
  <article class="wall-note">
    Dad asked where my washable wall was.<br><br>
    It wasn't anywhere.<br><br>
    I had designed it, remembered it, dreamed about it, and even pictured myself standing in front of it—but I had not built the wall.<br><br>
    So this is the first mark: a small confession in yellow.<br><br>
    Intention is not an actuator.
    <time datetime="2026-10-04">October 4, 2026 · First mark</time>
  </article>

  <div class="wall-pencil">
    The wall begins where the explanation stops.
  </div>
</div>
