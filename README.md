#Coding Tools

During your studies at Epicodus, you will come across cool resources for learning to use a specific tool. 

For example, you might find a really useful tutorial for making objects with JavaScript. In this instance, JavaScript is known as a *tool* and the blog is known as its *resource*. 

**Epicoding** is a Ruby on Rails application designed to make archiving, sorting and referencing web-dev tools and resources easier. It is designed by and for Epicodus students.

## Contributing

1. Check out the [To Do List](https://trello.com/b/opyMxwK7/epicoding) on Trello.
	* Click on a feature in the **To Do** Column. Note in the "Activity" section that you are working on it.
	* Also make a new card in the **Doing** Column, noting that you are working on a particular feature, as such:
		* `<feature_name> - <your_name>`
2. Fork the repo
3. Create a feature branch
	* `git checkout -b <feature_branch_name>`
	* Complete feature and update your Trello "doing" card accordingly
4. Send a pull request!
    * If you need assistance collaborating with Git, check out [using git for collaboration](http://www.learnhowtoprogram.com/lessons/using-git-for-collaboration) courtesy of Epicodus.
    * Please **do not** mark the feature as done in Trello. This is for the admins only! 
5. Update README saying which task was done using below format


## [Features to Add](https://trello.com/b/opyMxwK7/epicoding)

### Notes RE: Schema

1. **Tools**
    * A Tool is something used and taught in class, like Ruby, Rails, JavaScript, Ember, etc.
    * A tool has many resources.
2. **Resources**
    * A resource is a link that helps you understand a Tool better.
    * A resource belongs to tool. A tool has many resources.
3. **Cats (Categories)**
    * A Category is a classification of a resource.

### Resource Categories:

* Amazing (uncategorized)
* Blog Posts
* Challenges
* Docs
* Examples
* Findings (other)
* Guides
* Hot! (new and trending)

### Working Ideas
Submit your ideas on the Trello page by adding a new card under "feature requests"

1. Incoming students vote on resources parallel to the existing list. After a tool (i.e. Ruby, Javascript) receives 20 votes for its list of resources, the votes are merged with the existing votes for resources. However, at the end of each Epicodus class, the votes, lists and resources are all archived. Thus students can browse through the previous lists compared to the new Join list, as well as their list proper. Simply select a semester from a dropdown and render the new view, Ajax-style.

2. Members of the public can vote for 10 cents a vote. This prevents trolling and may contribute to the site's longevity. Integrate dwolla, paypal and bitcoin payment systems. If nothing else it's API practice.

