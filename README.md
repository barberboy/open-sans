Open Sans
=========
Quickly drop [Open Sans] into your project.


Usage
-----
You have several options for using this project:

### Clone with git

```sh
cd styles/fonts
git clone https://github.com/barberboy/open-sans
```

```html
<link rel="stylesheet" href="/styles/fonts/open-sans/open-sans.css">
```


### Download

Download and unpack the [.zip archive](https://github.com/barberboy/open-sans/archive/master.zip):

```sh
cd styles/fonts
wget https://github.com/barberboy/open-sans/archive/master.zip
unzip master.zip
mv open-sans-master open-sans
rm master.zip
```

```html
<link rel="stylesheet" href="/styles/fonts/open-sans/open-sans.css">
```


### Bower

```sh
bower install barberboy/open-sans
```

```html
<link rel="stylesheet" href="/bower_components/open-sans/open-sans.css">
```

If you’d like bower to put it in a different directory, just create a
[`.bowerrc`](http://bower.io/docs/config/) file and specify the
[`directory`](http://bower.io/docs/config/#directory) location:

```json
{
  "directory": "app/public",
  "analytics": false
}
```

### CDN

Quickly test Open Sans on your site by using the CDN hosted by [RawGit]. Feel
free to use it in production as well:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/barberboy/open-sans/2011-02-02/open-sans.css">
```


### Google Fonts

Not for you? Just use Google Fonts instead:

```html
<link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800">
```


Fonts and Weights
-----------------
This project includes Open Sans normal and italic styles in
[five different weights][Open Sans]. Pick and choose what you need.

### Open Sans

```css
body {
  font-family: 'Open Sans';
  font-weight: 300;

  font-family: 'Open Sans';
  font-weight: 400;

  font-family: 'Open Sans';
  font-weight: 600;

  font-family: 'Open Sans';
  font-weight: 700;

  font-family: 'Open Sans';
  font-weight: 800;
}
```

[RawGit]: https://rawgit.com/
[Open Sans]: http://www.google.com/fonts/specimen/Open+Sans
