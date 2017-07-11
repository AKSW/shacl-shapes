# Accessible Buildings

These shapes describe different accessible aspects of buildings. The meta data file is [meta.ttl](https://github.com/schreckl/rules/blob/master/rules/accessible-building/meta.ttl).

The following shapes are available:

| Aspect of the building | Types                                        |
|:-----------------------|:---------------------------------------------|
| **Entrance**           | Partly accessible                            |
|                        | Fully accessible                             |
|                        |                                              |
| **Lift**               | Partly accessible                            |
|                        |                                              |
| **Local Support**      | special support for people with disabilities |
|                        | for visually impaired                        |
|                        | for hearing impaired                         |

## Entrance

The *entrance* describes
* the way from a public area to the area which belongs to the building
* the entrance door area
* steps or ramps before the entrance door(s)
* separate entrances (for instance, special entrances for wheelchair users)

### Entrance is fully accessible by wheelchair users

Based on the mini-specification of the [Behindertenverband Leipzig e.V.](http://www.le-online.de/zeichenengl.htm). The entrance area is fully accessible for wheelchairs, if:
* entrance ground is flat (max. 3cm) or via ramp <= 6% gradient
* entrance door width: >= 90 cm

### Entrance is partly accessible by wheelchair users

Also based on the mini-specification of the [Behindertenverband Leipzig e.V.](http://www.le-online.de/zeichenengl.htm). The entrance area is partly accessible for wheelchairs, if:
* max. 1 step or via ramp with max. 12% gradient or
* entrance door width: >= 70 cm

## Local Support

### Special support for people with disabilities

A building has special support for people with disabilities, if it has a property buildaccess:localSupport with value `"true"^^xsd:boolean`.

### For hearing impaired people

A building has local support for hearing impaired people, if it has a property buildaccess:supportForHearingImpairedAvailable with value `"true"^^xsd:boolean`.

### For visually impaired people

A building has local support for visually impaired people, if it has a property buildaccess:supportForVisuallyImpairedAvailable with value `"true"^^xsd:boolean`.
