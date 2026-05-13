## 🛠️ Guia Iniciante: Como Configurar e Usar

Se você nunca usou Python ou APIs de Inteligência Artificial, este guia vai te ajudar a configurar tudo em 5 minutos.

### 1. Como conseguir sua Chave de API (🔑 API Key)
Para a IA funcionar, você precisa de uma "chave" que autoriza o seu código a usar o modelo Llama-3.
1. Acesse o site oficial: [Groq Cloud Console](https://console.groq.com/keys).
2. Crie uma conta gratuita.
3. Clique em **"Create API Key"**.
4. **Importante:** Copie e guarde em um lugar seguro, você não conseguirá vê-la novamente.

### 2. Instalando as Bibliotecas
As bibliotecas são pacotes de ferramentas que ensinam o Python a falar com a IA. Abra o seu terminal (Prompt de Comando ou PowerShell) e digite:
import os
from langchain_core.prompts import ChatPromptTemplate
from langchain_groq import ChatGroq

  
 
