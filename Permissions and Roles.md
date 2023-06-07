
### Glossary
In an attempt to be as clear as possible, I'll give a quick glossary here and will try to be really specific with the language I use in the following documentation.

- server
	- the VES Global discord server.  A collection of categories, chat channels, forums, announcements and users.  The general public and fans of VFX are welcome in some parts of the server, and there are special sections for VES members and staff.
- category
	- channels are organized into categories.  Different categories are generally represent different groups of users (the general public, or members of a specific sections, for example).
- channel
	- a channel is a chat room in discord.  It can be text, or a forum, or a voice chat section, etc.
- role
	- a role can be thought of as like a group.  Users on the server can be assigned various roles, and these roles control what they can do, what they can see, etc.
- permission
	- permissions are controlled through a specific type of role and are grant users special powers, like moderation, administration, etc.
- public
	- any new person that joins our server, until we find out otherwise, is considered a member of the general public and they don't have access to protected, members' only categories and channels. 
- VES Member
	- a member of VES in good standing.  This is someone that's been vetted and had their identity confirmed so that they can be granted access to members' only content.
- VES BOM
	- a VES member that has been elected to their Section's Board of Managers.  Again, this is a permission granted to vetted individuals and it gets them access to additional, protected channels/categories.  VES Global staff and individuals in non-BOM leadership roles may also have this permission.
- sections
	- VES has 15 sections worldwide - for example, VES LA, VES Oregon, VES WA, etc.
- user
	- any individual person, regardless of role, using the server.


## RULES for Admins/Devs/Mods
First, there are a few overriding rules that we're trying to abide by here.

1. For oversight and PR purposes, VES Global does not allow Sections running their own, individual discord servers.  
2. BOM Members are encouraged to work together, so *we* don't allow sections to set up private "walled gardens" between different sections.
3. VES general members can opt in or out of participation in any VES section they want to.
4. Don't clutter the server with unnecessary permissions and channel selections.  Keep the maintenance and admin side as simple as possible since this is being run by volunteers. 
5. Private work, NDA material, and real BOM business should not be conducted in discord's chat channels.  
6. We're a professional, global organization and for the good of the community, we have to insist on certain rules of conduct (spam, harassment, gossip, etc.).  We also encourage following discord's general etiquette and rules-of-the-road. 

## Keeping it Simple

