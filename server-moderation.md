## 1. General goals
### 1.1. Staff coordination

Keeping communication open and awareness of situations in and around the server is essential to the good functioning of the moderator team. 

Having a clear goal of good communication between all staff about their expected duties, server moderation incidents (see 1.2), and the overall community goals of the server, ensures the staff are unified in working towards those goals.

### 1.2 Incident handling

Moderation incidents on the server are inevitable; when they happen, the goal is to work towards a resolution that's consistent with previous incidents and the server's rules. 

Outcomes for members involved in incidents should be well understood by the server population at all times, so they know what to expect if they are involved in breaking the rules. 

Ultimately, here, members who break a server rule should know _which_ rule they violated and the consequences received for it should be consistent with other similar incidents.

## 2. Server Moderation

### 2.1 Staff role divisions

#### Goals addressed: 1.1

Given the current structure, the staff roles involved in moderation are, generically;
- Server Owner (Seraphina)
- Administrators (All roles specifically with the Administrator privilege granted)
- Server Moderators
- Advisors (non-privileged advisory input on incidents)

This division seems workable at the moment, however it may be desirable to add a "Senior Moderator" tier between Administrators and Server Moderators, into which trusted moderators can be bestowed the privilege to kick and ban users (which would be removed from the normal Server Moderator role).

This is mostly useful if the Moderator role is offered out on a rotating basis (see 2.2.1).

### 2.2 Staff responsibilities
#### Goals addressed: 1.1

The duties of each role should be clearly set out, and this should be clear to all members holding those roles. 

This structure is _heirarchical_, and responsibilities _cascade down_. The duties of a Server Administrator _extend and include_ the duties of a Server Moderator. In this vein, the Server Owner holds the duties of all the staff roles.

- _Server Owner - Seraphina_ 
	- Holds the ownership of the server (tautologically). 
	- Sets out the goals for the server and the community within it.
	  
- _Server Administrator_ 
	- Sets server policies that will align to the goals laid out by the Server Owner, in concert with the Server Owner.
	- Manages the Server Moderation and Advisor team members.
	  
- _Senior Server Moderator (if added)_
	- Handles removal of Server Members where required.
	  
- *Server Moderator*
	- Enforces the server rules and policies set out by the Server Administration team.
	  
	- Handles removal of Server Members where required (in the absence of the *Senior Server Moderator* role)
	  
- *Advisor*
	- Offers their input and experience to the Server Moderator and Server Administration teams in a non-enforcing capacity.

_Discretion_ is a core responsibility of all staff. These are trusted positions 

#### 2.2.1 Staff Appointment and Rotation

It's often useful or desirable to _rotate_ staff at the Server Moderator level on a periodic basis, to encourage activity and to prevent stagnation within the moderation function. 

If so, this is where adding the _Senior Server Moderator_ role comes into its highest form of relevance; Rotation of Server Moderators is best performed when the role does _not_ carry expressly elevated privleges. 

While the role remains a position of trust, it requires substantially _less_ trust in the individual Server Moderator. This would be achieved by the removal of the Server Moderator's permissions to Kick and Ban Users. 

They'd retain: 
- Manage Users (for adjusting their roles)
  
- Manage Messages (for removing messages sent by others) 
  
- Timeout - though the use of a Quarantine Channel (see 2.3.1) should be preferred over timeouts.

Appointment of rotating staff is usually handled via an application form, which is then reviewed by the Senior Server Moderators (in an advisory capacity) and the Server Administrator team. 

The Server Administration team (including the Server Owner) ultimately handles the selection of the Server Moderation team for each defined rotation (usually 3 months).

### 2.3 Incident Handling

When incidents occur _on or in the community surrounding the server_ (say, externally on a Server Member's tumblr blog), Server Moderators and above should respond to the incident in a consistent and structured way, in order to achieve the goals noted.
#### 2.3.1 Incident Handling: Specific Channels
##### Goals addressed: 1.1 & 1.2

- Quarantine:
	Problematic users who are disruptive to the server are often handled using Discord's _timeout_ facility, but doing this simply mutes them within the server, offering short-term respite from the disruption.
	
	_Quarantine channels_ (a _"jail"_ of sorts) into which a user can be locked by means of the addition of a singular server role, offer a space for discussion between Server Member and Server Moderator that is isolated from the public server, but is visible to all staff and persistent once the incident has been resolved.
	
- Incident Log:
	Once an incident has been successfully resolved, a structured record of the  incident placed into a log channel offers a quick reference for all staff into what happened, when, who was involved, and what the resolution was. 
	
	This works best when it utilises a consistent template, such as:
	
```
**__Server Incident Report__**

## Moderator Name:

## Date and Time of Incident (use @time):

## Discord ID (@mention) of Instigating User:

## Instigating Message(s) (copy-paste message URL(s)):

## Investigation Log (use full sentences, but be concise):

## Final Moderation Decision:

## Time of Final Moderation Decision:
```
#### 2.3.2 Incident Handling: Process Flow
##### Goals addressed: 1.2

With Quarantine channels as outlined in 2.3.1, handling of an incident becomes a mappable process of:

1. Check to see which Quarantine channels are available (Possibly with a bot command, but this can be manually verified by visiting the channel and visually reviewing the memberlist there)

2. Assign the offending user the appropriate quarantine role.

3. Greet the user in the Quarantine channel __with a ping__ since they will likely be unable to see the initial message.

4. Explain to the user the reason why they are in the Quarantine channel and be specific to the rule violation(s). If able, post a screenshot of the violation and remain as impartial to the context of the offense as possible.

5. Search within the Incident Log channel for prior incidents which reference this Server Member. A search string like `in:#incident-log mentions:<Server Member>`.

6. Aim the conversation into acknowledgement of the offense. Allow the Server Member to ask questions but maintain your composure and speak only to the facts of the situation.

7. After achieving acknowledgement of the offense, issue a proportionally appropriate outcome (See 2.3.2) and ensure the Server Member is aware of this outcome. 
 
	If the *Senior Server Moderator* role is required to remove the Server Member from the server as part of their outcome, one should be requested in the moderation coordination channel by pinging that role. 
	
	While the Server Member is quarantined this can be considered non-urgent, since they've already been removed from the public server at this point.

8. If the Server Member is to remain in the server, allow the Server Member to ask any more questions and at an opportune time, relieve them of their Quarantine role.

#### 2.3.3 Incident Handling: Outcomes

This aspect varies a lot server-to-server, but from the most common systems:

**Three Strikes** - simple, concise, easy to understand, popular with people who like baseball. 
  
Server Members accumulate _Strikes_ as in Baseball when they are deemed to be at fault for breaking a server rule. 
  
After having received two such strikes, the Server Member's next incident is automatically escalated and the Server Member's removal from the server is considered.
  
It's good to have these strikes _expire_ after a certain amount of time (3 months or so) to prevent historical incidents keeping a Server Member at the two-strike threshold in perpetuity. 
