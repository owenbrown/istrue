## Is True

Is True facilitates distributed fact-checking. 

### How does this work?

During account creation, a new user selects people and organizations who they trust. This step creates the user's _Trust Network_.

The user installs a browser extension. Each time the user visits a web page, the browser extension queries the user's Trust Network to look for annotations regarding the page's creator's trustworthiness. 

### What is a Trust Network?
The Trust Network is a list of people and organizations that a user trusts, plus the people and organizations they trust. 

For example, Alice trust her brother, Bob. Bob trusts the medical journal [The Lancet](https://www.thelancet.com). Therefore, The Lancet's is part of Alice's Trust Network. If Alice visits any page on The Lancet's domain, the browser extension will indicate that Bob trusts The Lancet. Alice can click a link to an annotation that Bob wrote in which he describes why he trusts the Lancet.

### Transmitting each page URL invades users privacy
The initial implementation focuses on simplicity. New ideas are fragile, and we must create a proof-of-concept as quickly as possible. We respect users' privacy and security and will find a way to protect both.

### Should this exist?
I don't know yet. Between 90% and 99% of new software projects shouldn't exist because they don't solve a serious and compelling problem for anyone.
I've [created a page](need-approach-benefit-competition) to try to answer this question. 

In the run-up to the 2020 United States presidential election, I maintained a dialogue with a friend whose news sources were different than mine. I spent many nights reading and researching articles he sent me. Through careful analysis, I was often able to show that the items he shared were either complete fabrications or carefully constructed to be shared virally on social media while misleading their audience.

I was frustrated because it took hours to determine whether an article was true, but I only shared that analysis with one person. How can our society survive this flood of dis-information when it takes hours to debunk fake news but only a few seconds to share a lie?

### Make Something People Want
I'm a software developer who loves building things, so my instinct is to build proof-of-concept. However, the product manager and former start-up founder in me knows that there are faster ways to determine whether this project is pursuing.

This project solves two separate problems for two user groups.
*Passionate advocates of the truth* need a way to fight fake news effectively. These people are like me. They are willing to spend hours to find out what is true, but they are frustrated that their efforts little or no impact on other people. The project empowers these people to make fight dishonesty in a meaningful way.

*Typical users*  want to make decisions based on accurate information. For example, my mother reads articles about the Covid-19 vaccine, and she does not know who to believe. The stakes for her are real - life and death. The project helps her know who to trust.

### How to contribute
Glad you asked! Check out our [how to contribute page](https://owenbrown.github.io/istrue/how-to-contribute).
