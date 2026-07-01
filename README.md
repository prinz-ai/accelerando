# accelerando
## A Chronicle of Events Leading to the Singularity[^1]

# 2025

***January 4***:  Sam Altman [writes](https://x.com/sama/status/1875603249472139576): "i always wanted to write a six-word story. here it is: ___ near the singularity; unclear which side."

***January 25***:  OpenAI [announces Project Stargate](https://openai.com/index/announcing-the-stargate-project/), which is intended to bring a massive amount of compute online over the next few years.  Other industry participants (xAI, Amazon, Microsoft, Meta, Google, *etc.*) quickly follow by significantly expanding their datacenter build-outs.

***February 24***:  Anthropic [releases Claude Code](https://www.anthropic.com/news/claude-3-7-sonnet).

***April 15***:  OpenAI updates its [Preparedness Framework](https://cdn.openai.com/pdf/18a02b5d-6b67-4cec-ab64-68cdfbddebcd/preparedness-framework-v2.pdf), isolating "AI self-improvement" as a category for the first time.  "High" risk associated with this capability as the equivalent of "giving every OpenAI researcher a highly performant mid-career research engineer assistant", relative to those researchers' 2024 baseline.

***April 16***:  OpenAI [releases Codex CLI](https://techcrunch.com/2025/04/16/openai-debuts-codex-cli-an-open-source-coding-tool-for-terminals/), initially designed to run locally from terminal software.  This release [is closely followed by a cloud-based version of Codex](https://openai.com/index/introducing-codex/) (on May 16).

***June 10***:  Sam Altman describes his vision of the future in an essay entitled [The Gentle Singularity](https://blog.samaltman.com/the-gentle-singularity) The essay begins with: "We are past the event horizon; the takeoff has started."

***September 15***:  OpenAI [releases a new version of Codex](https://openai.com/index/introducing-upgrades-to-codex/), based on GPT-5 (itself released just a few weeks prior).  Codex significantly grows in popularity following this release.

***September 29***:  On release of Sonnet 4.5, Anthropic [surveys 7 of its researchers](https://assets.anthropic.com/m/12f214efcc2f457a/original/Claude-Sonnet-4-5-System-Card.pdf) regarding the acceleration in their work from using Sonnet 4.5 in Claude Code.  The reported median productivity boost estimate is 20%-30%.

***October 29***: Sam Altman and Jakub Pachocki announce [during a livestream](https://www.youtube.com/watch?v=ngDCxlZcecw) that OpenAI is targeting an automated AI research intern for September 2026.  A fully automated AI researcher is to follow by March 2028.  Sam Altman later [posts](https://x.com/sama/status/1983584366547829073) that the "intern" will run on "hundreds of thousands of GPUs".

***November 19***:  OpenAI [asked GPT-5.1-Codex-Max](https://x.com/Miles_Brundage/status/1991238750802727373) to diagnose and explain 20 internal research and engineering bottlenecks that OpenAI has actually encountered in the past, each of which took ≈1 day for the OpenAI team to solve. The model scored 8% on this eval (named "OpenAI Q&A").

***November 24***:  Anthropic [releases Opus 4.5](https://www.anthropic.com/news/claude-opus-4-5), which immediately becomes the coding model of choice for most programmers.  In connection with this release, Anthropic [surveys 18 members of its technical staff](https://assets.anthropic.com/m/64823ba7485345a7/Claude-Opus-4-5-System-Card.pdf) to estimate the productivity boost they get from using Opus 4.5 in Claude Code.  50% of survey participants report productivity improvement of at least 100%; average reported productivity improvement is 220%.  Two researchers characterize the model as a "near-complete entry-level researcher replacement", albeit with "meaningful caveats".

***December 19***:  METR [announces](https://x.com/METR_Evals/status/2002203627377574113) that Opus 4.5 has a 50%-time horizon of approximately 4 hrs 49 mins, significantly higher than any other model released to date.

# 2026

***January 9***:  Anthropic's Jack Clark [reveals](https://post.substack.com/p/the-ai-revolution-is-here-will-the) that "the main thing" he worries about is "whether people succeed at 'building AI that builds AI' - fully closing the loop on AI R&D (sometimes called recursively self-improving AI)".

***January***:  A series of tweets from Anthropic and OpenAI researchers confirm that nearly all code at these labs is now written by Claude Code/Codex:  
* [Boris Cherny](https://x.com/bcherny/status/2015979257038831967) (Anthropic): "Pretty much 100% of (the Claude Code team's) code is written by Claude Code + Opus 4.5. For me personally it has been 100% for two+ months now, I don’t even make small edits by hand. I shipped 22 PRs yesterday and 27 the day before, each one 100% written by Claude."
* [Santiago Hernandez](https://x.com/santiaghini/status/2012447234806382665) (OpenAI): "recursive self-improvement is around the corner.  you can feel it in the corners of your terminal window"
* [roon](https://x.com/tszzl/status/2015253546372153347) (OpenAI): "programming always sucked... it's amazing how quickly I've moved on and don't miss even slightly... 100% (of coding is being done by Codex for me), I don't write code anymore"
* [Thibault Sottiaux](https://x.com/thsottiaux/status/2018258151603388639) (OpenAI): "Codex now pretty much builds itself, with the help and supervision of a great team.  The bottleneck has shifted to being how fast we can help and supervise the outcome."
* [Noam Brown](https://x.com/polynoamial/status/2018387805341380848) (OpenAI): "Codex is writing all my code these days."

***January 20***:  At the Davos conference, Dario Amodei [says that powerful AI is not that far off](https://x.com/deredleritt3r/status/2013613671704924640):

> The mechanism by which I imagined it would happen is that we would have models that are good at coding and AI research. And we would use that to create the new generation of models and speed it up, to create a loop that would increase the speed of model development. We are now at a point where I have engineers at Anthropic who say: 'I don't write any code anymore, I let the model write the code, I edit it, I do the things around it.' We might be 6-12 months away from a model that can do everything SWEs do end-to-end. And then the question is, how fast does that loop close? Not every part of that loop is something that can be sped up by AI. There's chips, manufacture of chips, training time for the model. There's a lot of uncertainty. It's easy to see how it could take a few years. It's very hard for me to see how it could take longer than that. But if I had to guess, I would guess that it goes faster than people imagine. And that key element of code, and increasingly research, going faster than people imagine - that's going to be the key driver.

***January 26***:  Dario Amodei, in "[The Adolescence of Technology](https://www.darioamodei.com/essay/the-adolescence-of-technology)", writes that AI "is now writing much of the code at Anthropic" and "already substantially accelerating the rate of our progress in building the next generation of AI systems".  He adds: "This feedback loop is gathering steam month by month, and may be only 1-2 years away from a point where the current generation of AI autonomously builds the next.  This loop... will accelerate rapidly in the coming months and years."

***February 4***:  GPT-5.2 (high) is [finally scored by METR](https://x.com/METR_Evals/status/2019169900317798857), achieving new SOTA performances on its 50% benchmark (6 hrs 34 mins, beating Opus 4.5 by over an hour) and 80% benchnmark (55 mins, beating Opus 4.5 and Gemini 3 Pro by over 10 minutes).

***February 5***:  [Opus 4.6](https://www.anthropic.com/news/claude-opus-4-6) and [GPT-5.3-Codex](https://openai.com/index/introducing-gpt-5-3-codex/) are released on the same day.  OpenAI announces that GPT-5.3-Codex "[is our first model that was instrumental in creating itself"](https://x.com/deredleritt3r/status/2019475360438493597), with early versions of the model used to debug its own training, manage its own deployment, and diagnose test results and evaluations.  New Codex models are now being released on a monthly basis.[^2]. 

***February 8***:  [OpenAI's Super Bowl ad](https://x.com/OpenAI/status/2020649757434327362) features Alan Turing, Bayes' Theorem, scenes from Pantheon, and a book opening to a chapter entitled "The Singularity Is Near".

***February 24***:  Anthropic releases its new [Frontier Safety Roadmap](https://www.anthropic.com/responsible-scaling-policy/roadmap) and the first [Risk Report](https://www-cdn.anthropic.com/08eca2757081e850ed2ad490e5253e940240ca4f.pdf) under its updated [Responsible Scaling Policy](https://www-cdn.anthropic.com/e670587677525f28df69b59e5fb4c22cc5461a17.pdf).  These documents state that it is "plausible, as soon as early 2027," that Anthropic's AI systems could fully automate, or otherwise dramatically accelerate, the work of large, top-tier teams of human researchers in domains like energy, robotics, weapons development and AI research, and that, "in the next few years," AI models could have a broad range of capabilities that exceed human capabilities.  Anthropic promises to publicly announce within 30 days if it has developed an internal model that "could pose significant risks above and beyond" those posed by its publicly available models, "includ(ing) any internal models that we are deploying for large-scale, fully autonomous research".

***March 4***:  Dario Amodei, [in a new interview](https://www.tmtbreakout.com/p/tmtb-dario-amodei-anthropic-ceo-at), says: "I think this year is going to have a radical acceleration that surprises everyone. Exponentials catch people off guard — there’s the old parable of the second half of the chessboard, where you have one grain of rice in the first square, two on the second, four on the fourth. By the time you get to the 64th square, you have billions or trillions of grains of rice. We’re standing on square 40 out of 64, and from square 40 to square 64, it’s going to go faster than you think — even having seen how fast it’s gone so far. I don’t think people are ready for it. I think we are on the precipice of something incredible."[^3]

***March 11***:  Anthropic co-founder and chief science officer Jared Kaplan [tells Time magazine](https://x.com/AndrewCurran_/status/2031731035105628270) that fully automated Al research could be "as little as a year away".

***April 6***:  Anthropic [hits annual run-rate revenue of $30B](https://x.com/deredleritt3r/status/2041287132463919297), up from $19B in just the previous month and $9B at year-end 2025.

***April 7***:  Anthropic [releases a system card](https://www-cdn.anthropic.com/53566bf5440a10affd749724787c8913a2ae0841.pdf) for Mythos Preview, a new class of model that the company does not initially intend to make generally available, and [announces](https://x.com/AnthropicAI/status/2041578403686498506) that Mythos Preview "has already found thousands of high-severity vulnerabilities—including some in every major operating system and web browser."  Anthropic also [announces "Project Glasswing"](https://x.com/AnthropicAI/status/2041578392852517128), a partnership with various firms and organizations that will use Mythos Preview to find and fix security flaws in various existing systems - before powerful AI models to be released in the future are able to exploit them.

***April 14***:  It is [announced](https://x.com/Liam06972452/status/2044051379916882067) that GPT-5.4 Pro has solved Erdős problem #1196 in one shot, after 80 minutes of thinking.  This is by far the most interesting mathematical result achieved by any AI model to date (but probably still not a "Move 37").  Famed mathematician Jared Lichtman explains: "I care deeply about this problem, and I've been thinking about it for the past 7 years. I'd frequently talk to Maynard about it in our meetings, and consulted over the years with several experts... The problem was not a question of low-visibility per se. Rather, it seems like a proof which becomes strikingly compact post-hoc, but the construction is quite special among many similar variations."

***April 20***:  It is [reported](https://x.com/Yuchenj_UW/status/2046246166871089438) that Sergey Brin has formed a "strike team" at Google aimed at improving Google's coding AI models.  "The end goal is AI takeoff or AI that can improve itself… Brin has told staffers that improving Google AI’s coding abilities is a step toward that eventual goal."

***April 23***: OpenAI releases GPT-5.5, which is based on "Spud" - a larger pre-trained model.  

[roon posts](https://x.com/tszzl/status/2047386955550470245): 

> there are early signs of 5.5 being a competent ai research partner. several researchers let 5.5 run variations of experiments overnight given only a high level algorithmic idea, wake up to find completed sweep dashboards and samples, never having touched code or a terminal at all

[Aidan McLaughlin posts](https://x.com/aidan_mclau/status/2047388367705575701):

> over break i dictated to 5.5 for minutes describing a new ambitious rl run. hit send and forgot about it as i hung out with friends and bf for a few days. returned on monday to an industrial-scale rl run humming after it worked for 31 hours

Based on my private conversation with an OpenAI researcher, the model still does not qualify as an automated AI research intern because "we have a technical definition of a research intern that involves a lot more autonomy".

**April 29**:  It is [reported](https://www.wsj.com/tech/ai/white-house-opposes-anthropics-plan-to-expand-access-to-mythos-model-dc281ab5) that the Trump administration has opposed a broader roll-out of Anthropic's Project Glasswing "because of national-security risks posed by the model".  If true, this is the first known instance of the U.S. government attempting to block or restrict a roll-out of a frontier AI model.

***May 4***:  Jack Clark [writes](https://importai.substack.com/p/import-ai-455-automating-ai-research) that, based on publicly available information, "there’s a likely chance (60%+) that no-human-involved AI R&D - an AI system powerful enough that it could plausibly autonomously build its own successor - happens by the end of 2028"; if this were to fail to occur, it would be because "we will have revealed some fundamental deficiency within the current technological paradigm".  Clark also believes that there's a 30% chance that a non-human-involved AI R&D system can be built in 2027.

***May 4-5***:  It is [revealed](https://www.nytimes.com/2026/05/04/technology/trump-ai-models.html) that the Trump Administration is considering the introduction of "government oversight" over new AI models, which could include "a formal government review process for AI models".  On May 5, NIST [announces](https://www.nist.gov/news-events/news/2026/05/caisi-signs-agreements-regarding-frontier-ai-national-security-testing) that CAISI has signed agreements with Google, Microsoft and xAI regarding "frontier AI national security testing" and has also renegotiated its existing agreements with OpenAI and Anthropic.[^4]  On the same day, Chris Lehane [confirms](https://x.com/deredleritt3r/status/2052013136337674294) that CAISI is testing GPT-5.5-Cyber and that OpenAI is partnering with the U.S. government on developing a "responsible deployment strategy" for this model, including how to provide it to U.S. federal, state and local governments, critical infrastructure operators and allies.

***May 20***:  An unreleased OpenAI general reasoning model [solves the planar unit distance problem](https://cdn.openai.com/pdf/74c24085-19b0-4534-9c90-465b8e29ad73/unit-distance-remarks.pdf), a famous open question first posed by Paul Erdős in 1946.  The model had no scaffold, did not use Lean, and solved the problem completely autonomously, without any human involvement.  Noga Alon: "This has been one of Erdős' favorite problems, I have heard him myself mentioning the problem multiple times in his lectures.  I believe it would be fair to say that every mathematician working in Combinatorial Geometry thought about this problem, and lots of mathematicians working in other areas spent at least some time thinking about it."  Timothy Gowers: "If a human had written the paper and submitted it to the Annals of Mathematics... I would have recommended acceptance without any hesitation."

A chart released by OpenAI [in an accompanying blog post](https://openai.com/index/model-disproves-discrete-geometry-conjecture/) reveals that, remarkably, its internal model can solve the unit distance problem 48% of the time if provided sufficient compute.

***June 2***:  The White House releases an Executive Order, "[Promoting Advanced Artificial Intelligence Innovation and Security](https://www.whitehouse.gov/presidential-actions/2026/06/promoting-advanced-artificial-intelligence-innovation-and-security/)", which establishes a "voluntary framework" enabling frontier labs to provide access to new "covered frontier models" to the U.S. government, for a period of up to 30 days before the model is released to "other trusted partners".  The NSA is charged with determining whether a model is a "covered frontier model" based on a classified benchmark that will seemingly cover only cybersecurity capabilities.

***June 2***:  OpenAI CFO Sarah Friar [says](https://www.youtube.com/watch?v=TjrShuj_Zsg) that OpenAI's model training "mostly" happens in the United States "for USG reasons for making sure that a national asset and effect is happening on US soil".

***June 4***:  It is [reported](https://www.notus.org/technology/trump-ai-stake-openai) that senior U.S. government officials have held early discussions with "major AI companies" about the "potential for the federal government to acquire some shares in their firms".  It emerges that Sam Altman has been discussing this idea with Trump since early 2025. 

***June 9***:  Anthropic [releases Fable 5](https://www.anthropic.com/news/claude-fable-5-mythos-5), an improved version of Mythos Preview.  The model is noteworthy for its excellent coding capabilities.

***June 10***:  Dario Amodei releases [a new essay](https://darioamodei.com/post/policy-on-the-ai-exponential), "Policy on the AI Exponential", in which he writes that, if the scaling laws continue for "only a year or two longer", we are "likely" to achieve powerful AI, a.k.a. "a country of geniuses in a datacenter". 

***June 10***:  A [leaked OpenAI internal company memo](https://www.reuters.com/business/openai-expects-go-public-within-next-year-information-reports-2026-06-10/) states that OpenAI expects to launch its IPO "within the next year" (*i.e.*, by June 2027), but "if advances in OpenAI's technology enable RSI (AI that can create new AI on its own), it could weaken the push for a quick IPO".  This seems to suggest that OpenAI leadership views RSI as possible by year-end 2026.

***June 12***:  The U.S. government, after having received a report from Amazon of an alleged serious vulnerability in Anthropic's Fable 5 and Mythos 5 models, [issues an export control directive to Anthropic](https://www.anthropic.com/news/fable-mythos-access) to suspend all access to these models by any foreign national, whether inside or outside the U.S., including foreign national Anthropic employees.  Anthropic suspends access to these models for all customers.

***June 15***:  The Financial Times, quoting a person close to OpenAI, [reports](https://x.com/deredleritt3r/status/2066555668434239990) that, "in recent days, the industry has been working (with the U.S. government) on ensuring foreign national researchers could continue to work on developing the most advanced models".  This seems to indicate that the U.S. government has been looking to restrict foreign nationals from working on frontier models across the industry.

***June 16***:  Sam Altman [reveals](https://x.com/deredleritt3r/status/2067019412960379007) that the fully automated AI researcher targeted by OpenAI for March 2028 would be able to "figure out completely new architectures", which seems to indicate that it would be superhuman or near-superhuman at ML research.[^5]

***June 16***:  NVIDIA [introduces](https://x.com/DrJimFan/status/2066921736369766762) ENPIRE, a set of eight Codex agents given a fleet of robots, an allocation of GPUs and a generous token budget that is able to serve a variety of physical world tasks.  "All we did is to give Codex an API to the world of atoms, and the rest is emergence."  "We... discovered a new type of 'physical scaling': 8 robots exploring in parallel improves significantly faster than fewer ones."

***July 1***:  Access to Fable 5 is restored worldwide after [Anthropic agrees](https://www.anthropic.com/news/redeploying-fable-5) to implement various safeguards and work with the U.S. government on new safety protocols and standards, as well as releases of future models.

[^1]: This chronicle starts in early 2025 with Anthropic's and OpenAI's releases of the first agentic coding models. The reader is well within his right to ask the author why this particular point was the one chosen as the threshold for crossing the event horizon. Would it not have been better to choose OpenAI's release of the first reasoning model (September 2024) as the threshold? Or perhaps the release of GPT-4? The release of GPT-3.5? Some even earlier ML milestone? The author agrees with this criticism and posits that, indeed, it is possible that mankind took its first firm step towards the singularity approximately 400,000 years ago when man first learned to control fire. Be that as it may, any chronicle has to start *somewhere*, and, in the author's view, having it start right before Sam Altman definitively wrote (in June 2025) that "we are past the event horizon; the takeoff has started" is as good a place as any. 

[^2]: GPT-Codex-5.1-Max was released on November 19, 2025.  GPT-Codex-5.2 was released on December 18, 2025.  GPT-5.3-Codex was released on February 5, 2026.

[^3]: At this time, Anthropic was also engaged in a stand-off with the U.S. Department of War over Anthropic's demands to place contractual restrictions on the use of Claude for the Department's activities related to domestic mass surveillance and autonomous AI weapons.  The Department of War threatened to designate Anthropic a supply chain risk as a result of Anthropic's stance on this matter.

[^4]: This announcement later mysteriously disappears from NIST's website.

[^5]: Sam Altman also reveals that the automated AI research intern targeted for September 2026 will run on an equivalent of 500,000 A-100 GPUs.
	

[^6]: As of early morning on July 1, 2026, OpenA
