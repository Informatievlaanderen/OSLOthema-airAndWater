|Class|Definition|Origin|
|:-------------:|:-------------:|:-------------:|
|Observation|An observation is the act of observing a property.|ISO O&M|
|Property|A property is a facet or attribute of an object referenced by a name.|ISO O&M|
|Feature|Features are abstractions of real-world phenomena.|ISO O&M|
|SpatialSamplingFeature|Spatially defined part of the Object to be observed and representative of that Object|ISO O&M|
|Result|The observation result in an estimate of the value of a property determined through a known observation procedure.|ISO O&M|
|Metadata|Metadata is data that contains information about data.|ISO O&M|
|Procedure|A workflow, protocol, plan, algorithm, or computational method specifying how to make an observation, create a sample, or make a change to the state of the world (via an actuator). A procedure is re-usable, and might be involved in many observations, samplings or actuations. It explains the steps to be carried out to arrived at reproducible results.|[SOSA](https://www.w3.org/TR/vocab-ssn/#SOSAProcedure)|
|Sensor|Device, agent (including humans), or software (simulation) involved in, or implementing, a procedure. Sensors respond to a stimulus, e.e., a change in the environment, or Input data composed from the Results of prior observations, and generate a result. Sensors can be hosted by platforms.|[SOSA](https://www.w3.org/TR/vocab-ssn/#SOSASensor)|
|Platform|A platform is an entity that hosts other entities, particularly sensors, actuators, samplers and other platforms.|[SOSA](https://www.w3.org/TR/vocab-ssn/#SOSAPlatform)|
|ObservationCollection|A collection of one or more observations, whose members share a common value for one or more properties. |[SOSA-extension](https://www.w3.org/TR/vocab-ssn-ext/#sosa:ObservationCollection)|
|System|System is a unit of abstraction for pieces of infrastructure that implment Procedures. A system may have components, it's subsystems, which are other Systems.|[SSN](https://www.w3.org/TR/vocab-ssn/#ssn-system)|
|SystemCapability|Describes normal measurement, actuation, sampling properties such as accuracy, range, precision etc… of a system under some specified conditions such as a temperature range. The capabilities specified here are those that affect the promary purpose of the system, while those in operatingrange represent the system's normal operating environment, including conditions that don't affect the observation or the actuations.|[SSN](https://www.w3.org/TR/vocab-ssn/#SSNSYSTEMSystemCapability)|
|OperatingRange|Describes normal operating properties of a system under some specified conditions. For example, to the power requirements or maintenance schedule of a system under a specified temperature range.|[SSN](https://www.w3.org/TR/vocab-ssn/#SSNSYSTEMOperatingRange)|
|SurvivalRange|Describes survivalproperties of a system under some specified conditions. For example the lifetime of a system under a specified temperature range.|[SSN](https://www.w3.org/TR/vocab-ssn/#SSNSYSTEMSurvivalRange)|
|Device|An apparatus (hardware + software / firmware) intended to accomplish a particular task (sensing the environment, actuating, …). A device is a tangible object which contains some logic and is producer and/or consumer of data. A device is always assumed to be capable of communicating electronically via a network.|[FIWARE](https://fiware-datamodels.readthedocs.io/en/latest/Device/Device/doc/spec/index.html)|
|SamplingFeatureComplex|Sampling features are frequently related to each other, as parts of complexes, through sub-sampling, and in other ways. If present, the association class SamplingFeatureComplex shall link a SF_SamplingFeature to another SF_SamplingFeature. It shall support one attribute.|ISO O&M|
|Specimen|A Specimen is a physical sample, obtained for observation(s) carried out ex situ, sometimes in a laboratory.|ISO O&M|
|AirFeature|Air features are abstractions of real-world phenomena, in this case pertaining to air.|ISO O&M|
|AirQualityObservation|An observation of air quality conditions at a certain place and time.|[FIWARE](https://fiware-datamodels.readthedocs.io/en/latest/Environment/AirQualityObserved/doc/spec/index.html)|
|Measure|Value described using a numeric amount with a scale or using a scalar reference system |ISO O&M|
|AirQualityIndexObservation|Air quality index corresponding to the air quality observed.|[FIWARE](https://fiware-datamodels.readthedocs.io/en/latest/Environment/AirQualityObserved/doc/spec/index.html)|
|AirQualityLevelObservation|Overall qualitative level of health concern corresponding to the air quality observed.|[FIWARE](https://fiware-datamodels.readthedocs.io/en/latest/Environment/AirQualityObserved/doc/spec/index.html)|
|AirPollutantObservation|An observation of air pollutants at a certain place and time.|~FIWARE|
|AirPollutantValueObservation|An observation of the quantitative value of air pollutants at a certain place and time.|~FIWARE|
|AirPollutantLevelObservation|Overall qualitative level of air pollutants. |~FIWARE|
|AirQualityObservationCollection|A collection of one or more air observations, whose members share a common value for one or more properties.|[SOSA-extension](https://www.w3.org/TR/vocab-ssn-ext/#sosa:ObservationCollection)|
|WaterQualityObservationCollection|A collection of one or more water observations, whose members share a common value for one or more properties.|[SOSA-extension](https://www.w3.org/TR/vocab-ssn-ext/#sosa:ObservationCollection)|
|WaterFeature|Water features are abstractions of real-world phenomena, in this case pertaining to water.|ISO O&M|
|WaterQualityParameterObservation|An observation of water quality conditions at a certain place and time. |~FIWARE|
|ChemicalAgentConcentrationObservation|An observation of the quantitative value of chemical agents in the water observed at a certain place and time. |N/A|
|BioIndicatorObservation|An observation of a specific biological indicator in the water observed at a certain place and time.|N/A|
|BioticIndexObservation|An observation of a biotic index in the water observed at a certain place and time.|N/A|