# vHomelander 

vHomelander is a [Hugo](https://gohugo.io/) theme for technical documentation sets, providing simple navigation, site structure, and more.

This is not an officially supported VMware product, but we're having fun with it, aren't we?

## Prerequisites

The following are basic prerequisites for using vHomelander in your site:

- Install a recent release of the Hugo "extended" version (we recommend version 0.53 or later). If you install from the 
  [release page](https://github.com/gohugoio/hugo/releases), make sure you download the `_extended` version 
  which supports SCSS.

- Install `PostCSS` so that the site build can create the final CSS assets. You can install it locally by running 
  the following commands from the root directory of your project:

  ```
  sudo npm install -D --save autoprefixer
  sudo npm install -D --save postcss-cli
  ```

<!-- ## Example and usage

TODO: Create this repo
You can find an example project that uses vHomelander in the [vHomelander Example Project repo](https://github.com/mikeroysoft/vhomelander-example).The vHomelander Example Project is hosted at [https://mikeroysoft.github.io/vhomelander/](https://mikeroysoft.github.io/vhomelander/). -->

To use the vHomelander theme for your own site:

  - (Recommended) Copy the [example project](https://github.com/mikeroysoft/vhomelander-example),
     which includes the vHomelander theme as a submodule.
    You can customize this pre-configured basic site into your own vHomelander themed site. 
    
  
  - Add vHomelander to your existing Hugo site repo's `themes` directory. You can either add vHomelander as a Git submodule, or 
    clone the vHomelander theme into your project.

    Most of the necessary content (menus, buttons, hero text, 'featured' images) can be added into the config.toml and index.html files by using shortcode blocks.
See the [vHomelander Getting Started Guide](https://mikeroysoft.github.io/vhomelander/docs/getting-started/) for 
details about the various usage options.

## Documentation

vHomelander has its own user guide (using vHomelander, of course!) with lots more information about using the theme, which you can find at [https://vHomelander.dev/](https://vHomelander.dev/). Alternatively you can use Hugo to generate and serve a local copy of the guide (also useful for testing local theme changes), making sure you have installed all the prerequisites listed above:

```
git clone --recurse-submodules --depth 1 https://github.com/mikeroysoft/vhomelander.git
cd vhomelander/example-lander-site/
hugo server --themesDir ../..
```

Note: you need the `themesDir` flag when running Hugo because the site files are inside the theme repo.

## Contributing 

Please read [CONTRIBUTING.md](https://github.com/mikeroysoft/vhomelander/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.
See also the list of [contributors](https://github.com/mikeroysoft/vhomelander/graphs/contributors) who participated in this project.

## License 

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](https://github.com/mikeroysoft/vHomelander/blob/master/LICENSE) file for details
