# How to edit item names?
- Open `GameControllerScript` and scroll down to line 715 and you should see this code:
```cs
private string[] itemNames = new string[]
{
	"Nothing",
	"Energy flavored Zesty Bar",
	"Yellow Door Lock",
	"Principal's Keys",
	"BSODA",
	"Quarter",
	"Baldi Anti Hearing and Disorienting Tape",
	"Alarm Clock",
	"WD-NoSquee (Door Type)",
	"Safety Scissors",
	"Big Ol' Boots"
};
```
- Now, click right mouse button on this code and choose `Edit Method`.
- Then, just edit the item names to whatever you want.
- Before you compile, you need to remove the line below because it won't let you to Compile the `.dll` for some reason.
```cs
base..ctor();
```
- Now, compile the code, save the module and check if it works.