### speakingurl
---
https://github.com/pid/speakingurl

```
npm install speakingurl --save
yarn add speakingurl --dev
bower install --save speakingurl
component install pid/speakingurl

npm test
git clone git@github.com:takagotch/speaingurl.git
cd speakingurl
npm install
gulp
commit apps

gulp bumpup --patch
gulp
gulp release

gulp
gem build speakingurl-rails.gemspec
gem push speakingurl-rails-x.x.x.gem
```

```
gem 'speakingurl-rails'
//= require speaking url
```

```
<script src="bower_components/speakingurl/speakingurl.min.js"></script>
```

```js
var slug;
slug = getSlug("xxx");
console.log(slug);
slug = getSlug("xxx");
console.log(slug);
slug = getSlug("xxx", {
  separator: '_'
});
consolg.log(slug);

slug = getSlug('xxx');
console.log(slug);
slug = getSlug('xx | (xxx) * xxx', {
  custom: {
    '*': 'Boo'
  },
  mark:true
});
console.log(slug);


var options = {
  maintainCase: true,
  separator: '_'
};
var mySlug = require('speakingurl').createSlug(options);
var slug = mySlug("xxx");
console.log(slug);

var options = {
  titleCase: [
    "","","","","",
    "","","","","",
    "","","","","",
  ]
};
var mySlug = require('speakingurl').createSlug(options);
var slug = mySlug('welcome to the jungle');
console.log(slug);

```


