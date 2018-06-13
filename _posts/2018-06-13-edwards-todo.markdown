---
layout: post
title:  "To do list"
date:   2018-06-13 9:43:00 +1000
categories: admin 
author: Steven Edwards
---

A list of topics to cover. Please add additional topics.

* Linear Programming
	* Basics
		* Farkas Lemma?
	* Algorithms
		* Simplex Method
		* Dual Simplex Method
		* Barrier Method (Interior Point Methods) are they the same?
		* Network Simplex
		* Other?

* Non-Linear Programming
	* Basics
		* Common Linearisations
	* Algorithms
		* Frank-Wolfe

* Mixed-Integer Programming (MIP)
	* Basics
		* Integer Hull
		* Convex Hull
		* Facet Defining Inequalities
		* Valid Inequalities
		* Core points ?
	* MIP Cuts (essentially what are all the cuts Gurobi uses)
		* Clique cuts
		* Cover cuts
		* etc
	* Decompositions
		* Classical Benders
		* Logic-Based Benders
		* Danzig Wolf
		* Column-Generation
		* Lazy Constraints
		* Lagrangian Relaxations

* Stochastic Programming ?
	* 

* Constraint Programming
	* Basics
		* Domain Propagation
		* Global Constraints
		* Search
	* Important Global Constraints
		* Disjunctive
		* Edge-Finding
		* Time-Tabling

	* SAT-Inspired Learning
		* First Unique Implication Points (1UIP)
		* Activity-based search
		* Luby restarts

* SAT (Satisfyability)
	* Might be worth doing it's own catergory?

* Applications
	* Scheduling
		* Problems
			* RCPSP
		* Models
			* Precedence Graphs (Activity-On-Node Networks)
			* Logic Graphs
			* Interval Variables
			* Optional Variables
		* Heuristics
			* Serial Schedule Generation Schemes
			* Parallel Schedule Generation Schemes
			* Interval based scheduling
		* Constraint-Based Scheduling
			* Scheduling Heuristics
			* Decompositions
	* Routing?
	* Rostering?
	* ?

* Admin
	* Create Zen of openOR? Stuff like
		* Concise is better than verbose
		* Understandable is better than technical?
		* Intuition first