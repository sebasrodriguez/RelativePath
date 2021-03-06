## Relative path support for Visual Studio Code
Now you can get the relative path to any file in the workspace.

Just press `Ctrl+Shift+H` (Mac: `Cmd+Shift+H`) and select a file.
Alternatively, you can press open command palette `F1` and search for `Relative Path`.

![GIF](https://media.giphy.com/media/3oEduJ5iRksPxpwoXC/giphy.gif)

## How to use
First, you will need to install Visual Studio Code 0.10. In the command palette (`Ctrl-Shift-P` or `Cmd-Shift-P`) select `Install Extension` and choose `RelativePath`.

## Important
Your workspace may be really big, so please wait for the initial file list to be created. This will happen only once.

## Options
The following Visual Studio Code setting is available for the RelativePath extension. It can be set in user preferences (`ctrl+,` or `cmd+,`) or workspace settings (.vscode/settings.json).

	{
		"relativePath.ignore": ["**/node_modules/**","**/*.dll"]
	}

## Bugs
Report them [here](https://github.com/jakob101/RelativePath).

## Licence
[MIT](https://github.com/Microsoft/vscode-go/blob/master/LICENSE)