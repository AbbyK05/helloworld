Abby Kamp Final Project Proposal

Problem Statement: Does increased Congressional campaign expenditures reduce Congressional committee meetings?

Null Hypothesis: The increased cost of running a campaign for a seat in the House of Representatives does not impact the frequency of House committee meetings.

Hypothesis: The increased cost of a Congressional campaign reduces the number of Congressional committee hearings.

Assumptions: 

1. I'm assuming that because members of Congress spend more time fundraising for their next campaign, Congressional committees meet less frequently.

2. I will directly testing funding and the number of committee hearings, but if I have time, I also want to test the number of bills marked up by commmittees.


Risks/Limitations
Congressional data is noisy, so indicating relationships is unlikely.

Data Sources
1. I will need to extract data from Congress.gov and create a dataset. My first dataset will contain:

committee: Name of the Committee
congress: Congress number (This data goes back to the 93rd Congress, 1973-1974)
all_legislation: all legislation considered by the committee
originated: Bills originating in the committee
referred:Bills referred to the committee for review from the House floor	
hearings: Forum for committee members and the public to learn about/debate a bill. *Not required step to move legislation, but key component to learning about issues and gaining support for legislation
markups: Formal step needed for a bill to advance to the House Floor. Members of the commitee consider possible changes. Concludes when committee agrees to report the Bill to the Chamber
reported: Bills sent to the floor for consideration with a committee report
discharged:Brings a bill to the House floor without the bill. Instead of the committee voting on the bill, it requires the vote of an absolute majority of House members

2. My second dataset is Brookings Vital Statistics on Congress Dataset 3-2 "House Campaign Expenditures: Major Party General Election Candidates, 1974 - 2014 (full cycle, net dollars; adjusted for inflation, 2014 dollars)"

