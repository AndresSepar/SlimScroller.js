# tinySmoothScroller
A smooth-scrolling function under 0.4 Kb (minified), with no dependencies.

##How to use
Just use the `tinySmoothScroller`-function with three parameters.
- Target position in `px`
- Optional duration in `ms`
- Optional switch to horizontal-scrolling in `boolean`
- Optional callback-function

##How small is this
The tidy, uncompressed code is less than one kilobyte. The minified code is less than half a kilobyte.

##Example
```
tinySmoothScroller(200,'x',function(resultPosition){
  console.log('The scroll position is now '+resultPosition);
});
```

##Is it pretty?
I am not sure. It works great though.

##Thanks
This is a smaller fork of [alicelieutier's smoothScroll](https://github.com/alicelieutier/smoothScroll).
