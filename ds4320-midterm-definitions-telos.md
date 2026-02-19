# DS 4320 — Definition Terms with Telos

**N.B.** The telos is not necessarially the full definition. It gives the core of the idea.
**N.B.** On the exam you are required to give a definition, not an example.

| Term | Telos |
|------|--------|
| Abstraction Level | Layer of detail at which we view data (e.g., view, conceptual, logical, physical). |
| Accuracy vs. Precision | Accuracy: closeness to truth; precision: consistency/repeatability of measurement. |
| Blind Analysis | Witholding information from analyzer, used to combat bias. |
| Cardinality | How many of one entity relate to how many of another (e.g. one-to-one, one-to-many, many-to-many). |
| Confidence Level vs. Standard Error | Confidence level is the value used to scale the SE to produce a confidence interval |
| Context | information necessary for proper interpretation of data |
| Data Dictionary | Documentation of each feature means. |
| (Domain) Localization | representation of a general principle in a specific domain (e.g., medicine, physics). |
| Entity vs. Attribute | an entity is the real world object being modeled and an attribute is a property of an entity  |
| Epistemic/Systematic vs. Aleatoric/Stochastic | Epistemic: could know but don't; aleatoric: cannot know (inherent randomness). |
| ERD | Entity-Relationship Diagram: diagram showing of entities, attributes, and relationships. |
| Error Bar | Visual a range showing uncertainty around a point estimate. (e.g., ±1 SE or CI) |
| Established Data | **Special term to UVADS** data that meets the standards we teach in this class |
| FAIR vs. CARE | FAIR has a technical focus whereas CARE has a focus on human impact (machine focus vs human focus) FAIR: Findable, Accessible, Interoperable, Reusable; CARE: Collective benefit, Authority, Responsibility, Ethics. |
| Figure of Merit | a scalar, usually a ratio, used to assess performance |
| Goal | measureable quantified objective |
| Human-centered design vs. Design thinking | design thinking is a set of ideas of which HCD is a sub set (**N.B.** this answer is debated, for our class we use this hierarchy) |
| Internal/Embedded vs External Metadata | embedded metadata is encoded with the data itself whereas external metadata exists in a separate location |
| Junction/Bridge Table | used to decompose many to many relationships into one to many relationships |
| License | rights and documentation of data use |
| Metadata | Data that describes other data for the purpose of contextualizing |
| Normal Forms | Rules for structuring tables to reduce redundancy and preserve integrity. |
| Oversampling | Intentionally sampling a group at a rate higher than their base rate |
| PCG64 and Mersenne Twister | Algorithms that produce sequences of pseudo-random numbers |
| Primary Key vs. Foreign Key | PK is a unique identifier a foreign key is a primary key from a different table |
| Provenance vs. DMP | provenance is the context of creation and history of a dataset whereas a DMP addresses the handling of the dataset over the whole life of the dataset |
| Query | action taken to retrieve information from a database |
| Random Number Generator (RNG) | Algorithm that yields (pseudo-)random numbers |
| RCT | Randomized controlled trial means there is a treament and control group assigned at trandom|
| Record | One row in a table; one instance of an entity with values for each attribute. |
| Relational Algebra | Formal operations (select, project, join, etc.) that define how tables are combined and filtered. |
| Representative Sample | Sample whose distribution matches the target population distribution |
| Sampling Bias vs. Selection Bias | **will not be on the test** |
| Sampling Weight | factor used to scale samples to the full population |
| Schema | Definition of tables, columns, types, and relationships |
| Selection Bias vs. Survivorship Bias | survivorship bias comes from subjects not completing the study period, is it a type of selection bias |
| Seed | Initial value that fixes an RNG so the same "random" sequence can be reproduced. |
| SQL vs. MySQL | MySQL is a specific RDBMS where as Structured Query Langugae is a language used to talk to the RDBMS |
| SQL vs. NoSQL | SQL is a language whereas NoSQL describes a category of data models, specifically not RDBMS |
| Standard Deviation vs. Standard Error | the standard error is the standard deviation scaled by 1/sqrt(n) |
| Stratified Sampling | Dividing population into strata and sampling from each strata separately |
| Technical Problem vs. Effectiveness Problem |  the technical problem is only concerned with the transmission of the symbols (in our case bits) whereas the effectiveness problem is concerned with whether the symbols achieved their goal (**N.B. From Shannon-Weaver model**)|
| The many to many problem | when encoded into the relational model M2M relationships create problems like data duplication which make database integrity hard to maintain |
| Uncertainty | Lack of knowledge about a value (**N.B.** We use this term in a general sense) |
