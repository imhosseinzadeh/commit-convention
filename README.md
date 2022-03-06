# commit-convention

instead of answering "what are the changes?", 
it’s better to answer "What are the changes for?" or "What happens if the changes are applied"?
--------------------------------------------
"subject"
use imperative, present tense (eg: use "add" instead of "added" or "adds")
don't use dot(.) at end
don't capitalize first letter
--------------------------------------------
"type"

feat – for a new feature for the user, not a new feature for build script.
Such commit will trigger a release bumping a MINOR version.

fix – for a bug fix for the user, not a fix to a build script.
Such commit will trigger a release bumping a PATCH version.

perf - for performance improvements.
Such commit will trigger a release bumping a PATCH version.

chore – changes that do not relate to a fix or feature and don't modify src or test files ,
a change that external user won't see
(eg: change to .gitignore or .prettierrc)

build – changes that affect the build system or external dependencies
(eg: change to pom.xml, application.properties, logback.xml)

refactor – for refactoring production code
(eg: renaming a variable.)

style – changes that do not affect the meaning of the code, likely related to code formatting
(eg: white-space, missing semi-colons, and so on)

test – for adding missing tests, refactoring tests; no production code change.

docs – updates to documentation such as a the README or other markdown files

revert – reverts a previous commit
