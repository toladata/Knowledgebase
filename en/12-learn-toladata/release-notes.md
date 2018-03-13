# Release notes

---

#### What's new in Version 2.2
February 14, 2018

NEW 🌟

* Fields for reporting `disaggregation` results is in place to add data.
* `Milestones` can be linked activities and directly viewed in the milestones section
* `Form` can be created, saved, and linked to a `program/WF1`. Data can be submitted to the form and a corresponding table is created on Track to store form data.
* `Indicators` list now has a KPI indicator tag for users to easily identify the key indicators.
* TolaData billing integration v.05 in place. The system automatically creates an 'Organization' for the user to log in.
* Testing server is setup to streamline front-end testing.
* A log of deleted tables in `Track` is setup in the back end. 
* Demo server hides the social authorization login to allow users to register.

IMPROVED 🤕

* Registered users can now access `Track` without issue.
* No more duplicate `Primary Sectors`!
* In `admin console`, 'country' and 'status' column is hidden from the user list.
* Importing new file on `Track` now takes the user directly to the table instead of showing 'new table' message.

FIXED 🐛

* `Indicators`: Disaggregations do not reload indicators page!
* `Activities/WF2/3`: Modules are now not added back after they are removed.
* `Sites`: Vertical scroll is working and the user can see all Org sites.
* `Sites`: For each site default is set to Active instead of Inactive.
* `Reports`: Indicator slider is showing correct dates when moved.
* `WF2/3`, `Indicators`: Moving the items do not break the UI.

#### What's new in Version 2.0
February 1, 2018

NEW 🌟

* User Configurable `Dashboard` is in place! Users can now create their own dashboard with charts and graphs from program and indicator data.
* Custom Workflows Levels is available. Admins can now assign their own workflow level labels.
* Users can add disaggregation types to indicators.
* First version of the German translation of the system is in place.

IMPROVED 🤕

* `Team` module includes OrgAdmin in the list of users who can access a `Program/WFL1`.
* `Activities/WF2 Budget` module items sum and roll up to the total budget amount of `WF2` and then sum up to `WLF1` total and actual `Budget`.

FIXED 🐛

* `WF1`: WF1/Program status color is now updating in the list view after saving.
* `Sites`: To add new sites, the 'office' field dropdown updates.
* `Objectives`: Users can edit an objective once created.
* `WF2`: Budget module now saves without the actual amount value.

#### What's new in Version 1.9.6
January 15, 2018

NEW 🌟

* `Unit of measure` added to `Indicator` list to show clarity of what is being measured
* `Approval Types` are now configurable
* Users can now add multiple `Approvals` 
* Data can now be collected and linked to multiple `sites`
* Save and Add Another button for quicker `Form` creation
* `Track` is stylized to be on brand
* On `Track`, logged in user is now directed to their Tables instead of home page
* Implemented unit tests for components/services/pipes for `Activity` front end
* Testing server is set up
* Django package in place for faster deployment

IMPROVED 🤕

* New users signing in to Demo server is directly assigned to `TolaData` organization by default.
* Restore point in demo server is updated. Factory restore point is updated with two programs and new users are assigned to them.
* Added messaging on demo server for users, alerting that database will be reset to restore point.
* Register New User Form has the check box for privacy disclaimer in a better location
* For `View Only` users, edit and delete options updated and `Activities/WF2` Disable + icon WFL2 for Program `View Only` 
* Warning for users on "Close" if they have edited an `Activity` form. 
* Branding of `Forms` in the `Form Library` to match `Activity`

FIXED 🐛

* Users can switch between `Activity` and `Track` without having to log in twice - API updates
* Adding a New Team Member is now set to  `View Only`
* `Admin console` shows user's email address
* `Milestone` dates can be edited by moving the slider on the `Milestone` tab 
* `Global Filter`: Cleaned up filter for just filter by `Program/WF1`
* `Global Filter`: Selected WFL1 is not shown as selected in the filter 
* `Global Filter`: Removing the last filter from filter bar clears filter
* `Track`: Data import from GoogleSheet is in place



