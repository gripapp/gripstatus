#	Grip Status Howto

## Reporting a Problem

### Step 1: GitHub

Create an [issue on GitHub](https://github.com/gripapp/gripstatus/issues/new) to describe the downtime/problem/degradation.

- Click on the cog icon next to labels on the right.
- Choose the affected systems (black labels)
- Choose a severity label (major outage, degraded performance, investigating)
- Fill in the title, leave a comment and click on `Submit new issue`.

### Step 2: statuspage_update

Open a Terminal window and run ``statuspage_update``.

Please note that this is an alias for ``statuspage update --name=gripstatus --token=<secret> --org=gripapp``


## Closing or Updating a Problem

### Step 1: GitHub

Close the issue to report it as resolved.
Add comments or change labels to update the problem.

### Step 2: statuspage_update

Run `statuspage_update` again.
