Available Grammar
=================
  - `@TODO`
  - `@FIXME`
  - `@CHANGED`
  - `@XXX`
  - `@IDEA`
  - `@HACK`
  - `@NOTE`
  - `@REVIEW`

Bug Report
----------
1. Add `@FIXME` Comment in SourceCode where Bug/Exception was Occurred.
2. Write Additional Information:
  1. Steps to Reproduce the Error
  2. `Exception` Message and Code
  3. Expected Result
  4. Actual Result
  5. Environment Detail
3. Mention the Task ID in Format `{T###}`.
4. (optional) Add Screenshots in Format `{F###}`.
5. Commit the Comments, also include Items 2.B, 3 & 4 in Commit Message too.
6. Award that Task with `Manufacturing Defect` Token.

Notes
-----
+ (WARNING) Do NOT edit Contents of `Vendor` files.
+ (NOTE) `@FIXME` Grammars Should Appear in a List/Window in Your IDE of Choice.
+ (NOTE) There Must be an Audit for this Bug(Commit) Appear in Phabricator & #todo Project.
+ (NOTE) These Kind of Bug Reports Remain in History of VCS for future References of that Scope of Code.
+ (NOTE) All Attached Files & Commit Reference HashTag will be Referenced in the Phabricator Task View.
+ (NOTE) These Audits May become Tasks Later.
