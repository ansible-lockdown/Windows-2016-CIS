# Changelog

## Release 1.3.1

- March 2024 Update
  - Typo Fixes

## Release 1.3.0

- September 2023 Updates
  - Bug Fixes
  - Added Updated Discord Links
  - Updated Galaxy Score Links
  - Updated Readme
  - Control 18.2.6 - Fixed Spelling For Member server
  - Control 18.3.1 - Adjusted when statement for Member server only.
  - PR'S Closed<br/>
  [#37](https://github.com/ansible-lockdown/Windows-2016-CIS/pull/37) - 9.2.1/9.3.1 Fixed Module Parameters in win_firewall - Thanks @gberginc<br/>
  [#37](https://github.com/ansible-lockdown/Windows-2016-CIS/pull/37) - Section 18 Fixed Module Parameters in win_regedit - Thanks @gberginc<br/>
  - Reviewed all DC Only and MS Only Controls to verify when statements are valid.
  - Updated win_skip_for_test controls

- August 2023 Updates
  - Updated to Central org based workflow.
  - Updated Linting files and ran against playbook
  - All modules fit FQCN standard.
  - Updated Readme.md

## Release 1.2.0

- May 2023 Updates
  - Updated pipelines for testing in Azure
  - Issues Closed<br/>
    [#5](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/5) - 9.1.4/9.2.4/9.3.4 - Wrong data value <br/>
    [#6](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/6) - 2.3.11.4 - Wrong data value <br/>
    [#7](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/7) - 18.9.95.1 - Wrong data value<br/>
    [#8](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/8) - 18.9.26.1.1 - Wrong data type<br/>
    [#9](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/9) - 18.4.1 - Wrong data type<br/>
    [#10](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/10) - 18.3.4 - Wrong data value<br/>
    [#11](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/11) - 19.7.4.1 - Wrong data value<br/>
    [#12](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/12) - 2.3.17.3 - Wrong data value<br/>
    [#13](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/13) - 2.3.6.4 - Wrong data value<br/>
    [#14](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/14) - 19.7.41.1 - Wrong data value<br/>
    [#16](https://github.com/ansible-lockdown/Windows-2016-CIS/issues/16) - 2.3.1.5/2.3.1.6 - Changed value from hardcoded to variable<br/>
  - Updated Galaxy Workflow
  - Updated module names to new standard.
  - Major Update: All task rule names updated to add win16cis to them in default main
    and in appropriate taks files.
  - Updated Ansible_vars_goss file to match new default main.
  - Ansible Lockdown Banner In Playbook (Testing)
  - Full Linting Check
