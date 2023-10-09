# Elk-Server-Lab

### Source
```
https://www.leveleffect.com/blog/how-to-set-up-your-own-home-lab-with-elk
```

Setting up the ELK Server in Part One involved configuring an Ubuntu OS, ensuring it's up-to-date, and enabling SSH access. Installation of Elasticsearch and Kibana required YAML file configurations. Logstash was installed to aid Elasticsearch, and Filebeat installation was straightforward.

In Part Two, SIEM and Security setup required essential certificate configuration in Elasticsearch and Kibana YAML files. Creating a Certificate Authority (CA) bundle using Elasticsearch-certutil was necessary, followed by verification with a curl command. The Elasticsearch setup password auto feature simplified the process. Access to the ELK login page was established after configuring all settings and restarting the system.

Moving to Part Three, importing data with Agent and Fleet was relatively simple. Configuring the server fleet involved specifying the CA location. Agent policies setup was straightforward, and the choice of Endpoint Security integration enhanced security. Setting up a Windows 10 VM and using PowerShell to manage certificate-generated log data. Adding the agent was effortless, connecting the Windows 10 VM to the ELK server for data access.

Part Four's roadmap outlined building a robust SIEM system with the ELK stack. It started with configuring a log aggregator and endpoint protection for better visibility. Subsequent steps included enabling Filebeat modules, updating certificates, creating API keys, and ensuring secure Filebeat configuration. Integrating threat intelligence feeds, like AlienVault OTX, was emphasized, along with the importance of dashboards for data analysis. The pre-built detection rules and advised on creating custom rules for identifying indicators of compromise, underscoring the need for vigilant monitoring across diverse data sources. The guide prioritized security and effective threat intelligence integration in constructing a robust SIEM system.

## Custom Dashboard
![image](https://github.com/cyberAngel9/Elk-Server-Lab/assets/82012925/be1d2286-6933-4e03-a895-77204f4b1dff)

## AlienVault OTX Dashboard
![image](https://github.com/cyberAngel9/Elk-Server-Lab/assets/82012925/698f8e23-b548-4249-9135-e22e63a907ae)

## Fleet Endpoint
![image](https://github.com/cyberAngel9/Elk-Server-Lab/assets/82012925/401b2dcf-b985-40e8-80a8-5faaf3400432)

## Rules
![image](https://github.com/cyberAngel9/Elk-Server-Lab/assets/82012925/f8b0d82b-3f3b-4a4c-b1ad-8bdb1c8d779f)

## Logs from Windows VM
![image](https://github.com/cyberAngel9/Elk-Server-Lab/assets/82012925/fb494935-a8db-4119-9796-0b0dcccf4941)

## Elk Network Diagram 
![image](https://github.com/cyberAngel9/Elk-Server-Lab/assets/82012925/878717c2-6228-477c-93d6-b31e1ad0363a)

