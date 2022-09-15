<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Girl with a Pearl Earring"
       author="JSTOR Labs team"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
       <param ve-knightlab-timeline source="17V2RrKTL6Y0x5_0KSPMEX4jjowek5miliKxiM8" timenav-position="bottom" hash-bookmark="false" initial-zoom="1" height="750">

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 
20th century after the earring worn by the girl portrayed there.[^1]
By the beginning of the Medieval period, the works of classical authors such as Pliny and Dioscorides were continuously collected and reproduced to create a genre of manuscripts known collectively as herbals. Today, we define herbals as a family of related books produced by naturalists, physicians, and proto botanists that identify and describe plants through text and/or illustrations and explain plants’ medicinal virtues, often incorporating local or indigenous knowledge as well as recipes for therapeutic preparations. As a genre, herbals were also highly interconnected. Authors of herbals routinely cited one another, commented on, or translated previously published herbals, synthesizing information on plant nomenclature, origin, and botanical lore in the process.
<param ve-entity eid="Q12554" title="Middle Ages">
<param ve-entity eid="Q297776" title="Pedanius Dioscorides">
<param ve-entity eid="Q6165948" title="herbal" aliases="herbals">
<param ve-knightlab-timeline source="17q3WVPouSqCFiSNd9b-eSkDNdRTM7d3JNBqBRQxi2hE" timenav-position="bottom" hash-bookmark="false" initial-zoom="1" height="750">
{#paragraph3}

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

## Google Books

Google Books test
<param ve-iframe src="https://archive.org/details/speciesplantar02linn/page/n3/mode/2up?view=theateroutput=embed"
                      

      

