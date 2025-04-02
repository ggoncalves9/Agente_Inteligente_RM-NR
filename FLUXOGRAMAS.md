# 🔄 Diagramas de Fluxo (Mermaid)  

### **1. Conexões entre Zaia e BoostSpace**  
```mermaid  
flowchart TD  
    A[WhatsApp] -->|Comando| B(Zaia)  
    B --> C{Verifica Tipo}  
    C -->|Agenda| D[Google Agenda]  
    C -->|E-mail| E[Gmail API]  
    C -->|Tarefa| F[BoostSpace DB]  
    D --> G[Resposta WhatsApp]  
    E --> G  
    F --> G  
