# `@blocksuite/integration-test`

Integration test for BlockSuite.

## Running Tests

You can run all integration tests using:

```bash
cd blocksuite/integration-test
pnpm test:unit
```

To run a specific test or test file, use the `-t` flag with a test name pattern:

```bash
# Run a specific test
pnpm test:unit -t "should access turbo renderer instance"

# Run all tests in a specific file
pnpm test:unit src/__tests__/edgeless/viewport-renderer.spec.ts
```

For debugging tests with the Playwright debugger:

```bash
pnpm test:debug

pnpm test:debug -t "should access turbo renderer instance"
```
