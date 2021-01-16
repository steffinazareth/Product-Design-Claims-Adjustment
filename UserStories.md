# User Stories

### User Story 1

As a claims adjuster, I want the ability of AI to help instantly calculate the amount to be paid from the documentation submitted related to that claim. Typically, more than half my time is spent evaluating multiple documents for one claim to come up with the right settlement price and the entire process can be exhausting. The breakdown of the settlement price calculated with intelligent AI capabilities can help me save time usually spent on making these lengthy calculations.

Acceptance criteria: Model accuracy greater than 80%.
**Refer screens 14 to 16 of the prototype.**

### User Story 2

As a claims adjuster, I want the option to accept or reject claims (after viewing their details including vehicle diagnostics) that come my way otherwise I feel frustrated because I do not have a choice in choosing what claim to work on. I want to be able to only take on those claims that I can complete for the day and not feel too overwhelmed by the sheer amount of claims coming through.

Acceptance criteria: If the claim is accepted, it is added to the ‘SCHEDULED’ tab (highlighted in green). If the claim is rejected, it is no longer present in the ‘ACTIVE’ tab.
**Refer screens 1 to 6 of the prototype.**

### User Story 3

As a claims adjuster, I want the option to view accepted (i.e. scheduled claim requests) and processed claims requests separately otherwise viewing all of them together would prove to be rather confusing especially when they add up to a large number. This clear distinction between the two, by having separate sections for each, will help immensely because if I have to reassess any processed claim (or access any processed claim), I will be able to look them up easily and view their documentation. Also, if I have to decide which incident location to head to next, I only have to view the list of incidents that are accepted and choose from any one of them the option to ‘Lock GPS’ (i.e feed the location of the incident to the cars GPS).

Acceptance Criteria: 
1. Separate section (‘SCHEDULED’ tab) available for scheduled (i.e. accepted) incidents. For any incident in the scheduled tab, the claims adjuster is shown the option to ‘LOCK GPS’. GPS can be locked for any one of the incidents in the ‘SCHEDULED’ tab. ‘DOCUMENT’ button is enabled (appears) for the incident whose GPS is locked. 
2. Processed incidents appear in the ‘PAST’ tab. The documentation and settlement amount can be viewed for each processed incident.
**Refer screens 7 to 10 and 19, 20 of the prototype.**

### User Story 4

The algorithm should send the claim request to a claims adjuster based on two criteria’s: 1) The distance the claims adjuster is from the location of the incident 2) The workload (accepted claim requests) taken on by the claims adjuster. If the claims adjuster nearest to the location of the incident and having the least workload for some reason happens to reject the request, the algorithm should send the claims request to the next best claims adjuster matching the two criteria’s. If no claim adjuster accepts the request within 30 minutes, the algorithm should automatically allocate the request to the claims adjuster it determines best suited to take on the claim depending on the criteria again. This claim request would be directly added to the ‘SCHEDULED’ tab.

Acceptance criteria: A claim request is allocated to a claims adjuster within 30 minutes.

### User Story 5

As a claims adjuster, I want a comprehensive documentation section where I can comment on the diagnostics received, make notes and upload images for different evidence categories. Having all of these sections present will enable me to document the claim in detail and perform a detailed assessment of the claim.

Acceptance criteria: Any comment made on the diagnostics, notes made or images uploaded are saved automatically. The speech-to-text option should function correctly while noting comments and taking notes, in addition to typing. All the information documented should appear without any inconsistency in the review section.

**Refer screens 11 to 15 of the prototype.**


## Priorities of User Stories

User Story 1 has high effort and high impact. User Story 2 has low effort and high impact. User Story 3 has low effort and low impact. User Story 4 has high effort and high impact. User Story 5 has medium effort and medium impact. Using the MOSCOW method, user stories 1, 2 and 4 are ‘must haves’. Our application is dependent on these features being present. User story 5 is a ‘should have’ because the AI will be using the information documented to make the calculation. And user story 3 is a ‘could have’ because with this we are simply providing a better user experience.

Considering both the Effort-Impact as well as the MOSCOW method, we can say that we should prioritize user story 2 first because it is low effort, high on impact and a must have. Next, we should prioritize user story 1 and 4 because although they are high on effort, they are also high on impact and must haves. Next in priority should be user story 5, it is a ‘should have’ and having medium impact and requiring medium effort. Last to prioritize is user story 3, it is a ‘could have’ and having low impact and requiring low effort.
