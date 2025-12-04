# 🤖 Sistema de Irrigação Autônoma — Projeto MNR *(Mostra Nacional de Robótica)*

Este repositório contém a página web oficial do projeto apresentado na **MNR – Mostra Nacional de Robótica**.  
O sistema consiste em um **robô de irrigação autônoma**, equipado com sensores e conectado à internet através de uma **placa ESP8266**, que envia dados para o servidor via **HTTP POST**.

A página web mostra informações coletadas em tempo real, além de uma área dedicada para apresentação do projeto.

---

## 📌 Funcionalidade do Sistema

### 🌱 Robô de Irrigação Autônoma
O robô coleta e envia dados ambientais essenciais para tomada de decisão, como:
- Umidade do solo  
- Presença de chuva  
- Data e horário da coleta  
- Estado atual (irrigando / aguardando)  
- Condições ambientais básicas  

Esses dados são enviados via **POST** pela placa ESP8266 diretamente para a API do site.

---

## 🖥️ Estrutura do Site

O site possui duas partes principais:

### 🏠 **Home**
- Apresentação do projeto  
- Objetivo do sistema  
- Imagens, descrição e explicação do funcionamento  
- Informações sobre a equipe e sobre a MNR  

### 📊 **Dashboard em Tempo Real**
Uma dashboard dinâmica com gráficos que se atualizam automaticamente a cada **15 segundos**.  
Nela é possível visualizar:

- **📅 Data / Hora** da última atualização  
- **💧 Umidade** do solo  
- **🌧️ Chuva** (sim/não)  
- Outros dados que a placa enviar  

Os gráficos são renderizados no navegador usando JavaScript, consumindo dados de uma API em PHP + SQL.

---

## 🚧 Tecnologias Utilizadas

### Backend
- **PHP**  
- **MySQL / MariaDB**  
- **API para recebimento de POST da ESP8266**

### Placa IoT
- **ESP8266**
- **Arduino Uno**

<img width="1313" height="618" alt="image" src="https://github.com/user-attachments/assets/4310349e-4138-446d-bd34-a0cc7bff67ea" />

<img width="1308" height="621" alt="image" src="https://github.com/user-attachments/assets/6317f4cd-7e40-4171-951a-cb4637e39c65" />

<img width="1293" height="225" alt="image" src="https://github.com/user-attachments/assets/fc9e5085-1537-4fb9-b2a4-7ff3b19e8ff8" />

Link oficial no gitpages


