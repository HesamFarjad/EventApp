# EventApp
Demonstrates event-driven programming in C#


# 🔥 Event-Driven Temperature Monitoring in C#

This project demonstrates how to use events and the `EventHandler<T>` pattern in C# to monitor temperature changes.  
It features a simple `TemperatureMonitor` class that raises an event whenever the temperature changes, and multiple subscribers (`TemperatureAlert`, `TempCoolingAlert`) that respond to it.

## 🔑 Key Concepts

- ✅ Strongly-typed events using `EventHandler<TEventArgs>`
- ✅ Loose coupling between publisher and subscribers
- ✅ Real-world scenario of temperature-based alerts

## 📂 Structure

- `TemperatureMonitor`: Publishes temperature change events.
- `TemperatureAlert`, `TempCoolingAlert`: Subscribers reacting to temperature changes.
- `Program.cs`: Entry point to simulate and test the system.

---

Feel free to test it, modify thresholds, or add new subscribers to explore how event-driven systems work in .NET!


