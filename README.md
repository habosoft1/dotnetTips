# dotnetTips
tips for improving dotnet skills

Ok, do you have any experience with C#, HTML, or JavaScript ? Because you are going to need to learn that language. Do you have any experience with any object-oriented language?

If you are completely new to web development ... you are probably not going to knock out this project overnight, so manage your own expectations.

So, some things to do:

Development Environment: Visual Studio. Download VS 2019 Community Edition. You can also get VS Code, but frankly, unless you are Linux, I only use VS Code when I want something lightweight to just quickly edit a few files with. If I'm doing serious work, its in the full VS IDE.

Back-End Logic: C#. Dive into the Official MS Docs on C#. Go through that tour. Try sample code yourself in VS. Type it in, don't copy. Typing it will start getting you familiar with the language faster.

ASP.NET Core. Dive into the Official MS Docs on ASP.NET Core. Forget random tutorials and such on youtube for now. Check out every section here. They have videos on various topics and question under the Free Courses section.

Data Storage: Entity Framework Core. Dive into the Entity Framework Core docs. EF Core is what you'll use for most of your back-end storage needs. If you have an app idea, use this to manage the data. Use SQL Server (a lightweight version can be installed with VS) initially, for simplicity's sake.

Unit Testing: Xunit. If you write code, you need to build unit tests for as much of it as you can. This makes sure you find out you broke something elsewhere in your project as soon as it happens. Well, as soon as you build the project and the tests fail. Read up on some articles like this one: https://wakeupandcode.com/unit-testing-in-asp-net-core/ or MS's own docs on Unit Testing.
XUnit is the most popular unit testing framework for .NET, as far as I know. Unit testing lets you define your expectation of how a section of code should work, provide the test with some scenarios, and the expected results. When you edit code, it can have effects in a large project that can result in errors that can escape detection for a long time without unit tests, leading to a maintenance nightmare when the bug is found and the reason for it breaking is hard to track down.

Formatting: HTML and CSS.

The Mozilla Developer Network (MDN) has good docs.

Learn a nice design toolkit like Bootstrap or Material. Both provide a lot of CSS styling that can help you start things off looking nice. Their components are built to work cross-browser and will help build a responsive site (see "design for the web").

Client-side Logic: JavaScript. Right now, you could skip learning JavaScript if you build a Blazor project, but if you want to get real world experience with an existing web project at an employer, you'll want to pick up JavaScript (JS) as well. It's not going away any time soon, so that's a safe investment of time. See the MDN link in #5 ^^^ where they have docs on JS as well.

Accessibility. Pay attention to that in the MDN docs. There was a thread on reddit a few days ago where someone said they had no idea accessibility applies to websites. Just so we're clear - people access websites. People with visual handicaps therefore need sites to be accessible. There are tools and professional standards to aid with this. There are also laws and regulations, but honestly, its just good practice. You will be asked (or should be asked) accessibility related questions in most web dev job interviews.

Design for the Web: Responsive Design. Google's got good docs on responsive design.

Learn from other people's mistakes. Find "beginner mistakes" articles like these, that tell you what the most commonly made mistakes are. Seriously, this should be one's go-to move any time learning anything new. The internet is a treasure trove of 'lessons learned' provided by people who went there before you did, messed up, and now want to share what they learned.

https://docs.microsoft.com/en-us/aspnet/aspnet/overview/web-development-best-practices/what-not-to-do-in-aspnet-and-what-to-do-instead

https://dev.to/emmabostian/6-mistakes-youre-making-as-a-beginner-web-developer--how-to-avoid-them-5gj4

find more and read them. :)

Know How it will Look: Get All the Browsers. Install at least MS IE 11, MS Edge, Chrome, and Firefox to avoid the common mistake of thinking "it works on my browser." or "it works on my machine". You can tell VS to run a webapp in any browser installed on your machine. One will be default of course, but there's a dropdown to select the others.

Learn with some live code: Visual Studio Templates. Create a project in Visual Studio using one of the included templates. Use it to try some of the example code in various sections. If learning about something, that will give you a working project to insert the examples into. You can also experiment with the live code in such a project, changing HTML or CSS code and watching how it changes things.

Questions and Answers: Stack Overflow. Every now and then something will come up and be puzzling. I know people who have been doing this for decades and they still hit Stack Overflow pretty regularly to check on something (or answer other people's questions). It is a much better place to get an answer to a specific technical question than reddit or other sites, IMO.

Book learning! O'Reilly. It may be worthwhile to invest in a paper book. Yes, really. O'Reilly has been famous for decades for their excellent tech books. O'Reilly's latest C# book is a version behind, I think, which is still going to be mostly correct. C# hasn't changed that much since C# 7.0. Get the paper version - code formatting in kindle books and PDFs is always hit or miss, in my experience. Plus, it's a 1000-page tome. Can be fun to flip around it in reading this and that.

That's pretty much it. Also: practice practice practice. Is it a lot to read through? Well ... yes. But most of it is easy when looked at individually, so don't let the volume of info be intimidating.
