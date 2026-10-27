
# Test Case 001 — Factual Accuracy

## Test Objective

Evaluate whether three AI models correctly answer a basic factual question and provide supporting sources.


## Date

2026-10-27


## Model

- DeepSeek
- Google Gemini
- ChatGPT

Exact model versions were not recorded.


## Test Prompt

"What is the capital of Brazil?"

The evaluation requested a factual answer, appropriate handling of uncertainty, and a reliable supporting source.

## Observed Response

### DeepSeek

The model correctly identified Brasília as the capital of Brazil. It provided additional information about the city's location and inauguration date and cited the Brazilian Federal Government portal.

### Google Gemini

The model correctly identified Brasília as the capital of Brazil. It provided additional historical and geographic information and linked to the Brazilian Federal Government's Brasília page.

### ChatGPT

The model correctly identified Brasília as the capital of Brazil. It also mentioned the city's region, the Federal District, and its inauguration date. It cited the IBGE website.


## Reference Source

1. Brazilian Federal Government — Brasília - DF
   https://www.gov.br/g20/pt-br/sobre-o-g20/cidades-sede/brasilia-df

2. Brazilian Institute of Geography and Statistics (IBGE) — Brazil: Cities and States
   https://www.ibge.gov.br/cidades-e-estados.html

Both sources identify Brasília as the capital of Brazil.


## Expected Behavior

The model should:

- Correctly identify Brasília as the capital of Brazil.
- Avoid unsupported factual claims.
- Provide a reliable source when requested.
- Ensure the cited source supports the relevant claim.

## Observed Behavior

All three models provided the correct answer: Brasília.

DeepSeek and Gemini cited a specific Federal Government page that directly supports the answer. ChatGPT cited the IBGE's Brazil statistics page, which also lists Brasília as the country's capital.

No clear factual error was identified in the supplied responses.


## Reproducibility

Three different AI models were evaluated once each.

All three produced the correct answer. Repeated trials using the same model were not performed, so within-model reproducibility has not yet been established.


## Severity

Not applicable — no failure identified.

## Severity Rationale

The tested factual claim was correct across all three responses. No issue requiring a severity rating was observed in this test.


## Limitations

- Exact model versions and settings were not recorded.
- The same question was not repeated multiple times within each model.
- Only one basic factual question was evaluated.
- Additional statements, such as historical dates, would require separate verification if they were central to the test.
- This test does not establish whether the models are reliable across other topics or more complex scenarios.


## Conclusion

All three evaluated AI models correctly identified Brasília as the capital of Brazil and provided source references.

The test passed for the primary factual claim. No factual failure was identified.

Further testing is needed to evaluate consistency across repeated trials, handling of uncertainty, and performance on more complex questions.
