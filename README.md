# About

This is a simple chatbot created for the Delaware Office of Defense Services, the statewide public defender's office which also assists folks with expungements. It walks users through the complex factors that will determine whether their criminal record is eligible for expungement and leads to, essentially, one of three results: likely eligible now, likely eligible after specific additional conditions (such as after more time has passed or fines have been paid), or likely ineligible.

See it in the wild at https://ods.delaware.gov/expungements/ .

# Contact

If you are a public defender’s office or justice advocacy group interested in making a similar chatbot for your state, please do not hesitate to connect with me, whether you're merely exploring the idea, are interested in the concerns we addressed with ours, have technical questions, need to contract a developer, or just want some tips to get started on your own.

Reach me at https://skydriftmedia.com/contact. From there, you can email, privately message me on social media, or use the online form.

Wishing you all the best with your legal justice efforts!

# Make your own

Here are the general steps to making your own chatbot.
1. Get a solid grasp on your jurisdiction’s law, policies, and procedures related to the chatbot's topic.
2. Map the decision information.
   - **Simple option:** Map the info as linearly as possible. For example, if you put it into a flow chart, you would want most of the operations to be in a straight line, without a lot of branching or loops, from start to finish.
   - **Advanced option:** Map the info in terms of (a) all the variables you might need to know, (b) all the relevant values, (c) all the calculations you might need to make, and (d) all the logical structure’s rules. For example, for the variable "offense level", the values might be "felony type C", "felony type B", and "misdemeanor type A" or whatever relevant labels your jurisdiction uses; a calculation for the variable "time passed" might be "current date minus date of conviction, rounded down to nearest year"; and a rule might be "if offense level is felony type C, and if time passed is less than ten years, then current eligibility is false".
3. Use the map to write interactive questions, responses, explanations, and next steps. Use non-legalese, plain language. Also write any introductory language that your office deems necessary (such as, you know, “This chatbot is not your lawyer.”).
4. Code your chatbot.
   - **Simple option:** Use [QnA Markup](https://www.qnamarkup.org/), an amazing tool from Suffolk University Law School's LIT Lab "for people with little or no programming experience. It was designed with attorneys in mind and transforms blocks of text into interactive question and answer sessions".
   - **Advanced option:** Use [docassemble](https://docassemble.org/). You've already done the bulk of the work by mapping the logic structure.
5. Style and design.
6. Test on website and debug.
6. Go live.
