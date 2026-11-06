# Drugs-Are-Not-Cool-v6.1

"Drugs Are Not Cool" is a text-based drug dealer simulation written in Python for the terminal. Despite the premise, the title and credits (Don'tDoDrugs.com) suggest it's meant as a cautionary game. It uses the rich library for styled menus when available, with a plain-text fallback.

Core loop: You run an illicit operation day by day. You buy seeds and ingredients from a supplier, grow or produce drugs at stations, sell to customers, and sleep to advance the day. Each sale builds money, XP, and reputation, but also raises your risk of arrest.

Main systems:

	•	Drugs and progression: Weed (level 1), Meth (level 3), and Cocaine (level 5). Higher tiers pay more but are riskier and need a Lab, a recipe, or both.
	•	Territories: Downtown, Suburbs, and Industrial, each with different profit ranges and risk levels.
	•	Customers: Daily emails from named buyers, plus black market orders that pay well but add heavy risk.
	•	Black market: Buy stations (Grow Room $500, Lab $800) and recipes, with level locks.
	•	Upgrades: Safe House and Police Bribe (lower risk), Chemist (doubles production), and extra production capacity.
	•	Workers: Hire help to automate growing and deliveries.
	•	Jail: If your risk gets too high you get arrested, with daily jail actions like training, a lawyer, or building reputation.
	•	Extras: Three difficulty levels (Easy, Normal, Hard), objectives, achievements, an activity log, and save/load.

It's a fairly large single-file game (about 2,250 lines) with a how-to-play screen, credits, and a typewriter-style text effect for the narration.