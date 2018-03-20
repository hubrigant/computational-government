# computational-government
This repo is setup as a notepad for getting my vague idea regarding similarities between a legal system and a computational system. Initially, this will largely be freeform text, but eventually the plan is to start writing a pseudo-code "constitution", some form of test harness (probably also p-code, at least initially).

The stretch goal of this project includes a simulator that different versions of the legal framework can be run through to help make the effects of proposed changes easier to understand and visualize.

The initial presumptions for the first version main branch include:
* __**This is a thought experiment,**__ it is not intended to be a replacement for any existing government, and indeed, it is anticpated that the results of this thought experiment may not work at all, even in the virtual simulation
* The primary goal of the system of government is to maximize the individual freedoms of national citizens, within certain constraints
* The main constraint on individual freedom is causing harm; an individual is free to do pretty much anything as long as the individual doesn't cause harm to another individual or group of individuals, unless they are
  * Agree to receive the harm
  * Are mentally capable of understanding the impact of accepting the harm
* Laws should be instituted as computationally-recognizable code
* Changes to the laws should be made as pull requests
* The test suite should strive towards 100% coverage
* The definition of the freedom-maximization function, and the corresponding harm definition and balance system will be critical and contentious
* While there is a goal to shift judicial burden from people to computers, it is expressly understood that
  * The computational system will not be able to handle all new inputs without adjustment
  * In the interim between the introduction of new input and the updating of the legal code to handle the new input, human review, likely in the form similar to existing judge/jury trials, will be necessary
* Groups/organizations have rights, but not the full rights as individuals, nor are individual organizational rights necessarily on parity with whatever equivalents exist for individuals
