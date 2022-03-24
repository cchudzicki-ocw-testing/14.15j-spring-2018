---
content_type: page
draft: false
learning_resource_types: []
ocw_type: CourseSection
parent_title: Lecture and Recitation Notes
parent_type: CourseSection
parent_uid: 9f4e8596-124d-1608-f9e6-b335a917765a
title: Recitation 9 Notes
uid: cc345d8d-6c56-e8b8-d5cb-038086ccf41b
---
## Topics

- Games with homogeneous externalities
- Games with local network effects

## Recall 

Congestion games had simple sets of payoffs but complicated network structure. There are games that have complicated payoffs with simple network structure. 

## Homogeneous Externalities

In classical economics, the demand curve is assumed decreasing and the supply curve increasing. The existence of network effects may create a weird shape of the demand curve. 

- *N* = \[0, 1\] continuum of players
- *S*{{< sub "_i_" >}} = {buy, not buy}
- *u*{{< sub "_i_" >}}(*S*{{< sub "_i_" >}}, *S*{{< sub "_\\-i_" >}}) = *u*{{< sub "_i_" >}}(*S*{{< sub "_i_" >}}, *x*) =   
    *v*{{< sub "i" >}}*x* — *p*  if *S*{{< sub "_i_" >}} = buy   
    0           if *S*{{< sub "_i_" >}}\= not buy
- *v*{{< sub "_i_" >}} ~ F(\[0, 1\])
- *p* > 0
- Where *x* is how many buy, *v*{{< sub "_i_" >}} is its value, and *p* is price.

### *Example: Office suites, SNS, etc.*

{{< resource 735c3dc4-69f4-26c4-a7c4-55839ab79bf3 >}}

- *x* = 1 — F(*v̅*) where *v̅* is the lowest value of agents who buy.

Claim: If agent with *v*{{< sub "_i_" >}} = *v̅* is better off buying, then any agent with *v*{{< sub "_j_" >}} > *v̅* is also better off buying. 

Corollary: We may assume without loss of generality that *x* (those who buy) have the highest values in equilibrium/socially optimal outcome. 

1. Socially optimal outcome
    1. Social welfare = {{< sub "v̅" >}}∫{{< sup "1" >}}\[\_v\_(1 — F(*v̅*)) — *p*\] dF(*v*)
    2. Maximizing this with respect to *v̅* yields the social best.
2. Nash equilibrum
    1. Pooling equilibrum:   
        If no one has the good (*x* = 0) then no one has incentive to buy ( *v*{{< sub "_i_" >}} \* 0 — *p* \< 0). Therefore, *x*{{< sup "_\\*_" >}}
    2. Separating equilibrium:   
        If someone buys (*x* > 0), then there exists the lowest type *v̅* who buys. His incentive must balance *v̅x* — *p* = 0.

Note that everyone's strategy is summarized by *x*. So consider the aggregate best response function BR(*x*) = *x̂*. With *v̅x* — *p* = 0 and *x* = 1 — F(*v̅*), we find:

- BR(*x*) = 1 — F(*p*/*x*).
- Its fixed point *x*{{< sup "_\\*_" >}} is an equilibrium. 

## Local Network Effects

Some games have both complicated payoff structure and complicated network structure.

 

{{< resource 09c2914f-edc0-70a5-d7f4-6caf72833219 >}}

 

- *N* = {1, 2, 3}.
- *S*{{< sub "_i_" >}} = ℝ{{< sub "\\+" >}} = \[0, ∞).
- *u*{{< sub "_i_" >}}(*x*{{< sub "_i_" >}}, *x*{{< sub "_\\-i_" >}}, δ, *G*) = 

{{< resource 8d7d1135-8ca6-47c1-6c66-0860dac6514f >}}

*i*'s best response satisfies

{{< resource 1c9f3f1d-a0a7-fc04-87d4-44b1d6f7d4e2 >}}
{{< resource 2719373e-98a6-f592-3bdf-233060d0a0fb >}}

- BR(*x*) = max { 𝟘, 𝟙 — δ*G*𝕏}