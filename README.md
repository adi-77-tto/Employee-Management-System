<h1 align="center">
  🖥️ Employee Management GUI
  <br>
  <sub><sup>Java Swing • OOP Design • Zero Dependencies</sup></sub>
</h1>

<p align="center">
  <a href="https://github.com/<your‑user>/employee-management-gui/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/<your‑user>/employee-management-gui/build.yml?label=CI&logo=github" alt="CI status">
  </a>
  <img src="https://img.shields.io/badge/JDK-11%2B-informational" alt="JDK 11+">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT License">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen" alt="PRs welcome">
</p>

<div align="center">
  <img src="docs/demo.gif" alt="Demo animation" width="720">
</div>

---

## ✨ Key Features

| Module | Details |
|:------ |:--------|
| **Entity Hierarchy** | `Employee` → `Manager` & `Intern` with polymorphic `toObjectArray()` for JTable |
| **CRUD Workflows**  | Add, update (performance / attendance / bonus), and live display of all personnel |
| **Bonus Calculator** | Salary automatically updated when a bonus % is applied |
| **Pure Java** | Runs anywhere the JDK does—no frameworks or external JARs |
| **Extensible UI** | Drop‑in dialogs (`JDialog`) make it painless to add new data fields |
