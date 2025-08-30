The PS files need to be converted to PDF first.

I use ghostscript for this. I go the the directorty and type:

```ps2pdf -dNOSAFER -sPAPERSIZE=a4```

The resulting PDF can be loaded into the tool inkscape to which I have installed a plug-in to export to Silhouette Portrait. I usually load only one page at the time.

I think it is good practice to print the pieces on paper first. Then you will get an idea about the sizes of the pieces and you can use it to see how big the piece of cardboard you will need.

I cut them by choosing: Extensions &rarr; Export &rarr; Send to Silhouette ...
It is good to select the option: "Preview: show cut pattern before sending". There I check the vertices where edges meet in a sharp angle. I check whether both edges are drawn towards that vertex. I prefer the setting to cut all edges twice.

The last pages usually shows me the result of the faces when they are exported from Orbitit. When there are very small pieces I glue them on paper with a printed template for higher precision.

Adjustments can be if needed. To scale up or down the pieces, one can update the variable scaling_size. It tried to make sure that this also keeps the (relative) position more or less the same, but this is in general unverified.
