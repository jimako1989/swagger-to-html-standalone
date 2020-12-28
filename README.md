# Swagger YAML/JSON into HTML on stand-alone

Creating HTML OpenAPI Document from swagger files (yaml/json) on stand-alone environment.

![ScreenShot](./api_docs_toppage.png?raw=true "ScreenShot1")

This html file doesn't fetch any resources from the internet.
![ScreenShot](./developper_tool.png?raw=true "ScreenShot2")

# How To Use
```
python swagger-to-html-standalone.py < /path/to/api.(yaml|json) > doc.html
```

FYI: making YAML 1.2 a superset of JSON.
c.f. https://en.wikipedia.org/wiki/YAML

# :warning: NOTE
**ALSO COPY CSS AND JS FILES** distributed from Swagger  not only HTML to show up the HTML API document correctly.
