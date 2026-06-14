# pipeline-compose-eval

Evaluate `when:` expressions for [pipeline-compose](https://github.com/aeswibon/pipeline-compose) pipelines.

## Usage

```yaml
- uses: aeswibon/pipeline-compose-eval@v0.1.0
  with:
    expression: startsWith(github.ref, 'refs/tags/v')
    context: '{}'
    github: '{"ref":"refs/tags/v1.0.0"}'
```

## License

MIT
