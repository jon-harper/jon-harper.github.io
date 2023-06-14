---
title: Part 3. Material Comparisons
summary: Comparison of commonly-printed materials.
authors: Jon Harper
date: 2023-05-19
# hide: toc
---

# Part 3: Material Comparisons

## Alternatives

Before substituting a more expensive or difficult-to-print material, consider a different formulation of ABS or a blend with additives. The simplest way to modify the characteristics of an ABS resin is to vary the ratio of the three ingredient monomers, and this is the reason different manufacturers offer ABS with varying properties. For the same reason, good filament manufacturers offer Technical Data Sheets for their products.

### ASA and ABS Blends

One issue with ABS is that it degrades under UV light (particularly direct sunlight). ASA is an alternative polymer:

1. It behaves much like ABS when printed.
2. It offers a higher heat tolerance, weather-resistance, and UV-stability.
3. It is, however, more expensive than ABS, harder to source, and generally available in fewer colors.

Instead of completely replacing with ASA or another filament, a blended resin can be used. Filament made from resin with additives can greatly enhance specific properties. Materials commonly added to ABS include PMMA (translucency), PC (heat resistance), and ASA (UV stability, weatherability).

As ASA grows in popularity and more manufacturers carry ASA filament, prices will drop and sourcing options increase.

### PC-ABS Blends

Blending ABS and PC is a popular method of introducing fire retardance to ABS.

### Fiber "Fills"

