# Background of micro and nano fab
* ___This section is under development, and may need re-formmating to better abstract the concepts.___

Here we'll lay out the basic processes that are used in micro and nano technology fabrication.

After this, on the [basics page](basics.md) we can talk about how to get started in a DIY fasion.

Table of Contents
=================

  * [Forming geometry](#forming-geometry)
     * [Optical Lithography](#optical-lithography)
        * [Background](#background)
        * [Details](#details)
        * [Positive Tone](#positive-tone)
        * [Negative Tone](#negative-tone)
     * [Electron and Ion Beam Lithography](#electron-and-ion-beam-lithography)
        * [Positive Tone](#positive-tone-1)
        * [Negative Tone](#negative-tone-1)
     * [Deposition and Epitaxy](#deposition-and-epitaxy)
  * [Altering chemical composition](#altering-chemical-composition)
     * [Diffusion](#diffusion)
     * [Ion Implant](#ion-implant)

## Forming geometry
Making shapes is key, second is making shapes out of different materials with various behaviors.

### Optical Lithography
#### Background
[Photolithography](https://en.wikipedia.org/wiki/Photolithography) is the technique of using beams of light to control chemical reactions which enable removal or retention of applied chemicals. Expanding the latin roots, it essentially means optical control of writing into a stone (a very hard and resilient material).

Lithography itself can be as simple as taking a metal knife and scratching a flat piece of stone or glass. Such an object could then be pressed into an ink or dye, and used as a stamper to make replica images. This is called [relief printing](https://en.wikipedia.org/wiki/Relief_printing)

Starting with [the history of photography](https://en.wikipedia.org/wiki/Photography#History), photosensitive chemicals were discovered and harnessed. The first major commercial success was chemistry based on halide salts (Cl-, Br-, I-) and Silver Nitrate, embedded in a gel of various sources (egg white albumen, collodion, gelatin). The halide salts would react with the [silver nitrate](https://en.wikipedia.org/wiki/Silver_nitrate), creating silver halide, which is highly photosensitive. Under exposure to light, silver halide crystals convert into metallic silver starting at crystal defects ([sensitivity speck](https://en.wikipedia.org/wiki/Sensitivity_speck)). Under short exposure, this produces a weak ["latent image"](https://en.wikipedia.org/wiki/Latent_image) in which each halide crystal is only partially converted to metallic silver. Converting a halide fully into metallic silver requires either intense irradiation, or [development](https://en.wikipedia.org/wiki/Photographic_developer) with a chemical reducing agent. Finally a fixer like [sodium thiosulfate](https://en.wikipedia.org/wiki/Sodium_thiosulfate#Photographic_processing) is then applied to dissolve any remaining photosensitive halides. In these systems, the gel bound all salts (until being dissolved with fixer) and particles so the resulting image was mechanically resilient.

[Instructions for Making a Simple Silver-Based Photographic Emulsion Suitable for Coating on Glass or Film](https://unblinkingeye.com/Articles/Emulsion/emulsion.html)

You can begin to imagine now that if the metallic silver was not composed of individual, dispersed particles, but rather were a solid that the gel would not be required. Furthermore, if the gel was not present, a developed artifact would have 3D topography (places where silver was present, and places where it was not).

#### Details
Usually a [photoresist](https://en.wikipedia.org/wiki/Photoresist) is composed of polymers that will either condense (join one another, more resistant to being dissolved) or lyse (get smaller and more easily dissolved; scission) upon exposure to light. Wikipedia says there are actually 3 types: photopolymeric, photodecomposing, and photocrosslinking.

#### Positive Tone
These resists go away when exposed.

#### Negative Tone
These resists stick around when exposed.
* [SU-8](https://en.wikipedia.org/wiki/SU-8_photoresist)

### Electron and Ion Beam Lithography
Similar to photolithography, but instead of causing the condensation or lysis based on a photo reaction, it is the result of electron or ion beam reactions. High-energy electrons can either cause condensation reactions, or lysis reactions. Ion beams primarily have a ballistic interaction, inducing lysis (also known as chain scission), but with some resists like [HSQ](https://en.wikipedia.org/wiki/Hydrogen_silsesquioxane) the scission of Si-H bonds leads to crosslinking.

[Focused Ion Beam Lithography - Heinz D. Wanzenboeck and Simon Waid](cdn.intechweb.org/pdfs/24490.pdf)

#### Positive Tone
These resists go away when exposed.
* [PMMA](https://en.wikipedia.org/wiki/Poly(methyl_methacrylate))

#### Negative Tone
These resists stick around when exposed.
* [HSQ](https://en.wikipedia.org/wiki/Hydrogen_silsesquioxane)

### Deposition and Epitaxy
* [Thin Film Deposition](https://en.wikipedia.org/wiki/Thin_film#Deposition)
* [Chemical Vapor Deposition](https://en.wikipedia.org/wiki/Chemical_vapor_deposition)
* [Plasma Enhanced CVD](https://en.wikipedia.org/wiki/Plasma-enhanced_chemical_vapor_deposition)
* [Epitaxy](https://en.wikipedia.org/wiki/Epitaxy)
* [Molecular-Beam Epitaxy](https://en.wikipedia.org/wiki/Molecular-beam_epitaxy)
* [Physical Vapor Deposition](https://en.wikipedia.org/wiki/Physical_vapor_deposition)
* [Electron-Beam Physical Vapor Deposition](https://en.wikipedia.org/wiki/Electron-beam_physical_vapor_deposition)
* [Atomic Layer Deposition - ALD](https://en.wikipedia.org/wiki/Atomic_layer_deposition)

## Altering chemical composition
### Diffusion
### Ion Implant