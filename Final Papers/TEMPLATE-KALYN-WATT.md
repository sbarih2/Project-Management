## Roots & Rituals
Kalyn Watt, Fall 2023


### Abstract

In this paper, I will be reviewing the open-source strategies and tools that will drive my project called Roots & Rituals, which is centered around leveraging the community to raise awareness and preservation of food traditions by submitting and finding recipes for dishes that originate from endangered cultures and languages around the world.

### Introduction

#### Purpose

Preserving food traditions is important for several reasons. It helps maintain the identity of a community and its local culture by transferring knowledge from older to younger generations. Additionally, it contributes to the preservation of cultural identity, as people retain their culinary traditions even after migrating to other countries, and certain foods become symbolic of a community's culinary culture and their conservation efforts (D’Andrea & D’Ulizia, 2023). Preserving food traditions is not only about maintaining culinary practices but also about protecting cultural heritage, promoting sustainability, and protecting local economies.

#### Open-Source Solution     

The term "open source" refers to code that is publicly accessible for anyone to inspect, modify, and share. More broadly, "open source" now represents a set of values and principles focused on open exchange, collaboration, transparency, and community-oriented development. The open and inspectable nature of open source code lets a global community of programmers enhance programs collaboratively by adding features and fixing bugs. "Open source" also favors the attitude of promoting working in transparent ways oriented towards the common good. Open source projects welcome the public to join their efforts such as contributing code, content, funding, translations, documentation, and more. This shared mission harnesses collective intelligence to build better, more inclusive solutions (Opensource.com).

For my project in particular, an open-source approach to an online endangered recipe exchange could help raise awareness and participate in preserving vulnerable foodways. Thoughtfully organizing the initiative's operations and community will prove critical to achieving these conservation goals sustainably over time.

#### Audience          

There are two main audience segments for this product: individuals are interested in contributing their endangered recipes from their own or a different cultural heritage and individuals who are interested in learning more about various food traditions. This open-source recipe exchange provides a solution for any user who is passionate about culinary culture and protecting food traditions. In addition to having recipes originating from various cultures, Roots & Rituals will also have recipes for beginner, intermediate, and advanced levels. The platform will also provide insight on ingredient sourcing to ensure inclusivity, irrespective of where you are located and your skill level.

### Strategy      

#### Version Control          

Managing an open-source software project collaboratively requires robust infrastructure to coordinate documentation, code, designs, and other materials needing versioning. GitHub is widely regarded as one of the best version control tools currently available on the market. It is capable of effectively supporting non-linear development and can be adapted to both small and large scale projects by encouraging community participation and a secure way of file editing (Sofela, 2020). For my project, GitHub's centralized version control system based on Git software perfectly fits these needs for streamlining endangered recipe exchange operations. Core maintainers can push updates to GitHub recipe submission templates, website code, how-to guides, policies, and imagery assets. These changes can then sync across the remote repositories of external contributors, who can pull down edits, make modifications, and submit fixes or improvements via pull requests.

Additionally, GitHub's native issue tracking tools facilitate decentralized task management across code sprints and hackathons. Project leaders can tag contributors to issues needing attention like optimizing site search, expanding ingredient dictionaries, or fixing browser display bugs. Markdown checklists within issues make assigning and tracking sub-tasks simple. Mention notifications alert members to urgent tasks such as recipe validation requests or plagiarism reports from the community. Pull request reminders can prompt contributors when their revisions need review or revision before merging into the master branch.

GitHub issue types and the labeling feature will allow contributors to distinguish content ideas from software enhancements from task volunteering. Transparent workflows encourage new contributors to responsibly scope submissions rather than overcommit.

GitHub Insights also provides project managers important metrics on repository activity to direct development efforts, such as visualizing peak hours for recipe submissions. Third-party apps like GitHub Projects can enable Kanban-style project boards for tracking progress. Overall, GitHub's comprehensive version control mechanisms guide smooth collaboration critical to the sustainability of a multifaceted community initiative.

#### Tech Stack 

