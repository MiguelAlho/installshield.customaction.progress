# InstalShield.CustomAction.Progress

This is a sample InstallShield project that creates a basic MSI that should show how to manipulate the progress bar in the context of a custom action.

Unfourtunately, building and running the installer does not have the desired effect. Progress bar fill is never incremented for the Custom Action, only reset.

Script adapted from : https://docs.microsoft.com/pt-br/windows/win32/msi/adding-custom-actions-to-the-progressbar