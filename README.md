# HIT Icons

Custom icons for [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons).

## Installation

Go to `C:\Users\<your_user>\AppData\Roaming\<Code or azuredatastudio Folder>\User` and place the `vsicons-custom-icons` folder.

Add following to `settings.json`:

```json
{
	// Replace <your_user> and <Code or azuredatastudio Folder> with your actual values
	"vsicons.customIconFolderPath": "C:/Users/<your_user>/AppData/Roaming/<Code or azuredatastudio Folder>/User",
	"vsicons.associations.folders": [
		{
			"icon": "hit",
			"extensions": ["hit", "hiam", "hitprog", "hoglandet"],
			"format": "svg",
			"light": true
		}
	]
}
```

Open the command panel (Ctrl + Shift + P) and execute `Apply Icons Customization` command in order to apply the settings.

### Azure Data Studio

Since vscode-icons is not published on the Azure Data Studio marketplace, it needs to be installed manually.

1. Download vscode-icons VSIX package
2. In Azure Data Studio, select `File > Install Extension From VSIX Package`
