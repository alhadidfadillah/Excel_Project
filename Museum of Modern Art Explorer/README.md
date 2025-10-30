# Build an interactive tool to explore the artwork at the Museum of Modern Art (MoMA)
This research dataset contains 157,630 records, representing all of the works that have been accessioned into MoMA’s collection and cataloged in their database. It includes basic metadata for each work, including title, artist, date made, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted as “not Curator Approved.”

## The Objectives
Create a tool that allows us to select nationality, artist, minimum year of creation, and display their earliest work.

## The Approaches
1. Clean the artwork data by looking up the artist(s) for each piece and extracting its date of creation.
2. Create dependent dropdown lists for nationality and artist, and display their number of artworks and their earliest & latest work on display.
3. Display their work, return additional information on the selected artist's earliest work after a certain date, along with the image of the artwork itself.
