# Help

SixtyForty assumes prior knowledge of investing.  To get started, you must have a **target portfolio** in mind - that is, a mix of asset types designed to provide investment returns at your risk tolerance (check out the [reading list](/READING.md) if you are new to these concepts).

The initial setup of SixtyForty can be a little fiddly.  However, once set up, all you need to do is periodically update your accounts and check the rebalance summary.  I (the author of SixtyForty) do this about once a month for 5 minutes during my morning coffee.

## Accounts

An account is a collection of holdings.  A holding is a stock, mutual fund, ETF, etc.  Add accounts to SixtyForty to mirror your real investment accounts.  For example, your 401k or RRSP account.  Add holdings to each account to match your actual investments.  It can be helpful to add a cash holding for deposits, dividends, etc.

## Asset Types

An asset type is a *kind* of holding, for example, stocks, bonds or cash.  SixtyForty uses asset types to define the **target portfolio**, for example: 60% stocks, 40% bonds, 0% cash.  Multiple holdings can be assigned the same asset type.  For each account, add the asset types you intend to monitor for rebalancing.  Set the allocation target for each asset type and finally assign holdings to the correct asset type.

## Updating

SixtyForty requires you to enter the value of your holdings periodically (a few times a year to once a month), a process called “updating”.  To update, go to the account screen and press the **Update holdings** button right below the list of holdings.  SixtyForty will refresh the rebalancing summary with each update.  It will also keep track of previous updates to generate history plots.

SixtyForty delays saving the update by about a minute.  This provides a short window to correct a mistake before the data becomes part of the account history.  You can remove older entries, going to the account setup menu and selecting “manage history”.  At this time, history cannot be edited.

## Rebalancing

By default, each account will have its own rebalance summary.  The summary shows the correction needed to achieve the target asset allocations.  Corrections are shown in red when they exceed the rebalancing error.  The summary will list the holdings associated with the asset type.  When there is more than one holding, you must decide which holding to buy/sell to rebalance (ie: the correction applies to the total for the asset type, not individual holdings).

Use the rebalance cashflow to simulate adding or removing cash from your account.  The rebalance summary will automatically update to reflect what changes need to be made to remain balanced.

SixtyForty supports rebalancing accounts separately or together.  This is controlled by changing the rebalance mode in the accounts setup screen (main screen setup menu).  When rebalancing accounts together, a single rebalance summary appears on the accounts screen.

## Account Groups

Accounts in SixtyForty are organized into account groups.  An account group is an independent collection of accounts.  They are useful if you are managing investments for others.

At a minimum, you will need to create one account group to manage your own accounts.

## Have a Question?

Please send me an [email](mailto:support@sixtyfortyapp.com)



