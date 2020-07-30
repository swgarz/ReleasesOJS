
## ojs-3.1.1

## New Features

	#520: Improve Submission Library utility
	#1692: Public identifiers for chapters
	#1816: Implement subscription support
	#1922: Add support for catalog paging
	#2714: Support browsing by section, subject and keyword
	#2872: Allow themes to override templates in plugins
	#3130: Improve blinding for role sharing between editor/author/reviewer
  
## Bug Fixes

	#1793: Test/fix PostgreSQL upgrades
	#1865: Adding review comments wipes out email changes
	#2102: Consider "Select All" feature for export tools
	#2195: Reviewers can sometimes see the names of the authors
	#2291: Missing site title
	#2441: Make wording of editorial team consistent in backend and frontend
	#2506: Fix genre assignment for upgrades
	#2564: Inconsistent HTML display in article titles
	#2571: Section word count field is inoperative
	#2759: Galleys displayed as Array
	#2794: Upload Revision canceled but still in revision list
	#2874: Remove citationLookup, citationParser and nlm30 metadata plugin
	#2894: Improve the reviewer selection list
	#2899: Error generating the path of Custom Page in Navigation Menu
	#2910: Non-administrators can see the Administration link on the front-end toolbar
	#2922: Uploading a new Galley file and selecting "Change file" corrupts the uploaded file
	#2933: Introduce menu caching
	#2942: Infinite loop in upgrade from 2.4.8.2 to 3.1, failing to skip missing files
	#2944: NavigationMenus - NMI_TYPE_CONTACT not returned by getMenuItemTypes
	#2945: restore defaults genres/components
	#2947: NavigationMenus - Issue with NMI with no displayable children
	#2952: NavigationMenus - NavigationMenu edit - unbind NavigationMenu from area
	#2955: Reference to chapters when editing component in OJS 3.1
	#2956: Plugins already installed in database but not filesystem cannot be re-installed
	#2960: Problems with Add Item action in Sidebar control
	#2962: Fix membership options
	#2964: APC usability issues
	#2965: Adding section editors to a section and returning to add more editors later breaks the section form
	#2967: Missing link from Site Administration to Journal Administration
	#2972: Untranslated locale keys in Roles select menu
	#2980: order by user_group_id in UserGroupDAO::getByRoleId
	#2987: Navigation Menus - not all default NMIs get translated upon install/upgrade
	#2988: Installation page depends on navigation menu tables, which may not exist
	#2989: Correct missing table alias for PostgreSQL upgrade
	#2994: Reveal more handler can fail to reveal more
	#2996: Paypal plugin has undeclared dependency
	#2998: Archiving page changes
	#3002: Enabled plugins disabled after upgrade
	#3003: Not possible delete Keywords in second language with X
	#3004: force_login_ssl should force register too
	#3007: remote galley and supp files are not displayed on the article page
	#3009: always provide multipleContexts variable
	#3011: Pass FormValidatorURL error message to js url validation
	#3015: New article components have NULL entry_key
	#3016: supplementary files migration
	#3028: citations parsing by line
	#3039: editor actions for all managers and sub-editors
	#3046: getCustomTemplateKeys parameters
	#3051: OAI record datestamp
	#3052: consider URL encoding for oai identifiers
	#3056: Navigation Config vs Static Pages
	#3062: wrong element attributes in oai_marc
	#3066: viewPlugin in the plugin gallery for journal managers
	#3070: Author names can be exposed to some reviewers
	#3071: Forms counter doesn't change
	#3072: Prevent range requests
	#3080: NavigationMenus - Custom Page Error on Site level
	#3084: Verify incomplete submissions behavior
	#3087: fix metrics assoc_type for supp files
	#3097: Sidebar blocks missing from search results
	#3101: Clean up locale settings upon language deletion
	#3106: choose e-mail template when selecting a reviewer
	#3108: Duplicated literal
	#3114: Select precedent reviewer for a new round failed
	#3122: Add copyFile method to SubmissionFileManager
	#3124: Enable OpenAIRE field for QuickSubmitForm
	#3125: Author name in export plugins
	#3127: Assistants not allowed to download galley files
	#3141: a string was missed in locale.xml
	#3144: NavigationMenus - Warnings removed for custom menuItems
	#3154: Error checking email format in profile page
	#3156: Submission Requirements translation are not available
	#3157: required tagit metadata fields not validated
	#3161: nl2br causes extra line breaks in copyright notice
	#3167: New discussion canceled but still in discussion list
	#3172: enable_beacon and other little things
	#3177: Replace calls to deprecated "create_function"
	#3178: Link on context logo/title in frontend incorrect
	#3184: Subscription type currency resets upon editing
	#3185: Correct PHP7.2 incompatibilities
	#3188: DECLINE decision sends unexpected "Unsuitable" in subject
	#3195: Fire form execute hooks in reviewer steps
	#3200: PostgreSQL type error in OAI interface
	#3204: COUNTER bot list is outdated
	#3206: Subscriptions page should not be accessible if payments are not enabled
	#3212: CSL styles should receive DOI without URL
	#3218: Upgrade failed: DB: Can't DROP 'user_group_id'; check that column/key exists
	#3219: Upgrade gets stuck due to lack of MoveNext() in repairSuppFilesFilestage
	#3220: fix migrateTimedViewsUsageStatistics
	#3228: Non-anonymized reviewer files not able to be deleted
	#3232: Manual payment plugin throws PHP Warning:  Missing argument 2 for Form::setData()
	#3237: Crossref as-crawled URLs should only include PDF galley URLs (if multiple formats are published)
	#3246: Update copyrights for 2018
	#3247: UI: reviewer page submission details - unnecessary information
	#3252: Getting section editors results in db error
	#3255: Ensure that upgraded reviews from OJS2 are double-blind
	#3267: NavigationMenus Site-wide unable to drop NMIs into empty NM edit areas.
	#3269: CSL Plugin doesn't display abbreviated journal title for AMA style
	#3273: When logged in, edit link on the announcement page is not working properly
	#3274: Redirect URI from Login as
	#3276: Native XML import fails on batch insert
	#3282: Missing navigation menu item for the search page
	#3283: Display usage statistics for last 12 months instead of for current year
	#3287: "User" and "Primary" (navigation menus management tools) are confusing
	#3288: "Custom Page" should not be default when adding a new navigation menu item
	#3289: Author `user_group_id` upgrade `UPDATE` is broken
	#3302: File upload gets stuck with certain language selections in multilingual journals
	#3311: "Subject" / "subjects" field "required" flag not behaving as expected
	#3318: Check minimum requirements before allowing to upgrade
	#3323: fix detachment of dependent entities at file revision upload confirmation
	#3329: Copyright Info with CC License Badge
	#3332: consider missing submission file in usage stats loader
	#3334: fix listing of successfully imported submissions
	#3336: External feed plugin obliterates custom blocks when enabled
	#3338: If html part of mail too long, new line with exclamation mark is inserted
	#3348: article DOI in native import
	#3357: Disciplin element should be discipline
	#3359: recommendOnly editor and section editor
	#3374: Dropdown nav menus in default theme don't work for rtl languages
	#3379: Article subtitles should appear in the issue TOC
	#3383: no context in LazyLoadPlugin get/setEnabled when using CLI
	#3385: Desisting from adding a new discussion leaves behind an empty discussion
	#3387: Remove gender fields
	#3390: upgrade email templates
	#3392: current release contains potentially dangerous old version of PHPMailer
	#3398: Section Editor assignment creates duplicate Pre-Review Discussion entries
	#3407: doubt about a translation
	#3412: RSS buttons left-over from OJS 2.x
	#3415: getTemplateResourceName for plugins in pkp-lib
	#3416: sr_SR migration to either sr_RS@latin or sr_RS@cyrillic
	#3420: Date issues for non-default date_format_short in reviewDueDate and responseDueDate
	#3421: Editing roles for a user in one journal destroys roles in others
	#3422: OJS 3.1.0.1 adding a participant with Safari does not close the modal window
	#3436: "Send to Review" and "Send to Production" for reccomendOnly users
	#3440: Even if you check "Do not send email" for notification, you receive email.
	#3443: Duplicate translation keys in en_US
	#3444: Multilingual custom email template does not apply to email body
	#3447: Task list shows too long
	#3448: Submission listings only show title for selected locale
	#3459: sitemap fix
	#3474: Restrict SubmissionFileRequestedRevisionRequiredPolicy to revision files only
	#3481: submission URL in recommendation form emails
	#3485: Missing sidebar items after upgrade from OJS 2.4.x with PostgreSQL
	#3488: Improve error presentation in file upload wizard
	#3491: Use mbstring-capable regexp functions in searching
	#3495: Modify API URLs in ui-library when restful_urls enabled
	#3506: Untranslated locale key for scheduledTaskLogs log file
	#3509: DataCite export plugin sets accepted date = submitted date instead of actual accepted date
	#3510: display last revisions of reviewer files
	#3517: require locale component for identifier tab, add a hook
  
  
  ## ojs-3.1.2
   
  ## New Features
  
	#1922: Add support for catalog paging
	#2422: [OJS 3.x] Notify user when email sending fails?
	#2438: [OJS] Editors should be able to add attachments to the Editorial Decision message
	#2805: Add opt-out settings for issue publish and announcements notifications
	#2820: Improve internal submission data reporting
	#2887: Add quick actions from submissions list
	#2958: Make author names multilingual
	#3575: Add a consent statement configuration option
	#3594: Implement form support in Vue.js/REST API
	#3600: Make reader and author registration optional / opt-in
	#3601: Extend internal articles report round 1
	#3691: Add default styling for HTML galleys
	#3673: Port article usage stats to master
	#3750: enable manager roles to add references during a submission
	#3770: Reduce the number of new submission notification emails for editors, and simplify their management
	#3779: possibility to set ssl version in WebService
	#3803: integrate new Crossref deposit and submissionDownload API
	#3812: possibility for plugins to add user and author metadata
	#3860: Allow to connect on custom ports / socket
	#3878: import/export of HTML galley images
	#3941: Permit dependent files in other areas of the workflow
	#4158: Allow JEs to assemble published articles into thematic collections
	#4164: Support generating DMARC compliant mails
	#4200: Permit deletions from the Copyedited grid
	#4294: consider article covers in native export and import

