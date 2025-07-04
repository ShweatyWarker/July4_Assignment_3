# July4_Assignment_3
Maple Syrup: The Staple Of Canadian Breakfast
# 🍁 MapleSyrupAPI

A beginner-friendly, proudly Canadian open-source project that lets you explore the **sweet world of maple syrup** through a fake RESTful API! This project is designed for developers who want to learn how APIs work, practice contributing to open source, or just love maple syrup as much as we do.

---

## 📦 What Is It?

**MapleSyrupAPI** is a pretend (but fully functional) API that serves deliciously fake data about different kinds of maple syrup — including:

- 🏷️ Syrup Name & Brand
- 🍯 Grade (Golden, Amber, Dark, Very Dark)
- 🌲 Province of Origin (Quebec, Ontario, etc.)
- 🍽️ Best Pairings (pancakes, waffles, bacon, etc.)
- 📊 Sugar Content
- 💬 Fun Facts

  Example response:

{
  "id": 3,
  "name": "L'Érable Supreme",
  "grade": "Amber",
  "origin": "Quebec",
  "pairings": ["Pancakes", "Sausage", "Cocktails"],
  "sugar_content": "67%",
  "fun_fact": "Quebec produces over 70% of the world’s maple syrup!"
}

🚀 Getting Started

Prerequisites
	•	Node.js (v18+ recommended)
	•	Git
	•	VS Code (optional but recommended)

🧰 Tech Stack
	•	Node.js
	•	Express.js
	•	Fake JSON data as a mock database
	•	VS Code
	•	Git + GitHub

 🎯 Beginner-Friendly Ways to Contribute
	•	✅ Add new syrups to data/syrups.json
	•	🌐 Translate API responses into French
	•	🔀 Create a /random syrup endpoint
	•	🧪 Add unit tests
	•	🖼️ Design a project logo or banner
	•	🖥️ Build a frontend (React, Vue, etc.)
 
🧊 Fun Facts About Canadian Maple Syrup
	•	Canada produces over 75% of the world’s maple syrup.
	•	The province of Quebec alone makes up more than 90% of that total.
	•	In 2012, nearly 3,000 tonnes of maple syrup were stolen in Quebec — worth over $18 million. It’s considered the stickiest heist in Canadian history. 🇨🇦
	•	Indigenous peoples were the first to harvest maple sap long before colonization.

	🐞 Known Bugs
	•	GET /api/syrups/:id doesn’t throw error for non-existent IDs
	•	Fun fact fields sometimes make people too happy
	•	POST accepts duplicate syrup names
	•	“Golden” grade syrup too OP compared to “Very Dark”
	•	Autocomplete thinks “Érable” is a typo (rude)
	•	Project owner drinks syrup straight from the bottle — untested behavior

	👥 Contributors
	Username
Profile Link

MapleMoose89
github.com/MapleMoose89

HockeyDadDev
github.com/HockeyDadDev

TimbitTechie
github.com/TimbitTechie

LoonieCoder
github.com/LoonieCoder

PoutinePusher
github.com/PoutinePusher

🧑‍🍳 How to Use

Example Requests
View all syrups:GET /api/syrups

View one syrup:GET /api/syrups/3

Add a new syrup:POST /api/syrups

Update a syrup:PUT /api/syrups/3

Delete a syrup:DELETE /api/syrups/3

 👑 Credits
 @ShweatyWarker
 
 Maybe you?
 ```
