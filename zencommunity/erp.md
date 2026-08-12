# ZenCommunity
## Epics, Personas & Affordance Criteria
*Product Backlog Foundation Document*

---

# Introduction / Overview

ZenCommunity is a WordPress community plugin that unifies three of the strongest engagement systems — community building, real-time chat, and support ticketing — into one native, blazing-fast platform. Site owners can create advanced, Facebook-style groups with real-time posts, media, mentions and comments; enable group and private one-to-one messaging; convert any post or chat into a tracked support ticket; and offer instant help through a site-wide live chat widget — all without leaving WordPress and without stitching together three-to-five separate tools. It also ships a dedicated community mobile app with live chat, support tickets, ticket analytics, push notifications and real-time communication.

ZenCommunity fits LMS communities (with tight Academy LMS integration), client portals, SaaS user groups, agency hubs, membership sites and business networks. This document defines the product's core Epics, the personas representing ZenCommunity's target ideal customer profiles (ICPs), and the affordance criteria that connect each persona and epic to concrete system capabilities. Each persona is written to map onto one or more epics, and each epic carries an affordance statement plus user stories with acceptance criteria — providing the foundation for entity modeling, backlog grooming and sprint planning.

---

# Personas

The following six personas represent ZenCommunity's primary ICPs: the site owner buying the plugin, the community manager running engagement, the support agent resolving tickets, the community member, the LMS course creator, and the developer/administrator responsible for setup and branding. Each persona lists goals, behavioral considerations, tasks, an elaborate scenario, and the system affordances they rely on.

## Persona One: Site Owner / Founder

**Name:** Tushar Rahman
**Pronouns:** He/Him
**Gender:** Male
**Preferred Title:** Mr.
**About Me:** Tushar, 40, runs a membership website and is tired of paying for and juggling several disconnected tools for community, chat and support. He wants one native WordPress solution that keeps users engaged on his site.

**Goals:**
- Replace 3–5 separate tools with one integrated community, chat and support system.
- Turn visitors into members and members into loyal, paying customers.

**Behavioral Considerations:** Cost-conscious and ROI-driven; wants fast setup and everything to work natively inside WordPress without switching platforms.

**Task:** Install ZenCommunity, enable community, chat and support, and grow engagement and retention.

**Elaborate Scenario:** Tushar installs the plugin, which auto-creates the groups, feed, profiles and chat pages. He consolidates his scattered tools into one system, watches engagement rise as conversations stay on-site, and tracks how community activity converts visitors into members.

**Affordances:**
- Provide community, real-time chat and support ticketing in one native WordPress system.
- Auto-create the pages needed for a community environment on activation.
- Keep conversations and support on-site to improve engagement and retention.

## Persona Two: Community Manager

**Name:** Amina Yusuf
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Ms.
**About Me:** Amina, 34, manages the day-to-day community for a SaaS user group. She creates groups, sparks discussion, and keeps members active and connected.

**Goals:**
- Build active, well-organized groups and discussions.
- Keep members engaged through real-time posts, mentions and comments.

**Behavioral Considerations:** Engagement-focused and hands-on; needs control over groups and moderation without wrestling with complex tooling.

**Task:** Create and manage groups, feeds and discussions, and moderate member interactions.

**Elaborate Scenario:** Amina spins up Facebook-style groups for product topics, posts announcements with media, and uses @mentions and comments to draw members into real-time discussion — moderating and organizing the feed as the community grows.

**Affordances:**
- Create and manage Facebook-style groups, feeds and discussions.
- Support real-time posts, media, @mentions and comments.
- Provide moderation and organization controls over member interactions.

## Persona Three: Support Agent

**Name:** Kwame Osei
**Pronouns:** He/Him
**Gender:** Male
**Preferred Title:** Mr.
**About Me:** Kwame, 31, handles customer and member support. He converts questions into tickets, resolves live chats, and juggles multiple conversations at once.

**Goals:**
- Track and resolve member requests without missing messages.
- Handle multiple live chat sessions efficiently from one place.

**Behavioral Considerations:** Responsiveness-driven and organized; needs everything in one queue so nothing slips through the cracks.

**Task:** Convert posts and chats into tickets, assign and track them, and staff the live chat widget.

