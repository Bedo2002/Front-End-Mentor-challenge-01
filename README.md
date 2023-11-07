# Frontend Mentor - Four card feature section

![Design preview for the Four card feature section coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

**To do this challenge, you need a basic understanding of HTML and CSS.**

## The challenge

Your challenge is to build out this feature section and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should:

- View the optimal layout for the site depending on their device's screen size

Want some support on the challenge? [Join our Slack community](https://www.frontendmentor.io/slack) and ask questions in the **#help** channel.

## Where to find everything

Your task is to build out the project to the designs inside the `/design` folder. You will find both a mobile and a desktop version of the design. 

The designs are in JPG static format. Using JPGs will mean that you'll need to use your best judgment for styles such as `font-size`, `padding` and `margin`. 

If you would like the design files (we provide Sketch & Figma versions) to inspect the design in more detail, you can [subscribe as a PRO member](https://www.frontendmentor.io/pro).

You will find all the required assets in the `/images` folder. The assets are already optimized.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.

## Building your project

Feel free to use any workflow that you feel comfortable with. Below is a suggested process, but do not feel like you need to follow these steps:

1. Initialize your project as a public repository on [GitHub](https://github.com/). Creating a repo will make it easier to share your code with the community if you need help. If you're not sure how to do this, [have a read-through of this Try Git resource](https://try.github.io/).
2. Configure your repository to publish your code to a web address. This will also be useful if you need some help during a challenge as you can share the URL for your project with your repo URL. There are a number of ways to do this, and we provide some recommendations below.
3. Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes to create reusable styles.
4. Before adding any styles, structure your content with HTML. Writing your HTML first can help focus your attention on creating well-structured content.
5. Write out the base styles for your project, including general content styles, such as `font-family` and `font-size`.
6. Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.

## Deploying your project

As mentioned above, there are many ways to host your project for free. Our recommend hosts are:

- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)

You can host your site using one of these solutions or any of our other trusted providers. [Read more about our recommended and trusted hosts](https://medium.com/frontend-mentor/frontend-mentor-trusted-hosting-providers-bf000dfebe).

## Create a custom `README.md`

We strongly recommend overwriting this `README.md` with a custom one. We've provided a template inside the [`README-template.md`](./README-template.md) file in this starter code.

The template provides a guide for what to add. A custom `README` will help you explain your project and reflect on your learnings. Please feel free to edit our template as much as you like.

Once you've added your information to the template, delete this file and rename the `README-template.md` file to `README.md`. That will make it show up as your repository's README file.

## Submitting your solution

Submit your solution on the platform for the rest of the community to see. Follow our ["Complete guide to submitting solutions"](https://medium.com/frontend-mentor/a-complete-guide-to-submitting-solutions-on-frontend-mentor-ac6384162248) for tips on how to do this.

Remember, if you're looking for feedback on your solution, be sure to ask questions when submitting it. The more specific and detailed you are with your questions, the higher the chance you'll get valuable feedback from the community.

## Sharing your solution

There are multiple places you can share your solution:

1. Share your solution page in the **#finished-projects** channel of the [Slack community](https://www.frontendmentor.io/slack). 
2. Tweet [@frontendmentor](https://twitter.com/frontendmentor) and mention **@frontendmentor**, including the repo and live URLs in the tweet. We'd love to take a look at what you've built and help share it around.
3. Share your solution on other social channels like LinkedIn.
4. Blog about your experience building your project. Writing about your workflow, technical choices, and talking through your code is a brilliant way to reinforce what you've learned. Great platforms to write on are [dev.to](https://dev.to/), [Hashnode](https://hashnode.com/), and [CodeNewbie](https://community.codenewbie.org/).

We provide templates to help you share your solution once you've submitted it on the platform. Please do edit them and include specific questions when you're looking for feedback. 

The more specific you are with your questions the more likely it is that another member of the community will give you feedback.

## Got feedback for us?

We love receiving feedback! We're always looking to improve our challenges and our platform. So if you have anything you'd like to mention, please email hi[at]frontendmentor[dot]io.

This challenge is completely free. Please share it with anyone who will find it useful for practice.

**Have fun building!** 🚀




create table lv( level int not null,Semster varchar(50) not null,Course_title varchar(50) not null,
Course_type varchar not null,Crdhrs int null,
Code varchar(50) not null,Preq varchar(50) not null);

Insert into lv( level ,Semster ,Course_title ,Course_type ,Crdhrs,Code,Preq)
values
(1,'1_st','General Chemistry(1)','Obligatory',3,'CH1101','-------'),
(1,'1_st','Mathematices(1)','Obligatory',3,'MA1101','-------'),
(1,'1_st','Physics', 'Obligatory',3,'PH1121','-------'),
(1,'1_st','Scientific English', 'Obligatory',2,'UN1101','-------'),
(1,'1_st','General Physics','Optional',3,'PH1125','-------'),
(1,'1_st','General Biology', 'Optional',3,'BIO1101','-------'),
(1,'1_st','Mathematical statistics','Optional',3,'MA1103','-------'),
(1,'1_st','Programming','Optional',3,'CS1101','-------'),
(1,'1_st','تاريخ وفلسفة العلوم','Optional',1,'UN1103','-------'),
(1,'1_st','مبادئ الإدارة والقيادة', 'Optional',1,'UN1105','-------'),
(1,'1_st','الثقافة البيئية','Optional',1,'UN1107','-------'),
(1,'2_st','General Chemistry(2)','Obligatory',3,'CH1202','CH1101'),
(1,'2_st','Mathematices(2)','Obligatory',3,'MA1202','MA1101'),
(1,'2_st','Physics(2)', 'Obligatory',3,'PH1222','PH1121'),
(1,'2_st','اللغة العربية', 'Obligatory',2,'UN1202','-------'),
(1,'2_st','Tutorial','Obligatory',3,'CH1204','CH1101'),
(1,'2_st','Introduction to Biophysics', 'Obligatory',3,'PH1226','-------'),
(1,'2_st','Applied Mathematics ','Optional',3,'MA1204','-------'),
(1,'2_st','Algebra','Optional',3,'MA1206','-------'),
(1,'2_st','التفكير النقدى','Optional',1,'UN1204','-------'),
(1,'2_st','الثقافة الإسلامية', 'Optional',1,'UN1206','-------'),
(1,'2_st','التعليم الذاتي','Optional',1,'UN1208','-------'),
(2,'1_st','Computer Systems','Obligatory',3,'CS2101','-------'),
(2,'1_st','Computer Programming','Obligatory',3,'CS2103','CS1101'),
(2,'1_st','Abstract Algebra', 'Obligatory',3,'MA2103','MA2106'),
(2,'1_st','Mathematical Analysis(1)', 'Obligatory',1,'MA2105','MA2102'),
(2,'1_st','Transferable Skills','Obligatory',1,'TS2103','-------'),
(2,'1_st','Discrete Mathematics', 'Optional',2,'MA2107','ST1206'),
(2,'1_st','Mathematical methods','Optional',3,'MA2121','MA1101'),
(2,'1_st','Probability Theory(1)','Optional',2,'ST2101','ST1101'),
(2,'1_st','File Processing','Optional',3,'CS2105','CS1101'),
(2,'2_st','Mathematical Analysis(2)','Obligatory',3,'MA2208','MA2105'),
(2,'2_st','Linear Algebra & Solid Geometry', 'Obligatory',3,'MA2220','MA1202'),
(2,'2_st','Digital Logic & Algorithms','Obligatory',3,'CS2202','CS2103'),
(2,'2_st','Data Structure & Algorithms','Obligatory',3,'CS2204','CS2103'),
(2,'2_st','Number Theory','Optional',3,'MA2212','MA1206'),
(2,'2_st','Data Basic systems','Optional',3,'CS2206','CS2103'),
(2,'2_st','Object Oriented Programming', 'Optional',3,'CS2208','CS2103'),
(2,'2_st','Statical Inference(1)','Optional',3,'ST2206','ST2101')
SELECT*FROM lv
