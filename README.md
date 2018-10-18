# WAVES Widget for embedding a list of virtual patients into a webpage


## The WAVES Project

The WAVES project combines skill sets of both academic and enterprise partners to make Scenario-based learning (SBL) more accessible for a wide range of professions.  SBL techniques are widely recognised as a key tool in the educational toolkit, for safe training in competency and decision-making.

[http://wavesnetwork.eu](http://wavesnetwork.eu)

## JavaScript Widget How to

Emded the following snippet into any webpage:

```javascript
<script>
        (function (w,d,s,o,f,js,fjs) {
            w['JS-Widget']=o;w[o] = w[o] || function () { (w[o].q = w[o].q || []).push(arguments) };
            js = d.createElement(s), fjs = d.getElementsByTagName(s)[0];
            js.id = o; js.src = f; js.async = 1; fjs.parentNode.insertBefore(js, fjs);
        }(window, document, 'script', 'mw', 'http://olab.wavesnetwork.eu/widget/widget.js'));
        mw('tag', 'keyword');
</script>
<div class="olab-widget"></div>
```

## JavaScript Widget Programming

Clone this repository

Run `npm install`

#### Building the widget
`./node_modules/.bin/webpack --config webpack.config.js`

#### Server in localhost
`./node_modules/.bin/webpack-dev-server --open`


<i>More instructions coming soon..</i>


