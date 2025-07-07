While reviewing investment banking interviews over the weekend, I noticed a recurring theme: deep skepticism toward AI. Bankers consistently questioned whether AI could truly handle the nuance and pressure of their workflows.
It reminded me of a broader pattern I’ve seen after sitting through hundreds of startup pitches in my role as a venture partner. In the VC world, we’ve developed a simple but powerful framework to explain why some AI products take off—while others stall, even with best-in-class models.
It comes down to what we call TAIR — Trust in AI Results. This isn’t a vanity metric. TAIR is a measurable, optimizable psychological threshold. It’s often the difference between breakthrough adoption and complete rejection—regardless of how technically sophisticated your AI might be.

Understanding user adoption barriers
Adoption is fundamentally blocked by fear. For maximum adoption, you want low fear and high confidence. TAIR helps you quantify that trust 
TAIR measures user confidence through a simple relationship that balances the value users get against the psychological barriers they face:

The equation makes intuitive sense:
Value: The benefit users get when AI succeeds
Risk: The consequence if the AI makes an error
Correction: The effort required to fix AI mistakes
When TAIR is high, users embrace AI features enthusiastically. When TAIR is low, adoption stalls no matter how technically impressive your AI is.
TAIR is primarily determined by product design decisions, not just the underlying AI capabilities.
The critical insight is this: TAIR is driven more by product design than by AI model performance. Yes, accuracy matters. But product teams can’t control the model improvement cycle — vendors ship better models over time.
What we can control is how risky an action feels and how painful it is to correct. That’s the real lever. In practice, I’ve seen two AI products using the same underlying models succeed or fail depending entirely on how they were designed around these trust factors.
High-Stakes Domains: Where Design Becomes Critical
In spaces like financial services and healthcare, I’ve seen firsthand how AI’s core limitations—especially around math and numerical reasoning—can create inherently low TAIR (Trust in AI Results). And in these cases, product design isn’t just important—it’s everything.
It’s not just about consequences; it’s about capability gaps. Today’s LLMs struggle with things like precise calculations, consistent numerical logic, and structured reasoning. That makes domains like accounting, tax prep, and investment advisory inherently tough—no matter how slick the UX is.
Take AI-powered tax software, for example. The real issue isn’t only the downside of getting it wrong (think IRS audits, penalties). It’s that LLMs can’t reliably handle the math or apply tax rules with precision. If the system were to auto-file returns without human oversight, the TAIR would crater:
Auto-Filing Tax AI TAIR = High ÷ (High × High) = Very Low



TurboTax gets this. Their strength lies in acknowledging the limitation and designing around it. Instead of just doing a final check, they’ve embedded human control throughout the entire journey: guided input from users, AI-powered suggestions, and human approvals at every critical step. The AI doesn’t replace human judgment—it enhances it, especially in areas where precision matters most.
Five Principles for Raising TAIR
Across the interviews we’ve done and the AI products I’ve seen gain real traction, a consistent pattern emerges: the most successful teams aren’t just optimizing model accuracy—they’re intentionally designing for TAIR (Trust in AI Results).
These five principles show up again and again. They’re not theoretical. They’re what consistently move the needle in real-world adoption.

1. Strategic human-in-the-loop (Improves Value, lowers Risk and Correction)
 One of the biggest misconceptions I see is that “autonomous” = better. In reality, removing humans entirely from the loop spikes Risk and kills trust. But layering human input everywhere kills Value. The key is to be surgical. Insert approval or review only at high-leverage points—like before a number goes into a client-facing deck, or before final submission. You protect confidence without slowing everything down.

2. Reversibility (Lowers Correction)
 When users know they can undo something, their willingness to engage goes up dramatically. Even simple features—“Undo,” “Revert,” “Restore previous version”—reduce friction. The psychological safety of reversibility makes users more comfortable taking advantage of what the AI can do.

3. Isolated consequences (Lowers Risk)
 I’ve seen adoption rates skyrocket just by separating exploration from deployment. Whether it's a sandbox, preview mode, or draft state—giving users a low-stakes space to test AI suggestions removes fear. You shift the mindset from “I’m risking something” to “I’m playing with options.”

4. Transparent reasoning (Lowers both Risk and Correction)
 When users can see why the AI made a choice, they’re more likely to trust it—or fix just the part that’s off. This is especially important in domains like finance or legal, where even small details matter. Explanations turn the AI from a black box into a collaborator.

5. Control gradients (Increases Value while managing Risk)
 Let users ease into the product. Start with safe, low-risk use cases and progressively unlock higher-value functionality as trust builds. Not every user wants full automation on day one. Designing for gradual control gives people room to grow their confidence.

Rethinking How We Ship AI
TAIR reframes how we think about AI readiness. It’s not just, “Is the model accurate enough?” It’s also, “Have we designed for high enough trust that people will actually use it?”
When I’m evaluating or building AI products now, these are the questions I ask:
How easily can users correct mistakes?


How severe is it if the AI gets it wrong?


What’s the upside if it gets it right?


Do users feel like they’re still in control?


Can they understand why the AI did what it did?


This shift is freeing. You don’t need perfect models to build great AI products. I’d take an 85% accurate system wrapped in a high-TAIR design over a 95% accurate one with poor trust design any day. Because at the end of the day, people adopt what they trust.
We See the Same TAIR Pattern in Investment Banking
In our interviews with over 13 bankers, one pattern came up again and again: when it comes to nuanced, high-stakes workflows, the limiting factor isn’t just model performance — it’s whether anyone, even a human, can extract the right information quickly and with confidence.
One VP pointed to rig count commentary buried in upstream oil & gas transcripts. These slides are critical in market update decks and often shape the banker’s strategic point of view in client meetings.
But the language used by management teams is often vague and indirect — “we plan to maintain current activity levels” instead of clearly stating, “we are keeping our rig count flat.” Even for experienced analysts, it can take hours to locate, interpret, and verify these subtle shifts across 20+ companies.
His concern wasn’t that AI might hallucinate — it was that the signal is so faint, and so inconsistently phrased, that even humans struggle to catch it reliably. That’s why he was deeply skeptical that AI alone could automate this task without significant oversight.
TAIR Breakdown:
Value: High — the insight drives a core slide in client decks


Risk: High — misreading or missing tone can lead to misinformation


Correction: High — verifying across scattered, messy transcripts is slow


TAIR = High ÷ (High × High) = Very Low

How to Raise TAIR
Automation won’t work unless the design explicitly accounts for this ambiguity. What actually helps:
Quote + Timestamp + Link for every AI-suggested insight


Language disambiguation: flag when AI is unsure whether phrasing implies a change (“soft signal detected”)


Promptable audit trails: “Show me all management commentary on rig activity in the last 10 days”


Side-by-side comparisons: “How did this quarter’s language change from last?”


The challenge isn’t pulling data—it’s interpreting nuance at scale. That’s where TAIR collapses—and where thoughtful product scaffolding can rebui
