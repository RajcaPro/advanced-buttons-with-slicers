# advanced buttons with slicers
No room for slicers because your report has too many visuals ? There is a way !
Use this trick and get extra room for your slicers ! 


<img width="366" alt="image" src="https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/922de6c8-9cbc-4519-8b2a-2ac9a1794af2">


He admits at first glance this may seem like black magic. It certainly raises some questions for you such as :
- does the data sort/group when you go from the button to the report page?
- Is it possible to go from the button to the report page?
- How to do this magic trick ?!

Let's start from the beginning. 

1. BUTTON 

First, go to the Insert section then find the element compartment and select the empty button -> BLANK

<img width="258" alt="image" src="https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/70910ecb-49ca-4e5b-ae34-0b5600e2f844">

After adding our blank, let's change a few settings for it such as : 
- text inside -> button style section 
- add shadow options -> button style section 
- change fill -> button style -> fill section
- and change the background so the colours complement each other -> size and style section 

Effect :

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/d001b8a5-5fa8-4fc2-a378-4be62c7d0caf)


To illustrate the changes made by the button, let's add a KPI in the form of Total Revenue and a stack bar chart total revenue by product category.

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/070fc57e-72f6-4dfe-b344-17ef58247476)

2. adding a field for slicers

In the next step we add an empty space for our slicers !

insert section -> elements -> shapes -> rectangle

We format our shape by changing the :

- fill colour -> shape style -> fill
- and border -> shape style -> border

Effect :

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/2eb93698-02b1-412c-8e99-00501d4c8de2)

add slicers -> date (choose what you want, in our case it's the date and the countries)

move slicers to the very top : select slicer -> format section -> bring forward

Finally, add an arrow button and also position it at the top: insert -> elements -> buttons -> arrow


Effect :

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/f4fee647-92d5-4c3e-a3bb-18b7836bd5f2)

The magical moment has arrived in which we will explain how we will connect the rectangle and the slicers to the button!  GET STARTED 🚀🚀🚀

3. Bookmarks will help us in all this by saving the state with the slicers and field displayed !

We need two of them.
1) To display the slicers 
2) To hide the slicers

To create a bookmark, select : view -> show panes -> bookmarks

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/82d8c712-970e-4f83-902d-c0036b2e0b0f)

For the purpose of this task, let's create two bookmarks named X OPEN and Y CLOSE 

After creating the bookmark, click on the 3 dots next to the x option and select update to load the current view into the bookmark.

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/5ca42e6b-c411-41e9-852e-25b39b056450)

Now we want to create a bookmark that hides our filters. 
To do this we go to : view -> show panes -> selection

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/dedda922-a157-49e0-8567-b6a3edb3da35)

We see several slicers, a shape and a button. we hide them by clicking on the icon resembling an eye ;)


![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/10b4c85b-28a3-4d5d-9f9b-0f956360ccce)

Effect :

everything has been hidden :) 

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/ec7722cd-36b0-4c8d-a3c2-0f58feed8ac6)

To update the bookmark use 3 dots and update for "y close".

The final step is to add an action to our "Slicer Settings" button and arrow !

Click on the button to activate the action section.
Next, we select the action type for the bookmark and the previously saved bookmark "x open".

Effect :

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/4501e107-39ab-4a2e-a53b-8e6d980484e6)

by clicking on the button our slicers will be displayed!🚀

Now let's deal with the arrow.
select arrow -> section format -> action -> type bookmark -> "y close"

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/c5ffdcd7-bbc6-4fdd-8754-c25416f5be3b)

now press the arrow and go to report !

We have one VERY IMPORTANT THING TO DO.
Namely, when we select something on one of the slicers and we want to go to the report page because, for example, the slicer field covers the chart, the data changes to the state before selecting the option!!!!


To avoid this we go to our bookmarks, select the 3 dots and uncheck the "DATE" section .

![image](https://github.com/RajcaPro/advanced-buttons-with-slicers/assets/175021059/02886c13-525f-4daa-8fe2-7065e6045338)

That's all in this article ! 

I hope you will use this technique and show it off at work : ) 

Greetings,
Mateusz Rajca





