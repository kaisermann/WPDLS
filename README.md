# WPDLS - WordPress Dashboard/Login Style

Basic custom WordPress admin style made easy

## How to use

1. Import WPDLS main file `index.styl` inside your `.styl` file with something like `@require 'wpdls'`.

2. Override the default style object `wpdls` variable with your custom values.

3. Call the `buildWPDLS()` mixin.

## Default style object
```stylus
wpdls = {
  dashboard: {
    // font: 'Arial'
    background: #fff
    navigation: #000
    submenu: darken(#777, 50%)
    text: #fff
    highlight: #777
    notification: #777
    link: #777

    button: {
      background: #000
      color: #fff
    }
  }

  login: {
    // font: 'Arial'
    color: #fff
    background: {
      color: #000
      // image: '../images/path-to-img.jpg'
      size: cover
    }

    /* Custom logo - Optional, can be deleted */
    logo: {
      // image: '../images/login-logo.png'
      width: 145px
      height: 145px
    }

    /* Custom login alert - Optional, can be deleted  */
    alert: {
      background: #fff
      color: #000
      link: #fff
    }

    /* Custom button - Optional, can be deleted  */
    button: {
      background: #000
      color: #fff
    }

    /* Custom form - Optional, can be deleted  */
    form: {
      background: #fff
      color: #000
      borderRadius: 5px
      // padding: 0
      input: {
        background: #fff
        color: #000
      }
    }
  }
}
```