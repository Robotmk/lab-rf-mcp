# Tutorial 

## Github Copilot vs. Claude Code 

We provide MCP server support both for **Github Copilot** and **Claude**. You can choose which one you want to use, or even use both in parallel.

Support for **Github** is built-in into VS Code, thanks to MS. 

To use **Claude Code** follow these steps: 

- install the [Claude Extension for VS Code](https://marketplace.visualstudio.com/items?itemName=anthropic.claude) (see the recomendation in the bottom right corner).
- Switch to the "CLAUDE CODE" chat tab on the right ("CHAT" is for Copilot)
- Click on "*Login with Claude.ai Subscription*"
- A dialoge will pop up, choose to **copy** the authentication link.  
(Don't try to open in the browser; your host's browser will open the authentication page and then redirect to "localhost", but the callback won't reach the container)
- From the "*PORTS*" tab, line "*noVNC*", click on the globe icon (second column) and connect to the VNC session
- Paste the link from your machine's clipboard into the VNC clipboard field:
![alt text](img/paste-link.gif)
- Right-click on the desktop and click on "Browser". Then paste the link on the address bar:
![alt text](img/link.gif)
- Login to Claude.com with your E-mail addres; you should receive then an Email with a link to get a 6-digit authentication code.
- Enter the auth code into the VNC browser; you should get a long authentication code. 
![alt text](img/authcode.png)
- Click on "copy", open again the VNC clipboard and copy it from there
- Switch back to the codespace tab
- Paste the authentication code in Claude's Chat Window. 



### Using the MCP Server


    Authenticate After logging in, the Claude command `/mcp` should list the MCP-Server "robotmcp-claude".


You can mention the MCP server via `#robotmcp-vscode` in your prompts. 