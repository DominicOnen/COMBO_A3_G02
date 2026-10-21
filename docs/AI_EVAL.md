# AI evaluation (threshold 0.2)

- Member queries: 12, top-1 accuracy: 100.00%
- No-match queries: 6, rejection accuracy: 100.00%

| Query | Expected | Got | Confidence | OK |
|---|---|---|---|---|
| Tell me about Member One | m1 | m1 | 0.950 | yes |
| Who is the product and GitHub lead? | m1 | m1 | 0.374 | yes |
| Who handled release packaging and the v1.0.0 tag? | m1 | m1 | 0.293 | yes |
| Tell me about Member Two | m2 | m2 | 0.950 | yes |
| Who knows TF-IDF and cosine similarity? | m2 | m2 | 0.328 | yes |
| Who built the matching engine and no-match logic? | m2 | m2 | 0.294 | yes |
| Tell me about Member Three | m3 | m3 | 0.950 | yes |
| Who is the API and integration engineer? | m3 | m3 | 0.320 | yes |
| Who built the FastAPI service and deployment? | m3 | m3 | 0.471 | yes |
| Tell me about Member Four | m4 | m4 | 0.950 | yes |
| Who knows React Native and Expo? | m4 | m4 | 0.226 | yes |
| Who built offline mode? | m4 | m4 | 0.287 | yes |
| What is the weather in Kigali today? | None | None | 0.043 | yes |
| Recipe for cooking potatoes | None | None | 0.050 | yes |
| who won the football match | None | None | 0.154 | yes |
| tell me something | None | None | 0.035 | yes |
| Explain quantum physics | None | None | 0.035 | yes |
| bitcoin price forecast | None | None | 0.056 | yes |

## Error table

None.