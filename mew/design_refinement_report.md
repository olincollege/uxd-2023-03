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

Addressing the onboarding process, we considered a novel approach where users
specify initial interests on the screen and a tutorial on how to use the app.
Additionally, we explored the concept of facilitating group chats by allowing
users to choose friends from the event attendee list, a suggestion that
resonated with the team. In terms of aesthetics, we created our app’s logo,
crediting Sela for her contribution.

Navigating through event details and chats prompted further discussion. We
weighed the options of accessing the chat feature through the profile or a
dedicated button in the navigation bar. The idea of a list of even bubbles on
the profile screen, akin to Instagram’s Highlights, gained traction. A pivotal
topic was the inclusion of a map feature, with team members expressing varying
opinions on its necessity and preferred placement. The team explored potential
integration options, such as a map icon in the navigation bar or a toggle
between bubble and map views.

Turning to the app’s aesthetic aspects, the team recognized the need to finalize
a color scheme. There was consensus on the possibility of offering multiple
themes, both initially and in settings, with some themes potentially being
monetized through either one-time purchases or a subscription model. Finally,
filters were identified as crucial for enhancing user experience, including
location (regions), activity types/categories, and age requirements. As we move
forward, the team is committed to refining selected designs, specifically
establishing a cohesive color scheme that aligns with the app’s purpose of
facilitating connections for young professionals in a new city. We chose a
greyscale prototype for the heuristic evaluation to pinpoint the strengths and
weaknesses of flows and functionality rather than the aesthetic.

### 4. Responses to Heuristic Evaluation Feedback

The heuristic evaluation feedback highlights several positive aspects of the
application, such as a simple interface for event pages and seamless integration
of maps and social media. However, concerns were raised, including confusion
about the purpose and aesthetics of the bubble view, limitations in chat
features, and a need for more flexibility. The evaluation identified various
issues, ranging from visibility of system status to user control and freedom.
Several recommendations for improvement were provided, including addressing
inconsistencies in the interface, implementing error prevention measures,
enhancing flexibility and efficiency, and improving the aesthetic design. Users
also needed more clarity on certain features, such as the meaning of bubble
sizes. Additionally, concerns were raised about user privacy and the integration
of external features like calendars.

With these concerns identified, we will be making the necessary changes to our
design. Our most important priority is defining the bubble rules and emphasizing
what makes them valuable compared to a map. Additionally, we will be clearly
defining each feature of our app, like the difference between saving an event
versus joining a chat versus RSVPing to an event. Other changes that will be
made are picking a color scheme, giving the user a way to unRSVP to an event or
leave a chat, creating a list view of the events, and adding filter and search
buttons to give users more flexibility.

## Navigating Choices: The Tradeoffs Made in Bringing it Online

Bringing our paper prototype online had distinct advantages in understanding
user interactions with the app. By bringing our prototype online, we were able
to clearly map out the interactions we wanted users to have with our app, giving
us a clearer understanding of possible pain points and frustrations users might
have. By shifting, adding, and removing visual features, we learned how
different designs and configurations would impact a user's experience much
faster than we could with a paper prototype.

However, there were some negative consequences of bringing our prototype online.
Transitioning a paper prototype to a virtual medium demands thoughtful
consideration of visual elements, which can be time-consuming. Decisions about
colors, fonts, and overall design aesthetics become critical, often requiring
sacrifices in time and effort that could otherwise be devoted to other aspects
of development or testing. Additionally, interacting with an app on a computer
offers distinct functionalities, such as hover actions, that aren’t mirrored in
mobile interactions. This discrepancy may create a divergence between the
intended user experience and the actual experience, necessitating additional
adaptations and adjustments to ensure coherence across different devices.

## Unveiling Key Insights: Examining Supported Evidence in the Current Phase

During this phase, we realized that what may seem intuitive to us is not
necessarily the same for individuals who haven’t invested as much time in our
product. For example: the bubble view. Our reviewers wondered what the purpose
of the bubble view served if there was already a map view, which some of them
viewed as more intuitive and less violating to the eyes. Whereas in our paper
prototype, users only had the bubble view, adding the map view here actually
reduced the uniqueness of the bubble view. Users could not determine the value
of using one view over the other. Additionally, there was confusion about
whether the bubbles’ size or color had any significant meaning or if it was just
for aesthetic purposes. A couple of reviewers also noted that they actually
prefer seeing information in a more standardized, plain text format. They find
it easier to read information than interact with graphics, which is incredibly
valuable to know. We want to find a way to provide a non-graphical way to
process the events posted in our app, such as a list view.

**INSERT IMAGE**

Adding to that, things that we hadn’t thought would be a problem ended up being
a concern during the heuristic evaluations. For example, our reviewers mentioned
that they understand that to save an event they have to press the large bookmark
button; however, they were unsure as to where it saves the event.

**INSERT IMAGE**

## Project Inquiry: Exploring Unanswered Questions and Acknowledging Shortcomings

Regarding the earlier point about the confusion revolving around the bubble
view, the simple solution would be to drop the bubble view and pursue refining
the map view; however, the bubble view has been vital to the identity of our
app, so we plan to move forward and investigate the design rules of the bubbles
(size, color, placement, etc.) and what makes them valuable compared to the map
view. We plan to incorporate user feedback about having a non-graphical view as
well, such as a list view, so users have truly diverse options that can serve
their preferences for looking at information.

There was also some confusion about what it means to save an event or join a
chat, and what the relationship between those interactions is. Originally, we
pondered what it meant to join a chat. Would the group chat be a space for
people who planned on attending the event or could people who were curious and
want to scout beforehand join as well? Would joining the chat automatically add
you to joining the event? Also, when saving/joining an event, how would that
appear for the user? Would the confirmation be in the form of the event being
shown on the in-app calendar? Would there be a specific section with all of
their saved/joined events? Would you automatically join the chat for the event?
We plan to investigate these questions by engaging with potential users to
understand their preferences and examining existing apps to identify a
universally effective structure for organizing and storing elements such as
events.