## Bug Fixes

	#1116: setLocale ignores source parameter if HTTP_REFERER exists
	#1619: Block adding discussion to oneself only
	#1783: Review Form Preview
	#1904: Closing ?> tags - you know you can give up on them
	#1908: Fix/resolve LOCKSS registration/manifest/plugin
	#2297: [OJS] The current role does not have access to this operation -message needs more details on how to acquire the needed role
	#2359: Improve "Required" field labels on review forms
	#2481: Reviewer has access to manuscript after declining review request
	#2638: Section policies are not displayed anywhere
	#2976: Open Review enhancements in OJS/OMP
	#3016: supplementary files migration
	#3171: [OMP] Navigation menu items for new releases, categories and series
	#3206: Subscriptions page should not be accessible if payments are not enabled
	#3242: Upgrade Smarty to v3
	#3282: Missing navigation menu item for the search page
	#3318: Check minimum requirements before allowing to upgrade
	#3403: Error 404 when addNavigationMenuItem
	#3404: Review dependency management
	#3462: Refine password element for user import (and possibly export)
	#3483: OJS Non-expiring subscription type does not work
	#3536: Don't display Review Form selection in Section settings when no review form exists
	#3543: both editor actions "Accept and Skip Review" and "Accept Submission" are logged as "(Accept and Skip Review)"
	#3556: getTemplatePath basePath
	#3563: place sr_SR migration before files migration
	#3565: [OJS 3.1.1] missing string editor.article.coverImage (all languages)
	#3570: Localization key typo
	#3573: Change database tables schema for Clustering
	#3578: Clean code for PHP 7
	#3580: UsageStatsOptoutBlockPlugin is not displayed
	#3589: [OJS3] API parameter year for issues does not work after update to 3.1.1.0
	#3590: When a reviewer decline an invitation, he/she is still flagged as having 1 active submission
	#3593: issue galley locale required validation
	#3597: remove double SQL for metrics supp file migration
	#3608: edit review assignment to add review form
	#3609: Keywords and Agencies metadata: when one of the two is mandatory
	#3611: [OMP-3.1.1.0] Payment send notification of payment Fatal error
	#3617: Investigate SQL Server support for OJS
	#3619: [OJS] Uploading supplementary file revisions fails in some circumstances
	#3622: OJS 3.1.1 Submission Library upload link error
	#3637: User notification form crashes in site-wide context
	#3638: Suggested username removes accented character
	#3640: remove viewInformationCenter link on the submisison step2
	#3653: [OJS 3] Author cannot upload revised article as a new version
	#3655: Locale strings for API errors don't seem to be getting translated
	#3662: Obfuscated access restriction for site administrator
	#3666: Section Editor assigned as an Author (only) can access discussions that they are not participants in
	#3672: [OJS] reviewer history is not ordered by date
	#3694: datacite and medra registered status migration
	#3705: Unable to Order back issues
	#3706: [OJS] Missing galley file breaks Crossref automatic deposts
	#3710: remove translations for unused plugins folders
	#3715: Navigation Menus - Add site-wide primary navigation menu
	#3720: [OJS] clarify language on DOI/DOAJ registration
	#3723: "Subeditors" are not introduced to users
	#3741: [OJS 3.1.1] when a submission enter to review stage the files are duplicated
	#3744: Upgrade OJS 2.4.8.1 to 3.1.1.0 supplementary files lost for active submissions
	#3749: Fix wrong assoc_type in citations upgrade
	#3754: Passing invalid sort parameter executes malformed SQL
	#3765: README file: update localization information
	#3773: Correct SQL ordering for payment check
	#3784: consider site primary locale and the submission locale change
	#3785: Correct missing escaping of template variable
	#3792: Update list separator locale key
	#3796: Correct missing locale key in OJS "log.review.reviewUnconsidered"
	#3802: Multiple duplicate names in "Enroll existing user" as reviewer search field
	#3807: Submission searching is case-sensitive in postgresql
	#3809: [OJS 3.x] Journal E-Mail Signature lost in migration from 2.4.8.2
	#3810: Can not edit review assignment
	#3811: Merge the user generates problems in the submission if he is a participant in the discussions
	#3820: file_type of newly uploaded JATS XML
	#3826: Resolve missing GROUP BY in submission list fetch
	#3834: Login page for disabled contexts not available
	#3836: Privacy consent statements error in registration form multi-journal install
	#3837: do not display references input field in the metadata modal submission tab
	#3845: Respond to requests for nonexistent journals with a 404
	#3846: NavigationMenu Feature - Locales for default NMIs retrieved from key and not database
	#3851: Ask two times a revision in a review round failed
	#3864: book double listed in a series, when ordered by title
	#3868: lib/pkp/tools/installPluginVersion.php fails with SetCharSet() error
	#3870: Reviewers can't complete step 1 of the review process due to privacy consent error
	#3871: submission.title untranslated in review reminder form
	#3873: Allow extended locale names in import/export XML
	#3874: Clean up overspecific/wrong subtitle language
	#3876: issue galley public identifier should not be required
	#3881: Disabled users receive notifications
	#3889: Remove PHPUTF8 library
	#3892: Check downloadability of submission files from the submission history
	#3893: [OJS] Running crossref scheduled task with Acron gives headers already sent error
	#3894: Ensure overdue status of review assignments is calculated the same in all places
	#3922: purchaseInstitutionalSubscription template: change page container element class
	#3926: [OJS] Review form elements grid, Order feature does not work
	#3929: purchaseInstitutionalSubscription template doesn't contain footer
	#3930: do not change the sequence of published articles when editing the "Schedule For Publication" form
	#3933: Issues with pages related to subscription
	#3935: reload submission after saving the Schedule For Publication form
	#3936: Cannot edit review assignment due date
	#3944: JSON responses do not consistently set content-type to application/json
	#3949: Consider extending Smarty class rather than SmartyBC
	#3950: HTML 5 compliance
	#3959: Duplicate role assignments can prevent submission from being displayed in lists
	#3967: Latest compatible plugin release is not recognized in plugin gallery
	#3980: SectionForm class: data property assignment through a method
	#3984: Search index helpers don't work with spaces in filenames
	#3989: Enable one-click reviewer access by default
	#3996: HTML image URLs with special characters do not work
	#4005: [OJS] Turkish locale update
	#4006: Enable assistants like copyeditors and layout editors to edit article metadata
	#4009: Usagestats not being processed if contextPath collides with "article"
	#4011: [OJS] Custom blocks not displayed in settings page after upgrading from OJS2.4.8 to 3.1.1.2
	#4014: Option to use a global sender address for emails (to fight spamfilters?)
	#4024: Ensure RoleBasedHandlerOperationPolicy is used where addRoleAssignment is used
	#4025: remove "STATISTICS_MAX_ROWS limit for stats downloads
	#4026: [OJS] Reviewer step 1, privacy consent error message is displayed as ##...##
	#4036: Reviewers receive a 0 rating when a review assignment is accepted
	#4043: [OJS] lib/pkp/tools/buildjs.sh is not working in Windows Subsystem for Linux / Debian
	#4046: [OJS] Review form elements, proposal for a description field
	#4048: Alt text for journal thumbnail is not used on site index page
	#4057: Remove misplaced/unwanted DC11 locale files
	#4061: Remove reference in Plugin::register() method argument
	#4070: Uploading revisions creates an incomplete email_log entry
	#4072: Submission metadata form: pressing save button triggers browser errors
	#4074: Access denied when trying to access some editorial/JM functions
	#4084: Bad template calls in master branch OAI metadataformats
	#4116: [OJS] GatewayHandler setupTemplate() missing parameter
	#4120: CSRF token missing for enable plugin action
	#4125: Subscriptions list is slow to load and does not apply row limit
	#4126: [OJS 3] Clarify reviewer state in ReviewerGrid
	#4131: Make OJS2 to OJS3 metrics upgrade faster on large installations
	#4133: Fix review assignment updated notification recipient
	#4146: Bad composer syntax
	#4147: Prevent review form radio button preselection
	#4149: Enrich OAI-PMH options for journals that do not publish online
	#4157: Empty query lingers after closing new query modal
	#4163: pkp/pkp-lib#4157 Handle cancel action on reload/click-away
	#4168: Add filter by last modified more than X days ago to submissions lists
	#4171: All authors are listed as "First" in Crossref Metadata
	#4179: [OJS] delete a note with a file in a query cause error 500 for editorialhistory
	#4182: Modals can disappear in RTL languages
	#4185: [OJS] Update Italian translation
	#4208: Replace tag-it library with something else
	#4212: PKPTemplateManager::initialize() redundant variable
	#4214: [OJS 3.1.1.4] Translation keys might be confused for some locales (navigation.submissions & about.submissions)
	#4215: [OJS] IssueEntrySubmissionReviewForm, missing parameter in execute hook call
	#4216: Expiry date announcements editing not work
	#4236: Remove email from DOAJ export
	#4242: keywords missing via OAI
	#4243: Errors unclear when Plugin upload fails
	#4248: References set to null
	#4263: No user for some reviewer actions in a submission event log
	#4264: Autosuggest for keywords metadata entry returns languages
	#4266: Reviewers do not have access to files uploaded in review discussions
	#4268: [OJS] Required asterisk missing
	#4271: Disable "membership required" checkbox for institutional subscription types
	#4277: Resolve "too few arguments" exception in OMP Series grid
	#4282: OJS 3.1. Files uploaded to to discussion show up in Copyediting under Upload/Select files
	#4287: Upgrade provideSupplementaryFilesForReview fails with "Invalid file!"
	#4293: Distinguish the user's URL field from the ORCID field
	#4295: JournalManager/Author metadata edit error: "Please enter the references."
	#4306: PublishedArticleDAO::getPublishedArticles calculates sort order incorrectly
	#4307: Make consent statements less "Canadian" / more declarative
	#4308: Privacy checkbox appears during submission even if no privacy statement exists
	#4311: [OJS] Licence badge not showing when referring https://creativecommons.org
	#4315: Description for radio buttons in appearance form is missing
	#4323: Add Smarty shim functions for theme compatibility
	#4328: Hook for adding columns to grids via plugin
	#4330: NotificationHandler, wrong handling of fadeOut callback causes unbindPartial exception
	#4332: [OJS] Section drop down is displayed with multiple required asterisks
	#4337: installer.miscSettings locale key undefined
	#4338: OJS 3 MetaData form freezes when required keywords missing
	#4340: Users in multicontext install are offered links to unprivileged contexts
	#4345: Declined submissions not moved to archive
	#4350: Crossref deposit status check doesn't make sense
	#4352: "Cancel" on "Are you sure you wish to leave the page" behaving badly
	#4370: Missing value in submission_settings index whitelist
	#4376: Unable to upload review revision
	#4381: Update copyright dates for 2019
	#4388: Relax administrator check for mailing users
	#4390: counter bot list not properly cached and used with PHP 7.2
	#4398: User Import tries to assign user groups without a user id
	#4401: Use full title for Google Scholar metadata
	#4403: consider case-insensitive bot match
	#4411: OMP category pages show duplicated published items
	#4413: Custom Page can't be saved if disable_path_info is set to on
	#4428: Permit API key to be used for content exposure (OAI/article view)
	#4432: consider username and email import mismatch
	#4446: Support categories in default theme
	#4455: use COUNTER bot list instead of botAgents.txt
	#4462: Context navigation menu entries can be blank
	#4478: Site-level browse block prevents display of other blocks
	#4482: Web feed plugin includes untranslated copyrightStatement locale key
	#4487: Rewrite phpMyVisites plugin for OJS/OMP 3.x
	#4489: Paypal plugin missing link to settings modal
	#4491: Navigation Menus - Custom Templates not available
	#4495: Navigation menu - title missing when editing item
	#4497: Distribution Settings do not save
	#4503: [OJS] Update nl_NL locale
	#4514: [OJS] Recoginze https URL to Creative Commons licenses
	#4522: Correct missing escaping of template variable
	#4542: Public URL Identifier breaks with a slash character
	#4547: "Create Reviewer" reviewer selection option breaks email template
	#4561: Fix Google Scholar plugin enabling on upgrade
	#4562: Hide edit/delete/upload link actions for galleys from authors
  
  
 
  ## ojs-3.2.0
  
  ## New Features

	#2072: [OJS] Versioning for published articles
	#2096: Add support for rtl locales
	#2438: [OJS] Editors should be able to add attachments to the Editorial Decision message
	#2508: Improve editor control over reviews
	#2820: Improve internal submission data reporting
	#2906: Improve Email Templates View
	#3594: Implement form support in Vue.js/REST API
	#3673: Article usage stats
	#3758: Selectively permit author metadata changes after submission
	#3803: integrate new Crossref deposit and submissionDownload API
	#3817: Add option to display journal summary on homepage
	#4149: Enrich OAI-PMH options for journals that do not publish online
	#4158: Allow JEs to assemble published articles into thematic collections
	#4683: Add option in default theme to use homepage image as header background
	#4772: Permit the "merge users" CLI tool to handle multiple users at once
	#4779: Replace bespoke translation toolset with more standards-based options
	#4844: Implement internal Editorial Report UI and algorithms
	#4867: Support publications/versioning for DOIs and verify depositing
	#4870: Support versioning in the reader interface
	#5085: Add proxy support to plugin gallery
	#5277: Add "Obsolete version" notice to PDF viewer when new version available

