Available Grammar
=================
  - `@TODO`: Something to be done
  - [`@FIXME`](#bug-report): Bug Report, should be corrected, Marked with :bug: Commit
  - `@CHANGED`: Version Changes together with `@SINCE` DocComment, _Usually_ Marked with :fire: or :zap: Commits
  - `@XXX`: Warn other programmers of problematic or misguiding code
  - `@IDEA`: A New Idea or Proof-of-Concept, Marked with :bulb: Commit
  - `@HACK`: Workaround or Customer Customizations, Marked with :ribbon: Commit
  - `@NOTE`: Add attention to something Important
  - `@REVIEW`: Needs to be Audited/Reviewed Immediately, _Usually_ Marked with :construction: Commit

Bug Report
----------
1. Add `@FIXME` Comment above SourceCode where Bug/Exception was Occurred.
2. Write Additional Information:
    1. Steps to Reproduce the Error
    2. `Exception` Message and Code
    3. Expected Result
    4. Actual Result
    5. Environment Detail
3. Mention the Task ID in Format `{T###}`.
4. (optional) Add Screenshots in Format `{F###}`(_Phabricator Specific_).
5. Commit the Comments(with :bug: Emoji), also include Items 2.B, 3 & 4 in Commit Message too.
6. Award that Task with `Manufacturing Defect` Token(_Phabricator Specific_).

Notes
-----
+ Do **NOT** edit Contents of `Vendor` files(Composer, Bower, ...).
+ Grammars Should Appear in a List/Window in Your IDE of Choice([PHPStorm](https://www.jetbrains.com/help/phpstorm/2016.2/defining-todo-patterns-and-filters.html)).
+ There Must be an Audit for this Bug(Commit) Appear in Phabricator.
+ These Kind of Bug Reports Remain in History of VCS for future References of that Scope of Code.
+ All Attached Files & Commit Reference HashTag will be Referenced in the Phabricator Task View.
+ These Audits May become Tasks Later.
