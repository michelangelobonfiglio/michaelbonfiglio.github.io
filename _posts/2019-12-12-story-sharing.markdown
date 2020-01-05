---
layout: post
title:  Story Publishing
description: Extending our content creator tool to allow users to publish content internally to their organization.
cat: OpenGov
tags: Product Design, Application, UX/UI, Interaction, OpenGov
thumb: thumb-stories.png
---
<section  markdown="1">
## Basics
</section>

<section class="basics">
<div  markdown="1">

#### Problem
The Stories product was built to allow governments to share narratives and corresponding data with the public to develop a sense of transparency and invest in public trust. Post-launch we learned of two use cases that seemed to want to be solved together. The first was our customers were using the tool to create stories that were not meant to be exposed publicly. The second was leaders needed a way to review documents internally before they went out to the public.

To solve this customers would really need 2 things: the ability to set permissions on these artifacts and more control on publishing options. The first was blocked by a larger initiative to address permissions at scale, so we chose to focus on publishing controls.


</div>
<div markdown="1">
#### Role
- Problem Discovery
- Research
- Interaction Design
- Visual Design

#### Goals
- Drive usage for internal communication
- Address low hanging UX inconsistencies
- Set up foundations for access control
</div>
</section>


<section  markdown="1">

## Process
![Process](/assets/images/stories/process.png)

</section>

<section class="col-2" markdown="1">
<div  markdown="1">
Because of a lot of moving people and vision collateral, this feature got a little ahead of itself. So we had to take a few steps back to fully understanding the architecture that existed in product, and then to work with engineering, product management, and leadership to reset expectations.
</div>

![Recipe](/assets/images/stories/stories-recipe.png)

</section>


<section  markdown="1">
### How everyone thought it worked
The requirements and goals for the project assumed that the publishing flow worked the same in stories as it did in our other products: there was a single artifact that could be toggled in visibility. Our other products had a similar model but used different language

![Assumed Flow](/assets/images/stories/stories-assumed.png)

</section>

<section  markdown="1">

### How it actually worked
However, the draft and the published version were not in sync. Publishing created a new separate object from the draft which could be overwritten when you clicked republish.


![Actual Flow](/assets/images/stories/stories-actual.png)
</section>

<section  markdown="1">

### Research Insights

Through interviews and observation with heavy users on our Customer Success team, we learned there was confusion on the publishing flow.

Being able to edit without publishing changes was very valuable, but with no indication that edits had been made, that ability wasn’t clear to most users.

![republish](/assets/images/stories/stories-republish-flow.png)
</section>

<section  markdown="1">

## Results

### Separate edit from publish
We moved publishing to the summary page so that the editor only contained saving interactions.

![edit](/assets/images/stories/stories-results-edit.png)

![save](/assets/images/stories/stories-results-save.png)

</section>

<section  markdown="1">

And the summary page housed publishing status interactions.

![republish note](/assets/images/stories/stories-results-republish-note.png)
![republish dialog](/assets/images/stories/stories-results-republish-dialog.png)

</section>

<section  markdown="1">

Which allowed us to easily add the publish to organization status.

![republish dialog](/assets/images/thumbs/thumb-stories.png)

</section>