Fiber "fills" are another option. Within the last few years, manufacturers began selling filaments with up to 30% fiber content. These [glass-](https://www.3dxtech.com/product/fibrex-abs-gf/) and [carbon-fiber](https://atomicfilament.com/collections/abs-3d-filament/products/carbon-fiber-ultra-black-abs) doped filaments have higher heat resistance, greater  stiffness, and improved dimensional stability than regular ABS. Carbon-fiber-filled ABS (CF-ABS) is the most common form of ABS fill.

Both CF-ABS and GF-ABS have similar print requirements to their non-filled counterparts, but notably require a hardened metal nozzle. Most FDM printers use brass for nozzles; the fibers will erode a non-hardened nozzle.

More ABS blends and alternatives are likely to make their way into filament. As FDM 3D printing popularity grew in the last decade, filament manufacturers increased the variety of resins used to make filament. This trend will likely continue: for example, Sabic distributes [more than 20 ABS resins grades](https://www.sabic.com/en/products/polymers/acrylonitrile-butadiene-styrene-abs/cycolac-resin). Larger filament manufacturers now carry filament in three or more ABS resin grades, but this is a far cry from Sabic's full catalogue.

## Material Comparisons

Filament manufacturers consider nozzle temperature when choosing a base resin for their filament, particularly for materials that have high requirements. As a result, the [Print Temperatures](#print-temperatures) section contains averages developed from multiple sources.

Values are sourced from [Polymaker](https://us.polymaker.com) for the remaining tables on this page. Polymaker was chosen because their products include Technical Data Sheets, they carry a wide range of materials, and they are competitively priced.

### Print Temperatures

| Material | Nozzle Temp. | Bed Temp. | Air Temp. | Notes |
|---|---|---|---|---|
| PLA | 180-220°C | 25-65°C | 15-30°C | Most common 3D-printed material due to low melting point. |
| TPU | 210-250°C | 25-60°C | 15-30°C | High flexibility makes this material difficult to print. |
| PETG | 230-250°C | 70-80°C | 15-30°C | PETG is at the upper range of capabilities for most entry-level printers. |
| **ABS** | **230-250°C** | **90-110°C** | **45°C+** |  |
| ASA | 235-255°C | 90-110°C | 45°C+ |  |
| PA | 230-260°C | 60-110°C | 45°C+ | Some forms of PA do not require a heated enclosure. |
| PP | 220-250°C | 85-100°C | 45-60°C | |
| PC | 260-300°C | 80-120°C | 45°C+ | Must be annealed after printing to relieve stress. |

### Price

Prices are current May 2023.

| Material | Unit Price ($/kg) | Source Filament |
|----------|-------------------|-----------------|
| **ABS**  | **22**            | [**PolyLite ABS**](https://us.polymaker.com/products/polylite-abs)
| ASA      | 30                | [PolyLite ASA](https://us.polymaker.com/products/polylite-galaxy-asa) |
| PA6      | 67                | [PolyMide CoPA](https://us.polymaker.com/products/polymide-copa) |
| PC       | 52                | [PolyMax PC](https://us.polymaker.com/products/polymax-pc) |
| PETG     | 22                | [PolyLite PETG](https://us.polymaker.com/products/polylite-petg) |
| PLA      | 23                | [PolyLite PLA](https://us.polymaker.com/products/polylite-pla) |
| PLA+/Pro | 25                | [PolyLite PLA Pro](https://us.polymaker.com/products/polylite-pla-pro) |
| PP       | 83                | [SmartMaterials Polypropylene](https://www.matterhackers.com/store/l/natural-smartmaterials-smartfil-polypropylene-filament-175-07/sk/M8D8XF6V) |
| TPU (Shore 95A)  | 40        | [PolyFlex TPU95A](https://us.polymaker.com/products/polyflex-tpu95) |

### General Properties

| Property/Material      | ABS  | ASA   | PA6  | PC   | PC-ABS | PETG | PLA  |
|------------------------|------|-------|------|------|--------|------|------|
| Density (g/cm^3^)      | 1.12 |  1.13 | 1.12 | 1.19 | 1.1    | 1.25 | 1.19 |
| HDT @ 0.45MPa (°C)     | 100  | 102   | 111  | 114  | 106 | 78  | 60   |
| HDT @ 1.8MPa (°C)      | 98   | 100   | 70   | 99   | 112 | 75   | 58   |
| Vicat Softening Temperature (°C) | 104 | 105 | 117  | 120 | 135 | 84 | 158 |

*Source: Polymaker*

### Mechanical Properties

The layers used to make FDM printed materials cause the finished material to have different properties on the X- and Y-axes (horizontal) than the Z-axis (vertical), so values are given here for each (where available).

| Property                         | ABS  | ASA  | PA6  | PC   | PC-ABS | PETG | PLA  |
|----------------------------------|------|------|------|------|--------|------|------|
| XY Axis Tensile Strength (MPa)   | 33   | 43.8 | 66   | 59.7 | 39.9   | 32   | 52   |
| Z Axis Tensile Strength (MPa)    | 25   | 32   | 43   | 29.1 | 22.9   | 13   | 41   |
| XY Axis Young's Modulus (GPa)    | 2.17 | 2.79 | 2.22 | 2.05 | 1.84   | 1.47 | 3.43 |
| Z Axis Young's Modulus  (GPa)    | 1.84 | 1.96 | 2.56 | 1.84 | 1.68   | 1.09 | 3.01 |
| Flexural Modulus (GPa)           | 2.8  | 3.2  | 1.67 | 2.0  | 2.08   | 1.17 | 3.28 |
| Elongation at Break (%)          | 2.4  | 6.7  | 4.6  | 12.25 | 4.2    | 1.3  | 1.8  |
| Charpy Impact Test (KJ/m^2^)     | 12.6 | 10.3 | 17.2 | 25.1  | 25.8   | 5.1  | 3.3  |

*Source: Polymaker*

## Summary

ABS plastic is an excellent all-purpose plastic for 3D printing functional parts. Although it requires an enclosure to print safely and well, it is both the easiest engineering-grade plastic to print and the most affordable.

End-users familiar who are familiar with open-air filaments and inexperienced in ABS find that chamber temperature and appropriate cooling are a critical factors in quality ABS prints.

When a UV-stable and weather-resistant alternative is needed, ASA can be substituted at a higher price point. Blends and fills are available to give ABS other desired properties.

## Further Reading

### ABS

- [Acrylonitrile Butadiene Styrene](https://en.wikipedia.org/wiki/Acrylonitrile_butadiene_styrene). *Wikipedia, the free encyclopedia.*
- [Comprehensive Guide on Acrylonitrile Butadiene Styrene (ABS)](https://omnexus.specialchem.com/selection-guide/acrylonitrile-butadiene-styrene-abs-plastic). *Omnexus*.
- [What is ABS Material?](https://plasticextrusiontech.net/what-is-abs-material/) *Plastic Extrusion Technologies*. Oct 8, 2021.
- [A Guide to ABS Plastic Injection Molding Process](https://www.rapiddirect.com/blog/abs-injection-molding/). *Rapid Direct*. Feb 27, 2022.

### General Plastics

- [What is a Thermoplastic?](https://www.twi-global.com/technical-knowledge/faqs/what-is-a-thermoplastic). *TWI Global*.
- [What is a Polymer?](https://www.livescience.com/60682-polymers.html). *LiveScience*. Oct 13, 2017.
- [What is plastic resin? How is Plastic Resin Made?](https://europlas.com.vn/en-US/what-is-plastic-resin-how-is-plastic-resin-made). *EuroPlas*.
- [What is injection moulding?](https://www.twi-global.com/technical-knowledge/faqs/what-is-injection-moulding). *TWI Global*.

### Material Properties

- [Deflection Temperature Testing of Plastics](https://www.matweb.com/reference/deflection-temperature.aspx). *MatWeb*.
- [Filament Properties Table](https://www.simplify3d.com/resources/materials-guide/properties-table/). *Simplify 3D*.

*[FDM]: Fusion deposition modeling: a method of 3D printing material in layers by extruding heated plastic through a nozzle.
*[HDT]: Heat-deflection temperature: the temperature where a material under a fixed amount of stress begins to bend.
*[VOC]: Volatile organic compounds: these off-gas from many common products and chemicals, including during 3D printing.
*[VOCs]: Volatile organic compounds: these off-gas from many common products and chemicals, including during 3D printing.
*[PLA]: Polylactic acid: a brittle plastic with a low melting point; widely used for 3D printing.
*[PETG]: Polyethylene terephthalate glycol: a clear, slightly flexible polymer widely used for food-safe purposes.
*[TPU]: Thermoelastic polyurethane: a family of highly elastic polymers with a wide range of uses; often compared to rubber in mechanical properties.
*[PA]: Polyamide: a family of polymers that includes Nylon.
*[PC]: Polycarbonate: a family of polymers known for extreme hardness, resistance to heat, and clarity.
*[PTFE]: Polyfluorotetraethylene: also known as Teflon, PTFE tolerates very high temperatures but produces toxic gas when heated enough.
*[PMMA]: Poly(methyl methacrylate): a highly clear, rigid plastic commonly known as acrylic.
*[PEEK]: Polyether ether ketone: a plastic with exceptional mechanical, chemical, and thermal properties that is commonly used in extreme conditions (up to 500C).
*[ASA]: Acrylonitrile styrene acrylate: a UV-stable and more heat-resistant polymer related to ABS.
*[PEI]: Polyetherimide: a plastic similar to PEEK with a higher temperature range and adhesive properties; frequently used on 3D printer beds.
*[PP]: Polypropylene: lightweight material that is microwave- and dishwasher-safe. Commonly found in packing materials and drink bottles.
*[thermoplastic]: Thermoplastics are a class of polymers that can be heated enough to soften, processed into a desired shape, then allowed to cool. These plastics are normally safe to heat and reheat indefinitely without destructive effect, making them easy to recycle, amongst other benefits.
*[off-gas]: Plastics heated sufficiently break down and release gaseous byproducts; this is called off-gassing.
*[polymer]: 
    A polymer is a material made of repeating chains of smaller molecules and can be thousands or millions of links long. Examples of polymers are plastics, DNA, and proteins.
*[Vicat Softening Temperature]: 
    The Vicat softening temperature is used to determine the temperature at which a material can be penetrated 1mm by a fixed amount of pressure.
*[Tensile Strength]: Tensile strength: how far a material can be stretched before breaking
*[Flexural Modulus]: Flexural modulus: the tendency for a material to resist bending, defined by ratio of stress to strain.
*[Young's Modulus]: Young's Modulus: stiffness of a material when force is applied to the long axis
*[delamination]: Delamination: separation of a 3D print's adjacent layers due to material warp. A print with delamination is structurally weak and should be discarded.
*[anneal]: Anneal: To heat a material and allow to cool slowly in order to relieve internal stresses. Annealing plastic often takes hours.
*[annealed]: Anneal: To heat a material and allow to cool slowly in order to relieve internal stresses. Annealing plastic often takes hours.
*[warp]:
    Warp: Warp is deformation of printed plastic from uneven cooling. Warp typically affects parts at the edges and causes "lift" or "curling".
*[resin]: Plastic resin: plastic pellets that are the source material for industrially-made plastics, including filament. They are melted and formed into a desired shape, then allowed to cool.