## ha-mcp-for-xiaozhi

![GitHub Repo stars](https://img.shields.io/github/stars/anhrau688/ha-mcp-for-xiaozhi?style=for-the-badge&label=Stars&color=green)
![GitHub forks](https://img.shields.io/github/forks/anhrau688/ha-mcp-for-xiaozhi?style=for-the-badge&label=Forks&color=green)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/anhrau688/ha-mcp-for-xiaozhi?style=for-the-badge&color=green)
![GitHub release (latest by date)](https://img.shields.io/github/downloads/anhrau688/ha-mcp-for-xiaozhi/total?style=for-the-badge&color=green)
![GitHub release (latest by date)](https://img.shields.io/github/downloads/anhrau688/ha-mcp-for-xiaozhi/latest/total?style=for-the-badge&color=green)

## ha-mcp-for-xiaozhi- added full attributes for climate and fan devices

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=anhrau688&repository=ha-mcp-for-xiaozhi&category=integration)

<p align="center">
  <img src="https://raw.githubusercontent.com/c1pher-cn/brands/refs/heads/master/custom_integrations/ws_mcp_server/icon.png" alt="Alt Text" align="center">
</p>  

<p align="center"> 
Homeassistant MCP server for XiaoZhi AI，directly connect to Xiaozhi AI official server.
</p>



### Capabilities
#### 1.HomeAssistant itself acts as an MCP server and connects directly to the XiaoZhi server via the websocket protocol without the need for a proxy.
#### 2.Select multiple API groups (HomeAssistant's build in Intent APIs and user-configured MCPServer) in one entity and proxy them to Xiaozhi
#### 3.Support configuring multiple entities at the same time

---
### To watch video how to config（please like it for support, or post a few comments）

https://youtu.be/A8XC2nEJ0uw?si=4WzdSNp8yyYNYC8b

https://youtu.be/3eccQM_eRTI?si=glRr0qW4OnYm5qfr

---
 
### Installation：

Make sure your Home Assistant is being 2026.11 or newer

1.Open Setting -> Marketplace

<img width="659" height="493" alt="image" src="https://github.com/user-attachments/assets/0f1de8e1-cfca-479f-be92-f17e8127b93d" />



2.Add custom repositories: click on "Add from link" on the top right coner

<img width="621" height="208" alt="image" src="https://github.com/user-attachments/assets/ae7f8776-27c4-45a5-b8f7-01f3c68cfc2e" />



3.paste url of this repo in the box: https://github.com/anhrau688/ha-mcp-for-xiaozhi -> then click "Add" button
<img width="578" height="302" alt="image" src="https://github.com/user-attachments/assets/521d8167-50f5-4cae-90b2-aef3884282a9" />

4.back to Marketplace and find "MCP Server for Xiaozhi" now you can see this component show in the below list, then click on that note "Homeassistant MCP server for xiaozhi AI - add customs mcp for Climate and Fan device"
<img width="963" height="439" alt="image" src="https://github.com/user-attachments/assets/32289ec4-980e-4dd6-8c8c-f07191d98ceb" />

5.Install this component: click "Install" button
<img width="1223" height="229" alt="image" src="https://github.com/user-attachments/assets/c291e5e2-ce26-42d4-af3b-0c64691d36b2" />

<img width="600" height="315" alt="image" src="https://github.com/user-attachments/assets/8efffe8c-3983-4dc1-85bb-f49bee52c318" />

### Configuration：
1.Input WebSocket Access Point For XiaoZhi AI in this box -> click "Submit" -> click "Finish"
<img width="578" height="501" alt="image" src="https://github.com/user-attachments/assets/9aaa4665-361b-4a5b-a256-c5b7f609c674" />

 WebSocket can get in your xiaozhi.me account like this
<img width="724" height="690" alt="image" src="https://github.com/user-attachments/assets/883f8253-bb1f-432a-9c17-7812d13a42f9" />

Now your integration has been already
<img width="1123" height="326" alt="image" src="https://github.com/user-attachments/assets/675d26d0-7103-44bf-a21d-c8a7626eabf0" />

2.The final Step: Access your xiaozhi.me account ->open Configure -> Extension tab -> click "Refresh" icon, All of supported mcp tool wil be show in below

<img width="724" height="690" alt="image" src="https://github.com/user-attachments/assets/82c67e00-a34e-41d8-ba03-6ec2dd508b13" />






### Debugging Instructions

 1.The tools exposed depend on the type of entity you expose to the HomeAssistant voice assistant
   
 2.Try to use the latest version of HomeAssistant. There are obvious differences in the tools provided by the Oct version and the Nov version.

 3.If debugging doesn't work as expected, first check Xiaozhi's chat log to see how he handles the command and whether he has a tool that calls HomeAssist. Currently, a major known issue is that lighting and music control can conflict with the built-in screen and music control logic. This will be resolved after the XiaGe server supports built-in tool selection next month.
 
 4.If the process correctly calls the built-in function of HA, you can open the debug log of this plug-in to observe the actual execution status.
 



 
 

