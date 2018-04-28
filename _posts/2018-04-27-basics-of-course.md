---
layout: post
title:  "Basics, of course"
date:   2018-04-26 01:13:30 -0500
---

Embarking on this blog likely partial to my interest in systems, I figured I'd need a way to represent stuff. I may be a visual learner.

The basic system seems to be the most easily visualized. It's probably also the most useless. While systems generally contain inputs and outputs (flow) and stock, we'll be hardpressed to find a system lacking balancing and reinforcing loops (more about loops in a future post). 

The stock and flow representation of systems has its limits but it's a great place to start in visualizing an abstract system:

![basic_system]({{ "/images/basic_system.png" }})

Stating the obvious, inputs are those which are the steady source increasing the stock. Outputs are the steady drains of the stock. Why steady? Because in our diagram, they're unaffected by any loops influencing the rate of input/output activity. Again, more on loops in the future.

Stocks are core to understanding system dynamics. Systems operate on a quantity at their core. Consider this very simple system:

![tub_system]({{ "/images/tub_system.png" }})

The faucet serves the role of the input and the drain serves the role of the output while the water contained within the tub is our stock. The relationship between input and output determines the fluctuations of the stock. Consider a tub with a faucet that provides water at twice the rate the partially clogged drain removes it. What happens? The stock increases at a faster rate than one in which a system contains a balanced flow with congruent inputs and outputs. Similarly, a low pressure faucet with a pristine drain guarantees stock never accumulates and the tub never contains water. In the case of a shower, maybe that's perfect. A bath? Not so much. Enter balancing and reinforcing loops which adjust a system's input and output rates.

Brief note - I'm using [mermaid](mermaid) to render the above diagrams. It's working well for linear flows but we'll have to see how to get loops rendered as well. In any case, the markdown for the aforementioned renderings is below.

```
{% include basic_system.mmd %}
```

```
{% include tub_system.mmd %}
```

[mermaid]: https://mermaidjs.github.io/
