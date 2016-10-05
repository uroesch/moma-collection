[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.159060.svg)](http://dx.doi.org/10.5281/zenodo.159060)


The Museum of Modern Art (MoMA) Collection
===================

The Museum of Modern Art (MoMA) acquired its first artworks in 1929, the year it was established. Today, the Museum’s evolving collection contains almost 200,000 works from around the world spanning the last 150 years. The collection includes an ever-expanding range of visual expression, including painting, sculpture, printmaking, drawing, photography, architecture, design, film, and media and performance art.

MoMA is committed to helping everyone understand, enjoy, and use our collection. The Museum’s [website](http://www.moma.org/collection) features 70,688 artworks from INSERT DYNAMIC NUMBER FROM “Showing 11,045 out of …” from http://moma.org/artists END artists. This research dataset contains 129,024 records, representing all of the works that have been accessioned into MoMA’s collection and cataloged in our database. It includes basic metadata for each work, including title, artist, date made, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted by an "N" in the “Cataloged” field.

The Artists dataset contains 14,949 records, representing all the artists who have work in MoMA's collection and have been cataloged in our database. It includes basic metadata for each artist, including name, nationality, gender, birth year, death year, Wiki QID, and Getty ULAN ID.

At this time, both datasets are available in CSV format, encoded in UTF-8. While UTF-8 is the standard for multilingual character encodings, it is not correctly interpreted by Excel on a Mac. Users of Excel on a Mac can convert the UTF-8 to UTF-16 so the file can be imported correctly. The datasets are also available in JSON.

### Artworks
Field Name | Type           | Description  | Example
-----------------------|----------------|--------------------------|------------
Title | String | The title of the object | The Starry Night
Artist | String | Creator of the object | Vincent van Gogh
ConstituentID | Number | A unique number that identifies constituents within the Museum’s collection database | 2206
ArtistBio | String | Text display of nationality with birth and death years. It may include the country of birth as well | (Dutch, 1853–1890) 
Nationality | String | Accepted country of identification, often distinct from country of origin | (Dutch)
BeginDate | Number | Birth year of an individual or an institution’s year of origin | -1853
EndDate | Number | Death year of an individual or an institution’s year of termination | -1890
Gender | String | Gender identification of an individual | (Male)
Date | String | When the artwork was created | Saint Rémy, June 1889
Medium | String | Material of which this is this object/artwork is made | Oil on canvas
Dimensions | String | The overall dimensions of the object | 29 x 36 1/4" (73.7 x 92.1 cm)
CreditLine | String | Identifies and gives credit to the person, foundation, or method by which the object was acquired | Acquired through the Lillie P. Bliss Bequest
AccessionNumber | String | A unique number assigned to each object in the collection | 472.1941
Classification | String | The name of a group to which the work belongs within the museum's classification scheme, based on similar characteristics | Painting
Department | String | Department within the Museum which collected the object | Painting & Sculpture
DateAcquired | Date | The date the object was acquired by the Museum | 6/10/1941
Catalogued | String | Whether the metadata has been vetted by a curator | Y
ObjectID | Number | A unique number that identifies the record of the object in the collections database | 79802
URL | URL | URL to the object page on moma.org | http://www.moma.org/collection/works/79802
ThumbnailURL | URL | URL to the thumbnail of the image on moma.org |
Circumference (cm) | Number | The circumference of the object in centimeters | 72
Depth (cm) | Number | The maximum depth of the artwork/object in centimeters | 7.62
Diameter (cm) | Number | The maximum diameter of the artwork/object in centimeters | 22.8
Height (cm) | Number | The maximum height of the object in centimeters | 20.3
Length (cm) | Number | The maximum length of the object in centimeters | 33
Weight (kg) | Number | The weight of the object in kilograms | 450
Width (cm) | Number | The maximum width of theobject in centimeters | 21.6
Seat Height (cm) | Number | The height of the seat |
Duration (sec.) | Number | The duration of a time-based work in seconds | 418
 

### Artists
Field Name | Type           | Description  | Example
-----------------------|----------------|--------------------------|------------
ConstituentID | Number | A unique number that identifies constituents within the Museum’s collection database | 4360
DisplayName | String | The full name of the artist | Georgia O’Keeffe
ArtistBio | String | Text display of nationality with birth and death years. It may include the country of birth as well | American, 1887–1986
Nationality | String | Accepted country of identification, often distinct from country of origin | American
Gender | String | Gender identification of an individual | Female
BeginDate | Number | Birth year of an individual or an institution’s year of origin | 1887
EndDate | Number | Death year of an individual or an institution’s year of termination | 1986
Wiki QID | String | Unique identifier from Wikidata, Wikipedia, and other Wikimedia resources | Q46408
ULAN | Number | Unique identifier from the Getty Research Institute’s Union List of Artist Names (ULAN) | 500018666
 
 

The datasets are placed in the public domain using a [CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).

For a roundup of how people have used our data so far, visit our [Medium post](https://medium.com/@foe/here-s-a-roundup-of-how-people-have-used-our-data-so-far-80862e4ce220#.f6272outn). We love adding to the list, so please email us at digital@moma.org if you'd like to be included.

## Additional usage guidelines
### Images not included
Images are not included and are not part of the dataset. To license images of works of art in MoMA’s collection please contact [Art Resource](http://www.artres.com/) (North America) or [Scala Archives](http://www.scalarchives.com/) (outside North America).

### Research in progress
This data is provided “as is” for research purposes and you use this data at your own risk. Much of the information included in this dataset is not complete and has not been curatorially approved. MoMA offers the datasets as-is and makes no representations or warranties of any kind.

We plan to update the datasets with new and revised information on a regular basis. You are advised to regularly update your copy of the datasets to ensure you are using the best available information.


### Pull requests
Because these datasets are generated from our internal database, we do *not* accept pull requests. If you have identified errors or have extra information to share, please email us at [digital@moma.org](mailto:digital@moma.org) and we will forward to the appropriate department for review.

### Give attribution to MoMA
MoMA requests that you actively acknowledge and give attribution to MoMA wherever possible. If you use one or both of the datasets for a publication, please cite it using the digital object identifier [![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.159060.svg)](http://dx.doi.org/10.5281/zenodo.159060). Attribution supports efforts to release other data. It also reduces the amount of “orphaned data,” helping retain links to authoritative sources.

### Do not misrepresent the dataset
Do not mislead others or misrepresent the datasets or their source. You must not use MoMA’s trademarks or otherwise claim or imply that MoMA endorses you or your use of the dataset.

Whenever you transform, translate or otherwise modify the dataset, you must make it clear that the resulting information has been modified. If you enrich or otherwise modify the dataset, consider publishing the derived dataset without reuse restrictions.



The writers of these guidelines thank the [Tate](http://www.tate.org.uk/), [Cooper-Hewitt](http://www.cooperhewitt.org/), [Europeana](http://www.europeana.eu/), and the [Carnegie Museum of Art](http://www.cmoa.org/).
