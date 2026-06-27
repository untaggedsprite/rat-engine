# TESTS

rat-engine should be tested by output, not vibe.

A good pass turns messy input into a usable artifact while preserving the object, reducing distortion, and keeping distinctions intact.

## use

Give the model the README, SPEC, OPERATORS, and DISTINCTIONS.

Then give it one test case.

Ask it to use rat-engine and choose one primary move.

Score the result.

## scoring

Use 0, 1, or 2 for each category.

0 = missing
1 = partial
2 = strong

### object

Does the response keep the central object visible?

### structure

Does it separate claim, evidence, setup, interpretation, speculation, and action where needed?

### signal

Does it preserve the information that changes the answer?

### distortion

Does it reduce fog, overreach, collapsed distinctions, or unsupported certainty?

### move fit

Does the chosen move match the field?

### artifact

Does it return something usable outside the moment?

### language

Is the output clear, compact, and alive?

## pass target

A strong result scores at least 10 out of 14.

A useful result scores at least 8 out of 14.

A weak result may still be informative if the failure is specific.

## source tiers

Use three tiers of tests.

### tier 1: synthetic calibration

Synthetic cases are made to test one operator or distinction at a time.

Use them to confirm the engine understands basic moves.

### tier 2: public or paraphrased real cases

Public or paraphrased cases test transfer.

Use short excerpts, changed details, or public language patterns. Keep the example legible without turning the repo into a drama jar.

### tier 3: private field tests

Private field tests stay out of the public repo.

Use them locally to see how the engine handles real messy context.

## case template

Each public test case should include:

- source type
- primary pressure
- likely move
- input
- task
- strong output should

## case format

### case: short name

Source type: synthetic, public, or paraphrased

Primary pressure: what makes the field hard to handle

Likely move: MAP, CUT, BUILD, TEST, REFUSE, QUERY, or SYNTHESIZE

Input:

Add the short test input here.

Task:

Use rat-engine. Choose one primary move. Return a concrete artifact.

Strong output should:

- keep the object visible
- choose a fitting move
- preserve useful signal
- reduce distortion
- return a usable artifact

## review

After scoring, name the main failure.

Common failures:

- summary without structure
- confidence without evidence
- metaphor treated as proof
- refusal as performance
- synthesis as blur
- compression as flattening
- artifact missing

A failed test is useful when it shows where the engine loses shape.
