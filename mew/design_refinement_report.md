# Design Refinement Report

By Isa de Luis, Lily Jiang, Helen Bauer, Sela Domkofski, Daniel Quinteros

## Decoding the Design: Unraveling the Inner Workings of Bubble's Architecture

Our design is a mobile application that fosters building platonic relationships
through shared experiences at community events. The Bubble App aims to create a
low barrier to discovering and attending local events and promotes forming
friendships with other attendees. Specifically designed for young professionals
relocating to new cities in mind, the app addresses the challenges of building
new friendships in a new city, finding enjoyable activities in an unfamiliar
location, and the apprehension of attending events solo.

Upon launching the app, the user is greeted by an engaging interface for
browsing local events. Our design involves two distinctive views for event
browsing. The first is a scrollable “bubble” view, where each bubble represents
one event and is intelligently sized according to the user's predicted interest.
This creates a personalized list and is useful for users who want to quickly
find events that they’re interested in and care less about the location of the
event. The second view is a map that offers a spatial representation of event
locations, catering to those who might care more about finding events closer to
them. A toggle allows for convenient navigation between the two views, ensuring
users can choose the most suitable option based on their specific preferences
and needs. By offering two distinctive views for the same overall purpose, our
design addresses diverse viewing preferences and makes exploring events an
enjoyable endeavor.

The user should then flow from viewing a variety of events to selecting specific
ones that interest them. This will take them to a screen to view more details
about the event and interact with it (bookmarking for later viewing, joining the
group chat, or RSVPing to the event). The end goal for the user is to RSVP and
attend various events that they’re interested in while actively connecting with
other people by engaging in conversations through the chat feature.

We also included user authentication within our design, as a core feature of the
app is that each user creates their own profile for others to view. They have
associated data, such as their event preferences, age (to ensure they’re above
18), previously attended events, and friends. Not all of their associated data
is available to other users to ensure privacy and safety for all of our users;
for example, age is kept off of their public profile.

## Crafting Brilliance: Navigating the Path of Design Refinement

Our design process began with individual paper prototype sketches, which were
shared in a team meeting. Following a thorough review of everyone’s designs, we
discussed the strengths of each and selected a primary design to move forward
with. We took the style of that chosen design and created feature sketches of
the chat feature and events page of our app. After sharing and discussing these
sketches and the overall flow of the app, we made a final selection to proceed
with and then transitioned to implementing our designs using Figma.

### 1. Down-Scoping of the Project

During the Figma design phase, we worked on finalizing key aspects, such as the
organization of all elements within our design (main page, event page, map view,
etc. ). This iterative process allowed us to refine our vision and ensure a
cohesive and user-friendly interface. Part of this refinement involved cutting
down on the list of potential features and behaviors we wanted our app to have.

Two shortcomings of our app we previously discovered were the inconvenience of
downloading yet another app, and possible dexterity issues with the event
browsing screen (using the pinching motion to make each bubble bigger or
smaller). We aimed to improve our app with these concerns in mind. First and
foremost, we felt that we could engage users by maintaining a clean and
accessible design, making it more appealing to download our app. Secondly, we
actively considered feedback from team discussions and from our potential users
regarding the functionality of resizing bubbles for the user to indicate their
interest in the event. We ultimately decided to remove this functionality; it
posed too much of a burden on the user to input this information in this way and
also detracted from the overall purpose of the event browsing screen. The
refactored design has bubbles with a set size to reflect the user’s predicted
interest in the event (larger bubbles = predicted more interest).

### 2. Response to Paper Prototyping User Feedback

Our paper prototype consisted of sketches for 2 screens: the bubble layout of
the event browsing page, and the event details page. It was a simple version
intended to curate feedback about how intuitive the bubble layout would be to
new users. The results were positive from user testing; it was clear that they
understood what the purpose of the app was. It was interpreted early on as “an
app to show you events happening in your city,” indicating that the app’s
intention was abundantly clear just from those two screens. There was some
ambiguity around what it would look like to join a group chat for the event or
what saving an event meant, but it was a good starting point to know the bubble
event browsing design was sensible. One user specifically thought the chat icon
might be a registration page for the event, indicating we should consider
implementing text-based button labels or some other helpful signifier.

