# Release notes

---

#### What's new in Version 2.2

NEW 🌟
* Fields for reporting `disaggregation` results is in place to add data.
* `Milestones` can be linked activities and directly viewed in the milestones section
* `Form` can be created, saved, and linked to a `program/WF1`. Data can be submitted to the form and a corresponding table is created on Track to store form data.
* `Indicators` list now has a KPI indicator tag for users to easily identify the key indicators.
* TolaData Payments and user login: Chargebee Integration v.05 is in place. This includes direct to Chargebee page from the TolaData login page for users to add their details and 'Organization' name. The system automatically creates an 'Organization' for the user to log in.
* Testing server is setup to streamline front end testing.
* A log of deleted tables in `Track` is setup in the back end. 
* Demo server hides the social authorization login to allow users to register.

IMPROVED 🤕
* Registered users can now access `Track` without issue.
* No more duplicate `Primary Sectors`!
* In `admin console`, 'country' and 'status' column is hidden from user list.
* Importing new file on `Track` now takes the user directly to the table instead of showing 'new table' message.

FIXED 🐛
* `Indicators`: Disaggregations do not reload indicators page!
* `Activities/WF2/3`: Modules are now not added back after they are removed.
* `Sites`: Vertical scroll is working and user can see all Org sites.
* `Sites`: For each site default is set to Active instead of Inactive.
* `Reports`: Indicator slider dates is showing correct dates when moved.
* `WF2/3`, `Indicators`: Moving the items do not break the UI.

#### What's new in Version 2.0

NEW 🌟
* User Configurable `Dashboard` is in place! Users can now create their own dashboard with charts and graphs from program and indicator data.
* Custom Workflows Levels is available. Admins can now assign their own workflow level labels.
* Users can add disaggregation types to indicators.
* First version of the German translation of the system is in place.

IMPROVED 🤕
* `Team` module includes OrgAdmin in the list of users who can access a `Program/WFL1`.
* `Activities/WF2``Budget` module items sum and roll up to the total budget amount of `WF2` and then sum up to `WLF1` total and actual `Budget`.

FIXED 🐛
* `WF1`: WF1/Program status color is now updating in the list view after saving.
* `Sites`: To add new sites, the 'office' field dropdown updates.
* `Objectives`: Users can edit an objective once created.
* `WF2`: Budget module now saves without the actual amount value.

#### What's new in Version 1.9.6

NEW 🌟


IMPROVED 🤕
* New users signing in to Demo server is directly assigned to 'TolaData' organization by default.
* Restore point in demo server is updated. Factory restore point is updated with two programs and new users are assigned to them.
* Added messaging on demo server for users, alerting that database will be reset to restore point.

FIXED 🐛

















