# [FullStackOpen Part 7](https://fullstackopen.com/en/part7)

# 7.1: routed anecdotes, step1
Add React Router to the application so that by clicking links in the Menu component the view can be changed.

At the root of the application, meaning the path /, show the list of anecdotes:
![root app](https://fullstackopen.com/static/57c61f000e5eddce42c3a345c2819b77/5a190/40.png)

The Footer component should always be visible at the bottom.

The creation of a new anecdote should happen e.g. in the path create:
![footer](https://fullstackopen.com/static/c393db40b64e8eadd1220bdfccc8eede/5a190/41.png)

# 7.2: routed anecdotes, step2
Implement a view for showing a single anecdote:

![show sinlgle anecdote](https://fullstackopen.com/static/3287ad77ebb90dfac2d734d9801b20b0/5a190/42.png)

Navigating to the page showing the single anecdote is done by clicking the name of that anecdote:

![show single anecdote](https://fullstackopen.com/static/116f966d64a03287b86a6e6a03f6ba81/5a190/43.png)

# 7.3: routed anecdotes, step3
The default functionality of the creation form is quite confusing because nothing seems to be happening after creating a new anecdote using the form.

Improve the functionality such that after creating a new anecdote the application transitions automatically to showing the view for all anecdotes and the user is shown a notification informing them of this successful creation for the next five seconds:

![add notification function](https://fullstackopen.com/static/7640caca8b2a611c4f6203f343b996f9/5a190/44.png)

