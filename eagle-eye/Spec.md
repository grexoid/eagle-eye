# Task 8: Exploration of AI

This exploratory study investigates the
feasibility of using AI-powered workflows to potentially automate the
harmonization and bar-coding of land classification systems via the EAGLE
approach. Initial research focuses on evaluating whether AI models can be
effectively trained to comprehend complex logical relationships within class
descriptions and translate national classifications into a standardized English
framework. Furthermore, preliminary assessments will explore the viability of
aligning EAGLE terminology with international ISO standards to determine if AI
could eventually facilitate seamless semantic interoperability across diverse
land classification systems.

Task leader: Gregor Rosenauer (UBA)

Involved partners: CNIG, GISAT, NILU, space4environment, Stephan Arnold, WENR

## Our approach

This work will take a major step forward by creating a more intelligent
and automated way to describe land classification systems using the EAGLE approach.
Instead of relying mainly on experts for bar-coding, we will train AI models to
read and understand class descriptions and suggest the appropriate EAGLE
elements and the associated bar code values (BCVs). Building on promising early
experiments, the project will develop a workflow that makes these AI-based
suggestions more reliable, interpretable, and adaptable to multiple languages
and classification systems. The project will leverage the existing EAGLE bar coded CLMS products as
initial context and bar code new CLMS products as well as national and regional
classification systems (e.g. EUNIS, national land cover classifications).
As national definitions
usually are in national language, this task will also address automatic
interpretation / translation to English as a common language. 
The resulting findings of this tast could
later be used for building agentic workflows in GIS tools like ArcGIS or qGIS in
the case of CLC, highlighting versatility of EAGLE approach.

Beyond simply finding
matching words, the new approach will also teach the AI to understand the semantic
relationships between elements — such as parent and child relations between
EAGLE elements and BCVs that cover more than one EAGLE element — and how they
fit into the EAGLE structure. This represents a significant improvement
compared to today’s largely manual process. The outcome will be a practical,
transparent, and scalable method to help countries and institutions harmonize
their land classification systems, support European reporting needs, and reduce
the workload and uncertainty in the crosslinking process.

An additional dimension of
this work would target semantic interoperability and standardized terminology
(link to Task 3). The effectiveness of AI-supported bar-coding depends on the
consistency of language used in class descriptions. Aligning the EAGLE
terminology with the ISO 19144 series, particularly the Land Cover Meta
Language (LCML), is therefore an important step toward uniform and
interoperable understanding. Establishing a semantic mapping between EAGLE and
ISO concepts will allow AI models to interpret and translate class definitions
expressed in either terminology. By applying a harmonized terminology base and implementing a formalized,
machine-readable mapping between all EAGLE and ISO model elements utilizing
SKOS or a comparable standard, the AI will be capable of performing crosswalks such as “assign the
most similar classes from nomenclature A to nomenclature B,” even when one uses
EAGLE elements and the other ISO definitions. This semantic alignment will ensure that the AI can consistently derive
both EAGLE Core elements and ISO LCML structures from diverse class
descriptions, strengthening interoperability across European and international
land classification systems.

A few ideas how AI can be effectively used
in the EAGLE context, based on the project proposal:

* Automated Semantic Bar-coding

AI and Large Language Models (LLMs) can
be trained to automatically read textual class descriptions and suggest the
correct EAGLE elements and Bar Code Values (BCVs). This reduces the need for
manual expert interpretation by recognizing logical relationships between
elements within the EAGLE structure (Task 7 support).

* AI-Driven Bi-directional Translation (EAGLE to ISO Crosswalk)

AI facilitates the automated mapping of ISO nomenclatures directly
into the EAGLE matrix. In the reverse direction, AI models can effectively
process and translate standard land cover nomenclatures
into fully ISO-compliant nomenclature descriptions, establishing a seamless
semantic crosswalk.

* Nomenclature Translation and Cross-walking

AI can automatically interpret and
translate national land class definitions from local languages into English. By
relying on a harmonized terminology base, AI can also perform semantic
crosswalks to consistently match and assign similar classes across different
nomenclatures and data products (Task 4, Task 7 and Task 9 support).

* Enhancing EO Image Classification, Improving Interoperability

Newly created EAGLE- annotated products
can serve as valuable training data for deep learning models used in remote
sensing. This allows machine learning systems to generalize from large volumes
of data to detect and classify land-cover types with high accuracy. Applying
standardized EAGLE semantics and graph-based concepts ensures that data is
optimally provided to AI applications and provides clearly interpretable
objects (might be relevant for long-term strategy and EAGLE sustanability
discussion in Task 1)

* CLCplus Core Integration and User Support

The exploration of AI can be directly
connected to the CLCplus Core platform as a practical use case. Evaluating how
LLMs can support EAGLE generally can also assist with streamlining the complex
framework, potentially aiding the planned training and outreach activities
(Task 4 and Task 9 support).
