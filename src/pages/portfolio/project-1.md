---
title: Rescue Vox | Case Study
subtitle: "Conversational User Interface,\_Product Design"
date: '2019-05-10'
thumb_image: images/knowledgeable-plankton.png
image: images/green-avocado.png
template: project
---
###### **Team:** Just me

###### **My Role:** CUI Design, UX Writing, Product Design

###### **Project Objective:** Design a conversational user interface or voice user interface for an existing product.

## The Story

Requesting Emergency Services in a time of crisis should be a swift experience that leaves no opportunity for delay, as every second truly does count. I wanted to design a Conversational User Interface that effectively communicates to users how to activate the 911 emergency response system. This concept design utilizes an AI chatbot to understand why the user is requesting emergency services and sends the appropriate emergency response resources to the scene of the emergency.

## Problems & Opportunites

### Key Problem

Activating the current 911 system in the United States is an **antiquated** process that requires a caller to dial 3 numbers and press call. The caller is then asked “Do you need Police, Fire or EMS?” requiring the user to **think** on the spot of what resources they need.

## Competitive Landscape

#### America's 911 System

*Pandemic pushing America’s 911 system to breaking point*

###### “The strain could result in longer wait times and some providers going out of business, ambulance operators said. Ambulance providers are struggling to meet surging demand even while grappling with increased costs of personal protective equipment, overtime, staff shortages as workers fall ill and decreases in the type of emergency calls that are reimbursed.”

[-New York Times Article](https://www.seattletimes.com/nation-world/nation/pandemic-pushing-americas-911-system-to-breaking-point-ambulance-operators-say/)

> How can we alleviate the strain that this pandemic has put on our 911 system?

#### Denmark's 911 System

*Coronafiles: Chatbots take strain off Denmark’s emergency helplines*

###### “We put more staff on but we couldn’t keep up with the volume. Our biggest worry was that people with other diseases weren’t able to get through. It worked well enough that the chatbot service was rolled out beyond just the initial Copenhagen area to all of Denmark.”

[-Sifted EU Article](https://sifted.eu/articles/coronafiles-chatbots-helplines/)

> Denmark has proven that investing in a chatbot system can make for a more efficient Emergency response system.

#### HMW

![](images/008.png)

#### VUI or **Chatbot?**

When presented with the challenge of improving the 911 system by utilizing Artificial Intelligence, I found that ultimately both a VUI AND Chatbot would be necessary to meet the objectives of this project. I focused my scope on the Chatbot feature for this design as I felt it would be much easier to visually show how this product would work from a user interface.

#### Solution

![](images/010.png)

#### Product Goals

**1. Improve emergency response times**

**2. Decrease the strain on 911 operators**

**3. Decrease cognitive load of the caller**

***

### Discovery, Design & Testing

#### Discovery

![Mind Map](/images/mind-map.png)

#### List of All

|Intents                |Utterances                          |Entities                         |
|----------------|-------------------------------|-----------------------------|
|Activate 911 chatbot | `'I need an ambulance'`  | Trauma Call
Get emergency help fast and accurately|`'I need the police'`            |Emergency Medical Call            |
|Get help about what to do in an emergency           |`'I need the fire department'`             |Crime            |
|          |`'I don't know what to do'` |Fire/Rescue|

#### Initial Conversational Flows

![](images/015.png)

#### Findings

![User Testing: Tester #1 - This user suggested improving the urgency of the conversational tone. This user stated that interacting with the prototype was too slow. They also mentioned that it would be helpful to provide an intro to explain “what’s next” when the bot describes what steps to take after the user has clicked “no” to the question, “Are they breathing?”. Tester#2 - This user tested the chat bot design and said “my overall experience was that it was super easy, quick and intuitive. I liked that each question only had yes or no options — nothing more to think about.”. This user suggested providing feedback on when the ambulance and rescue team will arrive. They stated “I think that would be a feature people would greatly appreciate and help them stay calmer.” Tester #3 - This tester stated that it would be nice to activate the 911 Rescue Vox by speaking to it similar to an Amazon Alexa device or a Google Home device. They mentioned that this would help people that are visually impaired operate 911 even faster in the event of an emergency.](/images/user-testing.png)

#### Research Insights

*   **Improve tone urgency** - Part of the chatbot’s tone was too conversational.
*   **Super easy** - Liked that there were yes and no options.
*   **Quick and intuitive**  - Liked that there were few questions that speeds up the process of getting help to the scene.
*   **Provide eta feedback** - Give the user feedback on how long it will take the emergency crews to respond.
*   **Describe what’s next** - Provide the user with what they should do next.
*   **Needs voice feature** - Would be nice to activate 911 by speaking and having the bot respond quickly. *This is a future goal to work towards.*

#### Core User Needs

|Efficiency                |Reassurance                          |Competency                         |
|----------------|-------------------------------|-----------------------------|
|Being able to know that the 911 system will dispatch emergency response units to the scene of an emergency with accuracy and speed. |Reassurance that help will arrive to the scene and that the caller will be at ease when activating the 911 system. |Taking comfort in knowing that this emergency chatbot is well versed in emergency protocols and can provide guidance to the user when they need it the most.

#### Revisions

![](images/021.png)

#### Conversational Flows

![Flow1 - Breathing? Yes](/images/YES-BREATHING.png)
![Flow2 - Breathing? No](/images/NOT-BREATHING.png)
![Flow3 - Mistake](/images/Mistake-.png)

> I wanted to ensure that the Rescue Vox chatbot accounts for various paths that the user might encounter.

#### Prototype

[Bot Society](https://app.botsociety.io/2.0/designs/5fd056d41094cb4bbd86535d?m=interactive)

## Take Away

I really enjoyed designing this CUI chatbot experience! Designing for emerging technologies is without a doubt challenging, but I am glad I could apply my knowledge of user interface design, interaction design, and UX writing to this product.
