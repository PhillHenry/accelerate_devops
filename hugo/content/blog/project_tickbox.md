+++
title = '11 properties of highly effective projects'
date = 2025-10-22T14:38:10+01:00
+++

**What Successful IT Projects Have in Common**

Technology rarely sinks a project - people and processes do. 
Most IT failures can be traced not to flawed tools or frameworks, but to mismatched roles, poor communication, and missing feedback loops. 
Context always matters, but most successful projects share some universal traits.

---

### **People**

#### **Hire Great Developers**
This one’s obvious but still surprisingly rare. Why? Because hiring managers often don’t know what a good developer looks like - and good developers are expensive.

The best way around this is to have your strongest developers lead the hiring process. Skilled engineers can recognise other skilled engineers. 
And while great developers may cost more, hiring fewer but better ones reduces communication overhead - a major drag on productivity. Google has shown that smaller, stronger teams almost always move faster.

#### **Eat Your Own Dog Food**
If the people building the product aren’t the ones maintaining it, you can bet maintenance won’t be the top priority.
It’s human nature to prioritise getting something out the door when you don’t have to live with its quirks later. 
This was a major pitfall of early-2000s outsourcing. 
These days, staff are generally embedded in the development team if work is outsourced to a third party. 

#### **Define Quality Requirements Clearly**
Every work ticket should:
- Be reviewed and approved by the people implementing it  
- Contain accurate and complete information  
- Include acceptance criteria that define what “done” really means  

Negotiating ticket details is part of the process. That negotiation works best when the team feels psychologically safe - free to question assumptions and push back when something doesn’t make sense.

#### **Build Emotional Safety**
Steve Jobs once said, *“It doesn’t make sense to hire smart people and then tell them what to do. We hire smart people so they can tell us what to do.”*  

If you want smart people to speak up, leadership needs to listen - regularly. 
One-off away days won’t cut it. 
Daily stakeholder engagement is key. 
Agile practices like retrospectives and sprint planning formalise this, but the underlying principle is simple: communication should be continuous, not occasional.

#### **Say No to Silos**
“Scrum Master” is a role, not a job title. “DevOps” is a mindset, not a separate team.  

The more you silo responsibilities, the more corner cases slip through the cracks. Keep communication lines open and responsibilities shared.

#### **Maintain Regular Feedback Loops**
Show-and-tells, burn-down charts, retrospectives - these aren’t just Agile rituals; 
they’re tools for alignment. 
When communication works, no one should ever be surprised by project timelines or deliverables.

#### **Encourage Autonomy**
A conductor doesn’t tell the lead violinist *how* to play - only *what* to play. 
The same goes for software teams. Give teams clear goals, then trust them to decide how best to achieve them.

---

### **Process**

#### **Automate Everything**
...but especially automated regression tests.
They are the best defence against code rot and unintended side effects. 
Continuous integration is now standard in any major open source project, but surprisingly still spotty in some industries. 
If you have mastered this, move on to continuous deployment. 
You should be able to create and destroy whole test environments with a button click. 

#### **Logging is an Art**
Good logging is essential for effective maintenance. 
It’s also the first thing that is neglected when developers don’t maintain their own code - another reason to “eat your own dog food.” 
Note that even with good logging, you need people with a holistic - not siloed - view of the product as diagnosis tends to be like a jigsaw.

#### **Fail Fast**
Don’t overanalyze when a quick prototype will do. 
Often, it takes less time to try something than to debate it in meetings. 
If it fails, you’ve learned something valuable. 
Agile calls this a “spike” - a short, focused experiment to validate an idea.

#### **Keep Documentation Alive**
Documentation has a tendency to drift out of sync with reality. 
Developers rarely have time to update it, and professional documenters rarely have deep technical insight. 
One solution: let your test suite generate documentation. 
Behaviour-Driven Development (BDD) tools can keep code and documentation in lockstep, automatically reflecting the current state of the system.

---

### **Final Thoughts**

Every successful project balances people, process, and technology - but the first two matter most. 
Hire fewer, smarter developers. 
Give them autonomy, safety, and accountability. Back them up with automation, communication, and feedback loops.  

The tools will change. The principles won’t.

