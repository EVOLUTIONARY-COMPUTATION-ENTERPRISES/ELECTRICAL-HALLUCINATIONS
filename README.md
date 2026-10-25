# The Circuit Confusion Lab

An interactive, safety-first explainer about the claim that removing electrical protection means getting “more power.” It introduces the roles and limits of MCBs, RCCBs, ELCBs, and voltage stabilizers, then explores possible reasoning shortcuts with a clearly labeled evolutionary neural-network demonstration.

## Run locally

No build step or package installation is required. Open `index.html` in a browser, or serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## What’s included

- A conceptual overview of MCB, RCCB, ELCB terminology, and voltage stabilizers.
- A distinction between protective disconnection and voltage regulation.
- Conceptual diagrams of balanced three-phase waveforms and a hypothesized learning/interpretation pathway.
- An interactive neural network controlled by hypothetical scenario sliders.
- A genetic algorithm that evolves a small feed-forward network to fit a hand-authored rule on synthetic data.
- Possible cognitive explanations and links to further reading.

## Important limitations and safety

“More-power syndrome” is not presented as a recognized diagnosis. This project has no survey, observational, genetic, or brain data, so it cannot establish how many people hold the belief, why a particular person believes it, or whether a suggested factor causes it. It provides no evidence that DNA mutations cause electrical misconceptions; the diagram explicitly marks that claim as unsupported. The neural network and evolutionary algorithm are demonstrations, not validated cognitive models or medical tools. The genetic algorithm fits an invented target rule on synthetic examples; a lower error only means a closer fit to that invented rule, not better understanding of real people. Slider values are hypothetical and are not measurements of a person.

The three-phase waveform is a conceptual illustration of equal-frequency phase voltages separated by 120 electrical degrees in a balanced system. It is not a wiring diagram or instruction for working on electrical equipment.

Removing an MCB or residual-current device does not, by itself, raise the nominal supply voltage or create extra useful power. MCBs and RCCBs/RCDs have distinct protection functions and are not general-purpose voltage regulators or universal surge protectors. A stabilizer may adjust voltage within its design limits. Device behavior depends on its design, condition, ratings, installation, supply, and local standards.

This project is not a wiring guide or an electrical diagnosis. Do not open a live panel, bypass protection, or use this page to modify electrical equipment. Consult a licensed electrician for inspection or installation. Suitable, correctly installed protection can reduce specific hazards, but no device guarantees safety or prevents every injury or equipment failure.

## Project files

- `index.html` — complete static web app, styles, and interaction logic.
- `README.md` — project overview and safety notes.
- `.gitignore` — common operating system and editor files to exclude from version control.

## License

No license is currently included. Add a license only after choosing the terms under which you want others to use and redistribute the project.
