
_`How to encrypting Environment Variables`_
> _Docs references: https://docs.github.com/en/actions/security-guides/encrypted-secrets_
>
> _In Setting on Navbar of Repository -> Secrets -> Add Secrets key -> Actions -> Add Repository secrets_

_`What is gpg`_

_`Expressions & Contexts`_
> _Docs references: https://docs.github.com/en/actions/learn-github-actions/contexts_

- _GitHub context: information about your github_
- _Job context: information about your current job_
- _Steps context: reference to another steps in the step context (using step id)_
- _Runner context: information about your runner: virtual machine os, workspace,..._
- _Strategy conext:_
- _Matrix context:_

_`Using Functions in Expressions`_
> _Docs references: https://docs.github.com/en/actions/learn-github-actions/expressions#functions_

- _Using context combines with If statement to specify which step or job need to run._
- _If always(): always run no matter what happen_
- _If failure(): make step run even the previous run failure (failure() return true)_
