---
title: "Project4: Basketball Team Management Game"
date: 2026-04-09
categories: [AI, Research]
tags: [trustworthy-ai]
---

Chosen_Theme_and_Prompt: |
  For Assignment 4, I chose Option 1: AI as a Collaborative Creative Partner. 
  My objective was to use AI to help me co-design the core mechanics and rulebook for a brand new basketball video game.
  I wanted to create a hybrid Collectible Card Game (CCG) that combined the pack-pulling thrill of a mode like NBA 2K MyTeam with the hardcore, statistical team management of a real front office. To get the best results, I assigned the AI a specific persona to guide its creative output.

  My initial prompt was:
  "you are a professional recruiter from a NBA team, im trying to make a game that is having 5 nba player cards in a game and let them play the game, im still wondering should i make it a game that let the ai simulate the game by itself or let the player actually control the game?"

  As the collaboration went on, my prompts shifted to redirect the AI when it misunderstood my vision, and to push it for deeper technical documentation:
  "dont make it look like a yahoo fantasy game, i want it like a card game smth like NBA 2k myteam"
  "told u i want a collect card game but a team management one"
  "give me a diagram that can link up the mechanisms on what rules the game should follow, also i think i would make the salary base like a level up..."

Presentation_of_AI_Responses: |
  The AI was highly enthusiastic and generated massive amounts of text, but the creative process was definitely a back-and-forth negotiation.

  When I first asked about simulation vs. manual control, the AI provided a deep breakdown of the two philosophies:
  AI Response (Excerpt): "Going the simulation route makes this a game for the tacticians and the analytics junkies... You force the player to think deeply about multi-category synergy. They have to ask themselves the tough questions: Does my frontcourt provide enough BLK and REB without tanking my overall FGM percentage? Who is my primary PTS generator, and who is turning the ball over (TO) too much?"

  However, the AI initially leaned too heavily into making it a standard fantasy basketball clone. When I corrected it ("dont make it look like a yahoo fantasy game"), it swung too far the other way into an arcade gacha game. It wasn't until I forced it to combine both concepts that it generated the game's best mechanic:
  AI Response (Excerpt): "My apologies, I completely misread your scouting report there... You want the ultimate hybrid: A Front Office CCG. 1. The Cap-Weighted Card System: Cards have rarities (Bronze to Diamond), but those rarities correspond to salary hits. A Diamond card might eat up 40% of your total salary cap, while a Silver card takes up 5%. You can't field five Diamonds. You have to build a balanced squad."

  Finally, when I asked for a diagram to link the mechanisms together, the AI generated a complete plaintext flowchart mapping the game loop:

  =============================================================================
                    THE FRONT OFFICE CCG : CORE RULE MECHANISMS
  =============================================================================

  [1] MANAGER PROFILE (The User)
   |  Attributes: Level, XP, Virtual Currency (VC), Current_Salary_Cap
   |  Rule: Leveling up permanently increases the 'Current_Salary_Cap'.
   |
   +----> [2] CARD INVENTORY (The Collection)
   |       |  Attributes: Card_ID, Player_Name, Tier (Bronze->Diamond), 
   |       |              Salary_Cost, Contract_Games_Remaining.
   |       |  Rule: Cards consume contracts per game played.
   |       |
   |       +----> [3] WAIVER WIRE / PACK MARKET
   |               |  Rule: Spend VC to open packs or bid on dropped cards.
   |
   +----> [4] ACTIVE ROSTER (The Lineup)
           |  Rule A (Cap Limit): SUM(Active_Cards_Salary) MUST BE <= Current_Salary_Cap
           |  Rule B (Injuries): 'Out' players earn 0 stats.
           |  Rule C (Roster Lock): Starting 5 must be submitted before 5:00 PM local time.
           |
           +----> [5] THE MATCH ENGINE (The Game)
                   |  Rule: 5v5 Simulation. 
                   |  Mechanic: Compares active rosters across 9-category scoring 
                   |            (PTS, AST, REB, STL, BLK, FG%, FT%, 3PM, TO).
                   |
                   +----> [6] POST-GAME RESOLUTION
                           |-- 1. Deduct 1 game from active cards' contracts.
                           |-- 2. Award VC based on match outcome (Win/Loss).
                           |-- 3. Award XP to Manager Profile.
                           |-- 4. IF XP hits threshold -> Level Up -> Cap Increases.
                           |      (Loops back to [1])
  =============================================================================

Analysis_Table: |
  Category | Observation
  -------- | -----------
  Overall Evaluation | Critically evaluating this collaboration, the AI proved to be a highly capable but literal-minded creative partner.
  Strengths and Influence | What surprised me most was how the AI seamlessly translated abstract gameplay mechanics into actionable software engineering architecture. When designing the roster rules, the AI didn't just suggest ideas; it actively mapped out the backend logic. It suggested using top-down ER modeling, creating relational tables for player cards and live rosters, and writing complex SELECT statements to validate salary caps. As someone focused on database design and software engineering, seeing the AI frame the creative design through the lens of Oracle-style logic and SQL constraints made the output instantly applicable and highly trustworthy for a technical portfolio project.
  Weaknesses and Variability | The main limitation is that the AI lacks intuitive context. It operates in extremes until heavily guided. It understood the granular details of 9-category scoring (FGM, PTS, BLK, TO) perfectly, but it initially struggled to blend genres. It took three distinct prompt corrections to get the AI to understand the nuance of a "Front Office CCG." If I had implicitly trusted its first or second output, the game design would have been incredibly generic.

Conclusions: |
  This experiment significantly shifted my perspective on using GPT models for creative work. I learned that collaborating with an AI is not about pushing a button and receiving a finished product. It acts much more like an over-eager junior developer or an assistant coach. It possesses immense technical knowledge and can generate complex systems on the fly, but it requires a human "Head Coach" to establish the vision, enforce the parameters, and actively course-correct its assumptions. When managed properly, it is an incredibly powerful engine for brainstorming and technical structuring.
