# Accessible Buildings

These shapes describe different accessible aspects of buildings. The meta data file is [meta.ttl](https://github.com/schreckl/rules/blob/master/rules/accessible-building/meta.ttl). 

The following shapes are available:

| Aspect of the building | Shape files                                                                                                                                                                                                                                                                 |
|:-----------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrance**           | Partly accessible ([HTML](https://github.com/schreckl/rules/blob/master/rules/accessible-building/entrance-fully-accessible-by-wheelchair.ttl), [Raw](https://github.com/schreckl/rules/raw/master/rules/accessible-building/entrance-fully-accessible-by-wheelchair.ttl))  |
|                        | Fully accessible ([HTML](https://github.com/schreckl/rules/blob/master/rules/accessible-building/entrance-partly-accessible-by-wheelchair.ttl), [Raw](https://github.com/schreckl/rules/raw/master/rules/accessible-building/entrance-partly-accessible-by-wheelchair.ttl)) |

## Entrance

The *entrance* describes 
* the way from a public area to the area which belongs to the building
* the entrance door area
* steps or ramps before the entrance door(s)
* separate entrances (for instance, special entrances for wheelchair users)

### Specification: entrance fully accessible by wheelchair users

Based on the mini-specification of the [Behindertenverband Leipzig e.V.](http://www.le-online.de/zeichenengl.htm). The entrance area is fully accessible for wheelchairs, if:
* entrance ground is flat (max. 3cm) or via ramp <= 6% gradient
* entrance door width: >= 90 cm

### Specification: entrance partly accessible by wheelchair users

Also based on the mini-specification of the [Behindertenverband Leipzig e.V.](http://www.le-online.de/zeichenengl.htm). The entrance area is partly accessible for wheelchairs, if:
* max. 1 step or via ramp with max. 12% gradient or
* entrance door width: >= 70 cm
