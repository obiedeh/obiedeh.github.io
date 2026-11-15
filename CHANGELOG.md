# Changelog

## Unreleased

- 2026-11-15: Home page opening sentence corrected to "I design and build Physical AI and edge AI systems, and prove them on real robots and hardware." The earlier wording could be read as designing robots.
- 2026-11-15: Home page opening paragraph states what he builds first: "I design and build Physical AI, robotics and edge AI systems, then prove them on real hardware."
- 2026-11-14: Bench2Field page: the 2026-11-11 retest's board power on the Jetson AGX Thor at 30 frames per second added beside the frame times (24.9 to 25.0 W at default clocks, 28.5 to 29.7 W with the clocks pinned), from the [retest record](https://github.com/obiedeh/bench2field/blob/master/case_studies/01_perception_detector/runs/clock_retest_20261111/README.md).
- 2026-11-14: Bench2Field page and home page proof line corrected: the 47.8 ms full frame on the rover is labelled as a default-clock figure, and the 2026-11-11 retest with the clocks pinned (21.1 to 21.5 ms at p95 on the Jetson Orin NX, 8.9 W to 14.5 W at 30 frames per second) is stated beside it with its limits. The thread-spinning panel carries a dated note that the finding did not hold on retest.
- 2026-11-03: Commissioning copilot page dated to its October 3 record, with the November 1 test count and the retired Labs label removed from the band; home page copilot card tagged Ollama, the measured local stack, in place of Bedrock.
- 2026-11-03: Jetson Edge AI Security page: the 2026-10-29 TensorRT-on-Thor measurement (no engine for the shipped ONNX-ML models, CPU fallback). Physical AI Safety Observability page: the 2026-10-29 hazard analysis, method and vocabulary only. Both pages: contact line set to the approved wording.
- 2026-11-03: Home page: the second hero button reads "Read the newsletter" and links to At the Edge with Obyno, in place of "Discuss a system", so the page offers one next step and no service language.
- 2026-11-03: Home page and commissioning copilot page: the retired EmbodiedEdge Labs name replaced with EmbodiedEdge.
- 2026-11-03: Bench2Field page: test count corrected to 188 passing and 1 skipped, as run in the project's own environment.
- 2026-11-03: Bench2Field page brought up to date: case studies 02 to 05 added at their recorded status, 184 tests and the measured FP32 baseline accuracy, status dated 3 November, and the retired EmbodiedEdge Labs name replaced with EmbodiedEdge.
- 2026-11-03: Physical AI on Jetson page: a learning-from-demonstrations section with the recorded simulation results from 2026-10-18 to 2026-10-30 and the MoveIt planning record; dates and scope updated; contact line set to the approved wording.
- 2026-10-31: Validate repository instruction contracts and dated changelog entries on branch pushes and pull requests with five required-rule deletion checks and three enclosing-context checks; document the standard-library validation command without publishing site content.
- 2026-10-30: Link repository instructions to the shared hygiene policy and summarize board labels, private identifiers, hooks, immutable history and external handoff notes.
