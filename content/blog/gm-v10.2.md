+++
title = 'GooseMod v10.2'
date = "2021-07-31"
description = 'GooseMod v10.2 is now out: PGP verification for repos, plus some settings and API improvements.'
disableComments = true
+++

## **GooseMod v10.2** has been released! Features PGP verification for repos, plus some settings and API improvements.

### PGP Verification
- **Repos now have PGP verification support.** Repos can now be signed by their maintainers and verified within GooseMod. This should both improve security generally and for some specific attacks. The main advantage PGP adds is that it verifies repos are made and released by their owners. This prevents someone else taking over and publishing malicious updates as the repo would have to be signed with the same private key, which they should not have access to.

### Main Settings
- **Added copy debug info to utilities.**
- **Moved reset setting to end of utilities section.**
- **Added text to experimental section to clarify what it means.**
  
### Commands
- **Commands now use a custom GooseMod section.** Was previously reverted to using built-in after a Discord update.