The response to the bubbles as a way of showing events was positive, being seen
as “fun” and an appealing way to interact with information. A couple of users
did express a desire to have alternatives to the bubble view to explore events,
going as far as to list out a map view or calendar view as possibilities. We
decided to incorporate the map view in our design, as it was something we as a
team had also discussed as a potential feature. Overall, based on the user
feedback for our paper prototypes, we gained a clear insight into our next steps
to improve the app.

### 3. Responses to Team-Internal Deliberations

In a team meeting, we delved into critical aspects of our app’s design. The
discussion centered around the optimal event viewing workflow — whether to
utilize a home page with bubbles showcasing only RSVPed events or a bubble
screen intended for discovering new events. We engaged in a substantial
discussion about the interface style, weighing the merits of Tinder-style
swiping versus displaying all events at once in a bubble or list format. Drawing
inspiration from the [LA Events](https://www.discoverlosangeles.com/events)
page, we explored a list-based design incorporating date and category dropdowns
for efficient filtering. Emphasizing the utility of a calendar and category
filtering feature, we envisioned a user-friendly experience where event details
are accessible without entering each event individually.

Addressing the onboarding process, we considered an approach where users are
asked to specify initial interests on the screen, and then are taken through a
guided tutorial through the app’s main features (toggling between the bubble and
map views, and RSVPing to an event). Additionally, we explored the concept of
facilitating group chats by allowing users to choose people to connect with from
the event attendee list, a suggestion that resonated with the team. We also
created an app logo to emphasize the branding and legitimacy of our design,
crediting Sela for her contribution. Navigating through event details and chats
prompted further discussion. We weighed the options of having a dedicated button
in the navigation bar for easy access, or accessing the chat feature through the
profile screen, as we weren’t sure the chat feature should be highlighted to the
same degree as a core feature like viewing events. We also explored (through
more paper prototyping) various designs that meshed our bubble branding with a
functional and intuitive interface for accessing group chats. A design involving
horizontal lists of bubbles on the profile screen, akin to Instagram’s
Highlights feature, gained traction. Another pivotal topic was the inclusion of
a map feature. We recognized that it fulfilled user desires, but there were
varying opinions regarding its level of necessity and preferred placement. The
team explored potential integration options, such as a map icon in the
navigation bar or a toggle between bubble and map views. Turning to the app’s
aesthetic aspects, the team recognized the need to finalize a color scheme. We
each individually implemented a few designs in Figma with varying color schemes,
and then posed a quick survey to our potential users through an Instagram story
to get overall feedback. A sleek blue and purple theme won by a significant
amount.

**INSERT IMAGES**

Finally, filters were identified as crucial for enhancing user experience, to
tailor events only to specific locations (regions), activity types/categories,
age requirements, and more. As we move forward, we are committed to refining our
designs, specifically establishing a cohesive color scheme that aligns with the
app’s purpose of facilitating connections for young professionals in a new city.

### 4. Responses to Heuristic Evaluation Feedback

We implemented a greyscale Figma prototype for the heuristic evaluation to
pinpoint the strengths and weaknesses of flows and functionality rather than the
aesthetic. The idea was that we didn’t want the feedback to focus on aesthetics
just yet; we wanted to make sure we really nailed down the intuitive-ness of our
intended interactions and the flow of the app.

The heuristic evaluation feedback highlights several positive aspects of the
application, such as a simple interface for event pages and the seamless
integration of maps and social media. However, several important concerns were
raised regarding confusion about the purpose of the bubble view, a desire for a
more standardized list view for browsing events, and limitations in chat
features. The feedback recommended improving the design by explicitly explaining
the meaning of bubble sizes in the event browser view, having info/help buttons
on each page to refresh users on the app features, and making it clearer on how
to interact with certain aspects of group chats such as leaving one.
Additionally, concerns were raised about user privacy and safety (since the app
involves meeting what are essentially strangers), and the integration of
external tools like calendars. With these concerns identified, we plan to
discuss how to address them and make the necessary changes to our design. Our
most important priority is defining the bubble rules and emphasizing their value
compared to the map view. Additionally, we will be clearly defining each feature
of our app, like the difference between saving an event versus joining a chat
versus RSVPing to an event. Other changes that will be made are implementing our
chosen color scheme, giving the user a way to unRSVP to an event and leave a
chat, creating an additional list view of the events, and adding filter and
search buttons in all views to give users more flexibility.

## Navigating Choices: The Tradeoffs Made in Bringing it Online

Bringing our paper prototype online had distinct advantages in understanding
user interactions with the app. By having an online prototype, we were able to
clearly map out the interactions we wanted users to have with our app, giving us
a clearer understanding of possible pain points and frustrations users might
have. By shifting, adding, and removing visual features, we could explore how
different designs and configurations would impact a user's experience much
faster than we could with a paper prototype.

However, there were some negative consequences of bringing our prototype online.
Transitioning to a virtual medium demanded thoughtful consideration of visual
elements, which was rather time-consuming. Decisions about colors, fonts,
spacings, and overall design aesthetics became critical, and anything less than
pixel-perfect became much more obvious. Additionally, interacting with an app on
a computer offers distinct functionalities, such as hover actions, that aren’t
mirrored in mobile interactions. This discrepancy may cause us to overlook
design flaws that are present in the actual experience.

## Unveiling Key Insights: Examining Supported Evidence in the Current Phase

During this phase, we realized that what may seem intuitive to us is not
necessarily the same for individuals who haven’t invested as much time in our
product. For example: the bubble view. Our reviewers wondered what the purpose
of the bubble view served if there was already a map view, which some of them
viewed as more intuitive and less violating to the eyes. Adding the map view
actually seemed to reduce the uniqueness and value of the bubble view.
Additionally, there was confusion about whether the bubbles’ size or color had
any significant meaning, or if it was just for aesthetic purposes. A couple of
reviewers also noted that they actually preferred seeing information in a more
standardized, plain list format rather than interacting with cool graphics,
stating that it was easier to parse information quickly in a list. Based on this
feedback, we want to explore ways to offer a non-graphical, yet still visually
appealing, way to process the events posted in our app, such as a list view.

**INSERT IMAGE**

Adding to that, things that we hadn’t thought would be a problem ended up being
a concern during the heuristic evaluations. For example, our reviewers mentioned
that they understand that to save an event they have to press the large bookmark
button; however, they were unsure as to where it saves the event.

**INSERT IMAGE**

## Project Inquiry: Exploring Unanswered Questions and Acknowledging Shortcomings

Regarding the earlier point about the bubble view confusion, the simple solution
would be to drop the bubble view and pursue refining the map view; however, the
bubble view has been vital to the identity of our app, so we plan to move
forward, investigate the design rules of the bubbles (size, color, placement,
etc.), and solidify what makes them valuable compared to the map view. We plan
to incorporate user feedback about implementing a non-graphical event browsing
view as well, such as a list view. This will enhance the diversity of options,
which will better support individual preferences for viewing information.

There was also some confusion about what it means to save an event or join a
chat, and what the relationship between those interactions is. Originally, we
struggled a lot with deciding what it meant to join a chat. Would the group chat
be a space for people who planned on attending the event, or could people who
were curious and wanted to scout the vibe beforehand join as well? Would joining
the chat automatically cause you to RSVP to the event? How would a user leave
group chats? There is also a need for us to solidify aspects of the flow to
browse and eventually join an event. When saving/joining an event, how would
that appear for the user? Would the confirmation be in the form of the event
being shown on the in-app calendar? Would there be a specific section with all
of their saved/joined events? Would you automatically be added to the chat for
the event?

We plan to investigate these questions by engaging with potential users to
better understand their preferences for these specific interactions. We also
will continue drawing inspiration from existing apps to identify universally
effective structures for organizing and storing elements such as events.
