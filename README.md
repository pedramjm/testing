# Todo 
(for fully functioning deployable version)


## Front-end status:

> Complete

** Submit button needs to point to back-end action. **


## Back-end:

- Nodejs, MongoDB
- CI capable (dockerized, YAML etc)


## Other

Build in more tutorial style examples 
e.g.: use the ASRA web application as a guide, referencing examples as to how we'd assess the application.
- Scoping: draw some example diagrams, consider the attack surfaces, threat modeling, public/private etc.
- Authentication: none, however, if *there were*, then these are examples of things we'd consider (and things we'd want reviewed)
- Input Checking: show our inputs and outputs (diagram or UML), and show what we'd have to take into consideration (validation, sanitization, escaping)
- Cryptography: are we storing anything? Are we using keys? Plain english.
- Data in transit: HTTPS, Certificates etc.
- Malicious Code and Vulnerabilities: we are using third party software; how do we assess it (and continue to keep it up to date?) Whose responsibility is it?
- Cloud services: SaaS communication (we were going to use Google OAuth but that required opening up unnecessary external communication)



## Nice to haves:

- Front-end: toggle to enable/disable hover tooltips
- EVentually shift the domain scoping (and scope headings) to be dynamic (stored in MongoDB)
