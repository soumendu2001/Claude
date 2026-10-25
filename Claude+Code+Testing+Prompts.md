Copy and paste the following into Claude Code:

```
Context: I run a personal finance coaching service called "WealthPath." I want a website page I can open in my browser that helps clients understand their financial situation and gives them a simple plan.

Instruction: Create a single file called "wealthpath.html" with everything a client would need — a clean modern dashboard, an interactive financial intake flow (step-by-step, not a long form), a visual summary of their finances, personalized recommendations, and a way to book a consultation.

Implement it without using any frameworks or external libraries.

Input:

- Business name: WealthPath
- Tagline: "Clarity and control over your financial future"
- Intake questions: 
	Monthly income? (input number)
	Monthly expenses? (input number)
	Savings? (input number)
	Goal? (Save more, Get out of debt, Invest, Buy a home)
- Logic:
	Calculate savings rate
	Show financial health (Poor / Average / Strong)
	Give 2–3 personalized recommendations based on answers
- Dashboard:
	Show income vs expenses visually (simple bar or progress style)
	Show savings rate %
- Booking section:
	Name, email, preferred time, notes

Output: A single HTML file I can open in any browser — it should feel like a real fintech product, the intake should be smooth (one question at a time), calculations should update dynamically, and the UI should look polished enough to impress a client. Use the frontend-design skill and install it if you don't have it.

```