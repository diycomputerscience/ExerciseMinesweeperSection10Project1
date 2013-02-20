<h1>Section 11 Project 1</h1>

<h2>Overview</h2>

In the previous section, we focused on creating a shippable product. Ideally code should be released only when the code is satisfactory. However, for the sake of emulating an unfortunate, but real world scenario, and also for  meaning to show the difference between safe code and unsafe code, we will make several changes to our code in this section to make it better and safer than it earlier was.

In this project, we will focus on defensive coding. We will focus on things like:
 1. Validating invariants in a method
 1. Defensive coding - Cloning arguments that are passed to a method before using them in the method
 1. Defensive coding - Cloning return values from a method before returning them

These defensive coding concepts have been explained very well in Joshua Bloch's book <a href="http://www.amazon.com/gp/product/B000WJOUPA/ref=as_li_qf_sp_asin_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=B000WJOUPA&linkCode=as2&tag=adaplearonli-20">Effective Java (2nd Edition) (Java Series)</a><img src="http://www.assoc-amazon.com/e/ir?t=adaplearonli-20&l=as2&o=1&a=B000WJOUPA" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />. If you don't have the book, a couple of internet searches will also yield you good material.

Run ```AllTests``` and verify that 64 tests are run, and 6 tests fail. You have to get them to pass.
