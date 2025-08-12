# PersonalizedMenu-KEBI_Project
Exam project for the Knowledge Engineering and Business Intelligence course in the Computer Science (LM-18) master's degree program, at University of Camerino.

## Project description

Many restaurants have their menus digitized. Guests can scan a QR code and have the
menu presented on their smartphones. A disadvantage is that the screen is very small and it
is difficult to get an overview, in particular, if the menu is large. However, some guests can
not or do not want every meal, e.g. vegetarians or guests with an allergy. Instead of showing
all the meals that are offered, it would be preferable to show only those meals the guest
prefers.
The objective of the project is to represent the knowledge about meals and guest
preferences and create a system that allows to select those meals that fit the guest
preferences.
The knowledge base shall contain information about typical meals of an Italian restaurant,
e.g. pizza, pasta, and main dishes. Meals consist of ingredients. There are different types of
ingredients like meat, vegetables, fruits, or dairy. For each ingredient, there is information
about the calories.
Guests can be carnivores, vegetarians, calorie-conscious, or suffer from allergies, e.g.
lactose or gluten intolerance.

## Tasks

1. Create different knowledge-based solutions for recommending food depending on the
profile of a guest (carnivores, vegetarians, calorie-conscious, suffering from
allergiesetc.) usind the following representation languages:
• Decision tables (including DRD with sub-decisions and corresponding decision
tables);
• Prolog (including facts and rules);
• Knowledge graph/Ontology (including rules in SWRL, queries in SPARQL and
SHACL shapes)
2. Agile and ontology-based meta-modelling: adapt BPMN 2.0 to suggest the meals for
a given customer. For this, you can re-use or extend the knowledge graph/ontology
created in the previous task. One option that you have is to specify the class BPMN
Task with a new class and add additional properties, similar to what we have done in
class with the Business Process as a Service case. Think of a new graphical notation
for the new modelling element, which could be easy to understand for the restaurant
manager. Use the triple store interface (Jena Fuseki) to fire the query result. 
