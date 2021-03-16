# Rejection

## Query
```
{from:ingress-support@nianticlabs.com from:ingress-support@google.com} subject:{"Portal review complete" "Ingress Portal Rejected" "Ingress Portal Duplicate"} {reviewed duplicate} -edit -photo -AP
```

## Samples

### Undeclared
```
Subject: [Portal review complete: <PORTAL-TITLE>]
----------

We've reviewed your Portal submission and given the information you've provided in your submission, we have decided not to accept this candidate.

At this time, we’re not able to provide specific rejection reasons for each submission we review; however, the following are common reasons for rejection:

The candidate is on our PLEASE DON'T SUBMIT list
We couldn't find evidence that the candidate meets any of our ACCEPTANCE CRITERIA
The candidate was submitted in an incorrect location, and we weren't able to find the right location

-NianticOps

<PORTAL-TITLE>
<PORTAL-DESCRIPTION>

<PHOTO-URL>
```

```
Subject: [Ingress Portal Rejected: <PORTAL-TITLE>]
----------

Thank you for your Portal submission. However, this Portal candidate does not meet the criteria required for approval.

Please refer to New Portal Submission criteria at our Help Center for further information.

<PHOTO-URL>
```

### Duplicated
```
Subject: [Portal review complete: <PORTAL-TITLE>]
----------

We've reviewed your Portal submission, but we're not able to bring this candidate online at this time.

Your candidate is a duplicate of either an existing Portal or one that's too close to another live Portal to be safely Hacked.

-NianticOps

<PORTAL-TITLE>

<PHOTO-URL>
```

```
Subject: [Ingress Portal Duplicate: <PORTAL-TITLE>]
----------

Thank you for your Portal submission. This portal candidate is a duplicate of an existing Portal, or is too close to another existing Portal to be safely hacked. This candidate will enabled as a new Portal at this time.

<PHOTO-URL>
```

## Too Close
```
Subject: [Portal review complete: <PORTAL-TITLE>]
----------

We've reviewed your Portal submission and believe it meets the Candidate Portal criteria. However, this candidate is too close to an existing Portal, so we're not able to bring it online at this time.

-NianticOps

<PORTAL-TITLE>

<PHOTO-URL>
```