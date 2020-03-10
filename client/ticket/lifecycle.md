---
nav-section: Ticket
---
# Lifecycle of a Support Ticket

Each support ticket goes through certain lifecycle statuses from the point of it being created, to the point it is closed.

The different statuses are detailed below.

>**Note**: RTS handle progressing the support tickets through their lifecycle statuses.

## Reported

This is what each new support ticket is set to when it is first created.

## Being Investigated

When a support ticket is created, RTS will perform an investigation into the reported issue.

## Diagnosis Result

When RTS have completed their investigation into the reported issue, they will give the ticket a diagnosis result of one of the following:

- **Bug Verified**: RTS were able to recreate the issue and have confirmed that it is a bug.
- **Enhancement Request**: RTS believe that the ticket is not for a bug, but for an enhancement request and they will provide an explanation why they believe this to be the case. Each ticket that is given this type of diagnosis result will also be categorised into one of the following:
  - **Minor**: This is something that could potentially be carried out under the support contract using the allocated support resources (e.g. moving the location of a button).
  - **Major**: This is something that will need to be carried out outside of the support contract due to the required development workload and associated costs (e.g. developing a new spreadsheet import process).
- **More Info. Required from Client**: RTS have not been supplied with enough information to recreate/understand the issue so the person who created the ticket needs to [edit](edit) it to expand on the provided details.

> **Note**: If the investigation results in RTS determining that the issue is a user issue, the diagnosis result status will be bypassed and it will be set straight to **Closed: User Issue** (see below).

## On Hold

When a ticket is put on hold by RTS or yourself for any reason.

## Release Pending

If the resolution of a support ticket requires a change to the software, the ticket will be set to this status until the release containing the bug fix/enhancement has been deployed.

## Closed

When a support ticket has reached the end of its lifecycle, it will be set to one of the following closed statuses that reflects the end result:

- **Closed: Fix Released**: An update to the software was required to fix the reported issue. The release containing the fix has been deployed.
- **Closed: Enhancement Released**: An update to the software was required to implement the required enhancement. The release containing the enhancement has been deployed.
- **Closed: Info. Provided**: RTS have supplied the requested information.
- **Closed: User Issue**: RTS determined that the issue occurred due to the user trying to use the application in a way that was not intended. RTS will attempt to explain the correct process that should have been followed.
- **Closed: No Longer Required**: You have decided that the requested enhancement or request for information is no longer required.
- **Duplicate** - A Ticket for the same bug or enhancement request has already been created on the helpdesk.
