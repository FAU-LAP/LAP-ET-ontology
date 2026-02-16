# LAP-ET-ontology
LAP experimental techniques ontology is an ontology that enables a workflow:
1. The experimenter selects an experiment type (e.g., IV_experiment, Hall_experiment).
2. The system loads a specification/template for that experiment.
3. The user (or a tool) assigns channels (data streams) to the required semantics (AppliedVoltage, MeasuredCurrent, etc.).
4. The output becomes FAIR-ready data (structured + semantically grounded) for systems like CAMELS/OASIS/NOMAD.

So LAP-ET is best thought of as: an “experiment-type + measurement template” ontology used for configuration, validation, and semantic annotation.
