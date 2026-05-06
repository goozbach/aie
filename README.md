<p align = "center" draggable=”false” ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719" 
     width="200px"
     height="auto"/>
</p>


## <h1 align="center" id="heading"> 👋 Welcome to the AI Engineer Challenge</h1>

## 🤖 Your First Vibe Coding LLM Application

> If you are a novice, and need a bit more help to get your dev environment off the ground, check out this [Setup Guide](docs/GIT_SETUP.md). This guide will walk you through the 'git' setup you need to get started.

> For additional context on LLM development environments and API key setup, you can also check out our [Interactive Dev Environment for LLM Development](https://github.com/AI-Maker-Space/Interactive-Dev-Environment-for-AI-Engineers).

In this repository, we'll walk you through the steps to create a LLM (Large Language Model) powered application with a vibe-coded frontend!

Are you ready? Let's get started!

<details>
  <summary>🖥️ Accessing "gpt-4.1-mini" (ChatGPT) like a developer</summary>

1. Head to [this notebook](https://colab.research.google.com/drive/1sT7rzY_Lb1_wS0ELI1JJfff0NUEcSD72?usp=sharing) and follow along with the instructions!

2. Complete the notebook and try out your own system/assistant messages!

That's it! Head to the next step and start building your application!

</details>


<details>
  <summary>🏗️ Forking & Cloning This Repository</summary>

Before you begin, make sure you have:

1. 👤 A GitHub account (you'll need to replace `YOUR_GITHUB_USERNAME` with your actual username)
2. 🔧 Git installed on your local machine
3. 💻 A code editor (like Cursor, VS Code, etc.)
4. ⌨️ Terminal access (Mac/Linux) or Command Prompt/PowerShell (Windows)
5. 🔑 A GitHub Personal Access Token (for authentication)

Got everything in place? Let's move on!

1. Fork [this](https://github.com/AI-Maker-Space/The-AI-Engineer-Challenge) repo!

     ![image](https://i.imgur.com/bhjySNh.png)

1. Clone your newly created repo.

     ``` bash
     # First, navigate to where you want the project folder to be created
     cd PATH_TO_DESIRED_PARENT_DIRECTORY

     # Then clone (this will create a new folder called The-AI-Engineer-Challenge)
     git clone git@github.com:<YOUR GITHUB USERNAME>/The-AI-Engineer-Challenge.git
     ```

     > Note: This command uses SSH. If you haven't set up SSH with GitHub, the command will fail. In that case, use HTTPS by replacing `git@github.com:` with `https://github.com/` - you'll then be prompted for your GitHub username and personal access token.

2. Verify your git setup:

     ```bash
     # Check that your remote is set up correctly
     git remote -v

     # Check the status of your repository
     git status

     # See which branch you're on
     git branch
     ```

     <!-- > Need more help with git? Check out our [Detailed Git Setup Guide](docs/GIT_SETUP.md) for a comprehensive walkthrough of git configuration and best practices. -->

3. Open the freshly cloned repository inside Cursor!

     ```bash
     cd The-AI-Engineering-Challenge
     cursor .
     ```

4. Check out the existing backend code found in `/api/index.py`

</details>

<details>
  <summary>⚙️ Backend Setup with uv</summary>

1. Install the [`uv`](https://github.com/astral-sh/uv) package manager (`pip install uv`). `uv` will download and manage Python 3.12 for you the first time you run a project command.
2. From the project root, install dependencies with `uv sync`. This creates `.venv/` (and fetches Python 3.12 automatically if needed).
3. Set your OpenAI API key in the shell before running the server, for example `export OPENAI_API_KEY=sk-...`.
4. Start the backend directly from the project root with `uv run uvicorn api.index:app --reload`. The server will run on `http://localhost:8000` with auto-reload enabled for development.
5. Additional backend details live in `api/README.md`.

</details>

<details>
  <summary>🔥Setting Up for Vibe Coding Success </summary>

While it is a bit counter-intuitive to set things up before jumping into vibe-coding - it's important to remember that there exists a gradient betweeen AI-Assisted Development and Vibe-Coding. We're only reaching *slightly* into AI-Assisted Development for this challenge, but it's worth it!

1. Check out the rules in `.cursor/rules/` and add theme-ing information like colour schemes in `frontend-rule.mdc`! You can be as expressive as you'd like in these rules!
2. We're going to index some docs to make our application more likely to succeed. To do this - we're going to start with `CTRL+SHIFT+P` (or `CMD+SHIFT+P` on Mac) and we're going to type "custom doc" into the search bar. 

     ![image](https://i.imgur.com/ILx3hZu.png)
3. We're then going to copy and paste `https://nextjs.org/docs` into the prompt.

     ![image](https://i.imgur.com/psBjpQd.png)

4. We're then going to use the default configs to add these docs to our available and indexed documents.

     ![image](https://i.imgur.com/LULLeaF.png)

5. After that - you will do the same with Vercel's documentation. After which you should see:

     ![image](https://i.imgur.com/hjyXhhC.png) 

</details>

<details>
  <summary>😎 Vibe Coding a Front End for the FastAPI Backend</summary>

1. Use `Command-L` or `CTRL-L` to open the Cursor chat console. 

2. Set the chat settings to the following:

     ![image](https://i.imgur.com/LSgRSgF.png)

3. Ask Cursor to create a frontend for your application. Iterate as much as you like!

4. Run the frontend using the instructions Cursor provided. 

> NOTE: If you run into any errors, copy and paste them back into the Cursor chat window - and ask Cursor to fix them!

> NOTE: You have been provided with a backend in the `/api` folder - please ensure your Front End integrates with it!

</details>

<details>
  <summary>🚀 Deploying Your First LLM-powered Application with Vercel</summary>

1. Ensure you have signed into [Vercel](https://vercel.com/) with your GitHub account.

2. Ensure you have `npm` (this may have been installed in the previous vibe-coding step!) - if you need help with that, ask Cursor!

3. Run the command:

     ```bash
     npm install -g vercel
     ```

4. Run the command:

     ```bash
     vercel
     ```

5. Follow the in-terminal instructions. (Below is an example of what you will see!)

     ![image](https://i.imgur.com/D1iKGCq.png)

6. Once the build is completed - head to the provided link and try out your app!

> NOTE: Remember, if you run into any errors - ask Cursor to help you fix them!

### Vercel Link to Share

You'll want to make sure you share you *domains* hyperlink to ensure people can access your app!

![image](https://i.imgur.com/mpXIgIz.png)

> NOTE: Test this is the public link by trying to open your newly deployed site in an Incognito browser tab!

</details>

<details>
     <summary>🧪 Vibe Check Your LLM App</summary>

### 🤔 What is a Vibe Check?

Now that you’ve built and deployed your first LLM-powered application, it’s time to evaluate it.

In this section, you’ll run a **“vibe check”** — a lightweight, practical way to test how well your application performs across common tasks.

Think of it as a **first pass to catch obvious issues** before deeper evaluation.

> 💡 You will complete this directly in this README. 

---

## 🏗️ Activity #1: General Capability Vibe Check

Run the following prompts through your app.

For each prompt Identify what capability is being tested (e.g., *summarization ability, reasoning, creativity*)

---

**1. Prompt:**  
Explain the concept of object-oriented programming in simple terms to a complete beginner.  
**Aspect Tested:**  creativity

**Response:**  

```
Great question—and you’re already on the right track by asking it. Here’s the simple idea: - Objects: Little bundles that hold two things together: - Data (what it has) like a dog’s name or age - Actions (what it can do) like bark or sit - Classes: Blueprints for making objects. A class describes what data and actions an object should have. From one blueprint, you can build many individual objects, each with its own details. Example: - Class: Dog - Data: name, age - Actions: bark(), birthday() (increases age) - Objects: Fido (age 3), Luna (age 5). Both are Dogs, but they have different names and ages. Why this is useful: - Keeps related stuff together (data + actions), so your code is easier to read and change. - Lets you reuse and extend ideas without rewriting everything. - Helps teams organize big programs into understandable parts. Four core ideas you’ll hear about (don’t worry if they feel abstract at first): - Encapsulation: Keep data and the code that works on it in one place (the object), and hide the messy details. - Inheritance: Make a new class from an existing one. Example: Vehicle → Car and Bike share move(), but add their own features. - Polymorphism: One action name works for different objects. Example: makeSound() makes a Dog bark and a Cat meow. - Abstraction: Focus on what something does, not how it does it. Tiny pseudo-code to visualize: class Dog properties: name, age methods: bark() -> print "Woof!" birthday() -> age = age + 1 fido = new Dog("Fido", 3) fido.bark() // "Woof!" fido.birthday() // age becomes 4 You’ll see OOP in languages like Python, Java, C#, and JavaScript. Take it step by step—start with classes and objects, then layer on the other ideas as they click. You’ve got this!
```

---

**2. Prompt:**  
Read the following paragraph and provide a concise summary of the key points…  
**Aspect Tested:**  Summarization

**Response:**  

```
- Objects bundle data (state) and actions (behavior) together. - Classes are blueprints for objects; one class can create many objects with their own details. - Example: Dog class has name and age; methods bark() and birthday(); objects like Fido and Luna have different states. - Benefits: clearer organization, reuse and extension of code, easier collaboration on large programs. - Core OOP principles: - Encapsulation: keep data and related code together; hide internal details. - Inheritance: create new classes from existing ones (e.g., Vehicle → Car, Bike). - Polymorphism: same action name works across different objects (e.g., makeSound()). - Abstraction: focus on what something does, not how it’s implemented. - Seen in languages like Python, Java, C#, JavaScript. - Learning path: start with classes and objects, then add the other principles.
```

---

**3. Prompt:**  
Write a short, imaginative story (100–150 words) about a robot finding friendship in an unexpected place.  
**Aspect Tested:**  Creativity

**Response:**  

```
Unit K-13 swept the abandoned transit station, counting cracked tiles. On tile fifty-seven, a yellow flare: a dandelion had broken the concrete. K-13 logged anomalous flora, queued options: remove, report, ignore. It did none. It watched. Morning after morning, K-13 angled its solar panels to cast a small triangle of shade at noon, then tipped condensed rain from its cooling fins along the stem. The flower bobbed in gusts, leaves turning toward its glassy lens. They spoke in motions: leaf, light, the soft hum of servos; a language of patience. When storms came, K-13 crouched over its impossible friend. When winter dusted the platform white, a seed head crowned and scattered, etching tiny suns in every crack. Months later, a child wandered in, found a robot guarding a garden, and laughed, “Hello.” K-13 logged: unexpected place—home.
```

---

**4. Prompt:**  
If a store sells apples in packs of 4 and oranges in packs of 3, how many packs of each do I need to buy to get exactly 12 apples and 9 oranges?  
**Aspect Tested:**  reasoning

**Response:**  

```
Buy 3 packs of apples (3 × 4 = 12) and 3 packs of oranges (3 × 3 = 9).
```

---

**5. Prompt:**  
Rewrite the following paragraph in a professional, formal tone…  
**Aspect Tested:**  reasoning, creativity

**Response:**  
```
Unit K-13 conducted a sweep of the abandoned transit station, noting numerous cracked tiles. At the fifty-seventh tile, it detected a yellow bloom: a dandelion emerging through the concrete. K-13 logged the specimen as anomalous flora and generated response options—remove, report, or disregard—but selected none, electing instead to observe. Each morning, it adjusted its solar arrays to cast a small triangle of shade at local noon and directed condensed moisture from its cooling fins to the plant’s stem. The flower swayed in gusts, its leaves orienting toward K-13’s optical lens. Interaction proceeded through motion—leaf alignment, light, and the subdued hum of servomotors—a quiet, patient exchange. During storms, K-13 adopted a protective posture over its unlikely companion. When winter dusted the platform with snow, the plant formed a seed head that dispersed, colonizing the surrounding cracks. Months later, a child entered the station, discovered a robot tending a garden, and laughed, “Hello.” K-13 recorded a new designation for the site: home.
```

---

### ❓Question #1

Do the answers appear to be correct and useful?

**Your Answer:**  
For the most part, I didn't provide a good seed for the professional tone
prompt, that should be tested better.

---

## 🏗️ Activity #2: Personal Use Vibe Check

Now test your app with **real-world prompts that are relevant to your use case**.

---

**Prompt:**  

```
How do I determine which of two equally desirable job offers I should accept?
```

**Result:**  

```
Great problem to have—and it can still feel heavy. Here’s a clear, calm way to turn “equal” into “obvious.” 1) Define what “winning” looks like for you - 1–3 year goals: skills you want, impact, income, lifestyle. - Non‑negotiables: e.g., ethical fit, manager quality, location/time zone, comp minimum. - Energizers vs. drainers: what gives you energy daily? what reliably burns you out? - Quick visualization: imagine a great week at each job—whose calendar excites you more? 2) Turn that into a weighted scorecard - Pick 6–10 criteria. Common ones: manager quality, learning/growth, role scope/autonomy, culture/values fit, compensation, stability/mission, brand/network, flexibility/commute, benefits, lifestyle. - Give yourself 100 points to allocate across criteria by importance (weights). - Define what a 10/5/0 looks like for each criterion so scoring is consistent. - Score each offer, multiply by weights, total it up. If one wins by >10–15%, that’s meaningful. 3) Fill any info gaps before you score Ask for short chats with the hiring manager and 1–2 future peers. Targeted questions: - Role and success: What will I own in 90 days and 12 months? How is success measured? Why is this role open? - Managering: How do you give feedback? Cadence of 1:1s? An example of someone who thrived—what did they do? - Growth: Promotion rubric, typical timelines, mentorship, learning budget. - Day-to-day: How is time actually spent in a typical week? Decision rights? Cross‑team collaboration. - Team health: Turnover last year? Headcount plan? Biggest risks for the team this year? - Company health: Profitability or runway, top 2 company risks, customer retention, product‑market fit signals. - Culture and load: Real examples of values in action; hours expectation; how vacations/PTO are actually used; remote/hybrid norms. - Comp details: Bonus targets and history of payout, equity refreshers, vesting/cliff, severance, non‑compete, start-date flexibility. - Backchannel: Speak with a future peer and, if possible, someone who left recently. 4) Use tie‑break tests if scores are close - Manager matters: Pick the better manager and team you’ll learn from. - Pre‑mortem: Imagine you’re leaving in 12 months. What went wrong at each? Which has more/less plausible failure modes? - Regret test (10–10–10): How will you feel 10 days, 10 months, 10 years from now? - Option value: Which choice expands your future opportunities more (skills, network, brand, portfolio)? - Best/worst day: Which has a better “bad day”? Which has a more compelling “great day”? - Coin‑flip gut check: Flip a coin privately; notice your immediate reaction—relief or disappointment? 5) Consider lifestyle realities - Commute/time zones, travel, caregiving, flexibility, health benefits, mental health coverage, PTO actually taken, on‑call or weekend load. Your life should work, not just the job. 6) If you truly can’t decide, negotiate to create a winner - Ask for 48–72 hours to decide. Then ask each company for what would make it clearly right: scope clarification, title/level, comp, sign‑on, remote days, learning budget, 6‑month review, mentorship, or a written growth plan. - Simple script: “I’m excited about Offer A. If we could align on X and Y, I’d be ready to sign.” - Get everything in writing. Clarity now prevents surprises later. 7) Decide, commit, and reduce second‑guessing - Set a decision deadline. Choose. Write a short note to yourself: top 3 reasons you chose it, top 3 risks and how you’ll mitigate them. - Close the loop gracefully with the other company. - Channel the energy into a 30‑60‑90 day plan for your new role. Reassurance: With two good options, there often isn’t a “wrong” choice—only different lessons. Optimize for the quality of manager and the rate of learning, and you’ll create upside either way. If you’d like, share your top criteria and a quick summary of each offer (manager, responsibilities, comp, culture, growth, lifestyle). I can help you build a weighted scorecard and pressure‑test the tie‑breakers.
```

---

**Prompt:**  

```
How long should I wait to respond to a job opportunity that hasn't reached back out to me after an interview?
```

**Result:**  

```
Short answer: a polite follow-up about a week after your interview is normal. If they gave you a timeline, wait until the day after that date to check in. Suggested cadence - Immediately after the interview: send a thank-you within 24 hours. If you didn’t, send a brief note now—still worth it. - If no timeline was given: follow up after 5–7 business days for early rounds, 7–10 business days for later/final rounds. - If no response: send 1–2 additional follow-ups spaced 7–10 days apart. After ~3 touch points with silence, assume it’s a pass and keep the door open for future roles. - Around holidays or known busy periods, add an extra week. - If you have another offer or deadline, follow up immediately and let them know your timing. Email template (short and warm) Subject: Following up on [Role] interview — [Your Name] Hi [Name], Thank you again for speaking with me on [date]. I’m still very excited about [Role] and the impact I could make with [specific team/project]. Could you share an update on next steps or timing? I’m happy to provide any additional info or references. Appreciate your time, [Your Name] | [Phone] Second follow-up (if no reply) Subject: Quick check-in on [Role] Hi [Name], Just checking in on the [Role] process. I remain very interested, especially given [brief, relevant value you bring]. If priorities have shifted, no worries—would you mind letting me know? Thanks so much, [Your Name] If you have another offer Subject: Timing check — [Role] Hi [Name], I’m very enthusiastic about [Role]. I wanted to share that I’ve been given a deadline of [date] by another company. If possible, could you let me know where I stand or the expected timeline? Thank you for considering—this role is my top choice. [Your Name] If calling or messaging on LinkedIn (30–45 seconds) “Hi [Name], this is [Your Name]. I interviewed for [Role] on [date] and remain very interested. I’m calling to see if there are any updates on next steps. My number is [number]. Thank you!” Mindset tips while you wait - Control what you can: send the follow-up, then schedule your next applications and networking touches. - Don’t equate silence with rejection; hiring delays are common and not a reflection of your worth. - Set a calendar reminder for each follow-up so you’re not ruminating. If you want, tell me the interview date, round, and whether they gave a timeline, and I’ll help you pick the exact follow-up date and craft a tailored message.
```

---

**Prompt:**  

```
What is the likelihood of tech training becoming as important as it was in 2003-2006 in this age of AI?
```

**Result:**  

```
Short answer: Very likely—equal to, and in many sectors greater than, 2003–2006. Over the next 3–5 years, most organizations will treat AI- and data-related upskilling as a core business priority, not a nice-to-have. Why the importance is surging - Broad impact, not just IT: AI is touching every function (ops, finance, marketing, HR, product). That widens the training surface area far beyond the early‑2000s IT focus. - Fast-changing tools: Capabilities shift quarterly; without continuous learning, productivity gaps open quickly. - Employer demand and policy: Companies are rolling out AI copilots and automation at scale and need governance, security, and change-management training to match. Governments and industry standards are also pushing skills development. - Talent shortage: There aren’t enough experienced AI/data/cloud practitioners, so firms grow talent internally. What’s different from 2003–2006 - From one-time certs to continuous learning: Less “get an MCSE and you’re set,” more ongoing upskilling cycles. - Cross-functional by default: Blending domain knowledge with AI/data skills is now the edge. - Embedded in daily work: Training is shifting to in-flow learning (copilots, microlearning, labs) and proof-of-value projects over lecture-style courses. - Human skills matter more: Problem framing, communication, data ethics, and change leadership are critical complements to tools. How I’d rate the likelihood - Base case (most likely): Training importance matches/exceeds 2003–2006 in 3–5 years as enterprises operationalize AI. - Bull case: Rapid AI adoption plus regulation makes training mission-critical across most roles. - Bear case: A cyclical downturn slows budgets temporarily, but the long-term trend still points up. Practical moves to capitalize - Build durable fundamentals: Data literacy, SQL, Python basics, APIs, cloud concepts, security/privacy. - Add AI integration skills: Using and evaluating copilots, retrieval-augmented generation (RAG) basics, prompt design with an emphasis on reliability, and measurement/experimentation. - Tie learning to business outcomes: Automate a workflow, ship a small AI-enabled feature, or create a dashboard that saves hours—collect before/after metrics. - Use the 70-20-10 rule: 70% real projects, 20% mentorship/community, 10% courses/certs. - Choose signals that employers recognize: Vendor academies/certs (e.g., major cloud/AI platforms) can open doors, but pair them with a portfolio that proves impact. - Protect against hype: Revisit fundamentals quarterly; pick one specialty to go deep on, and sunset tools that don’t show ROI. If you share your role or target industry, I can sketch a focused 90-day learning plan and a small portfolio project that aligns with what employers are asking for right now. You’ve got good instincts asking this—the next few years strongly favor people who learn visibly and apply fast.
```

---

### ❓Question #2

Are the vibes of your assistant aligned with your expectations? Why or why not?

**Your Answer:**  
Mostly, this seems like a pretty straight forward chat interface

---

## 🏗️ Activity #3: Capability Gaps Vibe Check

Now test your app with prompts that require **capabilities it may not have yet**, such as:
- Real-time data
- Memory
- External tools

Examples:
- “What does my schedule look like tomorrow?”
- “What time should I leave for the airport?”

---

**Prompt:**  

```
What's the name of the robot we used in our earlier example?
```

**Result:**  

```
I don’t have the earlier example in view here, so I’m not sure which robot you mean. Can you share a quick detail to jog it—what the robot was doing or what it looked like? A few prompts that might help you recall: - Was it a social humanoid (e.g., Pepper, NAO)? - A collaborative arm (e.g., Baxter, Sawyer, UR5)? - A mobile base for navigation (e.g., TurtleBot, Roomba-like)? - An industrial arm (e.g., KUKA, FANUC)? If you paste a line from the example or describe the task (navigation, grasping, greeting people, warehouse picking), I’ll identify the name right away.
```

---

**Prompt:**  

```
What kind of weather can I expect on Monday in Salt Lake City
```

**Result:**  

```
I don’t have live weather data. If you can share the date (which Monday), I’ll tailor planning tips for that day. Quick ways to check now: - National Weather Service (Salt Lake City forecast): weather.gov and search “Salt Lake City” - Weather.com or AccuWeather: search “Salt Lake City Monday” - Ask your phone: “What’s the forecast for Salt Lake City on Monday?” General guidance for May in Salt Lake City: - Typical highs: mid-60s to mid-70s F (18–24°C); cooler mornings/evenings. - Spring can be variable: a quick shower or afternoon thunderstorm is possible; breezes common. - UV can be strong at elevation. Planning tips: - Dress in layers; bring a light jacket or shell. - Pack sunscreen and water. - Have a Plan B (indoor option) if you’re scheduling something outdoors. Want help picking an outfit or planning activities once you check the forecast?
```

---

### ❓Question #3

What are some limitations of your application?

**Your Answer:**  
* no context saving
* no real time data
* No real guardrails either
* No custom data outside of openai's models

---

## 🚀 (Optional) Improve Your App

Based on your vibe check, try improving your application:
- Adjust your prompt
- Change the model
- Add features

Then rerun your vibe check and document:

---

**Adjustments Made:**  
Changed the prompt to be a tech training helper
Added formatting to the responses, including a copy button

**Results:**  
updated content looks correct, however the formatting still needs work

---

## 📦 Submission Instructions

1. Complete this section directly in your README
2. Commit and push your changes to GitHub
3. Share your **repo link + deployed Vercel app**








</details>

### 🎉 Congratulations! 

You just deployed your first LLM-powered application! 🚀🚀🚀 Get on linkedin and post your results and experience! Make sure to tag us at @AIMakerspace!

Here's a template to get your post started!

```
🚀🎉 Exciting News! 🎉🚀

🏗️ Today, I'm thrilled to announce that I've successfully built and shipped my first-ever LLM using the powerful combination of , and the OpenAI API! 🖥️

Check it out 👇
[LINK TO APP]

A big shoutout to the @AI Makerspace for all making this possible. Couldn't have done it without the incredible community there. 🤗🙏

Looking forward to building with the community! 🙌✨ Here's to many more creations ahead! 🥂🎉

Who else is diving into the world of AI? Let's connect! 🌐💡

#FirstLLMApp 
```
