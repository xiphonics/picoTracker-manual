# Picotracker Manual

## Development

While developing and writing content for the manual, you can have a preview of the site by running:
```
./preview.sh
```

When run in preview mode, `picosite` will serve the website on the url:  http://localhost:8080 and will watch the site directory and its subdirectories for file changes and rebuild the output when it detects modifications to the files.

## Building Outputs

Uses picosite and weasyprint to generate HTML and PDF outputs from the markdown source files.


### HTML

To build the html output run:
```
./build.sh
```

### PDF

TODO: instructions on building PDF with weasyprint.

## Acknowledgements

Thanks to @squiggythings [WaveTracker documentation website](https://github.com/squiggythings/wavetracker-site) for initial CSS design and example of how to use nice, clean semantic HTML.

