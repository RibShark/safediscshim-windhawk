# SafeDiscShim (Windhawk Edition)
### [Installation Guide](/INSTALL.md)
SafeDiscShim is a compatibility tool that allows for SafeDisc protected games which utilize the insecure Macrovision
Security Driver ("secdrv.sys") to run on modern versions of Windows which have said driver blacklisted. Previous methods
to restore functionality to these games relied on forcefully installing the driver, potentially opening security risks.

In contrast, this tool does not rely on any drivers to function. Instead, it automatically loads alongside SafeDisc
protected games and intercepts any communication requests that would have been sent to the driver, instead sending the 
expected response itself and allowing the game to boot.

# Disclaimer
SafeDiscShim is purely designed as a compatibility tool: no security mechanisms are bypassed in the operation of this 
tool and SafeDisc protected games still require their original discs in order to function, even when using this tool.
Certain games may have additional compatibility issues outside of the SafeDisc protection; this tool makes no attempt to
fix such issues.
