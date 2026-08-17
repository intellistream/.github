# IntelliStream Research Incubator

IntelliStream incubates early-stage systems research across intelligent applications, evolving-data infrastructure, and model execution.

Projects remain in IntelliStream while their abstraction, maintainers, documentation, tests, reproducibility, licensing, and release process are still taking shape. Mature projects graduate into the organization that owns their long-term technical boundary.

## Ecosystem

```text
IntelliStream research incubator
        | mature projects graduate
        +----------------+-------------------+
        v                v                   v
    RIDE Lab          DataSys            vLLM-HUST
 agent-native         data systems       inference runtime and
 systems research                         hardware execution
        |
        v
      SAGE
 flagship product
```

- [RIDE Lab](https://github.com/RIDE-Lab) conducts agent-native systems research. Its flagship product [SAGE](https://github.com/RIDE-Lab/SAGE) owns agent programming, RAG, workflow, evaluation, and service orchestration; [Sage Mate](https://github.com/RIDE-Lab/sage-mate) is an application built with SAGE.
- [DataSys](https://github.com/DataSysResearch) owns framework-neutral stream, graph, vector/index, online-update, query, lifecycle, and benchmark systems.
- [vLLM-HUST](https://github.com/vLLM-HUST) is the independent inference substrate and owns model runtime, KV/cache scheduling, compilation, kernels, and hardware execution.

These organizations collaborate across distinct technical boundaries. RIDE Lab research systems and products call vLLM-HUST; RIDE is not a runtime layer above it. IntelliStream spans the ecosystem as an incubator rather than acting as another runtime layer.

## Graduated Projects

### DataSys

- [DataSys project directory](https://github.com/DataSysResearch) - 15 graduated public data-system repositories.
- Flagships: [MorphStream](https://github.com/DataSysResearch/MorphStream), [CANDOR-Bench](https://github.com/DataSysResearch/CANDOR-Bench), [GRACE](https://github.com/DataSysResearch/GRACE), and [Sesame](https://github.com/DataSysResearch/Sesame).

### RIDE Lab and SAGE

- [RIDE Lab project directory](https://github.com/RIDE-Lab) - agent-native systems research, products, applications, and benchmarks built on vLLM-HUST.
- Product entry points: [SAGE](https://github.com/RIDE-Lab/SAGE), [SAGE Docs](https://github.com/RIDE-Lab/SAGE-Docs), [SAGE Agentic](https://github.com/RIDE-Lab/sage-agentic), [SAGE RAG](https://github.com/RIDE-Lab/sage-rag), [SAGE Eval](https://github.com/RIDE-Lab/sage-eval), [SAGE Studio](https://github.com/RIDE-Lab/sage-studio), and [SAGE Tutorials](https://github.com/RIDE-Lab/sage-tutorials).
- Application: [Sage Mate](https://github.com/RIDE-Lab/sage-mate).

### vLLM-HUST

Model-runtime, cache-scheduling, compiler, kernel, and hardware-execution projects graduate to [vLLM-HUST](https://github.com/vLLM-HUST) after maintainer review.

## Graduation Policy

A project is ready to graduate when it has:

- a clear public abstraction and ecosystem boundary;
- named maintainers and durable organization ownership;
- documented setup, supported environments, and contribution path;
- tests and a reproducible evaluation path;
- explicit licensing and citation information where applicable;
- a sustainable release or artifact-maintenance process.

Private, unpublished, or collaborator-sensitive repositories require confidentiality, access, secrets, package, and submission-policy review before transfer.

## Official Entry Points

- [sage.org.ai](https://sage.org.ai/) - SAGE product and public documentation.
- [ride-lab.github.io](https://ride-lab.github.io/) - RIDE Lab research organization and portfolio.
- [lab.sage.org.ai](https://lab.sage.org.ai/) - IntelliStream team and research portal.
- [github.com/intellistream](https://github.com/intellistream) - active incubator projects and migration redirects.

## Contributing

Use the issue tracker and contribution guidance in the relevant project repository. For ownership or graduation questions, contact the project maintainers before moving or renaming code.

## Contact

- Email: [shuhao_zhang at hust.edu.cn](mailto:shuhao_zhang@hust.edu.cn)
- Website: [lab.sage.org.ai](https://lab.sage.org.ai/)
