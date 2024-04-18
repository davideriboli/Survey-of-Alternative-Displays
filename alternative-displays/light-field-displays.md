# Light-field Displays

* Light Field Labs Solidlight
* Avalon Holographics
* Fovi3D
* Others

Light-field displays are a specialized subset of display technologies that offer some unique capabilities over lenticular and multiview displays. They tend to use a lot of individual light elements that are able to cast a dense amount of light rays that will allow you to get a full parallax view of 3D content.&#x20;

Some general things to know about light-field displays:

* They have a lot of specialized optical elements - instead of thinking in pixels, you're thinking more in individual elements that are casting lots of individual rays. Think of it like having dozens or hundreds of individual video projectors pointed towards a viewer, each with their own unique image.
* Having all of these individual elements often means they need a lot of power, but that doesnt necessarily result in more brightness since the light is so spread out.&#x20;
* Since they are effectively driving hundreds of projectors, that means the computation required to drive even a small desktop monitor sized panel can be orders of magnitude more pixels than others
* Due to their ability to guide light in space and modular display element nature, they can theoretically be seamlessly tiled to larger sizes (like LED panels)more easily than LCD screens.
* Related to all of the above, most of these are for specialized applications (think medical or military) OR incredibly expensive, even in the commercial sense.

They are incredibly impressive displays that can promise true depth and making an image float out in space, but they are still very early in their journey to be commercially viable. Very few of them have been demonstrated publically, but in the next few years there will probably be more and more of them appearing.

### Light Field Labs Solidlight Display

[Light Field Lab](https://lightfieldlab.com)

{% embed url="https://vimeo.com/622893790" %}
[https://www.lightfieldlab.com/press-release-oct-2021](https://www.lightfieldlab.com/press-release-oct-2021)
{% endembed %}

Light Field Labs announced their Solidlight display in 2021. A commercial product or a demo that isn't hidden behind other material, has not yet appeared, but they do claim the ability to tile multiple units together so that very large displays can be created. The display they will offer will be approximately 28" as a single unit. Similar to other displays on this list, they also have a custom software rendering pipeline called WaveTracer so that 3D scenes can be ported and rendered on their display.

Here is the [closest to a more complete description](https://www.ibc.org/features/the-holodeck-emerges-into-the-light/8357.article) of how the technology works:

> Light Field Lab’s basic technology, branded SolidLight, is a 28in panel that is able to output 2.5 billion pixels, or more than 10 billion pixels per square metre. &#x20;
>
> “It is doing this at full P3 colour space in a way that has not been possible until now,” he says. “Just one of these panels by itself is already the highest resolution display that has ever been designed.”&#x20;
>
> Each panel packs a proprietary FPGA, GPUs, wall and display controllers. In front of that is the key innovation of a ‘nano particle polymer surface energy relay’. “This gives us the opportunity to form a singular continuous wavefront composed of cones of light,” he explains. &#x20;
>
> The wavefront contains amplitude based on patterns and frequencies that is being modulated by a phase guide that sits on top of the polymer surface. &#x20;
>
> “The phase guide control plane is what allows us to converge the amplitude into a focal region,” he says. “In order for anything to exist as a true wavefront you need extremely high density sampling to generate billions and billions of photons.”&#x20;
>
> Since it is modular and bezel-less, these panels can be combined to form video walls of any size with configurations exceeding hundreds of billions of pixels.&#x20;

To put 2.5 Billion pixels in context: a standard 4K display is 3840x2160 which comes out to 8,294,400 pixels, and an 8K display is 33,177,600 pixels. So packing 2.5 billion pixels into a 28" panel (if that is truly what they are doing) is an incredibly dense display.



### Fovi3D

[Fovi3D](https://www.fovi3d.com/activehogel) is another unreleased experimental technology using microLED displays, spatial light modulators and a lot of other custom electronics, software and optics to create a sense of depth.

> FoVI3D’s ActiveHogel™ is a frameless, tileable, spatial light modulator designed to accommodate large format light-field displays (LfD).

{% embed url="https://www.youtube.com/watch?v=J-ImjtBFa0w" %}

Further resources from FoVi

* [https://github.com/TLBurnett3/LightField](https://github.com/TLBurnett3/LightField) - Tools for evaluating light-field radiance images
* [2019 Technical Deep dive PDF](https://www.arch.tamu.edu/app/uploads/2021/10/FoVI3D\_DeepDrive.pdf) on light-field imaging

### Multi Lens Display

I'm not sure if this truly fits in the light field category, but it feels close enough in operating principle. This experiment from around 2010 by [Hideki Kakeya](https://opg.optica.org/oe/fulltext.cfm?uri=oe-20-23-25902\&id=244861) utilizes a display that shows multiple angles of some 3D content and an array of microlenses to provide multiple glasses-free angles of that content. [More information here](https://scholar.google.co.jp/citations?user=o8t3EQgAAAAJ\&hl=en).

{% embed url="https://youtu.be/xLWf2P6d8cg" %}

A similar[ experiment from NVIDIA](https://research.nvidia.com/publication/2017-11\_near-eye-light-field-holographic-rendering-spherical-waves-wide-field-view) is below:

{% embed url="https://www.youtube.com/watch?v=NdTycenXID8" %}

Related to the multi-lens experiments above, take a look at the [Misapplied Science's Parallel Reality LED display](../experimental-other/other-experiments.md#parallel-reality-display) that uses similar principles.

