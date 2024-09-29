
---

# Azure Subscription Management with PowerShell

This repository contains scripts for managing Azure subscriptions via PowerShell, including checking the current subscription, listing available subscriptions, and switching between them.

## Prerequisites

- **Azure PowerShell Module**: Install with:
  ```powershell
  Install-Module -Name Az -AllowClobber -Force
  ```

## Key Commands

### 1. **Login to Azure Account**

```powershell
Connect-AzAccount
```

### 2. **Check Current Subscription**

```powershell
Get-AzContext
```

### 3. **List All Subscriptions**

```powershell
Get-AzSubscription
```

### 4. **Switch Subscription**

```powershell
Set-AzContext -Subscription "SubscriptionName or SubscriptionId"
```

## Folder Structure

- **/scripts**: Contains PowerShell scripts for subscription management.

## License

Licensed under the MIT License.

