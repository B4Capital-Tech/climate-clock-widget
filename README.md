# Build the Climate Clock widget for your website.

### Install prerequisites
Make sure you have [git](https://git-scm.com/downloads) and [yarn](https://yarnpkg.com/en/docs/install) for your system.

### Get the code
``` 
git clone https://github.com/BeautifulTrouble/climate-clock-widget.git
cd climate-clock-widget
``` 

### Install the dependencies 
```
yarn install
```

### Test your build on http://localhost:8080
```
yarn serve
```

### Produce dist/widget-v2.js
```
yarn build
```

Once built, the clock widget can be included on your site using 

```  
<script src="https://yourdomain.com/path/to/widget-v2.js" async></script>
<climate-clock />
```  
