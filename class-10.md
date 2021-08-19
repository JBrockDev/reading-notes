
# Class 9 - Reading Notes

## Error Handling & Debugging

Regardless of how well you understand Javascript, you'll run into plenty of times where you've made an error. One reason more veteran coders are faster is their experience with error handing and debugging. You can easily save dozens if not hundreds of hours of time over the course of a large project if you know how to effectively locate errors as well as pre-emptively handling errors. 

Understanding the order of execution can help with figuring out where to begin looking to narrow down an issue. Having a solid knowledge of how the scope of variables work will help to quicker realize that maybe a variable doesn't exist in your current context and that's why you're getting an undefined output. The Javascript interpreter, like other interpreters, process one line at a time. When it enters a function, it adds the function being called to the top of the stack as after it's completion in that function, it will need to execute whatever code remains in the original function. For example, renderTable function might call renderRow function. When we first entered the renderTable function it was thrown to the top of the stack, then when we called the renderRow function from the table function, that one was thrown on the top. After we complete renderRow, that item is thrown off the stack and we are back in the renderTable function. When the renderTable function is complete, we then throw that off the stack. 

We can utilize `debugger;` to tell the browser that we want to debug lines of code. This allows us to step through lines one by one, just how the interpreter reads the code. We can also jump over methods to avoid going into them if we don't need to see the exact operation or values of the function being called. 