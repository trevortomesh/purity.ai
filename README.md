# 📊 Purity.ai
***A nutrition label for your AI diet!***


---

![Mixed Collab](https://img.shields.io/badge/AI_Purity-Mixed_Collab-yellow)
![SPGR](https://img.shields.io/badge/AI_Assist-📝_Spelling_%26_Grammar-yellow)
![CMT](https://img.shields.io/badge/AI_Assist-💬_Code_Comments-red)
![OUT](https://img.shields.io/badge/AI_Assist-📄_Outline_Assistance-blue)
![LOG](https://img.shields.io/badge/AI_Assist-⚙️_Logic_Generation-orange)
![DOC](https://img.shields.io/badge/AI_Assist-📑_Documentation-red)

---

The AI Purity Scale is a framework for transparently communicating how much artificial intelligence (AI) assistance was used in a project, document, or artwork. This system introduces standardized badges—similar to GitHub shields—to provide a quick and clear summary of AI vs. human contributions.

---

🚀 Purpose

As AI tools become prevalent in coding, writing, and creative processes, it’s crucial to establish an honest and ethical framework for their use. The AI Purity Scale is designed to:
	
 	•	Promote transparency about AI involvement.
 	•	Prevent stigmatization of AI use while encouraging ethical practices.
 	•	Help educators, researchers, and developers evaluate contributions.

---

🎨 The AI Purity Scale

The AI Purity Scale measures contributions across a sliding range, using color-coded badges:

Scale |	Description |Color |Badge Example |
|-----|-------------|------|--------------|
Purely Human | Fully human-created | Blue | ![Badge](https://img.shields.io/badge/AI_Purity-Purely_Human-blue)	
Mostly Human | Minor AI assistance | Light Blue | ![Badge](https://img.shields.io/badge/AI_Purity-Mostly_Human-lightblue)
Mixed Collab | Equal AI and human input | Yellow | ![Badge](https://img.shields.io/badge/AI_Purity-Mixed_Colab.-yellow)	
Mostly AI | Significant AI use | Orange	| ![Badge](https://img.shields.io/badge/AI_Purity-Mostly_AI-orange)
Purely AI | Fully AI-generated | Red | ![Badge](https://img.shields.io/badge/AI_Purity-Purely_AI-red)
	
---

🛠 Category-Specific Badges

In addition to the overall scale, badges can identify specific types of AI assistance:

Category| Badge Example|
|-------|--------------|
Spelling and Grammar (SPGR) | ![SPGR](https://img.shields.io/badge/AI_Assist-📝_Spelling_%26_Grammar-yellow)
Code Comments (CMT) | ![CMT](https://img.shields.io/badge/AI_Assist-💬_Code_Comments-lightgreen)
Outline Assistance (OUT) | ![OUT](https://img.shields.io/badge/AI_Assist-📄_Outline_Assistance-blue)
Logic Generation (LOG) | ![LOG](https://img.shields.io/badge/AI_Assist-⚙️_Logic_Generation-orange)
Documentation (DOC) | ![DOC](https://img.shields.io/badge/AI_Assist-📑_Documentation-red)

You can combine these badges to show multiple forms of AI use.

---

🧩 How to Use AI Purity Badges

1. Add a Badge to Your Project

To include a badge in your README file or project page, use the following Markdown syntax:

```md
![Badge](https://img.shields.io/badge/AI_Purity-<MESSAGE>-<COLOR>)
```

Replace:

	•	<MESSAGE> with the text (e.g., 50% AI, 50% Human).
	•	<COLOR> with the appropriate color (e.g., yellow).

Example:

```html
![Badge](https://img.shields.io/badge/AI_Purity-Mostly_Human-lightblue)
```
Result: ![Badge](https://img.shields.io/badge/AI_Purity-Mostly_Human-lightblue)

2. Combine Badges for Specific AI Contributions

You can use multiple badges to show AI involvement in specific areas. For example:

![SPGR](https://img.shields.io/badge/AI_Assist-📝_Spelling_%26_Grammar-yellow)
![CMT](https://img.shields.io/badge/AI_Assist-💬_Code_Comments-lightgreen)
![OUT](https://img.shields.io/badge/AI_Assist-📄_Outline_Assistance-blue)
![LOG](https://img.shields.io/badge/AI_Assist-⚙️_Logic_Generation-orange)
![DOC](https://img.shields.io/badge/AI_Assist-📑_Documentation-red)

---

📜 Why Transparency Matters

	1.	Honesty: Clearly showing AI involvement builds trust with your audience.
	2.	Education: Teachers and students can better evaluate learning outcomes.
	3.	Ethics: Reduces the stigma around AI tools while promoting responsible use.
	4.	Recognition: Differentiates human contributions from AI assistance, giving proper credit.

---
🧮 How to Assess Your AI Purity Score

To help determine the AI Purity Score for your work, you can use the following instructions and prompt with ChatGPT (or any similar AI tool). This will allow you to evaluate the balance between human effort and AI assistance in your project.

Instructions

	1.	Reflect on how you used AI tools in your project and break it down into the following categories:
		•	Spelling and Grammar (SPGR): Did AI assist with grammar corrections, spelling checks, or rewriting text?
		•	Code Comments (CMT): Did AI generate comments for your code?
		•	Outline Assistance (OUT): Did AI help structure your work, brainstorm, or organize ideas?
		•	Logic Generation (LOG): Did AI contribute to generating or troubleshooting code, algorithms, or logical structures?
		•	Documentation (DOC): Did AI help create or refine documentation, explanations, or descriptions?
	  
	2.	Copy and paste the following prompt into ChatGPT (or another AI tool), filling in details about your project and how AI was used.

Here’s how you can update the README.md to include instructions for generating AI Purity Score badges automatically, using ChatGPT and the badges hosted in your GitHub repository.

---

🏷 Automatically Generating AI Purity Score Badges

To make it easier for users to assess and display their AI Purity Score, you can use ChatGPT to analyze your work and provide a badge that reflects the level of AI involvement. Follow these instructions to get your score and generate a badge for your project.

Step 1: Use This Prompt to Assess Your AI Purity Score

Paste this prompt into ChatGPT (or another AI tool), and provide details about your project:

```
I need help assessing the AI Purity Score for a project I created. Here's how I used AI:

1. **Spelling and Grammar**: Did AI assist with spelling and grammar (e.g., Grammarly, ChatGPT)?
2. **Code Comments**: Did AI help generate comments or annotate code?
3. **Outline Assistance**: Did AI help structure the work, brainstorm, or organize ideas?
4. **Logic Generation**: Did AI assist in generating code, algorithms, or logic?
5. **Documentation**: Did AI help write or improve documentation?

Based on my responses, assign an **AI Purity Score** using these categories:  

- **Purely Human**: Fully human-created (100% human, 0% AI).  
- **Mostly Human**: Minor AI assistance (75-90% human).  
- **Mixed Collaboration**: Equal AI and human input (50-50 split).  
- **Mostly AI**: Significant AI use (75-90% AI).  
- **Purely AI**: Fully AI-generated (100% AI).

Output the following:  

1. A summary explaining the score.  
2. The Markdown link for the corresponding badge from this repository:  
   https://github.com/trevortomesh/purity.ai  
```

Step 2: Retrieve the Correct Badge

The AI will determine your AI Purity Score and provide you with a badge link. Here are the available badges hosted in the repository:

| AI Purity Score     | Badge Example                                                |
| ------------------- | ------------------------------------------------------------ |
| Purely Human        | ![Purely Human](https://img.shields.io/badge/AI_Purity-100%25_Human-blue) |
| Mostly Human        | ![Mostly Human](https://img.shields.io/badge/AI_Purity-Mostly_Human-lightblue) |
| Mixed Collaboration | ![Mixed Collab](https://img.shields.io/badge/AI_Purity-Mixed_Collab-yellow) |
| Mostly AI           | ![Mostly AI](https://img.shields.io/badge/AI_Purity-Mostly_AI-orange) |
| Purely AI           | ![Purely AI](https://img.shields.io/badge/AI_Purity-100%25_AI-red) |


​	

Step 3: Add the Badge to Your Project

Once you receive the badge Markdown from ChatGPT, paste it into your project’s README.md file or documentation. For example:

# My Project  
![Mixed Collab](https://img.shields.io/badge/AI_Purity-Mixed_Collab-yellow)

Rendered Output:

Why Use These Badges?
	1.	Transparency: Clearly communicate how much AI was used in your work.
	2.	Ethics: Promote honesty in AI-human collaboration.
	3.	Recognition: Give credit to human effort while acknowledging AI assistance.

By following these steps, users can assess their AI Purity Score and add a corresponding badge automatically. Let me know if you’d like to refine this further! 🚀


Example Assessment

If you describe your project as:

“I used ChatGPT to generate the structure for my essay (Outline Assistance) and asked it to clean up spelling and grammar errors (Spelling and Grammar). I wrote all the content myself.”

AI Purity Score: Mostly Human (75-90% human)

Reasoning:
	•	AI was used for Outline Assistance and Spelling/Grammar corrections, but the content itself was human-written. The core creative work remains primarily human-driven, with AI playing a supporting role.

Why This Matters

The AI Purity Score helps communicate how much of your work was influenced by AI tools. It promotes transparency, encourages ethical use of AI, and gives credit where it’s due—both to human effort and AI assistance.

By including an AI Purity Score in your work, you ensure clarity and honesty in your process. 🚀

---

🌐 Future Directions

This framework can be expanded with:

	•	Automated tools for measuring AI involvement.
	•	AI contribution reports linking specific badges to project summaries.
	•	Formal standards for academic and industry use.

---

🤝 Contributing

Want to help improve the AI Purity Scale? Feel free to:

	•	Share your ideas in discussions.
	•	Add new badges for other forms of AI assistance.
	•	Build tools that integrate the AI Purity Scale with platforms like GitHub.

---

⚖️ License

This project is open source. Feel free to adapt the framework for your needs.
