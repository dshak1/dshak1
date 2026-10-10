# diar shakimov

c++ swe intern at ea, on the fc meta team. cs + math at sfu. building IntelliAudit, ai infra and hitl auditor tool. i like systems work: latency, concurrency, caches, the ugly parts of making something actually run.

i do not put work code here. site: [dshak1.github.io](https://dshak1.github.io)

## dev tools

[latenC](https://github.com/dshak1/latenC)
vs code extension that finds c++ performance antipatterns and then compiles real benchmarks instead of guessing. lock-free spsc ring buffer, iqr + p95/p99 micro-benchmark harness. mountain madness software systems prize.

[perfmap](https://github.com/dshak1/perfmap)
cache-aware hash map lab in c++17. baseline plus workload-tuned and indirect-storage variants, benchmarked against stl and abseil, generated reports. taught it at a gdsc sfu workshop.

[receipts](https://github.com/dshak1/receipts)
reliability ci for computer-use agents. run the task n times on isolated browsers, verify every outcome independently of what the agent claims, get a typed verdict (the interesting row is false_positive) with a wilson 95% interval and a ci gate. [landing](https://dshak1.github.io/receipts/).

deepSWE eval harness (private)
ablation harness for an ai bug-fix pipeline over a private ticket corpus: contamination-controlled retrieval, an eight-layer failure taxonomy, gates, a run ledger, a verdict form. retrieval measured by ablation over a labeled benchmark (hit-rate figure under re-measurement, so not quoted); warm query 12.4s to 1.4s on a 676-document corpus. it caught its own circular-eval bug, which is the part i am proudest of.

interviewMaxx (private)
stdlib-only python cli that tailors a resume from a tagged accomplishment bank and writes the pdf with a hand-rolled pdf 1.4 writer. zero deps because the target box has no package manager.

## systems stuff

[f1-telemetry-copilot](https://github.com/dshak1/f1-telemetry-copilot)
farvis. c++17 race engineer. 50hz telemetry, 20 concurrent sims, gemini on the pit wall. thread-safe ring buffers because the naive version fell over. originally just c++ telemetry project, added gemini just to be eligible for gemini track @ hackathon.

[gravity-simulator-updated](https://github.com/dshak1/gravity-simulator-updated)
watched a documentary with mom and built a gravity simulator in year 1 bcc (before claude code). c++ / opengl. def holds a special place in my heart. later the benchmark target for latenC.

[NIDS-GAN](https://github.com/dshak1/NIDS-GAN)
network intrusion detection plus gan synthetic data. research adjacent project.

## research

[IntelliAudit: using large language models to evaluate audit controls](https://arxiv.org/abs/2608.07688)
arxiv preprint, 2026, co-author. llms judging whether heterogeneous evidence satisfies compliance controls; the hard part is evidentiary sufficiency, not keyword matching.

## also

[s2s](https://github.com/dshak1/s2s) is a passion project developed in partnership with UBC CCEL Chapman Grant teaching kids Kazakh lanugage and culture as well as design and technical skills; live at [steppe2screen.com](https://steppe2screen.com). ios coming soon.

[linkedin](https://linkedin.com/in/dshakimov) · dshakimov@gmail.com
