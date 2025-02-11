| [home page](README.md) | [Controlling Color](controlling-color) | [Final project I](final-project-part-one.md)| [final project II](final-project-part-three.md) | [final project III](final-project-part-three.md) |

# Critique and Redesign

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: The Visualization

_[link to the original data visualization](https://data.world/makeovermonday/generative-ai-search-trends-in-the-united-states)_  

While selecting this particular data viz on Gen AI search trends in US based on region, I was initially drawn to the subject matter itself. AI-generated imagery, especially the 3 tools analysed here is something I’ve been exploring personally, and understanding regional interest of these tools based on google trends (DALL·E, Midjourney, and Stable Diffusion) felt intriguing. Looking at the viz sparks a lot of questions about technology adoption variation across location; about what factors drive these differences? Are they cultural, economic, or perhaps tied to industry hubs? An interest topic for the 3 companies themselves, to understand a surface level positioning within regions and overall understanding of the competitor.

At first glance, the original visualization was somewhat unclear. The numbers were there, but they didn’t immediately tell a story. I had to take a step back and ask: What exactly am I looking at? Were these just random search volumes or normalized trends for each region? Why were some states leading in searches for one tool over another? The data hinted at regional preferences, but without additional context, such as population density, or digital adoption rates, but it definitely was a start, however it was difficult to determine why certain states ranked higher and would there be confounding to correlate to adoption of the tool.

I also saw potential in the dataset’s depth. There wasn’t just one story here, but multiple narratives waiting to be uncovered. This made it a great exercise in narrowing down focus, a skill I want to refine, especially when dealing with large datasets. Additionally, the original visualization was interactive, which posed an interesting challeng of how do you translate an interactive viz into a static one without losing clarity or information so it is easier to understand at a glance? What works better in which contexts? This project became an opportunity to experiment with storytelling through visualization, refining both my analytical and design instincts in the process.

## Step two: the critique
_The entire critique is reorded on a google form, although I am attaching a short summary below._

The interactive data visualization on generative AI search trends across U.S. states effectively highlights regional differences in interest for Midjourney, Stable Diffusion, and DALL·E. The use of color-coding, a map, and a sidebar chart makes geographic comparisons intuitive, while the hover tool provides additional details. However, some usability issues limit its clarity and engagement. The visualization only presents relative search interest rather than absolute search volume, which can lead to misinterpretations. Additionally, the tooltip obscures the map, making navigation difficult, and the lack of state abbreviations on the map adds another layer of friction. A clearer title specifying the three AI models and permanently displaying percentage values on the bar chart could improve perceptibility.

There are multiple primary audience currently - AI researchers, marketing teams, and entrepreneurs, making the viz pretty dense and less specific, also it limits in absolute data and navigation hinders deeper insights. The evaluation method used effectively measures truthfulness, perceptibility, and engagement but lacks criteria for interactivity and data context. Adding assessments for navigation and dynamic interaction, as well as data framing, would provide a more complete evaluation. Improvements such as incorporating absolute search volume, better labeling, and search functionality would enhance usability and clarity.

## Step three: Sketch a solution

I found myself struggling with this step, trying to find a way to represent all 51 states in a single visualization while keeping it clear and meaningful. At first, I started stripping away elements from the original viz, removing interaction, the map and so on but that only led to another challenge, how should the states be arranged? Should I group them by geographic region, or maybe order them based on Midjourney's dominance, since it had the highest average trend share? Neither option felt entirely satisfying.

<img src="Data-viz sketch 1.png" width="600"/> 
I then experimented with a pie chart, thinking it made sense since the three AI tools’ search trends always summed to 100% within each state. But with so many states, the scale became overwhelming, making it hard to interpret.

<img src="Data-viz sketch 2.png" width="1000"/>
A grouped bar chart seemed more promising, offering better clarity, yet something still felt off. I even tried adding hover interactions to reveal percentages, since spacing and scale remained tricky for static numbers. I worked with Google Colab to explore different possibilities, coding out multiple versions and testing variations since I wanted to understand how 51 states viz would look and that was easier through this medium than hand sketch. Each attempt brought me closer to understanding what worked and what didn’t but the perfect balance still felt just out of reach.

## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