**Elaborate Scenario:** Kwame turns a member's group post into a support ticket with one click, assigns it, tracks its status to resolution, and simultaneously handles several live chat conversations from the site-wide widget — sending files and getting notified of new messages.

**Affordances:**
- Convert any post or chat into a trackable support ticket with one click.
- Assign tickets to team members and track their status to resolution.
- Handle multiple live chat sessions at once with file sharing and notifications.

## Persona Four: Community Member

**Name:** Grace Mwangi
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Ms.
**About Me:** Grace, 27, is a member of a course community. She wants to connect with peers, get quick answers, and stay in the loop without leaving the site or installing extra apps.

**Goals:**
- Join groups, post, and message peers easily.
- Get fast, instant help when she has a question.

**Behavioral Considerations:** Values convenience and immediacy; expects mobile access, private messaging, and real-time responses.

**Task:** Participate in groups, send private messages, and reach support through live chat.

**Elaborate Scenario:** Grace joins a group, posts a question in the feed, direct-messages a peer one-to-one, and when she hits a problem, opens the live chat widget for instant help — receiving push notifications through the community mobile app.

**Affordances:**
- Join groups and participate in real-time discussions, posts and comments.
- Send private one-to-one messages to other members without an external app.
- Access instant support via live chat and stay updated through mobile push notifications.

## Persona Five: LMS Course Creator

**Name:** Samuel Adeyemi
**Pronouns:** He/Him
**Gender:** Male
**Preferred Title:** Dr.
**About Me:** Samuel, 45, creates and sells online courses on Academy LMS. He wants an interactive student community wrapped around his courses to boost engagement and retention.

**Goals:**
- Build a student community around his courses.
- Provide group discussion, private chat and instant support to learners.

**Behavioral Considerations:** Outcomes-focused on engagement and retention; wants the community to live natively alongside his LMS, not in a separate tool.

**Task:** Attach a community, chat and support layer to his Academy LMS courses.

**Elaborate Scenario:** Samuel connects ZenCommunity to Academy LMS, creating a group per course where students discuss lessons, message each other privately, and raise support tickets — turning his LMS into a fully interactive learning hub with higher completion and retention.

**Affordances:**
- Integrate seamlessly with Academy LMS to build a course community.
- Offer group discussions, private chats and support inside the learning experience.
- Boost learner engagement and retention through on-site interaction.

## Persona Six: Developer / Administrator

**Name:** Lindiwe Ndlovu
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Ms.
**About Me:** Lindiwe, 33, is the WordPress developer/administrator who installs, configures and brands ZenCommunity, and manages roles and the live chat widget for the organization.

**Goals:**
- Set up and brand the community and chat widget to match the site.
- Configure roles, permissions and the mobile app cleanly.

**Behavioral Considerations:** Detail-oriented and control-focused; wants native WordPress behavior, customization, and reliable performance.

**Task:** Install and configure the plugin, customize the widget and branding, and manage roles and the mobile app.

**Elaborate Scenario:** Lindiwe installs ZenCommunity, customizes the live chat widget's colors, position, agent details and welcome message to match branding, sets role permissions, and launches the dedicated community mobile app with push notifications and ticket analytics.

**Affordances:**
- Install natively in WordPress with auto-created community pages.
- Customize the live chat widget's colors, position, availability and greeting to match branding.
- Configure roles and permissions and launch the dedicated community mobile app.

---

# Epics, Affordances & User Stories

Each epic below carries an affordance statement describing what the platform enables, followed by user stories tied to the personas above and the acceptance criteria that define done. Together these form the affordance criteria that link every persona and ICP to concrete ZenCommunity capabilities.

## Epic 1: Community & Group Building (Amina)

**Affordance:** Lets managers create advanced, Facebook-style groups with real-time feeds, posts, media, mentions and comments.

**User Story 1 (Community Manager):** Create and manage groups and discussions.

**Acceptance Criteria:**
- The system should allow custom groups and discussions to be created and organized.
- The system should support real-time posts, media, @mentions and comments in the feed.

**User Story 2 (Community Manager):** Moderate member interactions.

**Acceptance Criteria:**
- The system should provide moderation controls over posts, comments and members.
- The system should let managers organize and manage group content.

