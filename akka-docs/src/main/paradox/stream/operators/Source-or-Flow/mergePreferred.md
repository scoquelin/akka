# mergePreferred

Merge multiple sources.

@ref[Fan-in stages](../index.md#fan-in-stages)

## Signature

## Description

Merge multiple sources. Prefer one source if all sources has elements ready.


@@@div { .callout }

**emits** when one of the inputs has an element available, preferring a defined input if multiple have elements available

**backpressures** when downstream backpressures

**completes** when all upstreams complete (This behavior is changeable to completing when any upstream completes by setting `eagerComplete=true`.)

@@@

