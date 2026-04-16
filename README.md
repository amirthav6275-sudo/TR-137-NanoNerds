Project Idea
Reviews are treated like DNA — if they share too much similarity, they likely come from the same source.
This project visualizes reviews as a network and detects suspicious patterns by analyzing how closely reviews resemble each other.

Features
 Detect fake reviews using similarity analysis
 Interactive phylogenetic-style network visualization
 Risk scoring system (0–100)
 AI-powered review analysis (Claude API)
 Real-time updates when adding new reviews
 Fully browser-based (no server required)

HOW IT WORKS

1.PHYLOGENETIC TREE(NETWORK VIEW)
Compares every review with others using Levenshtein Distance
Connects similar reviews:
Thicker edges = higher similarity
Uses Union-Find algorithm to form clusters
Each node represents a review:
🔴 Red → High Risk / Fake
🟡 Yellow → Suspicious
🟢 Green → Authentic
Click any node to view:
Review content
Similar reviews
Risk insights

2.REVIEWS DASHBOARD
Displays all reviews with a Risk Score (0–100) based on:
High similarity with other reviews
Duplicate or near-copy content
Extreme ratings (1★ or 5★)
Very short or generic text

3.AI ANALYSIS
Paste any review for deep analysis
Uses Claude API (direct browser integration)
Returns:
Fake probability score
Verdict:
Authentic
Suspicious
Likely Fake
Detected signals (e.g., generic language, exaggeration)
Human-readable explanation

4.ADD REVIEW(REAL-TIME)
Add new reviews instantly
Automatically:
Recalculates similarity
Updates clusters
Re-renders graph
Assigns risk score

CORE CONCEPTS USED
Levenshtein Distance → Text similarity measurement
Union-Find Algorithm → Clustering similar reviews
Graph Visualization → Network-based analysis
AI/NLP → Contextual fake detection

TECH STACK
HTML, CSS, JavaScript
Graph Visualization (D3.js or similar)
Claude API (AI analysis)
No backend (runs entirely in browser)

USE CASES 
Detect spam or bot-generated reviews.
Analyzse e-commerce or restaurant reviews.





