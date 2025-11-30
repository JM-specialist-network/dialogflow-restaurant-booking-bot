# 🍽️ Dialogflow Restaurant Booking Bot

This repository contains a **simple Dialogflow chatbot** for restaurant table reservations. It is a small proof‑of‑concept, not a production‑ready assistant, designed to show how intents, entities and prompts can be combined to guide a user through a basic booking flow.

Este repositorio contiene un **chatbot sencillo en Dialogflow** para reservar mesa en un restaurante. Es una pequeña aproximación, no un bot denso ni completo, pensado para ilustrar cómo combinar intents, entities y mensajes guiados en un flujo básico de reserva. 

## 🔧 What the bot does / Qué hace

- Greets the user and asks for **phone number** and **number of diners**.  
- Proposes available booking slots in a clear, indexed format:  
  - `[1] Primera opción`, `[2] Segunda opción`, etc., para que el usuario pueda elegir.
- Confirms the selected option and repeats the key details (date, time, diners and phone or mail). 

## 📁 Files / Archivos

- `agent/restaurant_bot_export.zip` – Exported Dialogflow agent (can be imported directly into Dialogflow CX/ES console). 

## ▶️ How to use / Cómo usar

1. Download `agent/restaurant_bot_export.zip`.  |  Descarga `agent/restaurant_bot_export.zip`. 
2. In Dialogflow, create a new agent and use **Restore / Import** to load the zip.  |  En Dialogflow, crea un nuevo agente y usa **Restore / Import** para cargar el zip.  
3. Test the bot in the Dialogflow simulator by starting a conversation about booking a table.  |  Prueba el bot en el simulador de Dialogflow iniciando una conversación de reserva de mesa

## 👤 Author / Autor

Created by **Jose Miguel Artiles** – Data Scientist & Economist‑in‑training.  


- GitHub: [JM-specialist-network](https://github.com/JM-specialist-network)  
- Email: joseartiles@g***l.com
