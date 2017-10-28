# pure-css-animated-border

A pure css3 animated border which supports all moden browser.

## CDN Link
```
https://cdn.jsdelivr.net/gh/code-fx/Pure-CSS3-Animated-Border@V1.0/css/animated-border/animated-border.min.css
```

## Demo Link

See the [online demo](https://code-fx.github.io/Pure-CSS3-Animated-Border/).

## 1,2 Line Animated Boder Examples

```

<a href="ui-box top-leftToRight">
  Animated Hyperlink Border
</a>

<div class="ui-box bottom-rightToLeft">
  Animated Div Border
</a>

<button class="ui-box left-bottomToTop">
  Animated Button Border
</button>

<p class="ui-box right-topToBottom">
  Animated Paragraph Border
</p>

```

```
Modify border style, color, width and easing
<style>
  //top border
  .top-leftToRight:before{
    border-top: 1px solid Tomato;
    transition-timing-function: linear;
  }

  //bottom border
  .bottom-rightToLeft:after{
    border-bottom: 1px solid DodgerBlue;
    transition-timing-function: ease-in;
  }

  //left border
  .left-bottomToTop:before{
    border-left: 1px solid smokeWhite;
    transition-timing-function: ease-out;
  }

  //right border
  .right-topToBottom:after{
     border-right: 1px solid MediumSeaGreen;
     transition-timing-function: ease-in-out;
  }
</style>
```


## 4 Line Animated Boder Example
```
<a href="ui-box top-leftStart">
  <span class='ui-border-element'>
    Animated Hyperlink
  </span>
</a>
```

```
Modify border style, color, width and easing
<style>
  //top border
  .top-leftStart:before{
    border-top: 1px solid Tomato;
    transition-timing-function: linear;
  }

  //bottom border
  .top-leftStart:after{
    border-bottom: 1px solid DodgerBlue;
    transition-timing-function: ease-in;
  }

  //left border
  .top-leftStart .ui-border-element:before{
    border-left: 1px solid smokeWhite;
    transition-timing-function: ease-out;
  }

  //right border
  .top-leftStart .ui-border-element:after{
     border-right: 1px solid MediumSeaGreen;
     transition-timing-function: ease-in-out;
  }
</style>
```

## Animated Border Class Name

| Class Name       | Use Span |
| ---------------- |-------------|
| .ui-box .topBottom-leftRightCorner     | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .topBottom-rightLeftCorner      |  ```<span class='ui-border-element'> Your Content... </span>```  |
| .ui-box .forwardBorderTrain | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .backwardBorderTrain | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .border-inOutSpread | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .slideOpposite | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-leftToRight |  |
| .ui-box .right-topToBottom |  |
| .ui-box .bottom-rightToLeft |  |
| .ui-box .left-bottomToTop |  |
| .ui-box .top-rightToLeft |  |
| .ui-box .right-bottomToTop |  |
| .ui-box .bottom-leftToRight |  |
| .ui-box .left-topToBottom |  |
| .ui-box .top-inOutSpread |  |
| .ui-box .right-inOutSpread |  |
| .ui-box .bottom-inOutSpread |  |
| .ui-box .left-inOutSpread |  |
| .ui-box .top-slideOpposite |  |
| .ui-box .right-slideOpposite |  |
| .ui-box .bottom-slideOpposite |  |
| .ui-box .left-slideOpposite |  |
| .ui-box .top-leftStart | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-rightStart | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-rightStart | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-leftStart | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-leftStart-backward | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-rightStart-backward | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-rightStart-backward | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-leftStart-backward | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-leftStart-burst | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-rightStart-burst | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-rightStart-burst | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-leftStart-burst | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-leftStart-burst-backward | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-rightStart-burst-backward | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-rightStart-burst-backward | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-leftStart-burst-backward | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .top-stay | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .right-stay | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .bottom-stay | ```<span class='ui-border-element'> Your Content... </span>``` |
| .ui-box .left-stay | ```<span class='ui-border-element'> Your Content... </span>``` |

## Donate Link

[Donate Now](https://www.paypal.me/codefx).
