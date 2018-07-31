# Hivery Challenge:

Imagine that you are a newspaper supplying company, you purchase bulk of news papers from The Australian, Sydney Morning Herald, The Daily Telegraph etc and distribute them to the local news stands, convenient stores and wherever newsdecks are presented, 

A newsstand looks something like this

![enter image description here](https://i.imgur.com/6Gy2LfY.jpg)

And here's how a newsdeck would look, where buyers can simply grab a copy and proceed to checkout. 

![enter image description here](https://i.imgur.com/kRMWP6R.jpg)

For simplicity let us assume newsdeck has 5 rows and 4 columns, and each cell can hold 1 newspaper. In real life a newsdeck will have many rows and arbitrary columns and each cell can hold many newspapers stacked upon. 

Since your company is supplying newspapers, it is your best interest in arranging the papers in the newsdeck so that sales can be improved. i.e keep expensive and popular newspapers on the top so that buyers would buy that more, Some times you might have to keep same news papers in multiple cells since they sell out quickly. 

Your company has tie-ups with roughly 50,000 newsdecks all over Australia, now you are building an UI solution which would be used by the person who decides (for the entire Australia) what to put in newsdeck every single day. 

### Requirements
 - Design a virtual newsdeck to visually render the current newspaper arrangement and display stats (total prices, predicted_sales etc)
-  The user can swap (drag/drop) newspapers(icons) within the newsdeck and pull(drag/drop) possible newsfrom another location. (Use the images in the folder `img/newspapers` for icons or download suitable pictures or logos if you think thy would be appropriate)
- Each drag and drop should make a request to the server to calculate `predicted_sales` 
- After enough drag-drops the user might be able to preview his changes (before-after) before submitting his choice( no need to implement Submit).
- If you are applying for the front-end developer roles you can use the below mocked APIs which are self explanatory
 
		https://secure-cliffs-25767.herokuapp.com/hivery/newspapers
        https://secure-cliffs-25767.herokuapp.com/hivery/current_arrangement
        https://secure-cliffs-25767.herokuapp.com/hivery/get_predicted_sales?arrangement=1,1,1,1,2,2,2,3,3,4,4,4,5,8,8,10,11,11,12,12

#### Front-end Developer:
If you had applied the role of front-end developer your **front-end skills** and **design intuition** will be heavily assessed on these guidelines

- If the design optimal where the UI elements(Price details, back button, before/after, statistics, status bar, error messages etc) are placed at intuitive locations for human interaction. 
- If the end product is visually pleasing with consistent color code.
- The end product functions smoothly without any lags, without any JS-console errors. 
- If the end product is responsive for desktops and tablets (mobile can be excluded).
- [Bonus] You thought and implemented additional feature like best arrangement so far, option to take/save snapshot of an arrangement while trying many, used browser local-storage in order to cache `predicted_sales` to avoid server communication, highlighting changes, keyboard shortcuts for undo etc
- [Bonus] You went ahead and used a JS framework (VueJS, Angular or React)
- [Bonus] You wrote automated tests for the UI code with your choice of testing framework. 


#### Full-stack Developer:
Your **front-end skills** will be heavily assessed and basic familiarity in Django, Python & Relational DB is expected. 

- You are expected to build a server side solution using Django and deploy it in your choice of cloud (Heroku, AWS or Azure etc). You can take the above mocked APIs as start & come up your own version of database schema & APIs. 
- Front end solution should be highly performant and responsive to desktop & tablets without any JS-console errors
- You are not expected to have designing skills, so worry not on visual appeal but to keep the product functionable by covering as much as features.  
- [Bonus] You've managed to write automated tests for the front-end code with your choice of testing framework. 
- [Bonus] You've added more front-end features than requested here. 

#### Submission:
Kindly share the links of working solution **deployed in cloud** of your choice (Heroku, AWS etc) and provide a Github link to your solution so that we can see your code. Also don't forget to explain the features you have implemented and why your solution is the best. 

We thank you in ahead for your enthusiasm and very happy coding.
