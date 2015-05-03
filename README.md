<h4>Swift Tinted Button Extension</h4>

A small <i>Swift</i> extension for tinting <i>UIButton</i>, like a <i>UIBarButtonItem</i> or a <i>UINavigationItem</i>. Based on <a href="https://github.com/filipstefansson/UITintedButton">this</a>.

For example:
![alt tag](https://raw.github.com/maximbilan/SwiftTintedButtonExtension/master/img/4.png)

<h5>How to install:</h5>
Cocoapods:
<pre>
pod SwiftTintedButtonExtension
</pre>
Manual:</br>
Copy <i>SwiftTintedButtonExtension.swift</i> to your project.

<h5>How to use:</h5>
<pre>
self.button.setImageTintColor(UIColor.yellowColor(), state: .Normal)
self.button.setImageTintColor(UIColor.blueColor(), state: .Highlighted)
</pre>
