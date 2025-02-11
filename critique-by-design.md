| [home page](README.md) | [Controlling Color](controlling-color) | [Final project I](final-project-part-one.md)| [final project II](final-project-part-three.md) | [final project III](final-project-part-three.md) |

# Critique and Redesign

Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently.

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


<img src="Data-viz sketch 1.png" width="600" style="margin-top: 20px; margin-bottom: 20px;"/> 


<br>I then experimented with a pie chart, thinking it made sense since the three AI tools’ search trends always summed to 100% within each state. But with so many states, the scale became overwhelming, making it hard to interpret.


<img src="Data-viz sketch 2.png" width="1000" style="margin-top: 20px; margin-bottom: 20px;"/>

A grouped bar chart seemed more promising, offering better clarity, yet something still felt off. I even tried adding hover interactions to reveal percentages, since spacing and scale remained tricky for static numbers. I worked with Google Colab to explore different possibilities, coding out multiple versions and testing variations since I wanted to understand how 51 states viz would look and that was easier through this medium than hand sketch. Each attempt brought me closer to understanding what worked and what didn’t but the perfect balance still felt just out of reach.

## Step four: Test the solution

The objective was to understand how others interpreted the data, what stood out, and what improvements could enhance clarity and usability.

Results: 

_I interviewed one arts management and entertainment management master student, both woman around 25 years old with not much idea of the genAI tools compared in this data._

<img src="Table interview.png" width="600" style="margin-top: 20px; margin-bottom: 20px;"/> 


Synthesis and Takeaways: 

One of the strongest takeaways from the feedback was the need for a clearer narrative. While the visualization contained valuable data, it lacked an immediate takeaway, making it difficult for viewers to extract insights at a glance. Instead of presenting all 51 states together, breaking the data into separate graphs based on dominant AI tools or highlighting key trends could improve clarity. Think of what is it trying to show? 

Another key insight was that the current structure made it hard to compare trends effectively. Interviewees suggested separating the visualization in a way that better illustrates differences, either by grouping states where a particular tool dominates or by structuring the data into distinct comparisons. This helped me realize that not every state needs to be represented; instead, the focus should be on making the data more digestible and insightful. What is the insightful information?

The feedback also reinforced the importance of defining the audience. Without a clear understanding of whether the visualization was for AI researchers, marketing professionals, or general users, for interest of Midjourney, DALL-E or Stable Diffusion  it was hard to tailor the design for maximum impact. By refining the approach and focusing on the most relevant trends, the visualization could better communicate its insights, making it more actionable and engaging.

_Design Changes for the Final Redesign :_

_Based on this feedback, the final redesign will focus on simplifying the structure and emphasizing key insights rather than overwhelming viewers with excessive data. Instead of displaying all 51 states, the visualization will focus on the most relevant trends, mostly by separating graphs based on the dominant AI tool in each region or by highlighting the top search trends for each tool._

_Additionally, ordering and grouping will be adjusted to make the comparisons more intuitive. Rather than an arbitrary arrangement, states may be ordered by search volume or grouped into meaningful categories that highlight trends more clearly._

_By refining the context and audience focus, the visualization will aim to tell a story rather than just display numbers. These changes will ensure that viewers, whether interested in Midjourney, DALL·E, or Stable Diffusion, can quickly grasp key insights and their dominant standing effectively._

_I am thinking something like 3 different grouped bar charts each focusing on the key stakeholder(One of 3 Gen AI) to gague their top 10 states for the google trend search and it's positioning in comparison, so it is more specific and driven by a single narrative and maybe a comprehensive understanding among those states at the end._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. 

<img src="Midjourney vs OTHER (2).png" width="600"/> 
<img src="DALL-E vs OTHER (2).png" width="600"/> 
<img src="Stable diffusion vs OTHER (3).png" width="600"/> 

<div style="min-height:387px" id="datawrapper-vis-VvpRU">
  <script type="text/javascript" defer src="https://datawrapper.dwcdn.net/VvpRU/embed.js" charset="utf-8" data-target="#datawrapper-vis-VvpRU"></script>
  <noscript>
    <img src="https://datawrapper.dwcdn.net/VvpRU/full.png" alt="" />
  </noscript>
</div>

## AI acknowledgements
_I used GenAI(Copilot) to help me with ode for Google Colab and paraphrasing some parts like the summary from google form, as well as grammarly for proofreading my writing._

