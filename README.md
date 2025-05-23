# water-sensor
This Application Note describes a novel design of a conductivity water level sensor that is integrated with a sensor control management program running on a uTile PLC. The sensor element consists of two small carbon motor brushes used as sensor probes.

The probes detect the presence of water between the probes by sensing the change in electrical conductivity between probes due to the effect of water increasing the conductivity. The probes are run in a bipolar manner, meaning the polarity of the probes are reversed during alternate measurement cycles.

The bipolar probe operation mitigates any corrosion/plating effect of the sensing current that flows between the probes, eliminating a major cause of sensor failure that exists if the probes are operated in a unipolar manner, i.e. if the polarity of the probes remain fixed during operation.

The uTile PLC runs the sensor management control program efficiently and it uses only 35 lines out of an available 256 lines of program instructions.
