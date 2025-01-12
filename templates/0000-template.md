- Start Date: (fill me in with today's date, YYYY-MM-DD)
- PartiQL Issue (fill me in with the related PartiQL issue)
- RFC PR: (fill me in with the PR link once PR is created)

# Summary
[summary]: #summary

One paragraph explanation of the proposed specification change, API change, or feature.

# Motivation
[motivation]: #motivation

Why are we doing this? What use cases does it support? What is the expected outcome?

# Guide-level explanation
[guide-level-explanation]: #guide-level-explanation

Explain the proposal as if it were already included in the PartiQL specification or public APIs. The explanation should assume
the reader has proficient knowledge on the existing PartiQL specification.

- Introducing new named concepts.
- Explaining the feature largely in terms of examples.
- Explaining how PartiQL users should *think* about the feature, and how it should impact the way they use PartiQL. It should explain the impact as concretely as possible.
- If applicable, provide sample error messages, deprecation warnings, or migration guidance.
- If applicable, describe the differences between teaching this to existing PartiQL users and new PartiQL users.

For spec-oriented RFCs, this section should focus on how implementations, based on the proposed specification change, will get impacted. This section should include any required grammar that accompanies the specification change. 
For api-oriented RFCs, this section should focus on how PartiQL users would leverage or be affect by the changes.

# Reference-level explanation
[reference-level-explanation]: #reference-level-explanation

This is the technical portion of the RFC, and may be omitted for specification change proposals.

Explain the design in sufficient detail that:

- Its interaction with other features is clear.
- It is reasonably clear how the feature or API would be implemented.
- Corner cases are dissected by example.

The section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

# Drawbacks
[drawbacks]: #drawbacks

Why should we *not* do this?

# Rationale and alternatives
[rationale-and-alternatives]: #rationale-and-alternatives

- Why is this design/proposal the best in the space of possible designs?
- Which other designs/proposals have been considered, and what is the rationale for not choosing them?
- What is the impact of not doing this?

# Prior art
[prior-art]: #prior-art

Discuss prior art, both the good and the bad, in relation to this proposal.
A few examples of what this can include are:

- For specification proposals: Does this feature exist in any ISO SQL standard or other SQL dialects?
- For API changes: Do similar APIs exist in libraries such as Calcite? What are some details of the specific implementation?
- Papers: Are there any published papers or great posts that discuss this? If you have some relevant papers to refer to, this can serve as a more detailed theoretical background.

This section is intended to encourage you, as an author, to think about the lessons from other SQL dialects; provide readers of your RFC with a fuller picture.
If there is no prior art, that is fine - your ideas are interesting to us whether they are brand new or if it is an adaptation from other dialects and implementations.

Note that while precedent set by other dialects and libraries is some motivation, it does not on its own motivate an RFC.

# Unresolved questions
[unresolved-questions]: #unresolved-questions

- What parts of the design do you expect to resolve through the RFC process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?

# Future possibilities
[future-possibilities]: #future-possibilities

Think about what the natural extension and evolution of your proposal would
be and how it would affect the language and project as a whole in a holistic
way. Try to use this section as a tool to more fully consider all possible
interactions with the project and language in your proposal.
Also consider how this all fits into the roadmap for the project.

This is also a good place to "dump ideas", if they are out of scope for the
RFC you are writing but otherwise related.

If you have tried and cannot think of any future possibilities,
you may simply state that you cannot think of anything.

Note that having something written down in the future-possibilities section
is not a reason to accept the current or a future RFC; such notes should be
in the section on motivation or rationale in this or subsequent RFCs.
The section merely provides additional information.
