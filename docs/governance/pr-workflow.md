Dear CODEOWNERS,
on a recent PO Daily we have discussed a very important topic - a reputation of our Kyma project on Github. We have to ensure it is high and there are couple of measures to track it.
We decided to start from this one: The length of time Pull Requests remain open.
We would like to reduce the time to the minimum that’s why we set ambitious goal - **have every PR addressed within 1 working day.** We start from the CODEOWNERS side. Whenever new PR arrives at your door, you have 1 day to react by either:
- Making a review (positive / negative)
- In case of negative review - provide a reason. Don’t hesitate to tell the author that the PR is too big or it is not properly described (just comment in the PR).
- Making agreement with author on extended time to make review, keep all discussions under the PR and assign the reviewer to the PR.

A timer for “1 day” starts counting from the day following the day the PR was opened. We inherited quite a long list od open PRs in our project. We have to address them as well, with the same rules we introduced above. Please go through the list of PRs belonging to your team and process them (do it in alignment with your team’s PO in terms of your current sprint backlog, but do not wait too much!):
- Review [list of all unassigned PRs in Kyma](https://github.com/pulls?page=2&q=is%3Aopen+is%3Apr+user%3Akyma-project+archived%3Afalse+no%3Aassignee+-label%3Ado-not-merge%2Fwork-in-progress+sort%3Acreated-asc+-label%3Ado-not-merge%2Fhold+-label%3Ado-not-merge%2Finvalid-commit-message) and find processor
- Review [list of all assigned PRs](https://github.com/pulls?page=2&q=is%3Aopen+is%3Apr+user%3Akyma-project+archived%3Afalse+no%3Aassignee+-label%3Ado-not-merge%2Fwork-in-progress+sort%3Acreated-asc+-label%3Ado-not-merge%2Fhold+-label%3Ado-not-merge%2Finvalid-commit-message) in Kyma and apply above mentioned reaction starting from the oldest ones

As we go further, having above lists cleaned up, we may maintain our own review requests easily by checking the list of Review Requests addressed to us on a daily basis (to keep 1-day time)
- [My own Review Requests](https://github.com/pulls/review-requested)

Because most of you also actively create PRs, please start improvements from yourself, become a role model. The following rules should be helpful in getting better review process for all of us:
- Always provide PR described well enough. The description you provide in PR is the only thing needed for a review - no need to talk to the author in a different way than under PR in GH
- Separate individual changes from mass replacement done in many files according to the same pattern. Do two PRs instead of one. It can save a lot of time for the reviewer.
- If you expect PR to be addressed to a multiple teams for a review, consider creating a individual PRs for each team
- For the PRs to the shared resources (e.g control-plane/resources/kcp) when reviewers from many different teams are requested by default, try to use your own team reviewers first (discuss it with them directly).