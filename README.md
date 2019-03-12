# Caerus
 
An engine to play the EWN ([EinStein würfelt nicht!](https://en.wikipedia.org/wiki/EinStein_w%C3%BCrfelt_nicht!)) game developed in Pharo Smalltalk.  You can track my progress on [LittleGolem](https://www.littlegolem.net/jsp/info/player.jsp?plid=132193). 


## Version 0.02 

Just committed for the sole purpose of having a backup!  Lots of sloppy code, experiments & stubs.  But it works!  Now, I can start working on a full rewrite! 

As of 2019-03-10, Caerus (v0.02) was just a very incomplete (with sloppy code!) working version that will serve as a baseline for benchmarks & comparisons.  Caerus has played (via Monte Carlo simulations) a few hundred million games & positions withtout a walkback since the last code fix!  Now that I have a solid working engine, I can rewrite the whole thing more elegantly and have a new version that will have a solid sparring partner! 

Future plans include : 

-portability (at least for the headless app) with Cuis and Squeak   
-a basic UI (compatible across Cuis & Squeak dialects if that is possible)   
-a faster and more compact Move representation involving bit operations   
-a hash table in preparation for search algorithms with iterative deepening   
-full automation so the engine can play all by itself unattended on the LittleGolem server   
-multiple search algorithms (MCTS, random, expectimax, etc)   
-multiple search controls (time per move, time per game, time per N moves, N search depth, N Monte-Carlo simulations)   
-create a tournament manager to test versions & search parameters against each other   
-capability to distribute searches on multiple VMs & computers & OS   
-creation of an opening book on SQLite   
-ability to play headless as a "shell app"   

This **README** is still under development.  
   
More details on this engine's development will be found on my blog [L'endormitoire](http://www.endormitoire.wordpress.com).    