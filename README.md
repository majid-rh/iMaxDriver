# iMaxDriver

The iMaxDriver is provided in non-weighted and weighted versions that can be found in the above folders. 

The input edges and nodes should be defined in respective CSV files in the same folder of iMaxDriver.jar.

The *_nodes.csv contains <Gene Name,Cancer Expression,Normal Expression> rows.

The *_edges.csv contains <Source Gene Name, Destination Gene Name> rows in non-weighted version and <Source Gene Name, Destination Gene Name, Edge weight> in weighted version.

The config.txt can be used for parameters setting.

Finally the application creates a file named results.csv containing sorted genes.

