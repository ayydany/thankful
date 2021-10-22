# thankful
 
![preview](https://github.com/ayydany/thankful/blob/master/preview.png?raw=true)
[live version](https://danyboss.github.io/thankful/)

## Instalation
Simply download from [here](https://github.com/ayydany/thankful/archive/refs/heads/master.zip) and open it locally from your browser.

If you want to select it as your homepage thats gonna depend on what browser you're using.

* **Google Chrome**

  Go to the settings. In *Appearance*, check *show home page* and modify the link with the URL of the startpage. 
  
  Download the extension [*New Tab Redirect*](https://chrome.google.com/webstore/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmna?hl=en).

* **Mozilla Firefox**

  Go to the settings or copy/paste *about:preferences* in the URL bar. In *General*, copy/paste the URL of the startpage (it should be something like 
  
  `file:///C:/Users/[Your name]/Documents/thankful/index.html` 
  
  in *Home Page* and choose the option *Show my home page* for *When Firefox starts*.
  
  Download the add-on [*New Tab Homepage*](https://addons.mozilla.org/en-US/firefox/addon/new-tab-homepage/), it'll redirect you to your homepage each time you open a new tab.

## Customization
You can and probably must change the links that the webpage uses to make it your own.

To change the links open *index.html* and inside the `container` you'll find several `linkblock` elements, each one of these is a group of links, so to change what they point to all you need to do is replace to where the `a` tags point to, for example to change this link:

```html
<li><a href="https://www.link.com/">Link Title</a></li>
```

to point to google.com all you need to do is replace the link and title as such:

```html
<li><a href="http://www.google.com">clicking on me goes to google.com now</a></li>
```

It's also possible to change the search script to add new or remove old search variables, I'll add a simple tutorial on that later on but it should be pretty straighforward with minimal javascript knowledge.
