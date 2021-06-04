# language_dynamics

Data and code for paper S. Mimar et al. Linguistic evolution driven by network heterogeneity and the Turing mechanism.

Data

'final_table_galicia.csv' and 'final_table_carinthia.csv' is the linguistic data for Galicia and Carinthia repsectively that they include fraction of speakers of each language, population of towns/cities, language status and similarity measure for Galicia as well as latitude and longitude of the nodes.

Code

Source code in 'turing_instability_for_language_dynamics_galicia.ipynb' implements the language spread on the geographical network of Galicia where edgeweights are determined by the Gravity Law. Language concentrations diffuse similar to the Turing Mechanism (for theoretical background of Turing instability on networks, see PhysRevE.99.062303) and form the patterns. Simmulation concentrations are then aggragated to Region level and compared to the actual fractions of speakers.

