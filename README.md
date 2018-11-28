# no-body-functions

Javascript has the most important/basic characteristic that a functional programming language require: functions can be passed as arguments to other functions/methods and they can be returned as the result as well. We can say that with just this ability javascript is a kind of functional programming language from the beginning of the www times :P

In my opinion we can go into the path of functional programming with javascript in 3 steps: 

## 1) Avoid Mutation

Stop mutating objects, create new one instead, this is currently really simple with destructuring js capabilities. And stop using variables and start using constant (change `var` by `const` please). This is the most important step and the one give you most of the benefints of functional programming: avoiding most evil side effects.

## 2) Avoid functions with bodies

If your program is build by functions without bodies means that the approach is not more procedural, because there is no more bodies so there is no more sentences. The functions become just expressions, declarative rules, like logical equations or laws. So we moved from the procedural world to the declarative world. Programming like this make your code to be splitted in several small declarative pieces that at the first look seems more complex than the procedural approach but when you need to do something in a real situation you find that is easier to follow and when you have to do a change it is so much safer because you modify a little expression (or several) that just produce the effect of its result and no other unwanted ones. So you don't need to underestand the whole thing, you can focus just on the part that you have to change.

Lets see an example:

```
TODO: write an example here
```

You can start extracting code from your large procedural functions to smaller ones: 

 ```
 TODO: transform the big function in the example in a set of smaller one
 ```

Then you need to replace the loops by recursive functions

```
TODO: replace the loop by a recursive function
```

Ones you have all the pieces of data calculated by declarative expressions/functions you need to merge all the data and return the result

```
TODO: merge all pieces in one
```


## 3) Use Ramda

Using a functional programming framework like RamdaJs should helps a lot.



