# **EXAM #2 NOTES**






---


**2.8 Distributed Cognition**

**[GOAL #1] Students will understand methods for analyzing systems as having knowledge distributed across multiple artifacts and individuals.**



*   Cognition on its own is interested in the kinds of thought processes and experiences. We naturally think of those as occurring inside the mind. But distributed cognition suggests that models of the mind should be extended outside the mind. This theory proposes expanding the unit we use to analyze intelligence from a single mind to the mind equipped with other minds and artifacts and their relationships.
*   One of the seminal works in distributed cognition research is a paper in the Journal of Cognitive Science from 1995 called “How a Cockpit Remembers its Speeds”.
    *   The cockpit is a collection of controls, sensors, and interfaces, as well as the pilots themselves.
    *   This paper title tells us that it is this entire system: the pilots, the sensors, the controls, and the interfaces amongst them ⇒ that system as a whole is doing the remembering.
    *   No individual part in isolation remembers what the system as a whole remembers.
    *   ![screenshot](/images_Exam2/image16.png)

*   Distributed cognition is deeply related to the idea of cognitive load.
    *   Recall that cognitive load refers to your mind’s ability to only deal with a certain amount of information at a time.
    *   Distributed cognition suggests that artifacts add additional cognitive resources. That means the same cognitive load is distributed across a greater number of resources. Artifacts are like plugging extra memory sticks into your brain.
    *   Distributed cognition suggests models of cognition should be extended outside the mind
*   Every task you offload to artifacts decreases your personal cognitive load (cruise control = artifact; decreasing cognitive load while driving) (paper and pen = artifacts; decreasing cognitive load while doing a complex math problem)
*   Something important to note is that distributed cognition isn’t really another design principle.
    *   Distributed cognition is more of a way of looking at the interface design; it’s a way of approaching the problem that puts your attention squarely on how to extend the mind across artifacts. We could actually view many of our design principles as examples of distributed cognition.
    *   The point is that distributed cognition is a way of looking at interfaces and interface design that focuses your attention on what systems as a whole can accomplish as opposed to individuals on their own.
*   Distributed cognition is a perspective on analyzing systems that helps us emphasize the cognitive components of interfaces themselves. It helps us look at the things we design as extensions of the user’s own cognition. We can view anything from notes on a desktop to the entire internet as an extension of the user’s own memory.

**[GOAL #2] Students will understand the role of social cognition in interface design.**



*   Distributed cognition is concerned with how the mind can be extended by relations with other artifacts and individuals. Because we’re interface designers, we probably focus most of our time on the artifacts part of that. After all, artifacts are what we’re designing.
*   But the other part of distributed cognition, distributing across individuals, presents a powerful opportunity as well: the social portion of distributed cognition is concerned with how social connections create systems that can together accomplish tasks.
    *   It’s also concerned with the cognitive underpinnings of social interactions themselves: it’s interested in how perception, memory, and learning relate to social phenomena

**[GOAL #3] Students will understand the perspective of situated action in designing interactions and its focus on acting in the world.**



*   Like distributed cognition, situated action is strongly concerned with the context within which people interact.
*   But unlike distributed cognition, situated action is not interested in the long-term enduring or permanent interactions amongst these things.
*   That’s not to say the theory denies the existence of long-term memory, but it just has a different focus: **situated action** focuses on humans as improvisers.
    *   It’s interested not in the kinds of problems that people have solved before, but in the kinds of novel, situational problems that arise all the time.
    *   That's an important view for us to hold as interface designers.
    *   While we like to think we’re in charge of structuring the task for our users, in reality the task that they perform is going to grow out of their interaction. We can try our best to guide it in certain directions, but until the user gets their hands on it, the task doesn’t exist. And once they get their hands on it, the task is what they do, not what we designed.
*   **Takeaways**
    *   We must examine the interfaces we design within the context in which they’re used.
    *   We must understand that the task that users perform grows out of their interaction with our interfaces -- we don’t define it.
    *   We can try to structure it as much as we can, but until the users get started, the task doesn’t exist -- and once they get started they play a significant role in defining the task.
*   Situated action gives us a valuable lens especially to examine issues of memory.
    *   We mention in our lessons on memory and on design principles that recognition is easier than recall.
    *   People have an easier time recognizing the right answer or option when they see it than recalling it from scratch.
    *   That’s in part because memory is so context-dependent. Recognition provides the necessary context to identify the right option. Relying on recall means there’s little context to cue the right answer to the user.
*   Lucy Suchman’s 1985 book Plans and Situated Actions is the seminal book on the philosophy of situated action.
    *   The book is a detailed comparison between two views of human action:
        *   The first, she writes, “views the organization and significance of action as derived from plans”. And this is the model we very often adopt when developing interfaces: users make plans and carry out those plans.
        *   The second treats plans as derivative from situated action. In this view, people simply act in the world, and plans are what we derive from those actions. Instead of plans dictating actions, plans are just interpretations of actions.
    *   What this means for us as interface designers is that rather than assuming the user has a plan in mind that they are actively carrying out, we might consider viewing only their immediate interaction with the current screen. In other words, forget the history of actions that led a user to a screen, and ask just: once they’re here, how do they know what to do next?
    *   Later in this book, Lucy Suchman specifically touches on communication between humans and machines.
    *   There’s a lot more depth here as well. The key takeaway for us is the _focus on the resources available to the user at any given time_, but I do recommend reading the book and this chapter for more insights.

**[GOAL #4] Students will understand the pertinent takeaways of activity theory for HCI.**
*   ![screenshot](/images_Exam2/image19.png)
*   Activity theory is a massive and well-developed set of theories regarding the interactions between various pieces of an activity. It predates HCI, and in fact, activity theory is one of the first places the idea of interacting _through_ an interface came from.
*   In conversations about HCI, though, there are three main contributions of **activity theory** I’d like you to come away with:
    *   First, when we discuss designing tasks and completing tasks through an interface, we risk missing a key component: why.
        *   We could jump straight to designing the task, but why is the user completing the task in the first place?
        *   That has significant implications for our design.
        *   Activity theory generalizes our unit of analysis from the task to the activity.
        *   We’re not just interested in what they’re doing, but why they’re doing it and what it means to them. Our designs will be different, for example, if users are using a system because they’re required to or because they choose to.
    *   Second, activity theory puts an emphasis on the idea that we can separate low-level operations from higher-level actions.
        *   This had a special historical significance: before activity theory and similar theories reached HCI in the 1980s, HCI was largely concerned with minute things like how quickly a person could click a button or type in a command.
        *   Activity theory helped us zoom out from those low-level interactions to general user needs.
    *   And third, activity theory points out that actions by the user can actually move up and down in this hierarchy.
        *   A common example of this is driving a car.
        *   The first time you drove a car, shifting gears between park and drive was a very conscious action. You had to think about how to press the button, which way to push the stick, and when to release it.
        *   However, after driving a few times it becomes second nature. It has shifted from shifting gears being a conscious goal to it simply being an operator in your driving behavior.
*   In 1996, Bonnie Nardi edited a prominent book on the study of context in human-computer interaction, titled Context and Consciousness. Two papers in particular stand out to me, both by Nardi:
    *   The first is a short paper that serves in some ways as an introduction to the book.
        *   Here, Nardi outlines the general application of activity theory to HCI.
        *   “Activity theory is a powerful and clarifying descriptive tool rather than a strongly predictive theory.”
        *   She emphasizes activity theory as a descriptive theory for understanding the way systems work, rather than a way of dictating the way people should work. She also notes the relevance of activity theory to HCI.
            *   “Activity theory offers a set of perspectives on human activity and a set of concepts for describing that activity” and “This … is exactly what HCI research needs as we struggle to understand and describe “context”, “situation”, “practice”.
            *   She notes that the theory is uniquely suited to addressing some of the interesting issues facing HCI in 1996.
            *   It’s also fascinating to view from a historical perspective: today, we understand the role that context has grown to play, especially with emerging technologies. It’s fascinating to me to look back at how the community was constructing that debate 20 years ago.
    *   From her volume Context and Consciousness, Nardi wrote a comparison between distributed cognition, situated action, and activity theory:
        *   “Attention to the shaping force of goals in activity theory and distributed cognition... contrasts with the contingent, responsive, improvisatory emphasis of situated action.”
        *   First, she notes that activity theory and distributed cognition are driven by goals, whereas situated action deemphasizes goals for a focus on improvisation: “Goals are our musings out loud about why we did something after we have done it”
            *   She goes on to summarize that situated action says goals are constructed retroactively to interpret our past actions.
        *   Nardi also evaluates the role of permanent, persistent structures, noting they are important for activity theory and distributed cognition, but present a tension for situated action.
            *   Again see a similarity between activity theory and distributed cognition.
                *   Nardi writes that the main difference between these two philosophies is their evaluation of the symmetry between people and artifacts.
                *   “Activity theory, with its emphasis on... motive and consciousness... sees artifacts and people as different.” Activity theory regards them as fundamentally different, given that humans have consciousness.
                *   “Distributed cognition... views people and [artifacts] as conceptually equivalent... “agents” in the system.” Distributed cognition, by contrast, believes that artifacts can serve cognitive roles, and those should be considered conceptually equivalent.

**2.9 Interfaces and Politics**

**[GOAL #1] Students will understand the role that society plays in shaping interface design, and the role interfaces play in shaping society.**
*   In 1980, Langdon Winner published a highly influential essay in which he asked: Do Artifacts Have Politics? In other words, do technical devices have political qualities?
    *   When we say ‘politics’, we mean whether artifacts can personify specific forms of authority or power, whether for good or bad.
    *   What we’re referring to is the fact that artifacts or interfaces we design change the world around us just the way politicians or business interests do.
    *   Sometimes that’s by design. We might design interfaces not for usability or research, but to create change in the world.
    *   Other times, that social change happens in ways we didn’t anticipate. We design interfaces that are used and affect the world in ways we never anticipated.
    *   The paper describes numerous ways in which technologies, interfaces, and other artifacts demonstrate political qualities.
        *   “Reliance upon nuclear power... may be possible only in a totalitarian state.”
            *   For example, he opens by noting the belief that nuclear power can only be used in a totalitarian society because of the inherent danger of the technology.
        *   “dispersed solar sources are more compatible... with social equity, freedom, and cultural pluralism.”
            *   Solar, on the other hand, pushes society toward a more distributed and egalitarian structure. But of course, we understand that nuclear power isn’t authoritarian on its own.
        *   Winner is proposing that the push for certain technologies carries with it certain necessary political adjustments.
            *   That’s part of what it means to suggest that artifacts have politics.
            *   In the paper, Winner outlines two distinct ways in which artifacts have politics:
                *   **Inherently Political Technologies**
                    *   Like nuclear power, are technologies that are inherently political.
                    *   Certain technologies, whether due to complexity, safety, or resources, require considerable top-down organization. These lend themselves to authoritarian power structures.
                *   **Technical Arrangements as Forms of Order**
                    *   Technologies can also be used to achieve changes to social order when used in the correct way.
                    *   The technology itself has no inherent political leanings, but its use in a particular context accomplishes some.
                    *   Winner uses the example of a factory in Chicago in the 1880s that replaced workers with automated machines that produced inferior goods as a way of busting up the union. The new technology was inferior, but was used to serve a political purpose.
                *   So, according to Winner, artifacts may have two kinds of politics: they may be inherently political, or they may be used to achieve political motives.
*   **The three goals of HCI:**
    *   **1. Help a user do a task.**
        *   Most commonly in HCI, we’re interested in designing for usability. We want to make tasks easier through technology.
            *   So in a car, we might be interested in designing a GPS that can be used with the fewest taps or a dashboard that surfaces the most important information at the right time.
    *   **2. Understand how a user does a task.**
        *   Sometimes, we’re also interested in designing for research.
            *   We might design a dashboard that includes a visualization of the speed to see if it changes how people perceive how fast they’re going.
    *   **3. Change the way a user does a task due to some value that we hold, like safety or privacy.**
        *   A third motivation is to somehow change the user’s behavior, designing for change in response to some value.
            *   And oftentimes that may actually conflict with the other motivations.
            *   If we’re trying to discourage an unhealthy habit, we want to make the interface for that habit less usable.
            *   Cars have lots of interfaces created with this motivation.
                *   If I start driving without a seatbelt on, my car will beep at me.
                *   Some cars will cap your speed.
            *   Those interfaces serve no usability goals, but rather they serve the goal of user safety.

**[GOAL #2] Students will understand the nature of intentional and unintentional repercussions of interface design.**
*   **Negative change by design**
    *   The ability of interfaces to change behavior can be abused.
    *   We’re not just talking about places where people put explicit barriers up, like blocking people from accessing their content.
    *   There are instances where people create seemingly normal designs with underlying political motivations.
    *   Winner describes one such instance in his essay, “Do Artifacts Have Politics?”
        *   Robert Moses was an influential city planner working in New York City in the early 1900s.
        *   As part of his role, he oversaw the construction of many of the beautiful parks on Long Island. He also oversaw construction of parkways, roads to bring the people of New York to the parks. And as part of that, he oversaw the construction of overpasses to connect local roads over the parkways.
        *   But something unfortunate happened. These bridges were too low for buses to pass under them.
        *   As a result, public transportation couldn’t easily run to his parks. And as a result of that, only people wealthy enough to afford cars of their own could come to his parks.
        *   An unfortunate coincidence, right? The evidence shows it’s anything but a coincidence. Moses intentionally constructed those bridges to be too low for buses to pass under them as a way of keeping poor people out of his parks. His political motivations directly informed the design of the infrastructure, and the design of the infrastructure had profound social implications.
    *   One of the arguments from proponents of net neutrality is that without it, companies could set up fast lanes that prioritize their own content, or worse, severely diminish content of their competitors or content critical of the company.
*   **Positive change by design**
    *   We can design for positive social change as well, though.
    *   This goes beyond just encouraging people to be nice or banning bad behavior.
    *   Interfaces can be designed that lead to positive social change through natural interaction with the system.
        *   One example I like of this is Facebook’s ubiquitous Like button.
        *   For years many people have argued for a Dislike button to complement the Like button. Facebook has stuck with the Like button, though, because by its design, it only supports positive interactions. It dodges cyber-bullying, it dodges negativity.
    *   For usability purposes, it’s a weakness because there are interactions I can’t have naturally in the interface -- but this wasn’t designed with usability in mind.
        *   Then, Facebook added five other emotions to the Like button, but notice that even these all have a positive connotation to them.
        *   For two of them it’s obvious: love and wow.
        *   Sadness and anger, however, within this context take on a more sympathetic connotation.
        *   When someone posts something sad, you don’t want to ‘like’ it, but you want to express support -- that’s what sadness does. When someone posts something that makes them angry, you too want to sympathize.
        *   In some instances, these might be used negatively -- if I post something about a political candidate and someone reacts with ‘Sad’ or ‘Angry’, I might perceive that as criticizing my opinion, but even then it’s not a direct mapping the way ‘Like’ is.
        *   So it seems clear that this interface was designed to foster positive social interactions online at the expense of the usability of similarly supporting all social interactions online.
    *   This also doesn’t have to be strictly about dictating change, but it can also be about supporting change.
        *   For example, until a few years ago, Facebook had a more limited set of relationship options: Married, Engaged, In a relationship, and It’s Complicated.
        *   When Facebook added domestic partnerships and civil unions, it didn’t magically create those constructs.
        *   However, it supported an ongoing societal trend and gave it some validity.
        *   The same can be said for its expanded gender options. It supports a diverse group of people feeling as if the interface is designed with them in mind, which in turn supports society’s general movement toward acceptance.
*   **Positive change by happenstance**
    *   Positive change doesn’t have to happen by design, though. In fact, there are numerous examples of positive change happening more as a byproduct of technological advancement than as a goal of it.
        *   In Bijker’s _Of Bicycles, Bakelights, and Bulbs_, this is the ‘Bicycles’ example.
        *   Bijker tells a story of a young woman bicycling in England. Because of the physical design of the bicycle, she is wearing knickerbockers rather than the more traditional skirt. She pulls up to an inn, but the proprietor refuses to serve her because she is dressed improperly.
        *   In fact, in those days, the very fact that she is out without her husband is significant as well. But the bicycle provided the independence she needed to go to the inn on her own, and it created the need for her to wear less formal attire. The bicycle was thus a driver in both providing her independence and prompting the change in her attire.
        *   Both those changes forced society to challenge traditional gender roles.
        *   Its role in women’s liberation was so significant that Susan B. Anthony once said, “I think [bicycling] has done more to emancipate women than anything else in the world.”
        *   But when the bicycle was invented, it’s doubtful that the inventors sat down and said, “Surely, this will free emancipate women and change our culture’s gender roles!” But yet, that is exactly what ended up happening.
*   **Negative change by happenstance**
    *   If we aren’t careful, we can also inadvertently create negative changes -- or further preserve existing negative dynamics -- with our artifacts as well.
        *   A good example of this is the proliferation of the internet in the first place.
        *   When the internet first came along, it piggybacked on existing phone lines.
        *   Then, it started piggybacking on more expensive cable TV lines.
        *   Now, it’s following along with very expensive fiber optic lines.
        *   At every stage of the process, areas with more well-developed infrastructure get the latest internet speeds first.
        *   However, generally the areas with well-developed infrastructure are the wealthier areas anyway, either because wealthier citizens paid for improved infrastructure or because wealthy people chose to move to those areas.
        *   High-speed internet access is a big economic boon, and yet areas that are already economically advantaged are generally the first ones to get higher-speed internet access.
        *   Even today, in poor parts of the United States, the only available internet connections are slow, unreliable satellite connections with strict data caps.
        *   In the rest of the world, the issue is even more profound.
        *   And yet, this isn’t intentional.
        *   Unlike the bridges on Long Island, no one is saying, “Let’s withhold broadband access from poor people to keep them poor!”
        *   Instead, it’s natural to install better connections where there is existing infrastructure to build on -- but that very natural plan has profoundly negative implications for equitable access to the internet.

**[GOAL #3] Students will understand the value of value-sensitive design.**
*   In HCI, we describe the idea of interfaces becoming invisible. Some of that is a usability principle, but it applies more broadly to the way that interfaces integrate themselves into our everyday lives. And if our interfaces are going to integrate into people’s lives, then they need to share the same values as those individuals as well. This connects to a field called Value-Sensitive Design.
*   The Value-Sensitive Design Lab at the University of Washington defines **Value-Sensitive Design** by saying: “Value sensitive design seeks to provide theory and method to account for human values in a principled and systematic manner throughout the design process.”
    *   In this way, value-sensitive design is another dimension to consider when designing interfaces: not only is an interface useful in accomplishing a task and usable by the user, but is it consistent with their values?
*   One of the most well-developed application areas of value-sensitive design is privacy by design.
    *   Privacy is a value, and privacy by design has aimed to preserve that value in the design of systems.
    *   It’s possible to design useful, usable interfaces that don’t take privacy into account.
    *   That’s what makes an examination of users’ values an extra dimension of interface design.
*   **Paper Spotlight: “Value Sensitive Design and Information Systems” by Batya Friedman**
    *   Batya Friedman is one of the co-directors of the Value Sensitive Design Research Lab at the University of Washington, and she co-authored one of the seminal papers on the topic: Value Sensitive Design and Information Systems
    *   Friedman, Kahn, and Borning have an excellent paper on the philosophy.
    *   In it, they cover three investigations for approaching value-sensitive design:
        *   **Conceptual questions**
            *   Conceptual investigations are thought experiments where we explore the role of values through questions like: &lt;read some questions>
        *   **Empirical investigation questions**
            *   Empirical investigations go out and use real users, exploring how they make sense of interfaces, and answering questions like: &lt;read some questions>
        *   **Technical investigations**
            *   Technical investigations are like empirical investigations that target the system instead of the user.
            *   They ask the same kinds of questions about the system, like: &lt;read some questions>
    *   **Highlight features as read**
        *   The paper also proposes some of the fundamental features of value-sensitive design, like: value-sensitive design should be proactive, and value-sensitive design distinguishes between usability and human values.
        *   If you’re planning to work in an area where human values play a significant role, and I would argue that is most areas, I highly recommend reading through this paper.
*   **Value-sensitive design across cultures**
    *   One of the challenges with value-sensitive design is that values can differ across cultures.
    *   The internet makes it technologically possible to design single interfaces that are used by people in nearly every country.
    *   But just because it’s technologically possible doesn’t mean it’s practically possible, and one reason for that is that different countries and cultures may have different values.
    *   A recent newsworthy example of this occurred with the Right to Be Forgotten.
        *   The Right to Be Forgotten is a law in the European Union that allows individuals some control over what information is available about them online. That’s a value held by the European Union.
        *   However, technologies like Google were not generally developed with that value in mind.
        *   So, it has been an extraordinary effort to try to technologically support that right to be forgotten while still providing search capabilities.
        *   But that value isn’t universally shared. Many people argue that the law could effectively become internet censorship. So now we start to see some conflict in values between different cultures.
    *   If we’re to design interfaces that can reach multiple cultures, we need to understand the values of those cultures, especially if it might force us to design different systems for different people in order to match their local values.
*   **Tips for incorporating value-sensitive design into your interfaces**
    *   1. **Start early**. Identify the values you want to account for early in the design process, and check on them throughout the design process. The nature of value-sensitive design is that it might have significant connections not just to the design of your interface, but to the very core of the task you’re trying to support.
    *   2. **Know your users**. In order to design with values in mind, you need to know your users’ values. Certain values are incompatible with one another, or at least present challenges for one another. Privacy as a value is in some ways in conflict with the value of record-keeping. To know what to design, you need to know your users’ values.
    *   3. **Consider both direct and indirect stakeholders**. We usually think about direct stakeholders -- those are the people that actually use the system. Value-sensitive design encourages us to think about indirect stakeholders, people that do not use the system but are nonetheless affected by it. When you’re designing the internal system for use by a bank, for example, it’s used by bank employees, but bank customers are likely impacted by the design.
    *   4. **Brainstorm the interface’s possibilities**. Think not only about how you’re designing the system to be used, but how it could be used. If you wanted to make a system that made it easier for employees to track their hours, consider whether it could be used by employers to find unjust cause for termination.
    *   5. **Choose carefully between supporting values and prescribing values**. Designing for change is about prescribing changes to values, but that doesn’t mean we should try to prescribe values for everyone. At the same time, there are certainly values held in the world that we would like to change with our interfaces if possible, with regard to issues like gender equality and economic justice. Be careful and be deliberate about when you choose to support existing values and when you choose to try to change them with your interfaces.
*   **Challenges for interface designers** when artifacts or interfaces have political clout
    *   First, we need to think about places where we can use interface design to invoke positive social change.
    *   Second, we also need to think about the possible negative ramifications of our interfaces: what undesirable stereotypes are we preserving, or what new negative dynamics might we create?
    *   Ask yourself:
        *   What role can your technology play in creating positive societal change?
        *   What risks are there if your technology catches on?

**[GOAL #4] Students will understand how interfaces can draw from incentives besides usability and research.**



*   Reversing the relationship
    *   Political relationships and motivations can often have enormous impact on technology, too.
        *   From Bijker’s book of Bicycles, Bakelights, and Bulbs, the ‘Bulbs’ part refers to the battle over the design of the first fluorescent light bulbs in 1938.
        *   General Electric created a new kind of light that was far more energy-efficient.
        *   Power companies, however, were afraid this would reduce power consumption and cut into their profits.
        *   After a long drawn out battle involving the Antitrust Division of the US government and the US Department of War, the fluorescent bulbs that were ultimately sold were not as good as they technologically could be in order to preserve others’ business interests.
    *   More and more we see compatibility between devices or usage policies for technologies determined not by what is technologically possible, but by what satisfies political needs.
        *   To keep up with everything that I like to watch on TV, I have five different subscriptions. I have my cable TV subscription. I have Hulu. I have Amazon Prime. I have Netflix. I have an HBO subscription separate on top of my cable subscription. And that’s not to mention things I watch for free on their own apps, like Conan or anything on YouTube.
        *   And you might think, wouldn’t it be awesome to just have one experience that could navigate among everything I want to watch? There’s no technological reason against it. But there’s a complicated web of ownership and licensing and intellectual property agreements that determine the way the technology works.
    *   Technology changes society, but society changes technology, too.
*   You have almost certainly experienced political or business motivations changing the way in which a technology of yours works.
    *   Similar to the fluorescent light bulb, oftentimes these motivations are to preserve the power or profit of an influential organization in the face of radical change.
    *   Sometimes they might be the products of relationships or agreements between vendors or organizations to emphasize one another’s content.
    *   Generally, these are instances where technology either performs sub-optimally or has certain features because someone besides the user benefits.
*   Notice how all these perspectives harken back to the idea that user experience exists not only in individuals and groups, but in societies.



---


**2.10 Conclusions to Principles**

**[GOAL #1] Students will solidify their knowledge of the three views of the human in HCI.**



*   One way of knitting together the different ideas of HCI is to start very close and zoom out.
    *   At the narrowest level, processor model. Zoom out - predictor model.
*   **Processor model**
    *   This view looks at this almost like an interaction between two computers -- one just happens to be a human, but the human’s actions are approached almost computationally.
    *   If we’re going to take this model, we need to understand a lot about what the human can sense, remember, and physically do.
    *   The **GOMS model** approaches HCI in this manner as well: It distills the human’s role out into goals, operators, methods, and selection rules, all of which can be externalized.
    *   But this is a pretty narrow view of HCI.
*   **Predictor model**
    *   For the most part, we’re interested in something more task-focused. In fact, this is where we likely spend the majority of our time. This is the user interacting through some interface to accomplish a task.
    *   This is what we meant by the ‘Predictor’ model. The user is actively involved in looking at their task and making predictions about what to do and what will happen.
    *   We look at questions like the **gulfs of execution and evaluation**, how hard it is for the user to interact with the task, and how hard it is for them to get feedback on their execution.
    *   The interface ideally can disappear from the interaction (**invisibility**), making the user feel as if they’re just working on the task directly. Many of our design principles are constructed specifically to help with this: to help users quickly make sense of the interface and understand the underlying task.
    *   But in order to design this interaction effectively, we have to understand the way the user thinks about the task they’re performing. We have to understand their mental models, and in turn, we have to help make sure their mental models match the actual task. Here we have to get into questions like understanding the **user’s errors** and understanding the **mapping between representations and the underlying tasks**.
    *   We also have to address questions like expert blindspot and learned helplessness.
    *   Fortunately, we have a tool to help us with this: **cognitive task analysis**, and its related **hierarchical task analysis**.
    *   So, much of what we deal with in HCI occurs within this process of a human completing a task through some interface.
*   **Participant view**
    *   We’re also interested in how this interaction occurs beyond just the individual and the interface. This is what was meant by the ‘participant’ model. The user is not merely interacting with an interface or interacting with a task through an interface. They are interacting with other interfaces, other individuals, and society as a whole. They are active participants in the world around them.
    *   Sometimes we’re interested not only in the task that the user is performing, but also in their motives and reasons to be performing it.
        *   This is what **activity theory** advocates: treating the unit of analysis not as a task, but as an activity, including some elements of the context surrounding the task.
    *   Sometimes we’re interested in how other artifacts or minds combine to help accomplish the task.
        *   That’s what **distributed cognition** advocates.
    *   Sometimes we’re interested in deeply understanding the situated context in which a person is acting.
        *   That’s what **situated action** is most interested in.
    *   Sometimes we’re interested in how these interfaces integrate with existing social norms and relationships.
        *   That’s what **social cognition** examines.
    *   And sometimes we’re interested in dynamics even broader than this.
        *   Sometimes we’re interested in how the interfaces we design can create **positive social change**.
        *   Sometimes we’re interested in how interfaces risk perpetuating existing **negative relationships in society**.
        *   **Equity, flexibility, ease & comfort** -- exactly the goal of some of our design guidelines as well: to use interfaces to create a more equal society for all people.

**[GOAL #2] Students will integrate the multiple lessons across the previous several videos into a unified understanding of HCI’s principles.**



*   When we started our conversations, I commented that when you do HCI right, users won’t actually know you’ve done anything at all. Good HCI disappears between the user and the task that they’re completing. As a result, people can underestimate how complex good HCI can be to leverage.
*   There are a lot of designs you could propose.
    *   But the question here isn’t what you designed. The question here should be, how will you develop it? How will you evaluate it? How do we know which ideas are good and which are bad?
    *   We’ve given some heuristics and principles for doing this, but that doesn’t automatically get you to a good interface. ⇒ That just establishes a baseline. That’s what that principles portion of this course covers.
    *   To fully develop interfaces using these principles, we need the methods of HCI as well.
*   We’re interested in general principles and methods for designing interactions between humans and various different kinds of computational devices.
    *   Designing for a traditional screen has its own set of specific principles.
    *   However, it’s quite likely that you’ll be designing for this traditional kind of device, so here are **tips for designing effective on-screen user interfaces**.
        *   1. **Use a grid**. Grids are a powerful way of guiding a user’s sight around your interface, highlighting important content, grouping related content, etc. There’s a reason why newspapers and magazines have used grid-based layouts for decades.
        *   2. **Use whitespace**. Users are good at consuming small chunks of information at a time. Notice how news articles often use very short paragraphs and highway signs have lots of space around the text. Whitespace works with grids to provide context and guide the user’s visual perception of the interface.
        *   3. **Know your Gestalt principles**. Gestalt principles in UI design refer to how users perceive groups of objects. Users group objects together when they’re spatially close together, visually similar, or moving together.
        *   4. **Reduce clutter**. The eye has difficulty processing cluttered information, so reduce clutter wherever possible. Grids, whitespace, and Gestalt principles can help with this because they can invisibly communicate content that might otherwise need to be communicated visually. Instead of drawing a box to group controls together, you can surround them with whitespace. Instead of using headers and text to label different portions of some content, you can separate them with a grid. And so on.
        *   5. **Design in grayscale**. Color can be a powerful tool, but it also runs awry of universal design. There are enough colorblind individuals in the world that relying on color is problematic. Color can help emphasize the content and structure of your interface, but it shouldn’t be necessary to understand it. Take a stoplight, for example: red means stop and green means go, which is a problem if you’re deuteranopic, or red-green color blind. But the red light is always at the top and the green light is always at the bottom, so if you are deuteranopic, you can still understand what the light is saying. Color emphasizes the content, but the content doesn’t rely on color.

**[GOAL #3] Students will understand the principles as merely half the picture of HCI.**



*   Design guidelines and heuristics and principles are only half the picture. They’re necessary for good design, but they aren’t sufficient. You can’t just grab these guidelines off the shelf, throw them at a new task, and expect to have a perfect interface the first time.
    *   These principles give you a solid foundation, but every domain, every task, every target audience has unique requirements and criteria.
    *   To design usable interfaces, you have to understand your specific user. And remember, that isn’t you.
    *   What that means is you have to go out and find what your users need.
    *   You have to get inside their head and understand the task. You have to prepare multiple different ideas for them to try out. You have to evaluate those with real users. And you have to take that experience and use it to improve your design, and start the process all over again.
*   These guidelines and principles are useful in making that process as efficient as possible. But they aren’t sufficient on their own. **These principles are only half the picture. The other half are the methods.**

---
**3.7 HCI and Agile Development**

**[GOAL #1] Students will understand what agile development is in the context of HCI.**



*   New technologies and new eras call for new principles and new workflows. Specifically, the advent of the internet ushered in new methods for HCI. Many software developers now adopt an **Agile workflow**, which emphasizes _earlier delivery, more continuous improvement, and rapid feedback cycles_.
    *   For those of us here in HCI, that’s exciting: we love feedback cycles. We love building them for our users and we love engaging in them ourselves.
    *   It’s also a scary prospect, though. We’ve also discussed long prototyping processes that move from paper to wireframes to live demos, that involve lots of users in slow qualitative methodologies. And those things are all still very valuable.
    *   But nowadays, sometimes we also need to build really fast.
*   Think back to before the age of the internet. Developing software was expensive. It required a very specialized skillset. Software distribution was done the same way we sold coffee mugs or bananas: you’d go to the store and buy it. That distribution method was expensive as well. If you shipped software that was hard to use, the cost of fixing that was enormous: you had to mail each individual person an update disk. And the only way to get user feedback and even find out if it was usable was the same way you would do it before distribution: by having users come in for testing. All of this meant there was an enormous need to get it right the first time.
    *   Shigeru Miyamoto, the creator of Nintendo’s best franchises, described this in terms of video games as, “A delayed game is eventually good, but a rushed game is forever bad.”
    *   The same applied to software.
*   Fast-forward to now -- is that still true?
    *   Development isn’t cheap, but it’s not as expensive as it used to be: a single person can develop in a day what would taken a team of people months to do 20 years ago, thanks to advances in hardware, programming languages, and available libraries.
    *   But more importantly, distribution for software is now essentially free. Updating software is essentially free as well. Every day, you can download new apps and have them update automatically in the background. If you release something with a bug, you can fix it and roll it out immediately.
    *   Miyamoto’s quote is no longer as accurate because it is possible to fix games after they’re released.
        *   Tesla regularly pushes software updates to its cars via the internet.
        *   And perhaps most importantly, we can gather usage data from live users automatically and for free. And it isn’t just usage data: product reviews, error reports, buzz on the internet. Lots of feedback comes naturally. What this all means is there is now more incentive to build something fast and get it to users to start getting real feedback as early as possible.
        *   This isn’t justification to just throw out the design life cycle. The majority of HCI design and research still goes through the longer process. You need several iterations through the full design life cycle for big web sites, complex apps, anything involving designing hardware, anything involving a high-profile first impression, or anything involving anything even somewhat high stakes.
        *   But that said, there exists a new niche for rapid development. Maybe you came up with an idea for a simple Android game. In the time it would take you to go through this longer process, you could probably implement the game and get it in front of users and get a lot more feedback.
        *   That’s what we’re discussing here ⇒ **How do you take the principles we’ve covered so far and apply them to a rapid, agile development process**?

**[GOAL #2] Students will understand when it is appropriate and inappropriate to leverage more agile development techniques.**



*   When should you consider these more Agile methodologies?
    *   Lots of software development theorists have explored this space. Boehm and Turner specifically suggest that **Agile development be used only in certain circumstances**:
        *   First, it must be **an environment with low criticality**.
            *   By its nature, Agile development means letting users do some of the testing, so you don’t want to use it in environments where bugs or poor usability are going to lead to major repercussions.
            *   Healthcare or financial investing, for example, wouldn’t be great places for Agile development generally speaking -- although there have been efforts to create standards that would allow the methodology to apply without compromising safety and security.
            *   But for things like smartphone games or social media apps, the criticality is sufficiently low.
        *   Second, it should be a **place where the requirements change often**.
            *   One of the benefits of Agile processes is they allow teams to adjust quickly to changing expectations or needs.
            *   A thermostat, for example, doesn’t change its requirements very often. A site like Udacity, though, is constantly adjusting to new student interests or needs.
        *   These two components apply to the types of problems we’re working on.
        *   If we’re working on an interface that would lend itself to an Agile process, we also must set up the team to work well within an Agile process. That means small teams that are comfortable with a culture of change, as opposed to large teams comfortable with order. So, generally, **Agile processes can be good in some cases and with the right people, but poor in others**.
    *   ![screenshot](/images_Exam2/image3.png)



*   **Paper Spotlight**: “Towards a Framework for Integrating Agile Development and User-Centred Design” by Stephanie Chamberlain, Helen Sharp, and Neil Maiden
    *   In 2006, Chamberlain, Sharp, and Maiden investigated the conflicts and opportunities of applying agile development to user-centered design. They found, interestingly, that the two actually had significant overlap.
        *   Both agile development and user-centered design **emphasize iterative development building on feedback** from the previous rounds.
        *   Both place a heavy emphasis on the **user’s role in the development process**.
        *   Both emphasize the **importance of team coherence**.
        *   So it seems that agile methods and user-centered design agree on the most fundamental element: the importance of the user.
    *   By comparison, the conflicts are relatively light:
        *   User-centered design disagrees with agile development on the importance of documentation
        *   Also disagrees on the importance of research prior to design work beginning.
    *   But clearly the methodologies have the same objectives; they just disagree on how to best achieve it.
    *   As a result, they propose five principles for integrating user-centered design into agile development.
        *   Two of these were shared between the methodologies in the first place:
            *   (1) **high user involvement**
            *   (2) **close team collaboration**.
        *   User-centered design’s emphasis on prototyping and the design life cycle showers up by proposing that designers run a sprint ahead of developers to perform the research necessary for user-centered design. To facilitate this, **strong project management** is necessary.
    *   ![screenshot](/images_Exam2/image9.png)

       
*   **A/B testing**
    *   So in some contexts, it’s now no harder to construct an actual interface than it is to construct a prototype. So, we might skip the prototyping phase altogether. However, prototypes also allow us to gather feedback from users. Even though we can now easily construct an interface, we don’t want to immediately roll out a completely untested interface to lots of people. We might be able to fix it quickly, but we’re still eroding user trust in us and wasting our users’ time.
    *   That’s where the second facet of this comes in: A/B testing - **rapid software testing between typically two alternatives**.
        *   Statistically, this is no different from t-tests.
        *   What makes A/B testing unique is that we’re usually rapidly testing small changes with real users. That way we can make sure a change is positive before rolling it out to everyone. But look where testing and feedback are coming in here: they’re coming automatically with real users during normal usage of our tool. There’s no added cost to recruiting participants, and the feedback is received instantly.
        *   With A/B testing, we’re making tiny little changes and observing the impact in terms of numerical outcomes like conversions, time on page, and so on. So, **A/B testing is reminiscent of the processor view** of the user.
*   **Agile development techniques don’t replace the design life cycle. They just caffeinate it.**
    *   We’re still doing needfinding, but we’re probably doing it pretty tacitly just by reading user feedback or checking out interaction logs.
    *   We’re still brainstorming design alternatives, but we’re really just coming up with them in our head.
    *   We’re still doing prototyping, our prototypes just happen to work.
    *   We’re still doing evaluation by rolling our changes out to only certain participants first and making sure the response is good. The results of that evaluation then feed the same process over again.
*   **Tips for using HCI and Agile development together**, especially for mitigating the risks to the user experience presented by Agile development.
    *   1. **Start more traditional**. Start with a more traditional needfinding and prototyping process, and shifting to more Agile development once you have something up and running. Jakob Nielsen describes this as doing some foundational user research. Once you have something up and running, you have a way of probing the user experience further, but you need something solid to begin with, and that comes from the traditional process.
    *   2. **Focus on small changes**. Notice that when I was doing live prototyping and A/B testing, I was making small changes to an existing interface, not building an entire site from scratch.
    *   3. **Adopt a parallel track method**. Agile development often uses short two-week sprints of development. Under that setup, have the HCI research one sprint ahead of the implementation. The HCI team can do two-week sprints of traditional needfinding, prototyping, and low-fidelity evaluation, then hand the results to the development team for their next sprint.
    *   4. **Be careful with consistency**. One of our design principles was consistency, both within our own interfaces and across interface design as a whole. If your interface caters to frequent visitors or users, you’ll want to be conservative in how often you mess with their expectations. If you’re designing something like a museum kiosk, though, you can be more liberal in your frequent changes.
    *   5. **Nest your design cycles**. In Agile development you go through many small design cycles rapidly, and each cycle gives you a little bit of new information. Take all that new information you gather and use it in the context of a broader, more traditional design cycle aimed at long-term substantive improvements instead of small optimizations.
*   **Are you working in a high stakes area, like healthcare or autonomous vehicles? What’s the cost of user failure?**
    *   If it’s high, you probably will want to avoid agile development: after all, it’s built in large part around learning from the real failures of real users.
    *   If that’s a user unfairly failing to reach the next level of a game, that’s fine.
    *   If that’s a doctor entering the wrong dosage of a medication into a new interface, that’s not fine.
*   **You’ll also need to think of development costs.**
    *   Agile development relies on being able to get a product up and out the door quickly and change it frequently.
    *   If any part of your design is reliant on the hardware, then agile development presents challenges: it might be easy to roll out a software update to improve a car’s screen interface, but you can’t download a car to fix a hardware problem.
*   In many ways HCI and Agile development are a nice match:
    *   **both emphasize feedback cycles**
    *   **both emphasize getting user feedback**
    *   **both emphasize rapid changes.**



---


**3.8 Conclusion to Methods**

**[GOAL #1] Students will understand the design life cycle as a complete, iterative process for interface design.**



*   **Design life cycle**
    *   We take the results of our initial iteration through the design cycle and use the results to return to the needfinding process.
        *   That’s not to say we need to redo everything from scratch, but our prototypes and evaluation have now increased our understanding of the problem.
        *   There are things we learn by prototyping and evaluating about the task itself.
        *   The evaluation process may have also given us new questions we want to ask users to understand the task better.
    *   In many ways, synthesizing our experiences with the evaluation is our next needfinding process.
    *   We then move on to design alternatives: again, that doesn’t mean starting from scratch and coming up with all new ideas.
        *   Here it means expanding on our current ideas, fleshing them out a bit more, and brainstorming them in terms of those personas and scenarios we used previously.
        *   We might also come up with whole new ideas here.
    *   Then, more prototyping.
        *   At this point, we might discover that as we try to increase the fidelity of our prototypes, the technology or resources aren’t quite there yet.
        *   For example, while the gesture interface might have been promising in the Wizard of Oz prototype, we don’t yet have the technology to recognize gestures that way on the go.
        *   Or we might find that the expense related to the prototype is unfeasible, or the realizing the prototype would require violating some of our other user needs.
        *   For example, we could do gesture recognition if we had users hold a physical device that could recognize gestures, but that might be too expensive to produce, and it might conflict with our audience’s need for a hands-free system.
        *   So we move on with the prototypes that we can build, with the goal of getting to the feedback stage as quickly as possible.
        *   For voice, instead of trying to build a full voice recognition system, maybe we just build a system that can recognize very simplistic voice commands. Instead of recognizing words, maybe it just recognizes the number of utterances if that’s easier to build.
        *   For the screen, maybe we build a wireframe prototype that moves between different screens on a phone, but we don’t connect it to a real system. We still have someone Wizard of Oz it while running along with the participant. That way we focus on usability instead of things that take a lot of work to get right and might end up unnecessary if we find that the prototype isn’t useful.
    *   Then, we evaluate again.
        *   This time, we probably get a little more objective.
        *   We still want data on the qualitative user experience, but we also want data on things like: how long does it take a user to perform the desired actions in the interface? What prevents them from working with the interface?
        *   Imagine that we found, for instance, that for many exercisers, they go through places that are too loud for voice commands to work.
        *   Or, we find that the time it takes to pull out the interface and interact is too distracting.
        *   That information is once again useful to our ongoing iteration.
    *   At the end of that process, we again have some higher-fidelity prototypes, but no product yet. So, we go again.
    *   When you launch the product, instead of having a handful of users we bring in to use our interface, we have hundreds of users using it in ways we never expected
        *   And the cycle begins again.
        *   We have data we’re automatically collected either through usage tracking or error logs. We have user reviews or feedback they submit.
        *   So, we jump back into needfinding using the data we have available to us.
            *   We might find subtle needs or more novel new needs
        *   So the process starts again, this time with live users’ data.
        *   And in general, it never really ends.
            *   Nowadays, you very rarely see interfaces, apps, programs, or web sites that are intentionally put up once and never changed. That might happen because the designers got busy or the company went out of business, but it’s rarely one-off by design.
            *   And as the design evolves over time with real data, you’ll start to see nested feedback cycles: week to week small additions give way to month-to-month updates and year-to-year reinventions. In many ways, your interface becomes like a child: you watch it grow up and take on a life of its own.

**[GOAL #2] Students will understand the relationship between research methods and design principles.**



*   In many ways, design principles capture takeaways and conclusions found by this design life cycle in the past in ways that can be transferred to new tasks.
*   **Map human abilities and task analysis to needfinding**
    *   In uncovering needs, many of our needs are driven by our current understanding of human abilities.
    *   Task analysis allows us to describe those needs, those tasks, in formal ways to equip the interface design process.
*   **Map direct manipulation, mental models, and distributed cognition to design alternatives**
    *   Direct manipulation gives us a family of techniques that we want to emphasize in coming up with our design alternatives.
    *   Mental models provide us an understanding of how the design alternatives might mesh with the user’s understanding of the task.
    *   Distributed cognition gives us a view on interface design that lends itself to design at a larger level of granularity.
*   **Map design principles, representations and invisible interfaces to prototyping**
    *   Design principles give us some great rules of thumb to use when creating our initial prototypes and designs.
    *   Our understanding of representations ensures that the prototypes we create match with users’ mental models.
    *   Invisible interfaces help us remember that the interface should be the conduit between the user and the task, not the focus of attention itself.
*   **Map feedback cycle and interfaces and politics to evaluation**
    *   The vocabulary of the feedback cycle, the gulfs of execution and evaluation, give us ways to evaluate the interfaces that we design.
    *   The notion of politics in interface allow us to evaluate the interface not just in terms of its usable interactions, but in the types of society it creates or preserves.
    *   Those principles of HCI were all found through many years of going through the design life cycle, creating different interfaces, and exploring and evaluating their impact.
*   By leveraging those lessons, we can speed to usable interfaces much faster.
*   **Approaches to user-centered design**
    *   At a minimum, user-centered design advocates involving users throughout the process through surveys, interviews, evaluations, and more that we’ll talk about.
    *   However, user-centered design can be taken to even greater extremes through a number of approaches beyond what we’ve covered.
    *   **Participatory design**
        *   In participatory design, all the stakeholders -- including the users themselves -- are involved as part of the design team.
        *   They aren’t just a source of data, they’re actually members of the design team working on the problem.
        *   That allows the user perspective to be omnipresent throughout the design process.
        *   Of course, there’s still a danger there: generally, we are not our user, but in participatory design one of the designers is the user… but they’re just one user.
        *   So, it’s a great way to get a user’s perspective, but we must also be careful not to over-represent that one user’s view.
    *   **Action research**
        *   Action research is a methodology that addresses an immediate problem, and researches it by trying to simultaneously solve it.
        *   Data gathered on the success of the approach is then used to inform the understanding of the problem and the future approaches.
        *   Most importantly, like participatory design, action research is undertaken by the actual users.
        *   For example, a teacher might engage in action research by trying a new activity in his classroom and reflecting on the results, or a manager might use action research by trying a new evaluation system with her employees and noting the changes.
    *   **Design-based research**
        *   Design-based research is similar to action research, but it can be done by outside practitioners, too.
            *   It’s especially common in learning sciences research.
        *   In design-based research, designers create interventions based on current understanding of the theory and the problem, and use the success of those interventions to improve our understanding of the theory or the problem.
        *   For example, if we believed a certain intersection had a lot of jaywalkers because the signs had poor visibility, we might interview people at the intersection for their thoughts: or, we could create a solution that assumes we’re correct, and then use it to evaluate whether or not we were correct. If we create a more clearly visible sign and it fixes the problem, then it suggests our initial theory was correct.
        *   In all these approaches, notice iteration still plays a strong role: we never try out just one design and stop. We run through the process, create a design, try it out, and then iterate and improve on it. Interface design is never done: it just gets better and better as time goes on, while also adjusting to new trends and technologies.

---






---




**EXAM #2 END**
