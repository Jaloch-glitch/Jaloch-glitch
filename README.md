```
┌──────────────────────────────────────────────────────────────────────────────┐
│                                                                              │
│     ███████╗███████╗██╗     ██╗██╗  ██╗                                      │
│     ██╔════╝██╔════╝██║     ██║╚██╗██╔╝                                      │
│     █████╗  █████╗  ██║     ██║ ╚███╔╝                                       │
│     ██╔══╝  ██╔══╝  ██║     ██║ ██╔██╗                                       │
│     ██║     ███████╗███████╗██║██╔╝ ██╗                                      │
│     ╚═╝     ╚══════╝╚══════╝╚═╝╚═╝  ╚═╝                                      │
│                                                                              │
│     Kenya → Germany | Deriving gradients, not importing them                 │
│                                                                              │
└──────────────────────────────────────────────────────────────────────────────┘
```

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=Jaloch-glitch&style=flat-square&color=58a6ff)](https://github.com/Jaloch-glitch)
[![Followers](https://img.shields.io/github/followers/Jaloch-glitch?style=flat-square&color=58a6ff&label=followers)](https://github.com/Jaloch-glitch?tab=followers)
[![Stars](https://img.shields.io/github/stars/Jaloch-glitch?style=flat-square&color=58a6ff&label=stars)](https://github.com/Jaloch-glitch)

</div>

---

### `> whoami`

```python
class Felix:
    """
    Software engineer who believes understanding beats memorization.
    What I cannot create, I do not understand.
    """

    location = "Germany"
    origin = "Kenya"
    timezone = "CET (UTC+1)"

    by_day = "InfoSec Compliance & Data Governance"
    by_night = "Building neural networks from scratch"

    philosophy = "Ask 'why' until the abstractions dissolve"

    currently_reading = ["Kafka", "Orwell", "McCarthy"]
    # Writers who make every word earn its place

    def approach(self, problem):
        while not understood_from_first_principles(problem):
            ask_why()
            derive_it_myself()
            validate_against_known_implementation()
        return deep_understanding
```

---

### `> diff felix others`

```diff
+ Derived backpropagation from limit definitions, validated against TensorFlow
+ 5-6 hours per Karpathy video — implementing, not just watching
+ Built 25+ production workflows in enterprise data governance
+ Same rigor whether the deadline is compliance audit or gradient descent
- Tutorial following
- "It works, ship it"
- Surface-level understanding
```

---

### `> systemctl status learning.service`

```
● learning.service - Neural Networks: Zero to Hero
     Loaded: loaded (/karpathy/nn-zero-to-hero; enabled)
     Active: active (running) since 2024
       Docs: https://youtube.com/@AndrejKarpathy
     Memory: matrix multiplications and chain rules
```

```
MISSION PROGRESS
════════════════════════════════════════════════════════════════════════

[■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■░░░░░░░░░░] 78% ████████▌

Part 1  [████] DONE     Micrograd ─────────── Autograd from first principles
Part 2  [████] DONE     Makemore ──────────── Bigram language model
Part 3  [████] DONE     Makemore 2 ────────── MLP with embeddings
Part 4  [████] DONE     Makemore 3 ────────── Activations & gradients
Part 5  [████] DONE     BatchNorm ─────────── Normalizing activations
Part 6  [████] DONE     GPT ───────────────── 10.79M param transformer from scratch
Part 7  [▓▓░░] ACTIVE   Advanced ──────────── Scaling and production patterns

════════════════════════════════════════════════════════════════════════
```

<details>
<summary><b>What "DONE" actually means</b></summary>

```
Not: watched the video
Not: copied the code

Actually:
├── Implemented from scratch
├── Derived the math by hand (pen + paper)
├── Validated against production frameworks
└── Can explain it to someone else
```

</details>

---

### `> tail -f /var/log/recent.log`

```
[2026-07-14] Built: GPT from scratch — 10.79M params, trained 50 min on Shakespeare
[2026-04-20] Built: Equipment failure LSTM — ablation study, class imbalance analysis
[2026-03-20] Built: CIFAR-10 CNN — conv feature extraction, 72% on 10 classes
[2026-03-17] Built: House price regression — Random Forest, R²=0.81 on California housing
[2026-03-17] Built: Sentiment LSTM — full NLP pipeline from tokenizer to inference
[2026-03-03] Built: MNIST feedforward — 98.5% accuracy, zero convolutions
[2026-03-02] Built: Iris classifier — first production-pattern pipeline
```

**[Deep-ML Daily Practice](https://github.com/Jaloch-glitch/deep_ML)** — building fluency, one problem at a time

---

### `> ls xx_models/ --show-progress`

```
ML MODEL PORTFOLIO  ─  14 models built
════════════════════════════════════════════════════════════════════════

CLASSIFICATION
──────────────
01  iris_classifier           RandomForest            93.3% accuracy
02  mnist_classification      Feedforward NN          98.5% accuracy
06  image_classification_cnn  CNN (CIFAR-10)          72.5% accuracy
07  transfer_learning         ResNet18 fine-tuned     40.6% accuracy
08  object_detection_R-CNN    Faster R-CNN            COCO pre-trained
10  image_classification_v2   CNN (Fashion MNIST)     91.1% accuracy
11  xray_pneumonia            CNN binary              77.2% acc, F1 0.84

REGRESSION
──────────
04  house_price_prediction    RandomForest            R² = 0.81
05  stock_price_prediction    LSTM time-series        RMSE $77.93

NLP / SEQUENCE
──────────────
03  sentiment_analysis_imdb   LSTM                    custom tokenizer
14  gpt_from_scratch          GPT decoder             10.79M params

ANOMALY / TIME-SERIES
──────────────────────
09  credit_card_fraud         MLP + class weights     AUC 0.962, 82.4% recall
12  equipment_failure         LSTM + ablation         98% acc, F1 analysis
13  log_anomaly_detection     RNN autoencoder         reconstruction error

════════════════════════════════════════════════════════════════════════
```

---

### `> cat /proc/foundation`

```
MATHEMATICAL FOUNDATION
════════════════════════════════════════════════════════════════════════

Linear Algebra    MIT 18.06 (Strang)     ████████████████████░  7.5/8
                  Not memorized — understood geometrically
                  Column spaces, projections, four fundamental subspaces

Calculus          Stewart + Thompson      ████████████████████   Complete
                  Derivatives from limits, chain rule derived not memorized

Probability       MIT 6.041              ████████████████░░░░   70%
                  Just-in-time: learn when needed, not exhaustively

════════════════════════════════════════════════════════════════════════
              Foundation before frameworks. Always.
════════════════════════════════════════════════════════════════════════
```

---

### `> ls -la tools/`

```
drwxr-xr-x  ml_stack/
    ├── numpy         ████████████████████   The foundation — I think in arrays
    ├── pytorch       ██████████████████░░   Feedforward, CNN, RNN, LSTM, GPT
    ├── pandas        ████████████████░░░░   Data wrangling
    └── jupyter       ████████████████░░░░   Interactive exploration

drwxr-xr-x  languages/
    ├── python        ████████████████████   Primary weapon
    ├── javascript    ████████████████░░░░   Full-stack when needed
    ├── groovy        ████████████████░░░░   Collibra workflows
    └── sql           ████████████████░░░░   Data extraction

drwxr-xr-x  enterprise/
    ├── collibra      ████████████████████   25+ production workflows
    ├── sap_datasphere████████████████░░░░   Data warehousing
    ├── databricks    ████████████████░░░░   Big data
    └── compliance    ████████████████████   ISO, SOC2, GDPR
```

---

### `> tree projects/ --highlights`

```
★  gpt_from_scratch          10.79M param GPT decoder — attention derived from scratch
   github.com/Jaloch-glitch/gpt_from_scratch

★  equipment_failure_prediction   LSTM on sensor time-series + ablation study
   github.com/Jaloch-glitch/equipment_failure_prediction

★  image_classification_cnn  CIFAR-10 CNN — conv feature extraction, 72.5% on 10 classes
   github.com/Jaloch-glitch/image_classification_cnn

★  micrograd                 Autograd engine from first principles
   github.com/Jaloch-glitch/micrograd
```

---

### `> git log --oneline --graph metrics`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Jaloch-glitch&show_icons=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&border_color=30363d&hide_border=false" width="49%"/>
<img src="https://streak-stats.demolab.com?user=Jaloch-glitch&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e&border=30363d" width="49%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Jaloch-glitch&bg_color=0d1117&color=c9d1d9&line=58a6ff&point=c9d1d9&area=true&area_color=58a6ff&hide_border=false&custom_title=Contribution%20Graph" width="98%"/>

</div>

---

### `> cat /etc/felix/method.conf`

```ini
[philosophy]
core = "What I cannot create, I do not understand"
approach = "first_principles"
questions = "why > how"

[method]
step_1 = "Encounter the problem"
step_2 = "Resist the urge to Google"
step_3 = "Derive it myself (pen + paper)"
step_4 = "Implement from understanding"
step_5 = "Validate against known implementations"

[anti-patterns]
reject = ["tutorial-following", "copy-paste", "it-works-ship-it"]
embrace = ["confusion", "being stuck", "productive struggle"]

[timeline]
patience = "multi-year"
motto = "Precept upon precept, line upon line"
```

---

### `> cat ~/.signature`

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                                                                           ║
║   Felix Onyango                                                           ║
║   ─────────────────────────────────────────────────────────────────────   ║
║   Email:     jalochglitch@gmail.com                                       ║
║   GitHub:    github.com/Jaloch-glitch                                     ║
║   Location:  Germany                                                      ║
║   Timezone:  CET (UTC+1)                                                  ║
║                                                                           ║
║   Open to:   ML collaborations • Hard problems • First-principles work    ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

---

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────────┐
│       "What I cannot create, I do not understand." — Feynman            │
└─────────────────────────────────────────────────────────────────────────┘
```

</div>
