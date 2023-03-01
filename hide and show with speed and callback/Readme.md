Syntax:

$(selector).hide(speed,callback);

$(selector).show(speed,callback);

The optional speed parameter specifies the speed of the hiding/showing, and can take the following values: "slow", "fast", or milliseconds.

The optional callback parameter is a function to be executed after the hide() or show() method completes (you will learn more about callback functions in a later chapter).

The following example demonstrates the speed parameter with hide():



```
Example
$("button").click(function(){
  $("p").hide(1000);
});
```
