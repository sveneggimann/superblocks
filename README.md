# superblock
Finding superblock opportunities based on openstreetmap data.

Pre-processing
---------------
Extract population data as GeoTif and store in folder (here the example is R:/Scratch/313/sven/pop_fb).
Data Source (here the example for spain):  https://data.humdata.org/search?q=High%20Resolution%20Population%20Density%20spain&ext_page_size=25&sort=score%20desc%2C%20if(gt(last_modified%2Creview_date)%2Clast_modified%2Creview_date)%20desc 

Script execution
---------------
Step 1: Execute the preprocess_osm.py script to obtain osm data
Step 2: Execute the superblock script to simulat superblocks
