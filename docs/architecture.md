# Architecture

MGL runs entirely in the browser using a custom language runtime:

```
Source → Tokenizer → Parser → Executor → DataFrame → Output
```

The backend engine (mgl-engine/) provides a Node.js/TypeScript DAG executor for server-side use.