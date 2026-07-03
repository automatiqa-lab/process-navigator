# Process Navigator

A guided canvas for finding automation opportunities in the way you already work, with an AI agent working alongside you on the same board.

## What it is

Most people who run a process can feel where the friction is, but they rarely have a structured way to turn that instinct into a decision about what to automate. Navigator is a canvas that walks you through that thinking. You lay out how your process actually runs today, and a guided methodology helps you mark the steps that are repetitive, rule-based, and worth handing to software.

An AI agent works on the same canvas next to you. It reads the state of the board, suggests where the opportunities are, asks the questions you would forget to ask, and drafts the reasoning. You stay in control of the canvas. The agent proposes, you decide.

## Who it's for

Business and supply-chain people who run real processes and do not write code. If you can describe how your work gets done, you can use Navigator. No engineering background required.

## Why it exists

There are plenty of pieces of this problem in the open-source world, but nothing that puts them together: a guided canvas methodology, a focus on automation opportunities specifically, a co-working agent, and an audience of non-technical operators. Each part exists somewhere. The combination does not. Navigator is that combination.

## How it's built

The methodology comes before the code. What Navigator asks, in what order, and how it reasons about an opportunity is specified and reviewed before anything is implemented, because for a tool like this the methodology is the product.

The parts that make Navigator distinct are built directly: the agent orchestration, the methodology engine, and the two-way sync between the agent and the canvas state. The parts that are solved commodities are pulled off the shelf: canvas rendering and the LLM plumbing. Dependencies are MIT or Apache-2.0 only.

## Principles

- The person using Navigator never has to write code.
- The agent proposes, the human decides. The canvas belongs to the user.
- The methodology works on paper without the agent. The agent accelerates the work; it never gates it.

## Status

Early. The methodology is being defined ahead of implementation.

## License

MIT. See [LICENSE](LICENSE).