## Bug Fixes

	#1116: setLocale ignores source parameter if HTTP_REFERER exists
	#1375: [OJS] Updating issue without volume results on 0 on database
	#1403: Redirect to the current page after Login As
	#1908: Fix/resolve LOCKSS registration/manifest/plugin
	#2071: [OJS3] Create new issue stalls when volume number is not an integer
	#2294: [OJS] Returning to search from a search result leads to an expired document
	#2353: Test migration of ADODB to Composer dependency
	#2428: [OJS] CSRF token validity time (one hour) breaks the review form
	#2617: Add counts of submissions to submission tabs and list filters
	#3248: [OJS] submission emails: signature information is slightly duplicated
	#3330: [OJS] Payments need to be enabled to change the length of journal embargo
	#3340: Add timestamp to CSS and JS files for when they are built
	#3381: Problems scrolling PDF/HTML galleys in iOS
	#3386: [OJS 3.1] Declined submissions not appropriately highlighted as such
	#3439: [OJS] Institutional Subscription creation form "domain" field requirements need minor tweaking
	#3535: Section settings heading "Indexing" is not clear to end-users
	#3691: Add default styling for HTML galleys
	#3697: Improve / correct manuscript status in submission list for editors
	#3770: Reduce the number of new submission notification emails for editors, and simplify their management
	#3784: consider site primary locale and the submission locale change
	#3831: Can't override core templates
	#3910: Section editors can not access comments to editor discussion
	#3948: [OJS] webfeed Plugin rss2 missing XML namespace and date time issue
	#4021: Article subtitles not showing in "how to cite"
	#4054: Overridden plugin templates in theme not shown in child theme
	#4097: [OJS] Fix for #3705 breaks archives with PostgreSQL
	#4164: Support generating DMARC compliant mails
	#4168: Add filter by last modified more than X days ago to submissions lists
	#4204: Add hostname checking for ReCAPTCHA
	#4213: After thanking, reviewer decisions is not seen on Review page
	#4214: [OJS 3.1.1.4] Translation keys might be confused for some locales (navigation.submissions & about.submissions)
	#4215: [OJS] IssueEntrySubmissionReviewForm, missing parameter in execute hook call
	#4228: Limit the number of revisions uploaded messages received by editors
	#4273: [OJS] Missing breadcrumbs in static page
	#4282: OJS 3.1. Files uploaded to to discussion show up in Copyediting under Upload/Select files
	#4293: Distinguish the user's URL field from the ORCID field
	#4308: Privacy checkbox appears during submission even if no privacy statement exists
	#4319: Javascript error on plugin activation/deactivation: row with id not found
	#4320: [OJS] Bad placement of error messages for check-boxes
	#4323: Add Smarty shim functions for theme compatibility
	#4325: Update PubMed export based on NLM feedback
	#4328: Hook for adding columns to grids via plugin
	#4330: NotificationHandler, wrong handling of fadeOut callback causes unbindPartial exception
	#4332: [OJS] Section drop down is displayed with multiple required asterisks
	#4337: installer.miscSettings locale key undefined
	#4338: OJS 3 MetaData form freezes when required keywords missing
	#4340: Users in multicontext install are offered links to unprivileged contexts
	#4341: quell array/variable warning in template
	#4345: Declined submissions not moved to archive
	#4350: Crossref deposit status check doesn't make sense
	#4352: "Cancel" on "Are you sure you wish to leave the page" behaving badly
	#4370: Missing value in submission_settings index whitelist
	#4375: ajaxOptions deprecated in recent releases of JQuery/JQueryUI
	#4376: Unable to upload review revision
	#4383: Hook for service registration in a plugin
	#4388: Relax administrator check for mailing users
	#4390: counter bot list not properly cached and used with PHP 7.2
	#4398: User Import tries to assign user groups without a user id
	#4401: Use full title for Google Scholar metadata
	#4403: consider case-insensitive bot match
	#4410: Catalog Category page: $total variable is always 0
	#4411: OMP category pages show duplicated published items
	#4413: Custom Page can't be saved if disable_path_info is set to on
	#4414: Context path property creates conflict when disable_path_info is enabled
	#4428: Permit API key to be used for content exposure (OAI/article view)
	#4432: consider username and email import mismatch
	#4446: Support categories in default theme
	#4455: use COUNTER bot list instead of botAgents.txt
	#4469: Site contact email saved without locale during installation
	#4478: Site-level browse block prevents display of other blocks
	#4482: Web feed plugin includes untranslated copyrightStatement locale key
	#4487: Rewrite phpMyVisites plugin for OJS/OMP 3.x
	#4489: Paypal plugin missing link to settings modal
	#4491: Navigation Menus - Custom Templates not available
	#4495: Navigation menu - title missing when editing item
	#4497: Distribution Settings do not save
	#4514: [OJS] Recognize https URL to Creative Commons licenses
	#4522: Correct missing escaping of template variable
	#4532: [OJS] Minor mistake in notification message when removing a plugin
	#4533: [OJS] Duplicated content when submitting an invalid plugin's settings form
	#4545: Upgrade PHPUnit/Selenium/WebDriver testing toolset
	#4547: "Create Reviewer" reviewer selection option breaks email template
	#4556: Auto-assign editors to discussions that they reply to
	#4557: Images without alt text should have alt set to null
	#4561: Fix Google Scholar plugin enabling on upgrade
	#4562: Hide edit/delete/upload link actions for galleys from authors
	#4570: OJS 3.1.2 Empty section policy in submission step 1
	#4573: Ensure that OAI is enabled by default for new journals
	#4575: Autocomplete inputs (e.g. OMP 3.1.2 Add spotlight feature) are broken
	#4580: [OJS] OJS 3.1.2 Wrong header in default/styles/pages/indexSite.less
	#4590: No parameter substitution in email after selecting another template
	#4593: Catalog Category page: article galleys require payment/subscription but are open
	#4597: Remove exclusion of necessary library
	#4600: Custom theme not work on  OJS 3.1.2
	#4601: [OJS] orcidProfile Plugin: ORCID integration in User Register form broken
	#4602: [OJS] Review form problem : authors can always see the entire review form
	#4607: Cannot edit discussions
	#4608: Syntax error on SQL for PostgreSQL on Submission searching
	#4612: Possible hook regression from function signature changes
	#4613: authorName parameter unreplaced in NotifyForm
	#4615: Adjust for GROUPS becoming a reserved keyword in MySQL 8
	#4618: OJS Reset Article Permissions action is unclear
	#4619: Add citation_reference tags to GoogleSchorlaPlugin output
	#4625: No assignment for copyeditor/layout editor/proofreader after upgrade
	#4632: Remove deprecated support for static calls to Request functions
	#4642: Workflow sidebar is crunched on large screens
	#4649: Email validation breaks registration page
	#4654: Resolve assert() failure for journals without a saved copyright basis setting
	#4656: [OMP] Reviewer selection is not restricted to review stage
	#4675: [OJS 3.1.2] When switching to english language name and given name of users are not displayed
	#4678: [OJS 3.1.2] Use english help manual by default if local language has no manual
	#4680: {$submissionTitle} email variable should include full title
	#4682: Audit the default theme for skip links
	#4684: Add mobile-friendly header and nav menu to default theme
	#4688: Fatal error with method signature changes in PublicFileManager
	#4691: Fix PostgreSQL-incompatible quoting
	#4702: Create new reviewer "suggest username" button is broken
	#4705: Fix issue cover image size in default theme
	#4709: Navigation Menu Item Edit - Custom NMIs lose title after submitting form with same title
	#4713: Search default's today's date as Start Date / End Date
	#4714: Clean up SubmissionSearchIndex class hierarchy
	#4722: PKPString and Stringy\Stringy objects
	#4726: Event log lists {$submissionId} without replacement for OJS 2.x-sourced submissions
	#4727: Dead code hunt (Sprint 2019)
	#4738: pkp-lib/templates/frontend/pages/privacy.tpl - move breadcrumb out of div
	#4743: pt_BR manager.xml locale string missing closing ]]>
	#4754: Unable to Upload/Select Files from Copyediting stage
	#4756: Adding a Custom Page NMI with a slash in the path fails on display
	#4765: Import of issue from XML using native plugin may lead to several "current" issues
	#4784: [OJS] Missing the role of author when listing participants
	#4788: Validation broken on front end institutional subscription purchase form
	#4803: Hook PluginRegistry::loadCategory is ineffective for category jumping
	#4804: Error on upgrade: You can’t specify target table ‘submission_settings’ for update...
	#4812: sv_SE locale key for submission.license.cc.by-nc4.footer duplicates logo
	#4823: PostgreSQL-incompatible SQL on upgrade: INSERT metrics
	#4830: [OJS] Reviewing interests "tagit" results not styled properly on registration
	#4833: Favicon does not work in OMP
	#4842: Ensure 3.2 settings forms interact well with PLN plugin
	#4854: [OJS] First letter displayed in search Author Index
	#4856: Test the database migration to split submissions and publications
	#4857: Final workflow UI improvements for versioning
	#4859: Update search and search indexing for versioning
	#4861: Migrate support for cover images to publications
	#4866: Manual payment form action leads to 404
	#4868: Check that author details are not exposed to reviewers
	#4872: Clarify filesystem implications of CLI upgrade
	#4873: Implement proper file management for galley versioning
	#4874: Implement access control for the publication tab features
	#4877: Support previewing of metadata in the author/reviewer workflows
	#4880: Implement support for publications in XML import/export
	#4881: Remove galleys endpoint in submissions API
	#4882: Document API changes for publications
	#4883: Support versioning for the subscriptions/payments features
	#4886: Finish GalleyService features
	#4890: Selectively expose TinyMCE controls
	#4896: Ordering of sidebar blocks changed upon visiting the settings form
	#4905: Support exporting of pub ids after removal of PublishedSubmissions
	#4906: Remove published_submissions dependency in OAIDAO
	#4915: Reviewers' identities visible to other reviewers in discussion
	#4924: Article access status does not change when individual article or issue purchased
	#4936: Send database debug messages to the log rather than the browser
	#4939: Upgrade Issue: Table `email_templates`
	#4944: languages.xml is missing in some translations
	#4945: [OJS] Prefix fallback in article title
	#4948: [OJS] More accurate name for Site Navigation region's Search region
	#4949: [OJS] Search results should return a List
	#4951: npm audit messages
	#4953: lib/pkp/tools/installPluginVersion.php install data issue when running from command line
	#4978: Issue galleys have bullet points in default theme
	#4979: Installation form loops if an administrator username is specified with upper-case characters
	#4982: Typo in locale key "grid.action.deleteNotification" (or invalid LinkAction ID)
	#4984: [OJS] Notifications/tasks popover being displayed unexpectedly
	#4985: [OJS] Right clicking on an action of the notifications popover is executing it
	#4988: variable {$submissionLayoutUrl} not replaced
	#4989: "Review Options" choice not taken into account for individual review
	#5000: Fix submission language/languages metadata
	#5003: [OMP] Jquery missing 3_1_2-1
	#5006: [ojs 3.1.2] OpenAIRE plugin bug
	#5010: [OJS 3.1.2] some events are not logged
	#5011: getLocalizedSubject call generates fatal error in ArticleSearch class
	#5015: Languages block uses wrong `lang` attribute value.
	#5017: Submission subtitle not being stored in CrossRef
	#5021: Subscription grid search options are very limited
	#5023: Obsolete constant STATISTICS_DIMENSION_ARTICLE_ID causes warnings
	#5027: Cannot upgrade plugin via upload that was previously present but is no longer
	#5029: Bump PHP baseline
	#5042: Fix chapter ordering after versioning changes
	#5043: Consider upgrade script to reset submission status
	#5044: Implement scheduled publishing of individual articles/books
	#5045: Improve the pre-publication message in the new publishing workflow
	#5046: Allow publications to be "unpublished"
	#5047: It should not be possible to add a galley to a published version
	#5055: AuthorDashboard broken in master branch
	#5056: Submission email logs not always presented on Windows systems
	#5057: Wrong mEDRA endpoint TEST web service on OJS mEDRA Export Plugin
	#5063: XHTML files reported as text/xml on upload
	#5068: Native article import/export can't handle floating point sequences
	#5087: Categories input field appears even if no categories exist
	#5089: "No Section Editors
	#5098: Controlled vocab suggestions lead to slow load times
	#5103: Remove sexist language
	#5120: Citation URLs do not extract well with trailing periods
	#5122: Support iteration for DAO results
	#5127: Remove default count in query builder arguments
	#5138: [OJS] plugin metadata dc11 : maybe a typo
	#5139: Custom block plugin not working
	#5146: Missing hook call for submissionfilesuploadform::execute
	#5169: Update Custom Locale Plugin for .po file support
	#5170: Status modification date incorrectly stamped instead of modification date in event log
	#5175: Fix use of <h1> in header
	#5177: Issue archive pages should add headings to issue titles
	#5179: Article landing page should adjust heading levels hierachy
	#5201: pkp/pkp-lib#4919-fix Rewrite Slim routing using PATH_INFO
	#5208: Support publications/versioning for URNs and verify depositing
	#5216: Update in-app help for 3.2
	#5219: References added during submission are not stored with the publication
	#5234: Recommend-only editors should not be allowed to publish a publication
	#5236: "Journal Entry" tab name is confusing
	#5240: Skip links and anchors in the default theme should appear within landmarks
	#5248: 'reportxml.tpl' template don't found in OJS3
	#5255: Plugin upload from the gallery fails if package url contains whitespaces
	#5256: Bug in RoleDAO::getUsersByRoleId
	#5261: Upload of SVG images fails
	#5264: Crossref temporary deposit file name too long
	#5269: Missing GROUP BY in UserStageAssignmentDAO::filterUsersNotAssignedToStageInUserGroup causing paging problems in add participants grid
	#5276: CSRF token is included in GET request in the search form
	#5285: [OJS] Stop collecting user IP to email and event logs
	#5302: Use json_encode/json_decode instead of serialize/unserialize in report generator
	#5318: Default theme option to show journal description should say journal summary
	#5323: Adjust Travis testing for PHP7.3/PHP7.4
	#5329: Fix fatal error with PN settings
	#5332: Untranslated locale keys presented on sidebar from issue management
	#5354: Introduce interface for entity querybuilders
	#5355: Add confirmation prompt when creating a new version
	#5356: Use human-friendly numbers for versions
	#5358: Authors without sequence cause fatal OMP error when creating a new version
	#5362: Monthly scheduled task can be fired multiple times in a day
	#5372: Extend XML native import/export plugin to support alternatives to embedding
	#5374: Port integration testing framework to Cypress
	#5379: Remove deprecated/broken plugins
	#5382: Hooks for extending notification settings
	#5385: New issue notification can go to disabled users
	#5397: Strange folders in pkp-lib code
	#5398: Custom date ranges in statistics report generator ignored
	#5407: Use v-cloak to hide unstyled content flash before Vue kicks in
	#5408: Payments tab does not appear when payments are enabled in settings
	#5417: DC OAI interface does not include authors
	#5419: Payment settings form does not allow selection of single active payment plugin
	#5420: [OMP] Can't save featured and new releases in catalog entries
	#5423: CSS file upload error when saving
	#5427: Saving the Crossref plugin settings seems to hang, but in fact completes
	#5428: Publication > Permissions & Disclosure fields aren't prepopulated
	#5430: Refine "Public URL Identifier" availability and behaviour
	#5431: "Save" button is not available for my own submission's Publication tabs
	#5433: Editorial Activity page is broken - PHP syntax error
	#5434: Users report unavailable - PHP Fatal Error
	#5435: Improve DAO annotation for PHP Scrutinizer
	#5437: Call to nonexistent function SubmissionDAO::deletePubId
	#5438: Submission sequence no longer appears to be supported
	#5441: Review all in-app help links before 3.2 is released
	#5442: AuthorDAO::getPublishedArticlesForAuthor fails when executed from author search index
	#5449: Author list does not work
	#5450: Ensuring Blind Review directions need updating
	#5453: Replace homegrown country, language, and currency codes with a 3rd-party library
	#5460: Subscription reminder emails not being sent
	#5461: Resolve redundant email template XML files
	#5467: Archived submissions no longer show Published or Declined
	#5468: The context setting copyrightHolderOther should be multilingual
	#5469: Publication stats API doesn't account for earliest recorded statistic
	#5470: Publication stats table is not sorted by total stats
	#5471: Submitting file to Submission Library overwrites Publisher Library files
	#5473: [OJS] Assign DOIs action in DOI plugin broken
	#5474: [OJS] DOI status functions broken in Crossref plugin
	#5482: Newly assigned editors are not permitted to edit metadata
	#5483: [OJS] Published After and Published Before filters in search have every year from 0 to 2020
	#5486: & characters in PubMed exports are not escaped properly
	#5487: Some fields appear to be required in all languages
	#5488: Update copyright dates and license info
	#5507: Import plugin's check for local file paths is defective
	#5522: Link in journal health report task notification may be wrong
	#5525: Category nesting not reflected in submission form, OJS
	#5526: Selected value not loaded in Vue FieldOptions component
	#5534: Announcements do not appear after enabling
	#5537: Submission::getViews() method missing
	#5544: urlPublished refers to article in pkp-lib
	#5546: Fatal error when retrieving issues with galleys from API
	#5550: Fatal error due to changes in SettingsDAO
	#5553: Abstract length error message includes Array instead of correct length
	#5560: Files for old versions don't load
	#5563: Possible to access unpublished articles when not logged in
	#5569: Fix OJS 2.x to 3.x upgrade
	
	
	
	
  
 ## ojs-3.2.1
 ## New Features
	#5886: OMP site wide search
	#5784: [OMP] Site index should list all presses
	#5744: Add Noto font for Arabic characters
	#5703: Improve upgrade performance
	#5694: Allow subeditors to be assigned to Categories
	#5601: Add range slider for filter by last activity in submissions list
	#5190: Add TITLE parameter to IFRAME of article galley view
	#5177: Issue archive pages should add headings to issue titles
	#4888: Write integration tests for versioning features
	#3698: Support a "draft" option for reviews

 ## Bug Fixes

	#6026: Submission deletion can delete author records in other submissions
	#6022: PostgreSQL upgrade to 3.2.0 resets all submissions to unpublished
	#6000: Undefined const SCHEMA_PUBLICATION during upgrade
	#5977: Fatal error viewing HTML publication format in OMP
	#5974: TinyMCE can not be loaded in sr_RS@cyrillic locale
	#5967: SQL error on 3.2.0->3.2.1RC upgrade
	#5961: enabling crossrefReferenceLinking (even master branch) makes doi disappear
	#5933: [OPS] Editorial Statistics "Active Submissions" don't match actual number
	#5923: PostgreSQL 12 not properly supported
	#5920: Native ImportExport Plugin: Importing a localized publication causes an error
	#5907: CrossRefExportPlugin Article Search not filtering by `Status`
	#5903: Reorder OPS archive/browse handlers
	#5876: OJS3.2 Editorial activity stats counting submissions from removed journals
	#5872: Update Cypress and vue-cli to address warnings
	#5869: Clean up plugin installation error handling
	#5862: Resolve double slash in file paths during upgrade
	#5860: Multilingual form fields do not show primary locale on initial load
	#5856: Review Form not getting the correct title and description
	#5837: Publication and Submission State inconsistency
	#5833: [OMP] Order catalog by series position leads to database error
	#5813: Logged out users directed to site homepage instead of journal homepage when logo is present
	#5801: Recommend by Author Plugin duplicates entries
	#5796: Metadata sections in submission form
	#5791: Vue js error after choosing a file for uploading
	#5789: H1 for screen readers not available in Site level if site logo is given
	#5781: Optionally suppress SMTP authentication in PHPMailer
	#5698: Update the citation library to solving the citation problem.
	#5695: OJS - Extra space below empty submission list
	#5693: ValidationFactory reports required fields with value "0" as invalid
	#5640: Language installation features hidden from single-journal installations
	#5633: FormComponent subclasses, even when invoked via the API, require CSRF tokens
	#5631: Mismatch between datePublished and issue scheduling can cause problems
	#5630: Unscheduling a publication does not update the issue scheduling field
	#5617: Themes shown when installed, even if they are not enabled
	#5585: Update syntax for draggable options
	#5533: Unclear language for setting to allow participants to edit metadata
	#5532: Editors fail to schedule for publication
	#5373: Unported CC licenses 3.0
	#5288: Performance issue using LIMIT and OFFSET in search users query
	#5273: User validation email references {$contextName}, which is not resolved before sending
	#5265: Crossref error message is not translated
	#5240: Skip links and anchors in the default theme should appear within landmarks
	#5186: Add aria-required to register and login forms
	#5176: Sidebar blocks should always have a heading and section
	#5175: Fix use of <h1> in header
	#5095: Workflow participants receive more than one email about the same thing
	#5061: [OJS 3.1.2-1] Crossref module: Language of all metadata EXCEPT author names depends on submission language (author names depend on locale chosen)
	#4746: Announcement notification email should include the announcement content
	#4042: Editorial history should save the datestamp when a new review round starts
