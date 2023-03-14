# CelestialDB

*CelestialDB* is a SQLite database which stores data related to various celestial objects such as stars, lines of constellations and so on.

For now the there is only one database *stars* which has two tables: *stars* and *constellation_lines*.

The *stars* table has been created based on the data from https://github.com/astronexus/HYG-Database.

The *constellation_lines* table has been created based on data from https://github.com/hemel-waarnemen-com/Constellation-lines. This table has the *hr* column which relates to the column from the *stars* table with the same name. Every line has its own id *line_id* as some constellation cannot be drawn by a single line.