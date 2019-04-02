# istar4safety - Metamodel and constraints

This is a formalization of the iStar4Safety language, an extension of the iStar 2.0 language aimed at supporting the development of safety-critical systems.

The istar4safety.ecore file contains the metamodel of iStar4Safety language, complete with OCL constraints, using the Ecore language from the Eclipse Modeling Framework.

## Instructions
Before using the metamodel, it is necessary to install [Eclipse](https://www.eclipse.org/downloads/) - specifically, the Eclipse Modeling Tools. We have used the Eclipse IDE 2019‑03 version. In Eclipse, create a new Ecore Modeling Project and place the metamodel file within the model folder.

**In order to view the metamodel as a diagram**, right-click the file and select "Initialize Ecore Diagram..." Then select "Entities in a Class Diagram", click Next, and then Finish.

**In order to create a model that instantiates this metamodel**, you need to first open the metamodel as a diagram (see above). With the diagram open, select "Dynamic instance" in the Palette, then click on the "Model" entity of the model. Define a name for the model file, preserving the .xmi extension. Click Finish. You'll be able to edit the model in a tree-like view.

**In order to edit the OCL constraints**, first install Eclipse OCL through the Help/Eclipse Marketplace... option. We used version 6.7. Once it is installed, right-click the metamodel file (.ecore) and Open With > OCLinEcore Editor. With Eclipse OCL installed, you can also query an instance of the metamodel (i.e., a model) with the Interactive OCL Console.

## Credits
 - Language proposal by Moniky Ribeiro, supervised by Jaelson Castro
 - Formalization (Ecore metamodel and OCL constraints) by João Pimentel