This platform will be using MERN. MERN (MongoDB, Express.js, React.js, and Node.js) is a popular tech stack known for its high performance and scalability and is very effective for modern applications. MongoDB will be used as the database to store recipe information. One of the many advantages of MongoDB is its scalability, so as the number of contributors and recipes continue to grow, the platform will need a flexible tool to handle large amounts of data. Also in the backend are Express.js and Node.js. Express.js is known for its easy routing and requires relatively little effort. It is incredibly useful for building functional, versatile web applications. While not a programming language, Node.js supports an environment for JavaScript. React.js is a library for building responsive and simple interfaces.

MERN is open-source, making it not only incredibly easy to learn, but also cost-effective. The popularity of MERN has also fostered a supportive community of developers well-versed in the tech stack (Patel, 2023). Resources and tools are readily available and accessible for any developer to utilize so that the development process can be streamlined. This community makes it possible for transparency about updates and features that are regularly being added, reducing the friction points between developers and the tech stack.

#### Community and Collaboration

The core team will be responsible for attending bi-weekly, or if necessary, weekly meetings to discuss status updates and roadblocks. This team will consist of core maintainers, UX designers, managers, and developers. This will be a time where the team can express any sentiment toward the project in an open discussion. This can be about any topic regarding the project they feel needs to be addressed. In addition to these weekly meetings, daily asynchronous stand-ups can be useful for maintaining transparency and communication between developers on their progress, blockers, and next steps. Displaying progress from backlog to completion will promote an agile development process that will allow us to iterate quickly and streamline the development process.

Additionally, decentralized community coordination through open standards and ethical leadership principles sustains collaborative digital commons projects at scale. Recipe collection depends on crowd-sourcing contributions from members across the globe. The project should formally incorporate as a non-profit to establish a trusted legal identity and coordinate funding.

To distribute workload, contributors can self-assign recipe validation tasks using Trello boards. These task groupings can be based on their cuisine expertise and/or skill level. Trello provides an organized way to manage task delegations, and by leveraging tools like Trello, transparency on the status of tasks is made available to contributors. Surfacing more community voices through creator spotlights can also bolster inclusivity in guiding the project’s growth. When the main site launches, inviting cultural organizations, food bloggers, and social media influencers to preview and press events can promote sharing and garner interest in the platform.

Overall, decentralized community building grounded in transparency, and collective responsibility will maintain collaborative intelligence and work against commercial appropriation. This blueprint will hopefully empower Roots & Rituals to democratically govern itself over generations.

#### Hosting Interactive Public Events

Gatherings like edit-a-thons build contributor momentum while improving content. Weekend recipe archiving sprints could facilitate the intergenerational sharing of recipes. For example, there might be an event that allows old family cooks to digitize their handwritten recipe cards together with student volunteers. To promote accessibility of ingredients, we can assign community hosts to not only coordinate local ingredients sourcing, but also to teach traditional methods of sourcing.

Another way to facilitate in-person connection is the employment of annual conferences. These conferences can rotate globally between participating cultures. Within these conferences, we can create events to encourage members to cook shared meals together, hearing firsthand the history behind a particular food tradition and its rituals associated with it. We can also host breakout workshops for more niche culinary exploration. For example, allowing the community to brainstorm ingredient substitution ideas might promote inclusivity for those who have dietary restrictions or don’t have easy access to original ingredients. Smaller meet-ups piggybacking established open-source conferences attract new technical contributors in GitHub workflows.

These lively collective experiences can ultimately strengthen relationships between the core project creators and its peripheral allies. Consistently crediting event sponsors, chefs, donors, and volunteers promtoes open acknowledgment standards for the broader community and encourages further contributions. We can also utilize post-event metric reviews and surveys to assess activities needing adjustment, such as widening promotion to more linguistically diverse media outlets.

#### Defining Project Scope

