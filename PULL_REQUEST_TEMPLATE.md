## 📌 Summary
Briefly describe what this PR changes.

---

## 🎯 Scope
Clearly define the impact boundary of this PR.

Examples:
- CI configuration only.
- Documentation only.
- Python runtime logic.
- Graph schema and retrieval layer.
- Performance optimization.

> Explicitly state whether application logic has changed.

---

## ❓ Why
Why is this change needed? What problem does it solve?

---

## 🔢 Related Issue
Closes #  
or  
No related issue.

---

## 🛠️ Type of Change (select one)
- [ ] feat: new feature
- [ ] fix: bug fix
- [ ] docs: documentation only
- [ ] refactor: internal improvement (no behavior change)
- [ ] chore: tooling / build / CI / dependency update

---

## 🧠 Implementation Details
Key technical decisions, trade-offs, or constraints (2–5 bullets).

Example:
- Refactored device detection to centralize fallback logic.
- Enabled GitHub-formatted Ruff output for inline PR annotations.
- No runtime logic changes.

---

## 🔍 Review Checklist

### ✅ Common (Always Required)
- [ ] Commit message follows convention (`type: description`).
- [ ] CI passes (Ruff required).
- [ ] No hard-coded secrets/credentials added.

---

### 🐍 Python Code Quality (if Python code changed)
- [ ] All public functions/methods include type hints.
- [ ] `ruff format .` applied locally.
- [ ] `ruff check .` passes locally.
- [ ] Unused imports / variables removed.

If not applicable:
> Not applicable (no Python runtime logic changed).

---

### ⚡ Performance & Resource (if performance-sensitive logic changed)
- [ ] Device logic supports MPS/CUDA/CPU fallback (if applicable).
- [ ] Avoided redundant tensor copies / reloads.
- [ ] Memory footprint considered (batch size, caching, streaming).

If not applicable:
> Not applicable (no performance-related changes).

---

### 🧠 Graph / Retrieval Integrity (if Graph/RAG logic changed)
- [ ] Schema/ontology updates documented.
- [ ] Retrieval returns citations or graph paths as designed.
- [ ] Hybrid retrieval logic validated with example query.

If not applicable:
> Not applicable (no Graph/RAG logic changed).

---

### 📚 Documentation (if user-facing behavior changed)
- [ ] README updated (if needed).
- [ ] Docstrings/comments updated (English).
- [ ] Usage examples adjusted.

If not applicable:
> Not applicable (no documentation impact).

---

## 📸 Screenshots / Logs (Optional)
Attach screenshots or CI logs if relevant.

---

## 🧪 Testing
Describe how this change was verified.

Examples:
- `ruff format . && ruff check .`
- `python week01_main.py`
- `pytest -q`
- Manual verification on MPS/CUDA environment

Be explicit about how you validated the change.
