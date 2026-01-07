# ☕ Java Core

## 🚧 Current Mission: Mastering Streams
*Status: In Progress*

**My Plan:**
1.  Understand the difference between Intermediate (lazy) vs Terminal operations.
2.  Stop using `for` loops for simple filtering.
3.  Deep dive into `Collectors.groupingBy`.

**Resources I am using:**
* [Link] Oracle Official Docs (Hard to read but accurate)
* [Link] Venkat Subramaniam's talk on YouTube (Great for mental model)

**Current Struggles (To Figure Out):**
* Why does `stream.reduce()` sometimes require an "Identity"?
* When exactly does parallel stream become faster? (Need to benchmark this).

---

## ✅ Learned Concepts (The "Done" Pile)
* **Filter:** `stream.filter(x -> x > 10)` returns a new stream, doesn't modify original list.
* **Map:** Transforms data. 1-to-1 mapping.
