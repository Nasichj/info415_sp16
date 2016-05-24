```
    _____   ____________     __ __ _________
   /  _/ | / / ____/ __ \   / // /<  / ____/
   / //  |/ / /_  / / / /  / // /_/ /___ \  
 _/ // /|  / __/ / /_/ /  /__  __/ /___/ /  
/___/_/ |_/_/    \____/     /_/ /_/_____/  
    --- Web Application Security ---       

``` 

# Description
This course will cover the ins and outs of web application security from the perspectives of the developer, administrator, and attacker. We will cover attacks from the all too common Cross-Site Scripting (XSS) attack through Cross-Site Request Forgery (CSRF), SQL Injection (SQLi), all the way to more advanced topics.
 
The goals of this course centers around familiarizing students with how to recognize a possible vulnerability, write a proof-of-concept, and provide helpful remediation so that a developer can properly mitigate the issue. The emphasis will be on hands-on learning and the students will be expected to think creatively as they face common defenses and work with unfamiliar frameworks and languages.

# Grading
Grade breakdown:
- hw: 80%
- final: 20%

Late penalty: 
- 10% daily, incremented in 10% steps (24hrs from time due)
- stops at 50% deduction

# Resources
- Bitsync key: BAPDG2PLBHLTP72NDQLVE3MHVKCF5WUSQ 
- Suggested reading: Web Application Hacker's Handbook

# Weekly Schedule

## Week 1 - Foundations
### Tuesday
- introduction
- class overview
- threat modeling

### Lab
- tools setup
- capturing traffic

### Thursday
- how the internet works
- client to server communications
- browser basics

### Homework
- required
	- browsing by hand
- recommended
	- read WAHH chapter 12
	- read WAHH chapter 3


## Week 2 - XSS
### Tuesday
- cross-site scripting (XSS)
	- how it works
	- why it's so common
	- why it's bad
	- how to find it
	- how to mitigate
- reflective XSS
- stored XSS
- XSS demos
- practice: http://xss-quiz.int21h.jp/

### Lab
- character encoding
- unicode security
- punycode domains

### Thursday
- filter bypass techniques
	- no spaces
	- no script tag
	- XSS via images
	- encoding galore
	- other weirdness
- do stuff
	- filter bypassing

### Homework
- required
	- XSS challenges
	- pentest report
	- due next thursday


## Week 3 - XSS 2
### Tuesday
- regular expressions
- SuperSecureBank

### Lab
- puzzle
- time to work on HW

### Thursday
- advanced payloads
	- exfiltrating cookies
	- inducing user action
	- fake login forms

### Homework
- recommended
	- reading on CSRF and Clickjacking
		- WAHH Chapter 13 section on "Inducing User Action" (501-515)
		- http://www.troyhunt.com/2013/05/clickjack-attack-hidden-threat-right-in.html


## Week 4 - CSRF & Clickjacking
### Tuesday
- CSRF
	- how it works
	- why it's bad
	- how to find it
	- how to mitigate
- CSRF demo

### Lab
- puzzle solution
- how Tor works

### Thursday
- Clickjacking
	- how it works
	- why it's bad
	- how to mitigate
	- special tactics
- Clickjacking demo

### Homework
- required
	- CSRF challenges
	- clickjacking challenges
	- pentest report
	- due next thursday
- recommended
	- read WAHH chapter 9


## Week 5 - SQLi 1
### Tuesday
- SQL injection
	- how it works
	- why it's bad
	- how to find it
	- how to mitigate
	- how to pull data
	- special tactics
- SQLi demos
- SQL practice

### Lab
- social engineering

### Thursday
- SQL injection practice
	- OWASP Broken Web Application

### Homework
- required
	- SQL injection challenges
	- pentest report
	- due next tuesday


## Week 6 - SQLi 2
### Tuesday
- canceled

### Lab
- keyloggers

### Thursday
- Advanced SQL injection techniques

### Homework
- required
	- none
- recommended
	- read WAHH chapter 6
	- read WAHH chapter 7


## Week 7 - Authentication
### Tuesday
- common authentication issues
	- session fixation
	- session invalidation issues
	- timing attacks
	- user enumeration
	- insufficient entropy

### Lab
- canceled

### Thursday
- authentication 2.0

### Homework
- none


## Week 8 - Crypto
### Tuesday
- cryptography
	- public/private key
	- forward secrecy
	- hashes
	- stream vs block cipher
	- algorithm modes: ECB, CBC, others

### Lab
- bitcoin

### Thursday
- single signon
- business logic attacks

### Homework
- none


## Week 9 - Misc. Attacks
### Tuesday
- testing techniques
- review HW answers

### Lab
- canceled

### Thursday
- canceled

### Homework
- required
	- golden bank pentest
	- pentest report
	- due next thursday


## Week 10 - Advanced Attacks
### Tuesday
- homework
	- SuperSecureBank pentest
	- pentest report
	- due thursday

### Lab
- lockpicking
	- slides
	- https://www.youtube.com/watch?v=ChbyaXBKNY8

### Thursday
- final
