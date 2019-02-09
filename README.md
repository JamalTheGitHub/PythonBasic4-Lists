# PythonBasic4 Lists


Prerequisite => From this tutorial onwards, it is expected that you have the following extensions in your Visual Studio Code;

1)Code Runner 2)Python

If you want to know more on how to get Python on Visual Studio Code, google it.

First thing first, create a file called called whatever you want it to be called and save it as ".py". For example like this, "PythonTutorial.py". Navigate to that file and do your coding there.

================================================================================================

<h3>Lists</h3>

What is a <strong>list</strong>? Below is an example of a <strong>list</strong>.

    a = [1,3,-2]

If you look closely, the <strong>bracket,[]</strong> is what we call a list and inside the bracket is what we call <strong>elements</strong> in <strong>Python</strong>. In the above example, we can see that we have <strong>elements 1,3,-2</strong> in a <strong>list</strong> which is assigned to <strong>variable a</strong>. Now use the <strong>print function</strong> to call the assigned variable as below;

    print(a)

The output will just be <strong>"[1,3,-2]"</strong>. However, if we want to add another <strong>integer</strong> to the existing <strong>list</strong>, how would we do that? Here is an example;

    a.append(5)

<strong>append</strong> is a pre-defined function for the <strong>list datatypes</strong> which in layman's term means something like <strong>"add to"</strong>. The <strong>"."</strong> before the <strong>append</strong> is a common notation in order to call a defined or pre-defined function unto a <strong>variable</strong>. In this case <strong>a.append(5)</strong> means <strong>to add 5</strong> into the <strong>list</strong> which was assigned to <strong>variable a</strong>. <strong>Strings</strong> are also allowed in the list. Here is an example on how to add a <strong>string</strong>;

    a.append("I am a string!")

Now <strong>print(a)</strong> and you should be able to see the <strong>string</strong> inside the <strong>list</strong>. That is not all, you can also add another <strong>list</strong> into the existing <strong>list</strong>! Try the example below;

    a.append([33,45])
    print(a)

After running the code, you will see the <strong>new list [33,45]</strong> is in the<strong>list of variable a</strong>! It is like a <strong>listception</strong>! Alright, now that we know how to add to the <strong>list</strong>, how about to remove from the <strong>list</strong>? Look at the example below;

    a = [1,2,3,4,5]
    a.pop()
    print(a)

"<strong>a.pop()</strong>" removes the last <strong>element</strong> within the <strong>list</strong> which is "5". Well, how about removing specific <strong>elements</strong> within the <strong>list</strong>? Well, each <strong>elements</strong> within the list is actually numbered and it always start from index "0". For example, taking the above code, the <strong>element "1"</strong> is actually the index number "0" if we want to select it. The same goes for <strong>element "2"</strong> which is index number "1" if we want to select it. Remember that in a <strong>list</strong> the first <strong>element</strong> is always index number "0". Here is an example on how you could delete a specific <strong>element</strong> in a <strong>list</strong>.

    a = [1,2,3,4,5]
    a.pop(0)
    print(a)

Notice that after running the code, the <strong>element "1"</strong> is not included in the <strong>list</strong> because we have successfully removed it. Okay, but now how can we select the <strong>element</strong> that we want? It is simple and straightforward. It is almost similar to how we would remove the <strong>element</strong> but without <strong>.pop()</strong>. It will look like this;

    a = [1,2,3,4,5]    
    print(a[1])

Notice in the <strong>print function</strong> we have <strong>"a[1]"</strong>. What this means is telling python to select the index number 1 which corresponds to <strong>element "2"</strong> in the <strong>list</strong>. Run the code and see what happens. Is the result as expected? Now that we know how to add, remove and select <strong>elements</strong>, what about editing it? Well it is as simple as selecting an <strong>element</strong> but with a minor modification. Check out the example below;

    a = [1,2,3,4,5]
    a[0] = 33

    print(a)

Upon running the code, you will realize that at index "0", it has replaced <strong>element "1"</strong> with <strong>element "33"</strong>. That is how you edit an <strong>element</strong> within a <strong>list</strong>!

================================================================================================

Alright, now that we have understand the basic concept of <strong>list</strong>, here is an exercise for you to try out.

Given;

    a = ["cat","chicken","sheep"]

Swap the position between the "cat" and the "sheep". You have done this exercise before but with variables. Now with your knowledge of Python so far, solve this.