Roles and permissions in discord can quickly become a tangled and impenetrable mess.  Having unused (or barely used) channels and roles/permissions to manage will make maintenance confusing and quickly overwhelming - (I've made these mistakes, it's a real thing - and once you can't handle maintenance, server quality will degrade -- at best it looks bad, at worst, this discord gets shut down).

From a server standpoint, all permissions assigned to individuals are to be handled through the assignment of roles.  We don't assign permissions directly to individuals, and we don't create roles for a single individual.  If push comes to shove, create a role if you have to, but never assign hard permissions to an individual user.

In the same way, the best way to handle the channel permissions is at the category level.  The category gets the permissions, and each channel under that category inherits permissions (that's the goal, but we're already breaking that and I have serious complexity-concerns about doing so).

## New Channels

Right now we're trying to pair the server down to channels that are (or have a hope of becoming) active and those that are required.  We do not want to add more inactive channels.  If you add a channel or a role that ends up not being used, please delete it.  

### Planning ahead
It's easy to plan ahead, and our instinct, especially given the background a lot of us share, is to anticipate and put things in place before they're needed.  In our case, to keep things manageable, it's better to take a "Just in time" approach.  Creating a hundred channels, with a spiderweb of (potentially conflicting) permissions by imagining what will be useful or fun in the future creates a ton of overhead that may not ever get used.  

### When and how to create a new channels
If people are talking about home improvement in the general VFX channel, and you can see that it's beginning to fuck up other vfx related conversations, spin off a new home-improvement channel.  If the vfx channel never really has any vfx chatter in it, but it's all home-improvement, I'd suggest renaming it and creating a new channel just for VFX so that the historic, majority chatter, about home-improvement stays with the new channel.

If someone asks for a new channel really consider it before creating it for them.  We have forums and threads that users can use to create new "channels" with.  If it's obvious that this is a topic that has legs and is getting a lot of activity, consider the new channel.  Again, imagining new channels is easy, but they need to be useful.  If I create a channel for "3D", there will immediately be a request for "2D".  If you create a channel for "film", there will immediately be a request for a "games" channel, etc.  Please don't create channels that will be dead - get a commitment from someone (or a group of someone) to prime that pump and get the conversation going.

If a section channel's chat blows up into a lot of different topics and lots of threads -- so much so that trying to log in and catch up on the chatter becomes overwhelming, consider creating a forum for the members, so that they can self-organize the topics.  A forum is a great way to handle topics that are hot today but may die down in a few months or years.

If you create a new channel, click the plus button on the category, **don't click the private button** -- the new channel will inherit the permissions of the category.  If you need a channel added, for example, for BOM members in a section, click private and add ONLY the VES BOM permission.  If you need anything other than those two situations, see the rules above to ensure it's an allowed channel type, and then check the "Special" section immediately below:

### "Special"
If someone asks for a channel with special permissions, pump the brakes and ask some questions -- "what's it for," and "who has access?"  The new channel can't break any of the rules above (it can't be more private than what's outlined up there -- it has to have, at a minimum, VES BOM permissions), and whatever gets added as "special" is going to need special attention to maintain, keep current, etc.  By default, the only instance in which special attention is needed is when permissions are "partially" relaxed.  

By "partially relaxed," I mean, you have a channel that's read-only to one role, but can be written to by another (section specific announcements, for example), or where you need a way to allow members of a more general role (ves members) to have access to a channel (a sub-committee) without allowing everyone with that same (ves members) role access.  To do this, you need to create a new role and assign it to the particular users.

In the example of granting a sub-group of membership into a protected channel, there is no direct and easy way to create a mutual exclusion like these in discord - permissions are additive only -- and this is exactly where things can get out of hand.  We currently have 19 separate roles that control access to channels.  That's 15 sections, ves general membership, bom members, and 2 special roles for WA.  If every sections wanted two extra roles, that's alone becomes 28 additional roles/permissions to keep track of.  

For right now, if you have something like a committee channel that needs to be available to non-bom committee members, create the channel, give the VES BOM role access to it, and add the individual non-bom members directly to the channel.

## Current Roles - explanations
### General
There are "color roles", and "permissions roles" in discord.  Colors roles are used to set the users color when you see their name (we've adopted various shades of the VES Gold), and to grant access to specific channels.  As stated above, channel access has a default setting that's set on the category, but that default setting only applies to channels that are set to "sync" with their parent category.  

### Color Roles (these control access to different channels)

The position, top to bottom, of the list of roles in the server settings matters only in terms of the color that a members name shows up as and to optionally create different groupings of members on the members list.  If you look at the permissions of the color roles, you'll see that they are set to all off - nothing needs to be turned on for a member to have access to a protected channel.  If a channel allows a role, a person with that role will have access to that channel and they don't need any additional permissions.  A user can have multiple color roles - some are simply cosmetic, some control channel access.

- VES BOM
	- BOM members have a special sections to work together in.  This is a permission that anyone on any BOM globally gets.  Any BOM specific sections, in an channels, are visible to everyone with this role.  The general membership doesn't really need to see how the sausage is made, but BOM members should - it's an opportunity to learn, cooperate, coordinate, etc.
- VES Members
	- These should be confirmed, active members of VES.  We have a mechanism so that VES members can opt in to any section they wish.  This is to reduce noise for the members that don't care what's going on in other sections, and to allow more nomadic members to stay part of any chapter they want to globally.  VES LA sort-of should be the most active section, so I could see a lot of members opting in to just see all the fun stuff LA does.
- VES Australia 
	- This and the \<VES Section\> roles below grant normal member access to the section specific categories and channels.  Each section, by default, has a general chat channel available, and a BOM channel.  Remember, that BOM channel, even though it's in a sub-section, is visible to anyone globally with the VES BOM role.  If a member of the BOM wants to opt-out of the noise from sections other than their own, they can use the Browse Channels channel at the top left of the discord UI.
- VES Bay Area
- VES France
- VES Georgia
- VES India
- VES London
- VES Los Angeles
- VES Montreal
- VES New York
- VES New Zealand
- VES Oregon
- VES Toronto
- VES Vancouver
- VES Washington
- @everyone
	- This is a built-in generic role that everyone that logs into the server gets.  Consider it the "Public" role.  Users with this role can't see any member's only content.

There is a couple other color roles that are being used for back-end information purposes - they don't really do anything at the moment.  There is also a "bot" role that's just used to keep the bots separate from regular people.

### Permissions Roles

Permissions roles are intended to grant users specific powers, like moderation, channel create/delete control, admin access, etc.  These roles don't have a color assigned and only include the specific permissions needed for that role.  Permissions are additive, so adding a moderator role to an events manager will not replace the original moderator permissions, it will just add to them.

- Owner (hidden)
	- Heather is the owner.  She created the original server.  Owners have the ultimate power on the server and can grant or remove any permission to anyone.  Heather is God, but ownership is transferrable :-)  This role is the one true `root` user.
- Administrator
	- Scott (me) is currently the only additional Admin.  I've been doing a ton of dev work (bots, etc.) and needed this power for some of it.  If possible, I'm going to downgrade myself to DevOps.  Think of this role like member of the `root` group.
- Temporary Admin (color and permissions role)
	- This is another full admin role.  When assigned, the person with this power will show up in red and at the top of the user list so we know someone is poking around with danger powers.  It does so so that we remember to remove this role as soon as we're through using it (think `sudo`)
- DevOps
	- DevOps are the workers on the server - create and manage channels, roles, server settings, etc.  This person doesn't really have any moderation perms.
- ManageRoles
	- someone with this permission has the power to assign/remove the above color roles (and moderator and events manager perms) to other members. 
- Moderator
	- this role is for anyone that can help us keep things in order.  Mods have the power to manage stickers and emojis, as well as change other peoples nicknames and kick, ban, or time-out baddies.
- EventsManager
	- Anyone with this role is able to add or delete events (listed at the top-left of the UI)
- (some misc bot roles)
	- bots need powers.
- Admin Australia 
	- This and the \<Admin Section\> roles below grant the power to create channels, set permissions on those channels, and edit/delete/pin messages.  The assumption is that each section may want to modify the channels their users and BOM's want to use.  Admins granted this role must follow the rules outlined above when creating new channels.
- Admin Bay Area
- Admin France
- Admin Georgia
- Admin India
- Admin London
- Admin Los Angeles
- Admin Montreal
- Admin New York
- Admin New Zealand
- Admin Oregon
- Admin Toronto
- Admin Vancouver
- Admin Washington


## Asides/Concerns

### Moderation
We currently have categories for non-english speaking VES sections.  This is dangerous as there's no way for us to moderate and/or monitor them.  We need dedicated moderators for each of these sections.