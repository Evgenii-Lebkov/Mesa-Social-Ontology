# Mesa-Social-Ontology
Agent-Based Modeling using Mesa framework. This model illustrates social ontological concept introduced in my Bachelor's Thesis.

# Theoretical foundations

**Computational methods used:** Mesa framework (Agent-based modeling)

**Theoretical concepts used:** status, functions (in John Searle's sense), mechanisms (in the Machamer, Darden, and Craver sense).

The deontology of the organization, the structure of the organization, and the concept of organization itself are proposed in my bachelor thesis, which aims to supplement Searle's social ontology from the perspectives of naturalism and physicalism. 

The main element of an **organization** is an **accepted status**, which exists in the brain of an organization member and is accepted by means of a Declaration (in Searle's sense).

**The deontology of the organization** exists in the brain of the member and represents a set of the member's beliefs about the rules accepted in the organization (i.e., about status functions of different statuses). 

**The structure of the organization**, in its turn, does not exist in the brains of the members. It is an objective description of the functions that members perform while following the deontologies of the organization held in their brains.

# The description and goals of the model

The goal is to demonstrate how different organization members can have different deontologies of the organization in their brains, while the structure of the organization still exists and possesses its own emergent properties. In this model, the structure can be characterized as defective because the organization falls apart due to the fact that some members hold a different deontology of the organization in their brains, which is not taken into account by all members in this case.

**"Live queue"**
The model simulates a so-called "live queue", which is common in some countries. The most important distinction of a "live queue" is that members of this type of queue must remember their predecessor and successor, even while everyone sits in a chaotic manner on chairs near the office. This happens because anyone wishing to join the queue must ask: "Who is the last person?" and take their place after this person, if there is one. Joining the "Live queue" organization, its creation, and other similar actions are viewed as mechanisms.

**Model description**

Participants were modeled with two types of deontologies:
1. **Standard**. According to their deontology, it is necessary to warn other queue members when leaving from the middle of the queue.
2. **Deviant**. According to the deontology of these members, one can leave the queue suddenly and without warning at any moment.

If a "Live queue" organization includes members with these two types of deontologies, the structure of the organization can be called "defective" because the organization will not be able to persist for a long time. If a member leaves suddenly without warning, the successor of this person (who does not know who stood before the disappeared member) no longer knows who they are following. This creates problems in the functioning of the organization. To solve this, members would have to go beyond the deontology of the organization, trying to find who they should stand behind now. Therefore, the structure of the modeled organization is defective. It is an emergent property of the entity "organization".

Additionally, "loiterers" were added to the model. They are agents who simply stand near the office to increase realism, reflecting that not everyone near the office intends to enter there.

# Obtained results

The simulation demonstrated that the organization can exist even with a defective structure for some time. However, this duration is typically limited to an average of 800–1000 steps. The functioning of an organization where members hold differing deontologies demonstrates that "the structure of the organization" and "the deontology of the organization" can be fruitful concepts for social ontology.

<img width="642" height="491" alt="image" src="https://github.com/user-attachments/assets/c0a62ffe-bd8b-431d-9484-5aecf7692767" />

A plot showing the change in queue length over time. As can be seen, in this instance, the model stopped at step 600+ due to the disruption of the structure of the organization.
