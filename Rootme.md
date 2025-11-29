---
order: 99
---
# 🛡️ Root Me

Here is a summary of my activity on Root-Me :

## 🧠 Root-Me – Statistics

### 👤 General Information

| Field | Value |
|-------|--------|
| **Pseudo** | **Romane** |
| **Global rank** | **** |
| **Total score** | **** |
| **Challenges solved** | **** |



## 📊 Progress Overview

| Category | Completed | In Progress | Total | Progress |
|---------|-----------|-------------|--------|----------|
| **App - Script**      | 6  | 0 | 33  | <span class="auto-progress" data-done="6" data-total="50"></span> |
| **App - Système**   | 0  | 0 | 93  | <span class="auto-progress" data-done="0" data-total="97"></span> |
| **Cracking**           | 3  | 0 | 70  | <span class="auto-progress" data-done="3" data-total="77"></span> |
| **Cryptanalyse**     | 0  | 0 | 75  | <span class="auto-progress" data-done="0" data-total="77"></span> |
| **Forensic**          | 2  | 0 | 44  | <span class="auto-progress" data-done="2" data-total="44"></span> |
| **Programmation**  | 0  | 0 | 29  | <span class="auto-progress" data-done="0" data-total="28"></span> |
| **Réaliste**          | 0  | 0 | 62  | <span class="auto-progress" data-done="0" data-total="62"></span> |
| **Réseau**          | 12  | 0 | 35  | <span class="auto-progress" data-done="12" data-total="35"></span> |
| **Stéganographie** | 5  | 0 | 24  | <span class="auto-progress" data-done="5" data-total="24"></span> |
| **Web - Client**       | 11 | 0 | 42  | <span class="auto-progress" data-done="11" data-total="42"></span> |
| **Web - Serveur**    | 2  | 0 | 97 | <span class="auto-progress" data-done="2" data-total="109"></span> |
| **TOTAL**                                     | **<span id="total-done">0</span>** | **0** | **<span id="total-total">0</span>** | <span id="total-progress"></span> |


🔗 Link
    Root-Me profile : https://www.root-me.org/Rdvz

<script>
function updateProgressBars() {
  let totalDone = 0;
  let totalTotal = 0;

  document.querySelectorAll('.auto-progress').forEach(el => {
    const done = Number(el.dataset.done);
    const total = Number(el.dataset.total);

    totalDone  += done;
    totalTotal += total;
    const pct = Math.floor((done / total) * 100);
    el.innerHTML = `
      <progress value="${done}" max="${total}"></progress>
      <span>${pct}%</span>
    `;
  });
  // Update TOTAL row
  document.getElementById("total-done").textContent  = totalDone;
  document.getElementById("total-total").textContent = totalTotal;

  const totalPct = Math.floor((totalDone / totalTotal) * 100);

  document.getElementById("total-progress").innerHTML = `
    <progress value="${totalDone}" max="${totalTotal}"></progress>
    <span>${totalPct}%</span>
  `;
}
updateProgressBars();
</script>
