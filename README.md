# flutter-android-ios
A. Descriptive Questions: 
1. Can we nest the Scaffold widget? Why or Why not? <br />
Answer: We can nest the scaffold widget but we should use one scaffold in one page.
2. What are the different ways we can create a custom widget ? <br />
Answer: we can create custom widget by so many ways
        1. Stateless widget
        2. Stateful widget
        3. Customer Painter
        4. MethodChannel (Incoming intents)
3. How can I access platform(iOS or Android) specific code from Flutter? <br />
Answer: We can access platform specific code via MethodChannel and EventChannel(Streaming)
4. What is BuildContext? What is its importance? <br />
Answer: BuildContext is a locator that is used to track each widget in a tree and locate them and their position in the tree. 
        The BuildContext of each widget is passed to their build method. 
        Remember that the build method returns the widget tree a widget renders. 
        Each BuildContext is unique to a widget.

B. Coding Questions: 
1. Refactor the code below so that the children will wrap to the next line when the display width is small for them to fit.
![Answer 1](https://i.postimg.cc/LHktVw4W/ans1.png?dl=1)
2. Identify the problem in the following code block and correct it. 
![Answer 2](https://i.postimg.cc/jxdMnt6c/ans2.png?dl=1)
3. In the below code, list1 declared with var, list2 with final and list3 with const. What is the difference between these lists? Will the last two lines compile? 
![Answer 3](https://i.postimg.cc/mLbQpjtg/ans3.png?dl=1)

