# Lesson 3: User Interfaces

### SoBA iOS Curriculum

#### Assignment 1

Fork this repository to your own GitHub account. If you have not already set up a GitHub account or are not familiar with forking a repository, refer to [these instructions](https://github.com/phildow/soba-web-html-css) from the web class.

I have created a template Storyboard identical to the one we worked on in class. Complete it to meet the specifications we worked through in class:

1. Create custom view controller subclasses for the two additional views in the Storyboard 
2. The Login button should segue to the login view. Use a modal transition
3. Set up a delegate protocol so that the username and password can be communicated from the login view controller to the main view controller
4. Implement the necessary methods to set the delegate and get the username and password back (log them to the console from the main view controller)
5. Set up additional outlets and actions as necessary: username and password text field, cancel and login buttons, etc
6. Resize the Fancy Options view so that it is 280x200 and reposition its UI elements accordingly
7. The Fancy Options button should animate this view to the center of the screen from offscreen the bottom of the main view
8. You'll need to programmatically initialize the fancy options view controller. A Storyboard segue won't work.
9. Set up a delegate protocol so that you can communicate the love/hate and cats/dogs preference back to the main view controller
10. Animate the fancy options view back offscreen when the Save Changes button is pressed

This assignment should be a little more challenging. Help each other out!

#### Assignment 2

Create a new application using the Tabbed Application template, then complete the following: 

1. Ensure you have a total of four tabs
2. You'll need to add two additional tabs. Use Navigation Controllers for the two new tabs
3. For the two navigation controllers you've added, delete the default table view controller it comes with and use your own custom root view controller
4. For both custom root view controllers, add a button that segues to another view controller. You'll need to add the additional view controllers and connect the segue action. Use a push transition
5. Create a custom sublcass for all of your view controllers (subclass from UIViewController). The application comes with two. Create two additional subclasses for the root view controllers associated with the navigation controllers you added, and create two more subclasses for the two views that you push segue to.
6. Set the subclasses on the view controllers in the Storyboard file correctly!
7. Ensure you have set your subclasses correctly by adding interface to each custom view controller and hooking it up through actions or outlets.
8. Title each tab correctly and each view controller in your navigation controller lists
9. Set a custom image for each tab. You can try the free [Glyphish icons](http://www.glyphish.com/)

#### Assignment 3

Create a new Master Detail application and see if you can figure out what all the code and interface connections are doing. We'll be looking at Table Views and Navigation Controllers in more detail for our next lesson, and I'd like everyone to get a head start. See if you can modify the code to use a custom subclass for you model or to add additional functionality to the table view or detail view. Check the documentation!

#### Assignment 4

Explore [pttrns.com](http://pttrns.com/). Go through the categories at the left. Think about how you might implement one of these interfaces. 

*Pick one and try to implement it*, something with some interface in it, not just a big picture. We'll go over your choices and ideas in our next class.

Many of these interfaces are implemented with custom table views and collection views.