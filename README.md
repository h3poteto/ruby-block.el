# ruby-block.el --- highlight matching block


This file is ruby-block.el which is cusomized for [zenspider/enhanced-ruby-mode](https://github.com/zenspider/enhanced-ruby-mode).
When you use enhanced-ruby-mode instead of ruby-mode, you can not use ruby-block.
Because ruby-block require ruby-mode.


So I customized ruby-block.el for enhanced-ruby-mode.
You can use ruby-block in enhanced-ruby-mode, if you use this ruby-block.el.


Original ruby-block.el is [adolfosousa/ruby-block.el](https://github.com/adolfosousa/ruby-block.el).



## Installation

Copy this ruby-block.el in your .emacs path.

```
(require 'ruby-block)
(ruby-block-mode t)
(setq ruby-block-highlight-toggle t)
```


This software require enhanced-ruby-mode.
