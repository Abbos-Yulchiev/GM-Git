# GM-Git

Of all the conversations I find myself having over and over in this field, I think more than anything else I’ve been a
broken record convincing teams **not** to adopt GitFlow.

Vincent Driessen’s post “A successful Git branching model” – or, as it’s become commonly known for some reason,
“GitFlow” – has become the de facto standard for how to successfully adopt git into your team. If you search for “git
branching strategy” on Google, it’s the number one result. Atlassian has even adopted it as one of their primary
tutorials for adopting Git.

Personally, I hate GitFlow, and I’ve (successfully) convinced many teams to avoid using it and, I believe, saved them
tremendous headaches down the road. GitFlow, I believe, leads most teams down the wrong path for how to manage their
changes. But since it’s such a popular result, a team with no guidance or technical leadership will simply search for an
example of something that works, and the blog post mentions that it’s “successful” right in the title, so it’s very
attractive. **I’m hoping to possibly change that with this post, by explaining a different, simpler branching strategy
that I’ve used in multiple teams with great success**. I’ve seen GitFlow fail spectacularly for teams, but the strategy
I outline here has worked very well.
