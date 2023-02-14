Exemplary data for the IMRaD classification task.

Labels:

* “i”: Introduction
* “m”: Methods
* “r”: Results
* “d”: Discussion
* “w”: Related Work

Notes:

* Training/Test/Validation splits are stratified samples w.r.t.
    * Publication year
    * Computer science sub-discipline
* Paragraphs from a single paper are only ever assigned to one split, to avoid paper specific keywords or authors’ writing styles as confouning variables in prediction
