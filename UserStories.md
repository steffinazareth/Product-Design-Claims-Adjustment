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
