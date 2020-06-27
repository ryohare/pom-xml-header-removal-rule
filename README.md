# pom-xml-xsd-removal-rule
This rule will remove findings that occur when Fortify flags the XML document header which declares the pom.xml XSD with an external link. It also provides some examples of rulescript.
# Usage
```bash
sourceanalyzer -b pom  ./
sourceanalyzer -b pom -show-files
sourceanalyzer -b pom -scan -analyzers configuration -rules pom-xml-ignore-header.xml
``` 
