# MuleSoft from Start: A Beginner's Guide

Everything discussed in the Twitch live sessions for MuleSoft beginners.

- Follow me on Twitch to see the live streams: [DevAlexMartinez](https://www.twitch.tv/devalexmartinez)
- Or watch the recorded and edited (shorter) versions in [ProstDev's YouTube channel](https://www.youtube.com/prostdev)

---

## 🗓️ Next session

The next session is scheduled for `June 28, 2023` at `1:30pm ET`.

What we'll learn:
- Review our homework from the last session
- Design an API
    - Test with the Mocking Service
    - Publish to Exchange
- Implement an API in Studio
    - Core components

---

## 💻 Past Sessions

| Session | Title | Description | Twitch | YouTube
| - | - | - | - | - |
| 0 | Planning the Outline | Based on the book `MuleSoft for Salesforce Developers`, we reviewed the relevant topics and created an appropriate outline for the upcoming sessions. More info [here](https://medium.com/another-integration-blog/mulesoft-from-start-a-beginners-guide-session-0-e6e98ba4200a). | [Full video (55min)](https://www.twitch.tv/videos/1816506733) | [Edited video (38min)](https://youtu.be/xzi8peU87v0)
| 1 | [MuleSoft Overview](#✅-session-1) | We went through an overview of the different MuleSoft products and how to get involved with the community. More info [here](https://medium.com/another-integration-blog/mulesoft-from-start-a-beginners-guide-session-1-mulesoft-overview-62fa9307ea2f). | [Full video (1h2min)](https://www.twitch.tv/videos/1822381945) | [Edited video (34min)](https://youtu.be/I6BWPoD639A)
| 2 | [What is an API?](#✅-session-2) | We explained the API basics and learned what is MuleSoft's API-led connectivity approach. More info [here](https://medium.com/another-integration-blog/mulesoft-from-start-a-beginners-guide-session-2-what-is-an-api-9a4602bbc51a). | [Full video (1h1m)](https://www.twitch.tv/videos/1840283988) | [Edited video (35min)](https://youtu.be/M4gYW2o9IKc)
| 3 | [Design an API Specification](#✅-session-3) | We created the requirements for our Blog API and started designing our API Spec. Finish your homework before the next session! More info [here](https://medium.com/another-integration-blog/mulesoft-from-start-a-beginners-guide-session-3-design-an-api-specification-2a315899f22f). | [Full video (1h16m)](https://www.twitch.tv/videos/1846281214) | [Edited video (42min)](https://youtu.be/XIrCqwmTPQs)

---

## 📝 Outline & Links 🔗

### ✅ Session 1

<details>
<summary>MuleSoft Overview</summary>

- MuleSoft products
    - [Anypoint Platform](https://anypoint.mulesoft.com/) - You can create as many free trial accounts as you want! Just change the username in each account.
    - [Anypoint Studio](https://www.mulesoft.com/platform/studio) - Main IDE
    - [DataWeave](https://dataweave.mulesoft.com/)
        - [Extension for VSCode](https://marketplace.visualstudio.com/items?itemName=MuleSoftInc.dataweave)
        - [Playground](https://dataweave.mulesoft.com/learn/playground)
        - [DataWeave CLI](https://github.com/mulesoft-labs/data-weave-cli)
    - [Anypoint Code Builder (BETA)](https://www.mulesoft.com/platform/api/anypoint-code-builder) - STILL IN BETA!!! DO NOT USE YET!
    - [Composer](https://www.mulesoft.com/platform/composer)
    - [MuleSoft RPA](https://www.mulesoft.com/platform/rpa)
- [Community overview](https://www.mulesoft.com/community)
    - [Ambassadors](https://developer.mulesoft.com/community/ambassadors) & [Mentors](https://developer.mulesoft.com/community/mentors)
    - [Meetups](https://meetups.mulesoft.com/)
    - [Help forums](https://help.mulesoft.com/s/)
- [Trainings/certification](https://training.mulesoft.com/overview)

**Other resources**

- Sravan Lingam's [MuleSoft Training for Absolute Beginners](https://www.youtube.com/playlist?list=PL61bQcdxsK6_1tb0BbAtAOX_SdtvgQlxV)
- Jitendra Bafna's [Mule Technology Academy - Zero To Hero](https://www.youtube.com/@muletechnologyacademy-zero5625)
- [Whitney Akinola's blog](https://www.whitneyakinola.io/)
- Joshua Erney's [jerney.io blog](https://www.jerney.io/)
- Alex's [ProstDev blog](https://www.prostdev.com/) and [YouTube channel](https://www.youtube.com/prostdev)
- [Edgar Moran's blog](https://yucelmoran.com/)
- [Mulesy](https://mulesy.com/)
- Arul Alphonse's [TechLightning courses](https://techlightningweb.com/) and [YouTube channel](https://www.youtube.com/c/TechLightning)

</details>

### ✅ Session 2

<details>
<summary>What is an API?</summary>

- Understanding APIs
    - [Understanding APIs (Part 1): What is an API?](https://www.prostdev.com/post/understanding-apis-part-1-what-is-an-api)
    - [Understanding APIs (Part 2): API Analogies and Examples](https://www.prostdev.com/post/understanding-apis-part-2-api-analogies-and-examples)
    - [Understanding APIs (Part 3): What are HTTP Methods?](https://www.prostdev.com/post/understanding-apis-part-3-what-are-http-methods)
    - [Understanding APIs (Part 4): What is a URI?](https://www.prostdev.com/post/understanding-apis-part-4-what-is-a-uri)
    - [Understanding APIs (Part 5): Intro to Postman and Query Parameters](https://www.prostdev.com/post/understanding-apis-part-5-intro-to-postman-and-query-parameters)
    - [Understanding APIs (Part 6): What are HTTP Status Codes?](https://www.prostdev.com/post/understanding-apis-part-6-what-are-http-status-codes)
- MuleSoft's API-Led connectivity approach
    - **Experience layer**: Top layer. These APIs connect with the client applications like a Mobile app, a Web app, or a Smartwatch app.
    - **Process layer**: Middle layer. These APIs orchestrate the Experience and System layers.
    - **System layer**: Bottom layer. These APIs connect with the server applications or third-party systems like SAP, Facebook, Salesforce, etc.

**Other resources**

- [MuleSoft for Salesforce Developers book](https://www.alexmartinez.ca/post/i-wrote-a-book-and-it-s-been-officially-published-mulesoft-for-salesforce-developers)
- [5 API Led Connectivity Project Ideas](https://www.whitneyakinola.io/post/5-api-led-connectivity-project-ideas)
- [Plan for Aspiring MuleSoft Devs](https://www.whitneyakinola.io/post/plan-aspiring-mulesoft-developers)
- [3 Regrets as a Junior MuleSoft Dev](https://www.whitneyakinola.io/post/3-regrets-as-a-junior-mulesoft-dev)
- [A Comprehensive Book Review of MuleSoft for Salesforce Developers](https://www.whitneyakinola.io/post/mulesoft-for-salesforce-developers)

</details>

### ✅ Session 3

<details>
<summary>Design an API Specification</summary>

- Step 1: Write down [requirements](/notes/blog-api-reqs.md)
- Step 2: Design the API spec in Design Center
    - Anypoint Platform > Design Center > Create > New API Specification
    - Name: `Blog API`
    - `Guide me through it`
    - Create API
- [This](/sessions/3/in-session-spec.raml) is the RAML we generated during the session.

**Homework**

- Finish creating the API Specification with the resources we didn't get to create during the session: `Writers`, `Categories`, and `Comments`.
- The solution will be added to this repo before the next session.

</details>

### ◻️ Session 4

- Design an API
    - Test with the Mocking Service
    - Publish to Exchange
- Implement an API in Studio
    - Core components
- Briefffff summary of ACB (BETA)

### ◻️ Session 5

- Deploy API to CloudHub - manually
- Runtime Manager
- API Manager
- CI/CD with GitHub Actions
    - Maven
    - Secured/encrypted properties

### ◻️ Session 6

- DataWeave

### ◻️ Session 7

- MUnit manually
- MUnit CI/CD
- Postman
- Mention BAT CLI