## Epic 2: Real-Time & Private Messaging (Grace)

**Affordance:** Enables real-time group discussions and private one-to-one messaging between members without an external app.

**User Story 1 (Community Member):** Participate in real-time group chat.

**Acceptance Criteria:**
- The system should allow members to join and chat in group discussions in real time.
- The system should deliver messages instantly with notifications.

**User Story 2 (Community Member):** Send private one-to-one messages.

**Acceptance Criteria:**
- The system should allow members to send direct one-to-one messages.
- The system should not require an external app to message privately.

## Epic 3: Support Ticketing (Kwame)

**Affordance:** Turns any post or chat into a trackable support ticket, assignable to team members and tracked to resolution.

**User Story 1 (Support Agent):** Convert a post or chat into a ticket.

**Acceptance Criteria:**
- The system should convert any post or chat into a trackable ticket with one click.
- The system should preserve the original context on the created ticket.

**User Story 2 (Support Agent):** Assign and track tickets.

**Acceptance Criteria:**
- The system should allow tickets to be assigned to specific team members.
- The system should track ticket status through to resolution.

## Epic 4: Live Chat Widget (Kwame)

**Affordance:** Provides a site-wide, always-on live chat widget for instant support, with multi-session handling and file sharing.

**User Story 1 (Support Agent):** Handle multiple live chat sessions at once.

**Acceptance Criteria:**
- The system should let an agent manage multiple concurrent chat sessions without losing track.
- The system should support file sharing and new-message notifications in chat.

**User Story 2 (Community Member):** Start a chat instantly from any page.

**Acceptance Criteria:**
- The system should keep the live chat widget active site-wide at all times.
- The system should allow visitors to start chatting immediately, with logged-in or anonymous options.

## Epic 5: Tool Consolidation & Native WordPress Setup (Tushar)

**Affordance:** Replaces multiple disconnected tools by keeping community, chat and support inside one native WordPress system that sets up automatically.

**User Story 1 (Site Owner / Founder):** Consolidate community, chat and support into one system.

**Acceptance Criteria:**
- The system should provide community, chat and support natively within WordPress.
- The system should auto-create the required community pages on activation.

**User Story 2 (Site Owner / Founder):** Grow engagement and retention on-site.

**Acceptance Criteria:**
- The system should keep conversations and support on-site rather than in external tools.
- The system should support engagement flows that convert visitors into members.

## Epic 6: LMS & Membership Integration (Samuel)

**Affordance:** Integrates with Academy LMS and membership sites to wrap courses in an interactive community with chat and support.

**User Story 1 (LMS Course Creator):** Build a student community around courses.

**Acceptance Criteria:**
- The system should integrate with Academy LMS to create course-based communities.
- The system should offer group discussion, private chat and support within the learning experience.

**User Story 2 (LMS Course Creator):** Boost learner engagement and retention.

**Acceptance Criteria:**
- The system should keep learner interaction on-site alongside the LMS.
- The system should support engagement features that improve course retention.

## Epic 7: Mobile App & Notifications (Grace)

**Affordance:** Delivers a dedicated community mobile app with live chat, support tickets, ticket analytics, push notifications and real-time communication.

**User Story 1 (Community Member):** Stay connected through the mobile app.

**Acceptance Criteria:**
- The system should provide a dedicated community mobile app with live chat and messaging.
- The system should send push notifications for new activity and messages.

**User Story 2 (Support Agent):** Manage tickets and view analytics on mobile.

**Acceptance Criteria:**
- The system should surface support tickets and ticket analytics in the mobile app.
- The system should support real-time communication from mobile.

## Epic 8: Branding, Roles & Configuration (Lindiwe)

**Affordance:** Lets developers customize the widget and branding, configure roles and permissions, and install natively with minimal setup.

**User Story 1 (Developer / Administrator):** Customize the live chat widget and branding.

**Acceptance Criteria:**
- The system should allow the widget's colors, position, availability and greeting to be customized.
- The system should let agent name, photo and status be configured for a personal feel.

**User Story 2 (Developer / Administrator):** Configure roles and permissions.

**Acceptance Criteria:**
- The system should support role and permission configuration for members, agents and admins.
- The system should install natively in WordPress with auto-created pages.