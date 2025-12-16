# 🧠 MindForge

**The Pocket Cognitive Architect Studio**

> *Simulate thinking. Train your mind. Understand intelligence — human and artificial.*

MindForge is a **mobile‑first cognitive simulation sandbox** that runs entirely in a single HTML file. It lets users build simplified models of thinking, run scenarios against them, and **visualize cognition in real time** — offline, on any device, with zero installation.

MindForge sits at the intersection of **psychology, AI, systems thinking, and self‑optimization**, presented through an interactive, forge‑style UI.

---

## ✨ What MindForge Is

MindForge allows users to:

* Build simplified cognitive architectures (memory, attention, learning, rules)
* Simulate thinking over time
* Train architectures on tasks
* Visualize thoughts as graphs, particles, matrices, and timelines
* Export simulations for learning, sharing, and reuse

It is designed to make **intelligence intuitive**, not academically perfect.

---

## 🚫 What MindForge Is Not

* Not a scientific replacement for ACT‑R or SOAR
* Not a neural‑network framework like PyTorch
* Not a productivity or note‑taking app

MindForge is an **intuition engine** — built to *see* thinking, not publish papers.

---

## 🧩 Core Mental Model

Everything in MindForge is built on one abstraction:

### Cognitive State

```js
MindState = {
  nodes: [Concept],
  edges: [Association],
  activations: Map,
  memory: MemoryStore,
  attention: AttentionModel,
  time: t
}
```

### Thought

A thought is **energy flowing through a system over time**:

* Injected into concepts
* Propagated across associations
* Modified by attention, decay, and learning
* Visualized as particles

---

## 🏗️ Architecture Studio

Architectures define *how thinking works*.

```js
Architecture = {
  name,
  parameters,
  update(state, input),
  visualize(state)
}
```

### Free Architectures

#### Spread Activation Mind

* Concepts as nodes
* Associations as weighted edges
* Energy spreads and decays

**Use cases**:

* Memory recall
* Word association
* Bias visualization

**Parameters**:

* Decay rate
* Spread factor
* Inhibition threshold
* Attention bias

---

#### Learning Network

(Simple feed‑forward neural network)

**Use cases**:

* Pattern learning
* Skill acquisition
* Classification intuition

**Parameters**:

* Learning rate
* Noise
* Reinforcement strength

---

### Pro Architectures

* **Rule Mind** – symbolic IF/THEN reasoning
* **ACT‑R‑Inspired Hybrid** – declarative + procedural memory
* **SOAR‑Like Goal Engine** – goals, subgoals, impasse resolution
* **Attention / Transformer‑Like Mind** – attention visualization (conceptual)
* **Custom Architecture Builder** – combine modules into reusable minds

> ⚠️ Academic inspiration, not strict fidelity

---

## 🎮 Scenario Playground

Scenarios define *what the mind is trying to do*.

```js
Scenario = {
  name,
  inputs,
  expectedOutputs,
  duration,
  evaluation(state)
}
```

### Built‑In Scenarios (Free)

* Decision Making
* Memory Recall
* Learning Curve

### Pro Scenarios

* Emotional response modeling
* Language learning
* Moral dilemmas
* NPC behavior simulation

### Scenario Builder (Pro)

* Define inputs over time
* Define rewards
* Define success metrics
* Train over multiple cycles

---

## 👁️ Visualization Engine

MindForge’s signature feature set.

### Graph View

* Nodes = concepts
* Size = activation
* Edges pulse with energy

### Particle View

* Thoughts visualized as moving light particles
* Speed = confidence
* Turbulence = confusion
* Color = cognition type

### Matrix View

* Weights
* Activations
* Attention matrices

### Timeline View (Key Feature)

* Play / pause / step
* Scrub through time
* Rewind thinking
* Compare runs (Pro)

### 3D Brain Map (Pro)

* Conceptual brain regions
* Cognitive modules mapped spatially

---

## 🧪 Training Mode

Training = repeated exposure + adaptation.

* Run scenarios repeatedly
* Reinforce successful paths
* Observe learning curves

**Metrics**:

* Accuracy
* Stability
* Decision time
* Memory retention
* Energy efficiency

**Comparison Mode (Pro)**:

* Human‑like
* AI‑like
* Hybrid

---

## 📤 Export Hub

### Free

* PNG (watermarked)
* Short GIF (watermarked)

### Pro

* Clean PNG
* Long GIF (timeline scrub)
* JSON (full mind state)
* Standalone HTML simulation
* API endpoint definition

---

## 📱 Mobile‑First Design

* Thumb‑friendly bottom toolbar
* Pinch‑to‑zoom
* Long‑press nodes to edit
* Swipe between architectures & scenarios
* Shake to randomize parameters (Easter egg)

Offline‑first. Works entirely in browser storage.

---

## 🔐 Freemium Model

### Free Tier

* 2 architectures
* 3 scenarios
* Basic visualization
* PNG export
* 10 local saves

### Pro Tier

* All architectures
* Scenario builder
* Advanced visualization
* Unlimited saves
* JSON / HTML export
* Cloud sync
* API mode

### Example Lock

```js
if (!user.isPro) {
  architectures = architectures.slice(0,2);
  maxNodes = 50;
  exportFormats = ['png'];
  showWatermark('Upgrade to MindForge Pro');
}
```

Soft previews are used instead of hard blocks.

---

## 🛠️ Technical Architecture

Single‑file HTML application:

```html
<!DOCTYPE html>
<html>
<head>
  <title>MindForge</title>
  <style>/* All CSS */</style>
</head>
<body>
  <div id="app"></div>
  <script>
    // Canvas engine
    // State store
    // Architectures
    // Scenarios
    // Visualizers
    // Exporters
    // License manager
  </script>
</body>
</html>
```

### Targets

* <500kb gzipped
* 60fps on mid‑range phones
* No external dependencies
* Fully offline

---

## 🎯 Target Users

* Psychology & neuroscience students
* AI & ML learners
* Indie game developers (NPC prototyping)
* Teachers & lecturers
* Self‑improvement and systems thinkers

---

## 🚀 Roadmap

### Near‑Term

* Core architectures
* Timeline visualization
* Export hub

### Long‑Term

* MindForge Cloud (share & fork minds)
* MindForge API (NPC brains)
* MindForge Edu (curriculum + classroom tools)
* AR visualization experiments

---

## 🧠 Philosophy

MindForge is built on one belief:

> *Understanding intelligence begins by seeing it happen.*

It is a forge for cognition — a place where thoughts can be shaped, tested, and understood.

---

## 📜 License

TBD (commercial + educational licensing planned)

---

**MindForge — See thoughts happen.**
