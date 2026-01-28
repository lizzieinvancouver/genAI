Started 4 January 2026

_Organizing myself somewhat on generative AI notes_

### Sorting out a lecture to give early in term for CONS 310
* See also https://github.com/lizzieinvancouver/hotecology/issues/56

### Chat with Cam (phone; 21 December 2025)
Most of the notes are in my orange notebook that I travel with, but here are the highlights to tell students

* What is an LLM?
* Chat window versus interacting with a computer/model
* It is not intelligent; it is a fascimile of intelligent
* Maybe the history of AI (also the randomization/temperature part)
* Machines cannot reason (see Gary Markus lectures etc.)

**Outsourcing comprehension/writing/reasoning*** leads to de-skilling, so we're all renting our cognitive abilities from megacorporations for the rest of our lives.

* Your LLM use is heavily subsidized
* Your inputs are helping them
* Models developed by using the Global South
* Data center usage of water etc.
* It's designed to be addictive (and uptake is going much faster since we have phones etc.)

* Review MIT experiments on whether you are learning with LLMs (I should look for new research; I did -- I have not found it)
* Review evidence that we get smaller networks and smaller information from it in the end?

* Fundamental abdication of human dignity to machines. 
* Plagiarism and just embarrassing to use (but if you want to https://guides.library.ubc.ca/GenAI/cite)

What can students do?
* Think about what materials you give to AI
* Vote
* Stay informed
* Pay for an email service not owned by google etc. (proton mail)
* Don't buy into the idea that you need to learn genAI to get a job 

## See also: ChatsBenNotes from 7 Jan 2026

## Asking Cam about temperature

I've heard people describe it well in podcasts, but can't remember which.  I think it's a simple as how much randomness you add to the generation run. It determines the slope of the curve from the most probable solution out towards the less probable solutions. With temp=0, the answer would be deterministic: the same solution every time for a given prompt. With high temp, there is a chance to get very low probability solutions, which can seem like higher 'creativity' but also higher hallucination. // It seems to be a feature of the 'softmax function' (Wikipedia: https://en.wikipedia.org/wiki/Softmax_function#Temperature). See also: https://www.ibm.com/think/topics/llm-temperature and https://towardsdatascience.com/a-comprehensive-guide-to-llm-temperature/  But not sure if these are helpful to students.

## Ref from Cam: Bender 2025

This is a really good article. She's a computer-psycho-linguist and a leading AI critic. The point about how we are fooled/lured into believing in an intelligence by the language itself was a new angle for me and really important.

## Cam's testimony at school board

https://camwebb.info/files/webb_FNSBSDSB_testimony_2026-01-20.pdf

## Model behind chatGPT from Bob Carpenter (emailed 15 Oct 2025)

Hi, Lizzie and Jonathan:

It was really great getting a chance to catch up yesterday.

Here's ChatGPT 3.0 in about 50 lines of pseudocode.  This is actually
complete, including tokenization, training, and then how it runs.  I
don't go into all the details of fine tuning, but the point is that
the output of fine tuning is the same architecture.  So this is very
close to the run-time architecture of all the current Chatbots.

https://statmodeling.stat.columbia.edu/2023/10/12/simple-pseudocode-for-transformer-decoding-a-la-gpt/

Here's a good example of how. I use ChatGPT for stats, though I've
posted several blog posts on this with examples:

https://statmodeling.stat.columbia.edu/2025/09/09/show-dont-tell-chatgpt-5-marginalizing-gelmans-measurment-error-model-in-stan/

I'll follow up separately on the biome composition model.

- Bob

* From this email's links: Nice overview of tokens: https://statmodeling.stat.columbia.edu/wp-content/uploads/2023/10/carpenter-transformers-pseudocode-oct-20-2023.pdf


## Reviewing stuff I have opened over the last week on 10 Jan 2026 
* Gary Marcus (cognitive scientist, ) -- What kind of AI world should we want? (https://www.youtube.com/watch?v=NUb61YMu1_o&t=8s) ... current AI is technically and morally inadequate ('frequently wrong, never in doubt')
* Great post by Gary Marcus: https://garymarcus.substack.com/p/three-years-on-chatgpt-still-isnt which includes:
> I do think they [LLMs] have their uses, but I worry about their costs to society, around bias, cybersecurity, misinformation, nonconsensual deepfake porn, copyright theft, energy and water usage, the gradual enshittification of the internet, the severe hit to college education, and so on.
This post makes the case that the problems like hallucinations are inherent to the technology and not likely to go away. ... but likely to feed massive MIS-information.
* I tried to figure out what a reasoning model is, but most of the content is when to use one. The closest I got is this: https://cameronrwolfe.substack.com/p/demystifying-reasoning-models which led me to search for 'chain of thought reasoning' which led to chain of thought prompting. Is a reasoning model just new prompt engineering? I gave up. 
* Post literate society -- https://jmarriott.substack.com/p/the-dawn-of-the-post-literate-society-aa1 -- about how no one reads anymore
* Geoffrey Hinton -- godfather of AI (big person against it)
* ‘reinforcement learning from human feedback’ (Ouyang et al., 2022) -- this must be the part Bergstrom talked about using global South labor (this step is in the cameronwolfe.substack above) -- see also https://elezea.com/2024/04/how-cheap-outsourced-labour-in-africa-is-shaping-ai-english/
* Good Atlantic arcticle I shoudl get a copy of https://www.theatlantic.com/ideas/archive/2025/10/ai-deskilling-automation-technology/684669/
* Deskilling: https://arxiv.org/pdf/2503.03924 which I downloaded (Shukla_etal_2025) and took the quote about airline pilots and deskilling from (used in cce hotecology lecture 3)
* MS study finds that AI makes you dumber and narrows your world https://www.forbes.com/sites/dimitarmixmihov/2025/02/11/ai-is-making-you-dumber-microsoft-researchers-say/, I downloaded the linked study which is Lee_etal_2025.pdf
* Generational cognitive atrophy (mentioned above? Not sure), which is on Hal and downloaded as: Mahajan_2025_cognitiveatrophyloop.pdf includes "Historical disruptions to cognitive structures—from the Gutenberg press to industrial schooling and the television
era—are examined to illustrate that cognitive decline is not irreversible. Each case demonstrates that epistemic
erosion was reversed when institutions responded with intentional design rather than technological determinism." ... also another use of friction being good ('friction-rich pedagogy' vs. LLMs which reduce friction)

## Some definitions
* alignment -- getting models to align with ethical principles (and user expectations)


