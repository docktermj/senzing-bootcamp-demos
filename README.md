# senzing-bootcamp-demos

Completed [Senzing Bootcamp] projects that you can open in an AI assistant,
explore and modify, without running the bootcamp yourself.

## Prerequisites

- Senzing is installed on your system. The demos do not install it for you.
- [git] is installed.
- One of the AI assistants supported by the [Senzing Bootcamp],
  installed and configured as described at the bottom of that page.

## Demos

Each top-level folder holds demos for one AI assistant.
Inside it, each subfolder is one business case.

| Business case                  | Folder                                 |
| ------------------------------ | -------------------------------------- |
| Banking KYC/KYB and AML        | `<assistant>/banking-kyc-kyb-aml`      |
| P&C insurance and claims fraud | `<assistant>/pc-insurnce-claims-fraus` |

Replace `<assistant>` with `chatgpt`, `claude` or `kiro`.

## Run a demo

1. Clone the repository.
   This creates a `senzing-bootcamp-demos` folder in your current directory.

    ```console
    git clone https://github.com/docktermj/senzing-bootcamp-demos.git
    ```

1. Open your AI assistant and, where the [Senzing Bootcamp] instructions
   tell you to select an empty folder, select a demo folder instead,
   for example `senzing-bootcamp-demos/claude/banking-kyc-kyb-aml`.

1. Do **not** enter `Start the bootcamp`.
   The demo is already a completed bootcamp that you can modify.

1. Enter a prompt to begin, for example:

    ```console
    Start the visualization server.
    ```

[git]: https://git-scm.com/install/
[Senzing Bootcamp]: https://hub.senzing.com/bootcamp/
