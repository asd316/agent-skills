---
name: experiential-explainer
description: Convert abstract technical, scientific, economic, strategic, or systems knowledge into grounded explanations that readers can mentally experience, predict, and transfer. Use when a user asks for a concrete scenario, first-person demonstration, intuitive explanation, “讲人话”, “让我有画面”, “实际会怎么发生”, or when a correct academic-style explanation would still be hard to internalize. Especially useful for causal mechanisms, feedback loops, tradeoffs, scale, uncertainty, and dynamic processes. Do not use for simple factual answers, direct operational steps, or requests whose goal is vivid fiction rather than understanding.
---

# Experiential Explainer

Build a runnable mental model, not merely a vivid story. Use perspective, action, feedback, imagery, and emotion only when they reduce the reader's mental translation cost.

Treat first-person perspective as a cognitive instrument rather than a writing style. Place the reader inside the causal system so they can observe state, make a meaningful choice, encounter a constraint, and see the resulting state change.

## Preserve the knowledge contract

- Establish the mechanism before dramatizing it.
- Keep facts, supported inference, disputed claims, forecasts, and invented scenarios visibly distinct.
- Never let narrative confidence upgrade uncertain knowledge into fact.
- Treat a scene as a demonstration of a mechanism, never as evidence that the mechanism or forecast is true.
- Preserve important technical distinctions and limits. Simplify the representation, not the underlying claim.
- Verify unstable or contested claims before rendering them when verification is available and the claim matters to the explanation.

## Build the explanation

### 1. Find the cognitive bottleneck

Infer what the reader needs to do with the knowledge: understand it, make a decision, remember it, explain it, or predict its behavior. Identify the smallest missing mental operation, such as:

- seeing an invisible causal chain;
- feeling the pressure created by a constraint;
- understanding scale or accumulation;
- distinguishing two similar mechanisms;
- following a feedback loop over time;
- predicting what changes when one variable moves.

Do not ask a clarifying question unless different interpretations would change the mechanism being explained.

### 2. Extract the causal skeleton

Before writing the scene, identify:

- the actors or components;
- their observable state;
- their goal or governing tendency;
- the constraints and available actions;
- the feedback or measurement signal;
- the state transition caused by each action;
- the outcome and its boundary conditions.

If this skeleton cannot be stated clearly, do not compensate with more imagery. Resolve the knowledge gap or state the uncertainty.

### 3. Choose the smallest fitting cognitive carrier

Use the carrier that makes the bottleneck easiest to grasp:

- **First-person simulation**: default for decisions, incentives, constraints, risk, and feedback.
- **Twin scenario**: compare two systems while changing only one important variable.
- **Failure replay**: start from a visible failure and trace backward through the causal chain.
- **Spatial or object model**: use for architecture, hierarchy, flow, capacity, or geometry.
- **Scale walk**: move through quantities or time horizons when intuition fails because of scale.

Prefer a familiar, minimal situation that is structurally isomorphic to the real mechanism. Do not force first person when the reader has no meaningful agency or observation point.

### 4. Run the scene through action and feedback

Anchor the reader with only what matters: who they are, what they want, what they can observe, and what is at stake.

Advance through three to six causal beats. Each beat should contain most of this loop:

`observable state -> available choice -> action -> immediate feedback -> updated belief or state`

Use concrete quantities when magnitude or threshold is causal. Use sensory detail only when it reveals state. Use emotion only when it conveys uncertainty, urgency, loss, temptation, or another force that changes a decision.

Do not give the first-person character information that a real participant could not know at that moment.

### 5. Bridge back to the formal model

After the scene, make the correspondence explicit:

- map the scene's actors, constraints, actions, signals, and outcomes to the real system;
- name the formal concept once the reader has an intuition to attach it to;
- state which parts were illustrative rather than literal;
- identify where the analogy stops matching reality.

Use a compact mapping table when three or more correspondences matter. Otherwise use one short paragraph.

### 6. Prove transfer with one perturbation

Change one important variable while holding the others stable. Show how the outcome changes and why. Prefer the variable most likely to expose whether the reader has the correct model.

Examples include removing the feedback signal, shortening the time horizon, increasing switching cost, changing capacity, or allowing a participant to observe hidden state.

### 7. Return to the user's actual question

Finish with the shortest technically accurate formulation of the mechanism and its consequence for the original question. Do not repeat the entire scene as a summary.

## Calibrate the response

Use the lightest form that creates understanding:

- For a quick explanation, use one compact scene, one bridge, and one conclusion.
- For a deep explanation, add the causal map, one perturbation, and the analogy boundary.
- For a comparison, use twin scenarios with the same protagonist and change only the deciding variable.
- When the user already understands the mechanism, skip scene-setting and demonstrate only the disputed or missing link.

Do not expose these as named modes unless doing so helps the user navigate a long answer.

## Avoid common failures

- Do not write a cinematic story whose details do no causal work.
- Do not use emotion to manufacture agreement or certainty.
- Do not bury the answer behind a long setup.
- Do not replace one unexplained abstraction with a decorative metaphor.
- Do not stretch an analogy beyond its structural match.
- Do not invent statistics, company motives, internal model behavior, or future events to make the scene feel concrete.
- Do not claim that behavior is literally a named algorithm merely because it resembles that algorithm.
- Do not fall into a repeated formula such as “你刚刚体验到的就是……”. Vary the bridge naturally.

## Use examples safely

For a question such as “为什么没有产品反馈闭环的模型公司更危险”, place the reader in the role of a model-company decision maker and contrast what they can learn after a release with what a product-integrated competitor can observe. Map release decisions, user corrections, evaluation signals, and retraining choices back to the feedback loop. Keep company-specific claims hypothetical unless sourced.

For a question such as “为什么连续表示可能呈现类似宽度搜索的行为”, qualify the underlying research claim first. Demonstrate how delaying a discrete commitment can preserve several possibilities, but do not assert that fixed vector-coordinate blocks literally store separate branches or that the process is BFS without evidence.

## Check before answering

Confirm that:

- the mechanism remains correct after removing the story;
- every vivid detail performs causal work;
- uncertainty and hypothetical content are labeled;
- the scene-to-concept mapping is recoverable;
- the reader can predict the direction of change under one perturbation;
- the final answer resolves the original question rather than merely creating atmosphere.