The mission of this project is to ultimately promote the endangering of culinary diversity and culture. With this in mind, we must assess what features are necessary to effectively support and communicate this mission. Firstly, having an explore page that allows users to navigate through the recipes is crictical to ensuring discoverability. The explore page also requires a comprehensive filtering system (e.g. skill level, dietary restrictions, proximity to ingredients, cuisine interests). This filtering system will maintain a user-centric approach and streamline the process of discovering recipes users are interested in. The platform also needs in-depth individual recipe pages that include historical background, associated rituals, clear instructions, and listed ingredients. Granular recipe template sections can also display detais on fading preparation techniques and rare seasonal ingredients. Contributor profiles should also capture information such as affiliated languages, cultural background, and experience level. This context helps editors prioritize validation tasks for recipes from severely endangered communities. It also streamlines user navigation. Another priority is multi-language translations. Multi-language translations will facilitate inclusive learning and increase our diversity of users.

#### Sustainability

Maintaining community excitement after the platform’s initial release requires engaging governance and leadership development. Routine feedback surveys give all members a voice in shaping policies and features, and rotation rounds should prevent volunteer burnout.

I will mention a few other ways to ensure project sustainability. Building metrics dashboards that track platform usage, retention, and feature requests can help the team focus on highest priority development areas. This will not only ensure community issues are being addressed, but also maintain a user-centric approach. It is also important to periodically revisit mission statements and realign our priorities as we may sometimes veer off course. This is especially important as global contexts and practices evolve. Documentation is perhaps one of the most important aspects of project sustainability. Setting strict documentation standards will ensure smooth leadership transitions and avoid reliance on sole individuals. In addition to documentation, instituting mentorship programs and training sessions for new leaders will ensure role requirements and qualifications are fulfilled.

In any community, especially this one, it is imperative to maintain diversity and inclusion. This will encourage multiple perspectives and contribute to the success of the platform. We can do so by spotlighting featured contributors across social channels and providing recognition to sustain participation. Simple incentives like profile badges for reaching submission or meal preparation thresholds will continue to motivate recipe collecting or cooking.

Lastly, pitch events allow creators and contributors to collaboratively develop promising side project ideas with support from the development and UX communities. This is a means of investing in the tools and training for more community leadership over time so that the platform can outlive its founders.

#### Funding Mechanisms

There are various funding mechanisms that can be simultaneously employed to cement multiple streams of income. Firstly, employing a “premium” structure can limit reliance on grants and external resources. Members can pay a small monthly or annual subscription fee to access premium cooking tutorial videos and other incentivizing pay-walled features. Although a less stable source of funding, we can also leverage branded merchandise when compounded with other methods.

Externally, crowdfunding campaigns and effective donation models can rally fundraising around new major milestones. Another priority is building strong partnerships with relevant food-related organizations. These can be large corporations or non-profits. Lastly, affiliate marketing of useful third-party products can raise funding and promote discoverabilty of other relevant services and products that support the missiom (Nagornyy, 2023). As cash flows stabilize, investing in search engine optimization and social referral programs can also sustain steady traffic growth to support expansion.

### Conclusion  

Collaborative technology and thoughtful leadership enable open-source initiatives to maintain sustainability, diversity, and success. Strategic organizational decisions guided by community transparency will empower Roots & Rituals to facilitate and foster global food heritage and intergenerational wisdom, even amidst cultural shifts.

### References 

D’Andrea, A., & D’Ulizia, A. (2023). Preserving local food traditions: A hybrid participatory approach for stimulating transgenerational dialogue. Societies, 13(4), 95. https://doi.org/10.3390/soc13040095 

Nagornyy, V. (2023, July 31). 10 funding opportunities for your open source project. Funded by Community. https://fundedby.community/funding-open-source-projects/

Patel, M. (2023, March 20). Mern : Why it is most popular framework for web app development?. Bytes Technolab Inc. https://www.bytestechnolab.com/blog/discover-why-mern-web-development-is-the-top-choice/#:~:text=The%20MERN%20Stack%20is%20designed,choice%20for%20building%20complex%20UIs.

Sofela, O. (2020, August 19). Git vs github – what is version control and how does it work?. freeCodeCamp. https://www.freecodecamp.org/news/git-and-github-overview/ 

What is open source?. Opensource.com. (n.d.). https://opensource.com/resources/what-open-source 



