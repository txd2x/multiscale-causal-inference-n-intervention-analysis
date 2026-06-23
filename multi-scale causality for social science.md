Date created: 2026-6-23
Author: Xingdi TIAN, PhD.
# Principles for Cross-Scale Causal Inference and Intervention Analysis in Social Science #

Causation in social science is a scale-dependent relation whose meaning depends on the variables, interventions, and identification strategies available at a given level of abstraction. Its interpretation depends on how systems are represented, how causal structures emerge through aggregation, how effects propagate across levels of organization, and how interventions are defined. A satisfactory causal analysis must therefore be simultaneously scale-aware and intervention-centered.
This would place the framework somewhere between methodological individualism, causal emergence theory, and modern causal inference, while remaining compatible with structural causal models and contemporary econometrics. It could serve as the foundation for a formal theory of multi-scale causal inference in social systems.
## Principle 1: Intervention Priority ##

A causal claim is meaningful only with respect to a well-defined intervention. The primary object of causal analysis is therefore not a variable, mechanism, or correlation, but an intervention and its consequences.

## Principle 2: Partial Fungibility ##
Causal claims are not attached to variables alone, but to a scale-specific representation of a system.
The same system may admit multiple valid representations at different scales. Variables, mechanisms, and identification strategies are therefore fungible across representations. An intervention defined at one scale need not possess an equivalent interpretation at another.

### (1) Intervention Fungibility ##
A causal claim is meaningful only if a corresponding intervention can be conceptually specified at the same scale.

For an individual:

$do(Education_i)$

may be interpretable.

For a nation:

$do(\bar{Education})$

requires a different intervention mechanism.

### (2) Scale-Specific Identification ###
Identification validity cannot be transferred across scales without additional assumptions.

## Principle 3: Emergence ##
Interventions may generate effects that are not reducible to the immediate consequences observed at lower levels of analysis. Aggregation, interaction, and equilibrium formation can produce causal structures that exist only at higher scales.

Aggregation is not causally neutral. The causal structure observed at a higher level may differ from, or exceed, that implied by lower-level relations. Macro-level causes may arise from the interaction and aggregation of micro-level processes and need not admit a unique micro-level realization.
Consequently, **causal explanations cannot be assumed invariant across scales.**
### (1) Non-Invariance of Aggregation [aka "ecological fallacy"] ##
Aggregation is not generally causally neutral.

Suppose individuals satisfy

$Y_i =βX_i+ϵ_i$

Then it does not follow that

$ \bar{Y}=β \bar{X}+ϵ$

captures the same causal effect. Heterogeneity, interaction, and network dependence may create entirely new macro-level relationships. **Causal parameters should not be assumed invariant under aggregation.** 

### (2) Mechanism Multiplicity ###
The same macro causal effect may arise from multiple distinct micro mechanisms.

For example:

Political participation may increase following educational expansion because of
civic skills,
social networks,
political efficacy,
economic modernization.

Different societies may realize different pathways.

Hence, macro causation often admits many micro realizations.
This implies **partial independence between explanation and identification.**
### (3) Emergent Causal Structure ###
Some causal relations may appear only after aggregation.
Examples include:
market equilibria, 
inflation dynamics, 
social norms,
institutional persistence.
No individual actor may possess the corresponding causal variable.

Yet stable interventions can exist at the collective level. **Macro-level causes may be real even when they are not reducible to individual-level causes.**

## Principle 4: Cross-Scale Causation ##
The effects of interventions propagate across levels of organization. Micro-level interventions may generate macro-level consequences, while macro-level interventions may alter the incentives, constraints, and behaviors of individual actors. Social causation is therefore inherently multi-level.

Social systems are characterized by reciprocal causation between levels of organization. Micro-level actions generate macro-level outcomes, while macro-level institutions, norms, and equilibria shape subsequent micro-level behavior.
Consequently, **many forms of endogeneity can be understood as unresolved cross-scale feedback.**

## Central Proposition ##

The validity and interpretation of a causal claim depend on how an intervention is represented, how its effects emerge through aggregation, and how those effects propagate across scales. Causal inference in social science should therefore be understood as the study of interventions within multi-scale systems rather than as the identification of isolated causal links.

## Cautionary Notes ##
### Distinguish Existence from Identifiability ###

A causal process may exist even when it cannot be identified.

This distinction is particularly important in social science.

Failure of identification may result from:
measurement limits,
strategic behavior,
equilibrium effects,
missing counterfactuals.

**Therefore**, lack of identification is not evidence against causal existence.
### Causal Compression ###

A macro variable often serves as a compressed representation of many lower-level states.
For example:
GDP,
unemployment rate,
social trust.

These variables summarize large numbers of micro conditions.
The causal usefulness of a macro variable derives not from ontological primacy but from informational compression.
**Thus**, causal variables are frequently chosen for their explanatory efficiency rather than their fundamental status.

### Linguistic Humility ###

Causal language should be proportional to the strength of identification.
Researchers should distinguish between:
causal effect,
mechanism,
prediction,
association,
narrative explanation.

Many disputes arise because these categories are conflated.
**Hence**, Every causal statement should explicitly specify its scale, intervention, and identification assumptions.