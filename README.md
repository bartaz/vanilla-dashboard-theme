# Vanilla Dashboard Theme

This is the Vanilla Framework theme for dashboard based websites.

## Theme local development

The simplest way to run Vanilla dashboard theme is to first [install Docker](https://docs.docker.com/engine/installation/) (Linux users may need to [add your user to the `docker` group](https://docs.docker.com/engine/installation/linux/linux-postinstall/)), and then use the `./run` script to build the site:

``` bash
./run build  # Build the CSS into the ./build/ directory
# or
./run watch  # Dynamically watch for changes to the Sass files and build automatically
```

### Viewing patterns in the browser

The [examples directory](https://github.com/vanilla-framework/vanilla-dashboard-theme/tree/develop/examples) contains example markup for each component of the framework.

To view these examples in the browser, run the local server with:

``` bash
./run serve
```

Once the containers are setup, you can visit <http://0.0.0.0:8102/vanilla-dashboard-theme/> in your browser to see the examples.
