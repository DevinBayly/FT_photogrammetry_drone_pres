# Purpose
This repo is for a presentation to a group on campus. To display the files you can serve them with any program.

To generate pdfs make use of this command while the presentation is being hosted
```
podman run --rm -t --network host -v `pwd`:/slides -u root docker://astefanutti/decktape http://localhost:8080 /slides/slides.pdf

```