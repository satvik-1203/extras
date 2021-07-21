<h1> This is where I start.</h1>

To install next js, its pretty straight forward, just type 
`yarn create next-app` or npx `create-next-app` and for the typescript support just add the -typescript flag at the end and that should do it:). 

Once you successfully install nextjs on ur folder, you should see a complete different folder structure from the common create-react-app (CRA). 

![Screen Shot 2021-07-21 at 8.12.10 AM](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5ynx88s8lykfzxa2ljm2.png)

You might have some what similar or no depending on the package manager and TypeScript.And at first you wont be seeing .next but it should be there once you start the app.

Now let's look at what each folder does.  

**.next** is where nextjs keeps all the built content so its nothing for us to play with :). 

**node_modules**where we store our node modules, does what the names says.

**public** anything that is kept in that folder you can access it with url. suppose you have a image.png there. if you type, *domain/image.png* you will get there :). 

**styles** like the name sounds, just for putting your css/sass in a folder

**pages** This is where next js shines itself. In the pages folder, each of the file is given with its specific route. 
`Each file must have a default export so that component gets loaded on the url` 
Example: pages -|
                |-> about.tsx . Now if we go to domain/about we should be able to see what the about.tsx is rendering. 
Note: All files in pages are preferred to be lowercased, especially index.tsx. Since these files are api routes, and by now you should know that api routes are always preferred to be in lowercased tho they can work uppercased as well.

*How do we do dynamic routing in nextjs?* 
example : domain/about/:id. Its actually fairly simple in next js.   pages -> about -|
                      |-> index.tsx (main page), 
                      |-> [pid].tsx(dynamic routing) 
We will also get into dynamic routing as we go more in to the blog.
![Screen Shot 2021-07-21 at 8.54.29 AM](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/39o3b2i6na1jaas6sdjr.png)

**In pages we also see api folder** this is for the purpose of backend api calls. we will discuss this in the end. you can also use node & express as you backend instead of next.js but its good to know it exists. 

What makes nextjs far superior over CRA ? 
The forms of rendering nextjs has. 

CRA - uses Client side rendering. What does this mean? 


 


