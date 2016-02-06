# CSS Accordion

![](/capture.gif)

## Demo

http://codepen.io/rofrol/pen/YwJELy

## Development

```
npm i
npm run css:watch
```

Open `index.html` in the browser.


## Based on

- inspiration from http://www.shanidkv.com/blog/angularjs-accordion
- animate max-height
  - http://stackoverflow.com/questions/3508605/how-can-i-transition-height-0-to-height-auto-using-css/20226830#20226830
  - https://coderwall.com/p/mn2a2g/how-to-use-css-transitions-for-height-and-width-from-0px-to-auto
  - https://bugzilla.mozilla.org/show_bug.cgi?id=571344
- onclick in css
  - http://stackoverflow.com/questions/13630229/can-i-have-an-onclick-effect-in-css/32721572#32721572
  - you can use angular for that http://stackoverflow.com/questions/25141139/toggle-class-with-ng-click-on-several-elements
  - you can also use `:target` for single open http://www.sitepoint.com/css3-vertical-accordion-using-target-selector/ or tabindex http://stackoverflow.com/questions/13630229/can-i-have-an-onclick-effect-in-css/21200841#21200841
- `user-select: none;`
  - http://stackoverflow.com/questions/826782/css-rule-to-disable-text-selection-highlighting
  - http://caniuse.com/#feat=user-select-none
- semantics
  - http://tympanus.net/codrops/2012/02/21/accordion-with-css3/
  - http://stackoverflow.com/questions/29845376/is-using-a-html-label-to-wrap-elements-semantic
  - http://learn.shayhowe.com/html-css/getting-to-know-html/
- no need to specify type for link http://stackoverflow.com/questions/7715953/do-we-need-type-text-css-for-link-in-html5
