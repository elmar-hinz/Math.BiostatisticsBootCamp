Experiments and Probability
============================

Set notation and probability
----------------------------

Notation
........

Sample space:

    .. math:: \Omega = \{1, 2, 3, 4, 5, 6\}

Event is a subset of :math:`\Omega`:

    .. math:: E = \{1, 2, 3\}

Elementary or simple event:

    .. math:: w = 4

Null event or empty set:

    .. math:: \emptyset

Interpretation of set operation rules
.....................................

* :math:`w \in E` implies that :math:`E` occurs when :math:`w` occurs
* :math:`w \notin E` implies that :math:`E` does not occur when :math:`w` occurs
* :math:`E \subset F` implies that the occurance of :math:`E` implies the occurance of :math:`F`
* :math:`E \cap F` implies the event that both :math:`E` and :math:`F` occur
* :math:`E \cup F` implies the event that at least one of :math:`E` and :math:`F` occur
* :math:`E \cup F = \emptyset` means that :math:`E` and :math:`F` are mutually exclusive
* :math:`E^c` is the event that :math:`E` does not occur

Logic
.....

Disjunction:
    This or that or both applies. Also inclusive disjunction or alteration.

Conjunction:
    Both, this and that applies.

Negation:
    Just the opposite.

De Morgan's laws
................

#. :math:`(A \cap B)^c = (A^c \cup B^c)`
#. :math:`(A \cup B)^c = (A^c \cap B^c)`

In words:

#. The negation of a disjunction is the conjunction of the negations.
#. The negation of a conjunction is the disjunction of the negations.

Also:

#. :math:`(A^c)^c = A`
#. :math:`(A \cup B) \cap C = (A \cap C) \cup (B \cap C)`

Augustus De Morgan (27 June 1806 – 18 March 1871) was a British mathematician and logician.

Probabilities and Variables
===========================

Three fundamental rules of probability
--------------------------------------

1. For event :math:`E`: :math:`E \in \Omega, 0 \leq P(E) \leq 1`
2. The total probability of the sample space is 1: :math:`P(\Omega) = 1`
3. If :math:`E_1` and :math:`E_2` are mutually exclusive events: :math:`P(E_1 \cup E_2) = P(E_1) + P(E_2`

Probability measure:

.. math:: P

Finite additivity:

.. math::

    P(\cup_{i=1}^n A_i) = \sum_{i=1}^n P(A_i)

Countable additivity:

.. math::

    P(\cup_{i=1}^\inf A_i) = \sum_{i=1}^\inf P(A_i)

Domain:

A domain :math:`F` is a collection of events.

* :math:`P` is defined on :math:`F` a collection of subsets of :math:`\Omega`
* Example :math:`\Omega = \{1, 2, 3\}` then
    .. math::
        F = \{\emptyset, \{1\}, \{2\}, \{3\}, \{1, 2\}, \{1, 3\}, \{2, 3\}, \{1, 2, 3\} \}
* When :math:`\Omega` is a continuos set, we assume that :math:`F` is sufficiantly rich
  so that any set that we are interested in will be in it.

The three rules of probability imply
------------------------------------

* :math:`P(\emptyset) = 0`
* :math:`P(E) = 1 - P(E^c)`
* :math:`P(A \cup B) = P(A) + P(B) - P(A \cap B)`
* if :math:`A \in B` then :math:`P(A) \leq P(B)`
* :math:`P(A \cup B) = 1 - P(A_c \cap B_c)`
* :math:`P(A \cap B_c) = P(A) - P(A \cap B)`
* :math:`P(\cup_{i=1}^n E_i) \leq \sum_{i=1}^n P(E_i)` (also for non-mutually-exclusive events)
* :math:`P(\cup_{i=1}^n E_i) \geq max_i P(E_i)` (dito)

























