# ubl-work-on-svg-images

We are working on converting all the current art work for UBL to SVG files going forward.

The `imageSummary.xsl` stylesheet is executed from the UBL repository directory, reading the local `UBL.xml` file and local `art/` directory to produce the result:
```
xslt2pe UBL.xml utilities/images/imageSummary.xsl ~/t/compare.fo new-dir=/Users/admin/t/new-images/ ; AHFCmd -d ~/t/compare.fo -o ~/t/compare.pdf -silent ; open ~/t/compare.pdf
```



