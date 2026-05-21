---
title: "Sentry Turret (May 2023 - April 2024)"
header:
  teaser: /assets/images/Sentry-Turret/banner.png
excerpt: A recreation of the turret from the Portal franchise. To maximize safety when handling and displaying the device, the .223 bullets (as shown in the franchise) were replaced with 2,000 V tasers.
order: 5
share: false
toc: true
toc_sticky: true
no_link_icon: false
---

<style>
td, th {
   border: none!important;
}
</style>

This project started as a fun side project during summer 2023. However, it was left in the unfinished projects folder once fall started. Unexpectedly, more effort was put into the design after being told about a project competition. Unfortunately, finishing the project in less than a week and a half was an impossible task. I then realized how little I had left to do and finished in spring 2024. After a couple of design iterations, I collaborated with Alvaro Lazaro Aguilar, a close friend from the USF Rocketry club, to include tasers and remote control in the design.

## Overview

![render1]({{ site.baseurl }}/assets/images/Sentry-Turret/render1.jpg){:width="75%"}{: .align-center}
<figcaption>Stowed configuration.</figcaption>{: .text-center}

![render2]({{ site.baseurl }}/assets/images/Sentry-Turret/render2.jpg){:width="75%"}{: .align-center}
<figcaption>Extended configuration.</figcaption>{: .text-center}

The turret has two configurations: stowed and extended. Similarly to the sentry turret character from Portal, the turret is stationary and can rotate along the z-axis. The movements are controlled by two independent 25 kg·cm servos. Servo-A controls the yaw and Servo-B controls the degree of deployment of the lateral wings.

## Demonstration

{% include video id="7K9JwKkkMXM" provider="youtube" caption="Finalized product (May 2024)." %}

<br />

{% include video id="UxmOcU_ZvJc" provider="youtube" caption="Render before taser design (August 2023)." %}

<br />

{% include video id="A9G9jy3HQnY" provider="youtube" caption="First demo (June 2023)." %}

<br />

## Mechanical Design and Assembly

![assembly1]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/1.png){: .align-center}|![assembly4]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/4.png){: .align-center}

<figcaption>Core of extension mechanism.</figcaption>{: .text-center}

<br />

![assembl2]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/2.png){: .align-center}|![assembl32]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/3.png){: .align-center}

<figcaption>Gears and rack in action.</figcaption>{: .text-center}

<br />

![assembly5]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/5.png){: .align-center}|![assembly6]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/6.png){: .align-center}

<figcaption>Servo housing for yaw control.</figcaption>{: .text-center}

<br />

![assembly7]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/7.png){: .align-center}|![assembly8]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/8.png){: .align-center}

<figcaption>Yaw rotation in action.</figcaption>{: .text-center}

<br />

![assembly9]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/9.png){: .align-center}|![assembly10]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/10.png){: .align-center}

<figcaption>Wing and taser connection.</figcaption>{: .text-center}

<br />

![assembly11]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/11.png){: .align-center}|![assembly12]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/12.png){: .align-center}

<figcaption>Main body mounting.</figcaption>{: .text-center}

<br />

![assembly13]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/13.png){: .align-center}|![assembly14]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/14.png){: .align-center}

<figcaption>Eye integration (tape).</figcaption>{: .text-center}

<br />

![assembly15]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/15.png){: .align-center}|![assembly16]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/16.png){: .align-center}

<figcaption>Legs and main structural support.</figcaption>{: .text-center}

<br />

![assembly18]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/18.png){: .align-center}|![assembly19]({{ site.baseurl }}/assets/images/Sentry-Turret/assembly/19.png){: .align-center}

<figcaption>Mirrored wing and full assembly.</figcaption>{: .text-center}

<br />

## Electronics Incorporation
