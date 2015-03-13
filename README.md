# AIMA3e-Java (JDK 7+)
Java implementation of algorithms from Norvig And Russell's "Artificial Intelligence - A Modern Approach - A Modern Approach 3rd Edition."

Java implementation of algorithms from [Norvig](http://www.norvig.com/) and [Russell's](http://www.cs.berkeley.edu/~russell/)  [Artificial Intelligence - A Modern Approach 3rd Edition](http://aima.cs.berkeley.edu/) 

# Getting Started Links 
  * [Demo Applications that can be run from your browser](http://aima-java.googlecode.com/svn/trunk/aima-all/release/aima3ejavademos.html).
  * [An overview of the project](http://code.google.com/p/aima-java/wiki/AIMA3eReadme).
  * [Instructions on how to set up your workspace](http://code.google.com/p/aima-java/wiki/GettingStarted).
  * [Javadoc for the aima-core project](http://aima-java.googlecode.com/svn/trunk/aima-all/release/javadoc/aima-core/index.html).
  * [Download the latest official version  = 1.8.0 (Aug 10 2014)](https://code.google.com/p/aima-java/wiki//p/aima-java/wiki/AIMADownloads).
  * Latest Maven Information (for integration as a third party library)<br>
  
      `<dependency>`<br>

          <groupId>com.googlecode.aima-java</groupId>
          <artifactId>aima-core</artifactId>
          <version>0.11.0</version>
      `</dependency>`

# Index of Implemented Algorithms
<table style="width:100%">
   <tbody>
   <tr>
       <td><b>Fig</b></td>
       <td><b>Page</b></td>
       <td><b>Name (in book)</b></td>
       <td><b>Code</b></td>
   </tr>
   <tr>
       <td>2</td>
       <td>34</td>
       <td>Environment</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/Environment.java">Environment</a></td>
   </tr>
   <tr>
       <td>2.1</td>
       <td>35</td>
       <td>Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/Agent.java">Agent</a></td>
   </tr>
   <tr>
       <td>2.3</td>
       <td>36</td>
       <td>Table-Driven-Vacuum-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/environment/vacuum/TableDrivenVacuumAgent.java">TableDrivenVacuumAgent</a></td>
   </tr>
   <tr>
       <td>2.7</td>
       <td>47</td>
       <td>Table-Driven-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/impl/aprog/TableDrivenAgentProgram.java">TableDrivenAgentProgram</a></td>
   </tr>
   <tr>
       <td>2.8</td>
       <td>48</td>
       <td>Reflex-Vacuum-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/environment/vacuum/ReflexVacuumAgent.java">ReflexVacuumAgent</a></td>
   </tr>
   <tr>
       <td>2.10</td>
       <td>49</td>
       <td>Simple-Reflex-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/impl/aprog/SimpleReflexAgentProgram.java">SimpleReflexAgentProgram</a></td>
   </tr>
   <tr>
       <td>2.12</td>
       <td>51</td>
       <td>Model-Based-Reflex-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/impl/aprog/ModelBasedReflexAgentProgram.java">ModelBasedReflexAgentProgram</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>66</td>
       <td>Problem</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/Problem.java">Problem</a></td>
   </tr>
   <tr>
       <td>3.1</td>
       <td>67</td>
       <td>Simple-Problem-Solving-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/SimpleProblemSolvingAgent.java">SimpleProblemSolvingAgent</a></td>
   </tr>
   <tr>
       <td>3.2</td>
       <td>68</td>
       <td>Romania</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/environment/map/SimplifiedRoadMapOfPartOfRomania.java">SimplifiedRoadMapOfPartOfRomania</a></td>
   </tr>
   <tr>
       <td>3.7</td>
       <td>77</td>
       <td>Tree-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/TreeSearch.java">TreeSearch</a></td>
   </tr>
   <tr>
       <td>3.7</td>
       <td>77</td>
       <td>Graph-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/GraphSearch.java">GraphSearch</a></td>
   </tr>
   <tr>
       <td>3.10</td>
       <td>79</td>
       <td>Node</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/Node.java">Node</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>79</td>
       <td>Queue</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/util/datastructure/Queue.java">Queue</a></td>
   </tr>
   <tr>
       <td>3.11</td>
       <td>82</td>
       <td>Breadth-First-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/BreadthFirstSearch.java">BreadthFirstSearch</a></td>
   </tr>
   <tr>
       <td>3.14</td>
       <td>84</td>
       <td>Uniform-Cost-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/UniformCostSearch.java">UniformCostSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>85</td>
       <td>Depth-first Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/DepthFirstSearch.java">DepthFirstSearch</a></td>
   </tr>
   <tr>
       <td>3.17</td>
       <td>88</td>
       <td>Depth-Limited-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/DepthLimitedSearch.java">DepthLimitedSearch</a></td>
   </tr>
   <tr>
       <td>3.18</td>
       <td>89</td>
       <td>Iterative-Deepening-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/IterativeDeepeningSearch.java">IterativeDeepeningSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>90</td>
       <td>Bidirectional search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/BidirectionalSearch.java">BidirectionalSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>92</td>
       <td>Best-First search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/informed/BestFirstSearch.java">BestFirstSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>92</td>
       <td>Greedy best-First search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/informed/GreedyBestFirstSearch.java">GreedyBestFirstSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>93</td>
       <td>A* Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/informed/AStarSearch.java">AStarSearch</a></td>
   </tr>
   <tr>
       <td>3.26</td>
       <td>99</td>
       <td>Recursive-Best-First-Search </td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/informed/RecursiveBestFirstSearch.java">RecursiveBestFirstSearch</a></td>
   </tr>
   <tr>
       <td>4.2</td>
       <td>122</td>
       <td>Hill-Climbing</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/local/HillClimbingSearch.java">HillClimbingSearch</a></td>
   </tr>
   <tr>
       <td>4.5</td>
       <td>126</td>
       <td>Simulated-Annealing</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/local/SimulatedAnnealingSearch.java">SimulatedAnnealingSearch</a></td>
   </tr>
   <tr>
       <td>4.8</td>
       <td>129</td>
       <td>Genetic-Algorithm</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/local/GeneticAlgorithm.java">GeneticAlgorithm</a></td>
   </tr>
   <tr>
       <td>4.11</td>
       <td>136</td>
       <td>And-Or-Graph-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/nondeterministic/AndOrSearch.java">AndOrSearch</a></td>
   </tr>
   <tr>
       <td>4</td>
       <td>147</td>
       <td>Online search problem</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/online/OnlineSearchProblem.java">OnlineSearchProblem</a></td>
   </tr>
   <tr>
       <td>4.21</td>
       <td>150</td>
       <td>Online-DFS-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/online/OnlineDFSAgent.java">OnlineDFSAgent</a></td>
   </tr>
   <tr>
       <td>4.24</td>
       <td>152</td>
       <td>LRTA*-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/online/LRTAStarAgent.java">LRTAStarAgent</a></td>
   </tr>
   <tr>
       <td>5.3</td>
       <td>166</td>
       <td>Minimax-Decision</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/adversarial/MinimaxSearch.java">MinimaxSearch</a></td>
   </tr>
   <tr>
       <td>5.7</td>
       <td>170</td>
       <td>Alpha-Beta-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/adversarial/AlphaBetaSearch.java">AlphaBetaSearch</a></td>
   </tr>
   <tr>
       <td>6</td>
       <td>202</td>
       <td>CSP</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/CSP.java">CSP</a></td>
   </tr>
   <tr>
       <td>6.1</td>
       <td>204</td>
       <td>Map CSP</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/MapCSP.java">MapCSP</a></td>
   </tr>
   <tr>
       <td>6.3</td>
       <td>209</td>
       <td>AC-3</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/AC3Strategy.java">AC3Strategy</a></td>
   </tr>
   <tr>
       <td>6.5</td>
       <td>215</td>
       <td>Backtracking-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/BacktrackingStrategy.java">BacktrackingStrategy</a></td>
   </tr>
   <tr>
       <td>6.8</td>
       <td>221</td>
       <td>Min-Conflicts</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/MinConflictsStrategy.java">MinConflictsStrategy</a></td>
   </tr>
   <tr>
       <td>6.11</td>
       <td>209</td>
       <td>Tree-CSP-Solver</td>
       <td>---</a></td>
   </tr>
   <tr>
       <td>7</td>
       <td>235</td>
       <td>Knowledge Base</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/kb/KnowledgeBase.java">KnowledgeBase</a></td>
   </tr>
   <tr>
       <td>7.1</td>
       <td>236</td>
       <td>KB-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/agent/KBAgent.java">KBAgent</a></td>
   </tr>
   <tr>
       <td>7.7</td>
       <td>244</td>
       <td>Propositional-Logic-Sentence</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/parsing/ast/Sentence.java">Sentence</a></td>
   </tr>
   <tr>
       <td>7.10</td>
       <td>248</td>
       <td>TT-Entails</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/TTEntails.java">TTEntails</a></td>
   </tr>
   <tr>
       <td>7</td>
       <td>253</td>
       <td>Convert-to-CNF</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/visitors/ConvertToCNF.java">ConvertToCNF</a></td>
   </tr>
   <tr>
       <td>7.12</td>
       <td>255</td>
       <td>PL-Resolution</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/PLResolution.java">PLResolution</a></td>
   </tr>
   <tr>
       <td>7.15</td>
       <td>258</td>
       <td>PL-FC-Entails?</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/PLFCEntails.java">PLFCEntails</a></td>
   </tr>
   <tr>
       <td>7.17</td>
       <td>261</td>
       <td>DPLL-Satisfiable?</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/DPLLSatisfiable.java">DPLLSatisfiable</a></td>
   </tr>
   <tr>
       <td>7.18</td>
       <td>263</td>
       <td>WalkSAT</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/WalkSAT.java">WalkSAT</a></td>
   </tr>
   <tr>
       <td>7.20</td>
       <td>270</td>
       <td>Hybrid-Wumpus-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/environment/wumpusworld/HybridWumpusAgent.java">HybridWumpusAgent</a></td>
   </tr>
   <tr>
       <td>7.22</td>
       <td>272</td>
       <td>SATPlan</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/SATPlan.java">SATPlan</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>323</td>
       <td>Subst</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/SubstVisitor.java">SubstVisitor</a></td>
   </tr>
   <tr>
       <td>9.1</td>
       <td>328</td>
       <td>Unify</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/Unifier.java">Unifier</a></td>
   </tr>
   <tr>
       <td>9.3</td>
       <td>332</td>
       <td>FOL-FC-Ask</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/FOLFCAsk.java">FOLFCAsk</a></td>
   </tr>
   <tr>
       <td>9.3</td>
       <td>332</td>
       <td>FOL-BC-Ask</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/FOLBCAsk.java">FOLBCAsk</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>345</td>
       <td>CNF</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/CNFConverter.java">CNFConverter</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>347</td>
       <td>Resolution</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/FOLTFMResolution.java">FOLTFMResolution</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>354</td>
       <td>Demodulation</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/Demodulation.java">Demodulation</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>354</td>
       <td>Paramodulation</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/Paramodulation.java">Paramodulation</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>345</td>
       <td>Subsumption</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/SubsumptionElimination.java">SubsumptionElimination</a></td>
   </tr>
   <tr>
       <td></td>
       <td></td>
       <td></td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA3e/"></a></td>
   </tr>
   </tbody>
</table>  

||  10.9 ||     383|| Graphplan                    ||---||
||  11.5 ||     409|| Hierarchical-Search          ||---||
||  11.8 ||     414|| Angelic-Search               ||---||
||  13.1 ||     484|| DT-Agent                     ||---||
||  13   ||     484|| Probability-Model            ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/ProbabilityModel.java ProbabilityModel], [http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/FiniteProbabilityModel.java FiniteProbabilityModel]||
||  13   ||     487|| Probability-Distribution     ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/ProbabilityDistribution.java ProbabilityDistribution], [http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/CategoricalDistribution.java CategoricalDistribution]||
||  13   ||     490|| Full-Joint-Distribution      ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/full/FullJointDistributionModel.java FullJointDistributionModel]||
||  14   ||     510|| Bayesian Network             ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/BayesianNetwork.java BayesianNetwork]||
||  14.9 ||     525|| Enumeration-Ask              ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/exact/EnumerationAsk.java EnumerationAsk]||
||  14.11||     528|| Elimination-Ask              ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/exact/EliminationAsk.java EliminationAsk]||
||  14.13||     531|| Prior-Sample                 ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/approx/PriorSample.java PriorSample]||
||  14.14||     533|| Rejection-Sampling           ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/approx/RejectionSampling.java RejectionSampling]||
||  14.15||     534|| Likelihood-Weighting         ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/approx/LikelihoodWeighting.java LikelihoodWeighting]||
||  14.16||     537|| GIBBS-Ask                    ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/approx/GibbsAsk.java GibbsAsk]||
||  15.4 ||     576|| Forward-Backward             ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/temporal/generic/ForwardBackward.java ForwardBackward], [http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/hmm/exact/HMMForwardBackward.java HMMForwardBackward], [http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/hmm/exact/HMMForwardBackwardConstantSpace.java HMMForwardBackwardConstantSpace]||
||  15   ||     578|| Hidden Markov Model          ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/hmm/HiddenMarkovModel.java HiddenMarkovModel]||
||  15.6 ||     580|| Fixed-Lag-Smoothing          ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/hmm/exact/FixedLagSmoothing.java FixedLagSmoothing]||
||  15   ||     590|| Dynamic Bayesian Network     ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/DynamicBayesianNetwork.java DynamicBayesianNetwork]||
||  15.17||     598|| Particle-Filtering           ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/bayes/approx/ParticleFiltering.java ParticleFiltering]||
||  16.9 ||     632|| Information-Gathering-Agent  ||---||
||  17   ||     647|| Markov Decision Process      ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/mdp/MarkovDecisionProcess.java MarkovDecisionProcess]||
||  17.4 ||     653|| Value-Iteration              ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/mdp/search/ValueIteration.java ValueIteration]||
||  17.7 ||     657|| Policy-Iteration             ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/probability/mdp/search/PolicyIteration.java PolicyIteration]||
||  17.9 ||     663|| POMDP-Value-Iteration        ||---||
||  18.5 ||     702|| Decision-Tree-Learning       ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/learning/learners/DecisionTreeLearner.java DecisionTreeLearner]||
||  18.8 ||     710|| Cross-Validation-Wrapper     ||---||
||  18.11||     717|| Decision-List-Learning       ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/learning/learners/DecisionListLearner.java DecisionListLearner]||
||  18.24||     734|| Back-Prop-Learning           ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/learning/neural/BackPropLearning.java BackPropLearning]||
||  18.34||     751|| AdaBoost                     ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/learning/learners/AdaBoostLearner.java AdaBoostLearner]||
||  19.2 ||     771|| Current-Best-Learning        ||---||
||  19.3 ||     773|| Version-Space-Learning       ||---||
||  19.8 ||     786|| Minimal-Consistent-Det       ||---||
||  19.12||     793|| FOIL                         ||---||
||  21.2 ||     834|| Passive-ADP-Agent            ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/learning/reinforcement/agent/PassiveADPAgent.java PassiveADPAgent]||
||  21.4 ||     837|| Passive-TD-Agent             ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/learning/reinforcement/agent/PassiveTDAgent.java PassiveTDAgent]||
||  21.8 ||     844|| Q-Learning-Agent             ||[http://aima-java.googlecode.com/svn/trunk/aima-core/src/main/java/aima/core/learning/reinforcement/agent/QLearningAgent.java QLearningAgent]||
||  22.1 ||     871|| HITS                         ||---||
||  23.5 ||     894|| CYK-Parse                    ||---||
||  25.9 ||     982|| Monte-Carlo-Localization     ||---||
