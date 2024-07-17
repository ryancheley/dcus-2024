# Error Culture

---

# Introduction

- I'm Ryan Cheley
- I'm the Senior Regional Director of Business Informatics ... but that just means I'm a Director of Enginnering
- You can find me here:

    - website
    - mastadon
    - linkedin

---

# Error Culture

^ notes: welcome to my talk 'Error Culter'. Today I'm going to be talking about Error Culture. Specifically what it is, how to tell if you're in an orgnization that suffers from it, and how to get out it

# What is it?

> A culture that accepts error notifications and ignores them, encouraging a reactive instead of proactive culture of problem solving

# Why is it bad? 

- Encourages the creationg of low signal to noise ratio for alerting
- allows **potentially** really bad problems to not be fixed until they are really bad: [See](https://miro.medium.com/v2/resize:fit:854/format:webp/1*QQvTuD-5AH2NKdh1_B_teQ.jpeg)

# Hero Culture

![We have a problem here!](https://miro.medium.com/v2/resize:fit:854/format:webp/1*QQvTuD-5AH2NKdh1_B_teQ.jpeg)

---

# Why does it happen?

- Error Fatigue
- Lack of Understanding of 
    - what the error is
    - why it's important
    - who it impacts
- Emphasis on Hero Culture, [see](https://naksecurity.medium.com/the-detriments-of-hero-culture-3fc455963d6e)

---

# Who does this happen to?

---

# People in Tech

- Developers
- Help Desk
- Sys Admins
- Network Admins

^ notes: Since we're at a tech conference, the obvious answer is folks in tech. This can be ....

---

# Office workers

- Administrative Assistants
- Data Anlysts
- Account Maangers
- C Suite Execs

^ notes: but you might not realize this has the potential to happen in other areas of life as well. 

---

# When does it start?

- Internal Reasons
- External Reasons

---

# Internal

- When someone decides that ‘we’ need to be notified of when ‘this’ happens again
    - Example here
- When an alert is created because it ‘might’ be useful but doesn’t provide full context for why
    - Example here
- When too many alerts are created without context for what the errors are
    - Example here

---

# External

- When a consultant indicates that it is ‘best practice’ to be notified of an alert but doesn’t provide more context
    - Example here
- When defaults for external software come with enabled alerts but no context or steps for resolution
    - Example here

---

# How can I tell if I'm in an error culture

- Do you receive emails or alerts from no-reply style email addresses that you have email rules that just delete them?
    - Example here
- Do you receive emails or alerts from no-reply style email addresses where your first reaction is to just delete them
    - Example here
- Do you see others around you put out fires that you knew were coming?
    - Example here
- Do you know why you receive alerts or errors? 
    - Example here

Any of these can point to you being part of an Error Culture.

---

# What can be done to fix it? 

No matter where you are in the 'ladder' at work (i.e. IC, or CTO) you can make a change

---

# Start here

Is the alert you are getting Actually Important? 

If it is NOT important, delete it.

Not just the alert, but the mechanism for the alert

Be mindful of Chesteron's fence here though! 

---

# It is important

But is it actionable? 

If YES

- Make sure the error indicates what needs to be fixed
- make sure the error indicates why it's important
- make sure the *right* people are being notified

If NO

- update it to be actionable
- include
    - Steps to resolution or documentation link for resolving the error
    - Update the alert to indicate it’s importance
    - Update the alert to go to the correct people

---

# Resources

---

# Questions

Questions? 