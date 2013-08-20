# The Paradox of Choice
- soedar
- soedarsono
- 2013/08/21
- thoughts
- published

When it has become clear that I would need to blog my thoughts for this course, I embarked on a journey to determine my blog engine of choice. I did my research, evaluated the pros and cons of the various options, and I came up with a list (okay, okay, the 'list' was actually a virtual list)

## Hosted blog services
- Wordpress.com: The cool features need $. And I can't show off my uber 1337 design skills.
- Blogger.com: That is so 2000s (Why do companies buy other companies and then literally stop innovation?)

## Self Hosted blog services
- Wordpress.org: I don't really want to manage a database. It's just a blog! Backing up posts would probably be a huge pain. (I *really, really* don't like losing data)
- Dropplets: Seems pretty cool with markdown posts. Easy templating. But I can't track whether you are viewing my blog.
- Or I could roll my own. Should be a fun project, and I can have full control. But it *can* be quite a lot of work to make everything right. Do I really need/want more work...

I decided that I didn't care whether you are reading my posts or not. And I decided that I don't want to reinvent the wheel. So I downloaded Dropplets, set up an aws instance, and voila! All done! And I can host my posts in a github project (so I would always have access to it, even after I decided to close the blog in the future). Sweet!

Like the real world, information is not perfect. We can hardly predict the future, and we'll never know if we need some features that we initially wanted. After the first week, it seems clear that there are 2 features that the blog probably would need but I had not considered:

- RSS Feed (PHEW! Dropplets auto generated the RSS feed.)
- Comments (Twitter driven comments... hmm. I hope it will do. Or I probably have to integrate discuz. ) (P.S. Prof Colin, would Twitter driven comments be ok? :p)

Barry Schwartz has an excellent TED talk (I have shamelessly stole his title), titled [**The Paradox of Choice**](http://www.ted.com/talks/barry_schwartz_on_the_paradox_of_choice.html/ "The Paradox of Choice"). Using somewhat dramatic and exaggerated examples, he illustrates how having more and more choice actually makes us unhappy. In particular, we now blame ourselves for choosing an imperfect option, instead of blaming the world for not having a perfect one.

The reason I raised this up is that I believe everyone will inevitably run into this problem. With more and more available options out there, it becomes harder and harder to choose. Unsurprisingly, our team ran into this problem when we are deciding which backend/middleware solution we wish to employ.

For the backend/middleware, from the top of my head, we have:  

- Python
	- Django
	- Flask

- Ruby
	- Rails
	- Padrino

- node.js
	- Express
	- Sails.js

- PHP
	- Vanilla/Roll-your-own (omg the *horror*)
	- CakePHP
	- CodeIgniter

- Java (I actually think static typing is a good idea. Sue me.)

So many choices! And I'm not even trying to be comprehensive. I'm pretty sure if you Google your favorite language and web framework, it is probably a good bet that there would be substantial list of projects in various stages of maturity and popularity. 

Being somewhat exposed to the lean startup and development model, the decision on which framework/language to be used should rest on the expertise of the group. In other words, if most members in the group have had prior experience developing Ruby on Rails (RoR) application, you should definitely use RoR in your project, especially for your Minimum Viable Product, when you just want to deliver the minimum and most compelling feature set that you wish to showcase for your product.

However, in the case of our group, our members are relatively competent developers with pretty diverse background (aka no common experience on a language/framework). In the spirit of trying something new and making mistakes, we decided to learn a new language and framework (namely node.js + sails.js). Although this might seem like a risky decision to use something that no one has had any prior experience in, I believe that we could pull this off given our experience using other web frameworks and our competency as developers. Web frameworks, at the heart of it, largely follow some similar principles and patterns, and I believe that we would be able to grasp the new framework.

Would we come to regret our decision, and then bang our head against the wall when we realize that we **really** need feature X that is a mature feature in framework Y but is not implemented in our choice framework Z? Given the large number of choices that we have, Schwartz seem to think so, and I am inclined to believe him (After all, I have already somewhat regretted my decision to use Dropplets for my blog). However, I believe that for developers, our strength and value lies in our ability to assimilate new ideas, evaluate the effectiveness of all available options, and if possible (but incredibly difficult), come up with a better solution to solve an existing problem.

P.S. For the record, I think teaching PHP/MySql might be a little dated. There are better web frameworks that allow you to do more whilst learning less, with less chance of screwing up. 