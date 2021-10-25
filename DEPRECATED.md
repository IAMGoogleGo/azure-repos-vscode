# Sunsetting the Azure Repos VS Code extension

We're sunsetting this Azure Repos VS Code extension.
On 2020-11-06 (Nov 6, 2020), we'll remove it from the VS Code Marketplace and archive the repository.
If you still have it installed, you may continue to use it, but it will not receive any further investment or updates.

## Why are we doing this?

Since we launched the extension four and a half years ago, Visual Studio Code has seen incredible adoption.
Azure DevOps and Azure Repos have similarly continued to see amazing growth.
However, use of TFVC, the centralized source control system, with VS Code has declined.
The majority of VS Code users prefer Git, and therefore use of the extension has declined dramatically in the last 1-2 years.
VS Code has great native Git support.
Therefore we have taken the decision to discontinue support of this extension.
Developers still using TFVC with VS Code will need to use an external version control client such as [the `tf` command line](https://docs.microsoft.com/azure/devops/repos/tfvc/use-team-foundation-version-control-commands).

## What happened?

1. We shipped a final update which contains this notice but contains no other functional changes, bug fixes, etc.

2. On 2020-11-06 we unpublished the extension from the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/).
Those who already have it installed can continue to use it, but without support from Microsoft.
The extension won't receive any updates, bug fixes, or security fixes, so you use it at your own risk.

3. We archived the [GitHub repository](https://github.com/microsoft/azure-repos-vscode) putting it into a read-only state.
This will not delete the code or historical issues (though all open issues and PRs were closed).
The repository is still readable and forkable.

## Is there any action for me?

If you want to keep using the extension, no, there's no action.
It will remain installed in your copy of VS Code.

If you want to stop using the extension, you can uninstall it on VS Code's extensions page.
If you do, you won't be able to reinstall it from the Marketplace.

## Thank you

To everyone who used the extension, provided feedback, or contributed bug fixes, THANK YOU!
