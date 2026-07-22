# IntelliStream Research Incubator

IntelliStream incubates early-stage systems research across intelligent applications, evolving-data infrastructure, and model execution.

Projects remain in IntelliStream while their abstraction, maintainers, documentation, tests, reproducibility, licensing, and release process are still taking shape. Mature projects graduate into the organization that owns their long-term technical boundary.

## Ecosystem

```text
IntelliStream research incubator
        | mature projects graduate
        +----------------+-------------------+
        v                v                   v
      SAGE            DataSys            vLLM-HUST
 application and      data systems       inference runtime and
 orchestration                            hardware execution
```

- [SAGE](https://github.com/SAGE-Research) owns agent, RAG, workflow, evaluation, studio, tutorial, and service-orchestration systems.
- [DataSys](https://github.com/DataSysResearch) owns framework-neutral stream, graph, vector/index, online-update, query, lifecycle, and benchmark systems.
- [vLLM-HUST](https://github.com/vllm-hust) owns model runtime, KV/cache scheduling, compilation, kernels, and hardware execution.

These organizations form a layered ecosystem. They do not map one-to-one to individual research directions, and IntelliStream spans all layers as an incubator rather than acting as a fourth runtime layer.

## Graduated Projects

### DataSys

- [DataSys project directory](https://github.com/DataSysResearch) - 15 graduated public data-system repositories.
- Flagships: [MorphStream](https://github.com/DataSysResearch/MorphStream), [CANDOR-Bench](https://github.com/DataSysResearch/CANDOR-Bench), [GRACE](https://github.com/DataSysResearch/GRACE), and [Sesame](https://github.com/DataSysResearch/Sesame).

### SAGE

- [SAGE project directory](https://github.com/SAGE-Research) - 25 graduated public application and orchestration repositories.
- Core entry points: [SAGE](https://github.com/SAGE-Research/SAGE), [SAGE Docs](https://github.com/SAGE-Research/SAGE-Docs), [SAGE Agentic](https://github.com/SAGE-Research/sage-agentic), [SAGE RAG](https://github.com/SAGE-Research/sage-rag), [SAGE Eval](https://github.com/SAGE-Research/sage-eval), [SAGE Studio](https://github.com/SAGE-Research/sage-studio), and [SAGE Tutorials](https://github.com/SAGE-Research/sage-tutorials).

### vLLM-HUST

Model-runtime, cache-scheduling, compiler, kernel, and hardware-execution projects graduate to [vLLM-HUST](https://github.com/vllm-hust) after maintainer review.

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
- [lab.sage.org.ai](https://lab.sage.org.ai/) - IntelliStream team and research portal.
- [github.com/intellistream](https://github.com/intellistream) - active incubator projects and migration redirects.

## Contributing

Use the issue tracker and contribution guidance in the relevant project repository. For ownership or graduation questions, contact the project maintainers before moving or renaming code.

## Contact

- Email: [shuhao_zhang at hust.edu.cn](mailto:shuhao_zhang@hust.edu.cn)
- Website: [lab.sage.org.ai](https://lab.sage.org.ai/)
