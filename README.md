# MercuryLOB: High-Fidelity Limit Order Book Simulator & Market-Making Framework

MercuryLOB is a high-fidelity **Limit Order Book (LOB) simulator** built to replicate 
exchange-level behavior, order matching rules, and microstructure dynamics.  
On top of the simulator, the project implements a **market-making alpha suite** including:

- Avellaneda–Stoikov quoting model  
- Adaptive bid–ask spread strategies  
- Inventory and risk management  
- Transaction cost & slippage modeling  
- Realistic cancellation and order arrival processes

This project helps you understand **market microstructure**, 
**order matching**, and **real-world market-making logic** used in 
HFT and prop trading.


## 🔍 Features

### **1. LOB Simulator**
- Price–time priority matching engine  
- Supports limit, market, cancel, and modify orders  
- Configurable order arrival processes (Poisson, Hawkes)  
- Nanosecond timestamp simulation  
- Depth tracking (L1–L10)

### **2. Market-Making Strategies**
- Avellaneda–Stoikov optimal quote computation  
- Inventory-aware spread adjustment  
- Volatility-based quote widening  
- Backtest-ready execution logic

### **3. Analytics**
- Mid-price, microprice, spread dynamics  
- Inventory & PnL curves  
- Quote placement heatmaps  
- Order queue position estimation


