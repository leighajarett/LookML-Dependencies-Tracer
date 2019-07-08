# LookML-Dependencies-Tracer

Contains a Python3 Jupyter Notebook which uses the LookerAPI to parse through the specified LookML model and results in a relational CSV file. The resulting table has one row for each dependency (i.e. a field that is referenced in the definition of another field), with the first column specifying the field name (name of the dimension or measure) of the given metric and the second specifying the field name of its dependency. 

The CSV can also be pushed into a database for visualization of the model's dependencies within the same Looker instance. If you are authorized as a user on Looker's internal sales engineering instance, you can see the resulting visualization [here](https://saleseng.dev.looker.com/looks/1113) and the project [here](https://saleseng.dev.looker.com/projects/lookml_dependencies/files/README.md).
