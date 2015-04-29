# UKGDS

The United Kingdom Generic Distribution System (UKGDS) is a collection of
power system network models that are representative of UK distribution
networks.

## Unofficial

The UKGDS was developed by the
[Centre for Sustainable Electricity and Distributed Generation][SEDG] (SEDG).
The [link](http://www.sedg.ac.uk/ukgds/) to the UKGDS resources is currently
(29/04/2015) broken. This repository will provide an unofficial home for the
network models until such a time as the resources are back online or a
[takedown request][takedown] from SEDG is received. May it prove useful in the
meantime.

## License

No license for the UKGDS resources has been issued by SEDG. This
[issue][license] is currently outstanding.

## Phase 1 Models

### EHV1

The EHV1 model is a 33kV rural network fed from a 132kV supply point. The
network has long lines, including a sub-sea cable between buses 318 and 304,
leading to voltage problems at the extremities of the network.

![EHV1](ehv1.png?raw=true)

### EHV2

The EHV2 model is a large rural network with interconnection at 132kV and
three separate 33kV sub-networks. Some of the 33kV networks are looped but
voltage problems still arise and are alleviated with shunt capacitors.

![EHV2](ehv2.png?raw=true)

### EHV 3

The EHV3 model represents a suburban area with mixed construction. The
topology is mostly radial but with some interconnection within the network
and links to neighbouring 33kV networks.

![EHV3](ehv3.png?raw=true)

### EHV4

The EHV4 model represents a suburban, meshed network. There are
interconnections to neighbouring networks at 132kV.

![EHV4](ehv4.png?raw=true)

### EHV5

The EHV5 model is a meshed, urban network with mostly direct 132/11kV
transformation but with a disturbing load connected through 33/6.6kV
transformers.

![EHV5](ehv5.png?raw=true)

### EHV6

The EHV6 model represents an underground, urban network. The topology is
strongly radial with conventional 132/33kV and 33/11kV transformation.

![EHV6](ehv6.png?raw=true)

### HV OHa/b

The HV OHa/b model is an 11kV rural network fed from a 33kV supply point.

### HV OH-UGa/b

The HV OH-UGa/b model is an 11kV rural - urban network fed from a 33kV supply
point.

### HV UG

The HV UG model is an 11kV urban network fed from a 33kV supply point.

### HV UG-OHa/b

The HV UG-OHa/b model is an 11kV urban - rural network fed from a 33kV supply
point.

[SEDG]: http://www.sedg.ac.uk/
[takedown]: https://github.com/sedg/ukgds/issues/1
[license]: https://github.com/sedg/ukgds/issues/2
