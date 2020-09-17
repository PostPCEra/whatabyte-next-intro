# whatabyte-next-intro

### What & Why?
 - This seems the most 'COMPREHENSIVE Step by Step ' example with complete 'Styling for a serious web site' , details are explained  are in these 3 PART tutorial
 - Next.js [Practical Introduction: Pages and Layout](https://auth0.com/blog/next-js-practical-introduction-for-react-developers-part-1/) , see final 'part-3'
 
### TODO
 - make this repo work with 'malearn' react js & next-css versions
 - once works, serach on web, before doing it, only copy these if THIS STYLING schema is good 

### build status
 - as it is 'npm run dev' gives errors
 - fix is : npm uninstall node-sass && npm install node-sass [as stated on this stackoverflow](https://stackoverflow.com/questions/37415134/error-node-sass-does-not-yet-support-your-current-environment-windows-64-bit-w)
 - after above fix, pages showed fine
 - reason for above error is, if you look at package.json , all packages are OLD vesions.
 -
 - Once you upgrade package.json libs to new versions, [we may try the following fix from dev.to site](https://dev.to/vladymyrpylypchatin/comment/m7fg)
```
// next.config.js
const withStyles = require('@webdeb/next-styles')

module.exports = withStyles({
  sass: true, // use .scss files
  modules: true, // style.(m|module).css & style.(m|module).scss for module files
})
```
-
- one more place to look at for Style SASS reference is [this popular NExt js boierplate](https://github.com/pankod/next-boilerplate/blob/master/next.config.js)
